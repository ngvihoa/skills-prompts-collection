---
name: figma-design-analysis
description: Analyze a Figma design, FigJam board, screenshot, or exported design into screen inventories, user flows, component states, and design tokens before implementation.
---

# Figma design analysis

Turn a bounded design reference into an implementation-ready analysis. Use the available Figma connector when the source is in Figma. Screenshots or exports can support a visual analysis when connector access is unavailable. No named subagent or custom delegation tool is required.

## Establish the scope

Identify the reference URL/node, screenshot, or export; the screen/flow/component to examine; and the artifact the user needs. Ask for missing access or scope only when it prevents useful analysis. Follow a relevant nested reference rather than expanding to the entire file by default.

If both structured design data and a rendered screenshot are available, inspect both: the structure explains hierarchy and tokens, while the rendered view shows the actual visual result. State when the input only supports a partial analysis.

## Choose the artifact

- **Screen inventory:** screen name, purpose, main actions, and entry/exit points.
- **User flow:** entry, actions, state transitions, exits, and dependencies. Flag alternate, empty, loading, and error paths when evidenced or missing.
- **Component analysis:** hierarchy, reusable elements, variants, states, responsive behavior, and accessibility questions.
- **Design tokens:** typography, colors, spacing, radii, and elevation. Distinguish declared tokens from values estimated visually.

Ground findings in the supplied node or image. Label inference and unanswered questions; do not turn an unseen interaction into a confirmed requirement. With a static image, describe visible states and ask about behavior only when it affects the requested work.

For a follow-up, reuse the gathered references and findings rather than repeating discovery. Delegation is optional when the environment and user scope allow it; pass the reference, scope, and desired artifact instead of requiring a particular agent name.

Return the requested analysis with reference links, observed behavior, and the few unresolved decisions that affect implementation. Produce implementation code only when it is also part of the user's request.
