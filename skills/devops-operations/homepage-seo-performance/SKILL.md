---
name: homepage-seo-performance
description: Measure homepage SEO and browser performance for a supplied website or local deployment, create a baseline or comparable before/after report, and distinguish static HTML findings from runtime measurements.
---

# Homepage SEO and performance

Audit the requested homepage using the project's existing measurement tools or the browser and audit tools available in the current environment. The workflow supports any framework and has no dependency on a particular repository, agent, or measurement script. Measure first; application changes belong to a separate requested scope.

## Target and evidence

Identify the URL or supplied HTML, runtime mode, deployment/build identifier when available, timestamp/timezone, viewport, and audit purpose. Distinguish where the application runs from its data source: a development server using production data is still a development runtime. Record relevant data/fixture differences without exposing configuration values.

Use the requested target and environment. Loading a live page may emit analytics or impression events, so describe that behavior accurately; avoid unrelated user actions, submissions, or synthetic tracking calls. Use existing scripts when they fit, otherwise use available tools. If a tool is unavailable, mark its measurements as missing rather than inventing a substitute result.

## Measurements

- Inspect the response status/redirects and initial HTML for title, description, canonical URL, indexing directives, headings, navigation, internal links, and meaningful page content. Describe structured data only to the level actually checked.
- Distinguish initial HTML from the DOM after rendering/hydration. A saved HTML file supports markup inspection; it cannot establish browser execution, network timing, hydration, or Lighthouse scores.
- Record uncompressed HTML size separately from network-transferred bytes. Framework payloads embedded in HTML are part of the HTML total: do not add them a second time. Measure such payloads only when the framework exposes them and explain the method.
- Record JavaScript transfer, scripting time, and long tasks separately. These are not interchangeable with Lighthouse Total Blocking Time (TBT).
- When Lighthouse is available, record version/configuration and measured LCP, CLS, TBT, and Speed Index. Collect mobile and desktop when relevant; prefer at least three runs per viewport and report the median and variation.
- Attribute large DOM/HTML contributions to measured sections. Attribute main-thread work only as precisely as traces or source maps permit; a chunk name or a large section alone does not prove a component caused the delay.

## Comparisons

Match runtime/build mode, URL or equivalent route, fixture/content, viewport, browser, cache state, and throttling. State which variables differ. If they prevent a fair comparison, report observations and limitations rather than claiming the code caused an improvement. Never compare a development build with a production build as evidence of a performance regression or gain.

Separate field data from lab measurements and a measured finding from a proposed fix. Do not claim search indexing, ranking, or user-wide performance from a single local audit.

## Report

Use the user's requested destination or the project's existing audit directory; otherwise use `reports/seo/`. Save a new report for each session, for example `homepage-performance-YYYY-MM-DD-runNN-ENV.md`. Use the user's configured timezone, record it, and increment the run number without overwriting earlier reports. Several repeated samples for one session belong in one report.

Include target/runtime, timestamp, build identifier when known, tools/settings, viewports, measurements and units, raw artifact links, initial content coverage, top contributors with evidence, SEO findings, comparison validity, recommendations, and missing checks. Keep secrets, authenticated payloads, and private user data out of saved artifacts. Mark a partial or failed measurement as incomplete and say what is needed to finish. Summarize the findings and link the report.
