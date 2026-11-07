# 🧰 Skills & Prompts Collection

Danh mục skills và prompt theo lĩnh vực công việc, kèm công dụng, nguồn cài và đường dẫn nội dung được lưu trong repo.

🧩 **284 tên skill** · 🗂️ **11 lĩnh vực** · 💬 **4 prompt**

Cập nhật **07/11/2026**.

<a id="contents"></a>

## 🧭 Mục lục

| Lĩnh vực | Phạm vi | Tên skill |
|---|---|---:|
| [🎨 Thiết kế UI/UX](#domain-ui-ux-design) | Giao diện, design system, Figma, chuyển động, khả năng truy cập và nhân vật tương tác. | 10 |
| [💻 Lập trình & kiến trúc](#domain-software-engineering) | Frontend, backend, mobile, framework, ngôn ngữ, API và cấu trúc mã nguồn. | 61 |
| [🧪 Kiểm thử & chất lượng](#domain-testing-quality) | Review code, QA, kiểm thử tự động, debug, đánh giá agent và hiệu năng. | 24 |
| [🔀 Git & quản lý công việc](#domain-git-project-management) | Commit, merge, pull request, release, issue và quy trình Linear/GitHub. | 20 |
| [🚀 Hạ tầng & vận hành](#domain-devops-operations) | Triển khai, CI/CD, môi trường, bảo mật, mạng, giám sát và xử lý sự cố. | 21 |
| [📊 Dữ liệu & phân tích](#domain-data-analytics) | SQL, cơ sở dữ liệu, schema, truy vấn, phân tích số liệu và trực quan hóa. | 13 |
| [🤖 AI agent & tự động hóa](#domain-agents-automation) | MCP, skill/plugin, cấu hình agent, browser/computer use và workflow tự động. | 45 |
| [✍️ Nội dung & media](#domain-content-media) | Viết bài, marketing, mạng xã hội, ảnh, video và nhân vật hoạt hình. | 9 |
| [📄 Tài liệu & công việc văn phòng](#domain-documents-office) | Word/PDF, bảng tính, slide, biểu mẫu, template và ghi chép. | 32 |
| [🔬 Nghiên cứu khoa học & học thuật](#domain-research-science) | Tìm tài liệu nghiên cứu, sinh học, hóa học, cơ sở dữ liệu khoa học và khảo cứu. | 39 |
| [🧠 Tư duy, lập kế hoạch & học tập](#domain-planning-learning) | Phản biện ý tưởng, làm rõ yêu cầu, thiết kế kế hoạch và học qua trao đổi. | 10 |

- 📦 [Nguồn và cách cài](#installation).
- 🔄 [Lưu ý về các tên upstream đã thay đổi](#upstream-changes).
- 📝 [Cấu trúc và cập nhật danh mục](#maintenance).

Mỗi skill có một lĩnh vực chính. Các bản cùng tên được gom trong một mục; một mục có thể có cả nguồn cài bên ngoài và bản tùy chỉnh được lưu trong repo. Prompt liên quan nằm trong lĩnh vực tương ứng.

<a id="domain-ui-ux-design"></a>

## 🎨 Thiết kế UI/UX

Giao diện, design system, Figma, chuyển động, khả năng truy cập và nhân vật tương tác.

| Skill | Công dụng | Nguồn / nội dung |
|---|---|---|
| `awesome-claude-design` | Use ready-to-use DESIGN.md files to scaffold complete design systems in Claude Design with colors, typography, components, and UI kits | [Awesome Claude Design](#source-awesome-design) |
| `design-motion-principles` | Motion and interaction design expert based on Emil Kowalski, Jakub Krehel, and Jhey Tompkins' techniques. Two modes — build interactive components with purposeful motion, or audit existing animations to catch AI-slop motion patterns (audit… | [Design Motion Principles](#source-design-motion) |
| `design-taste-frontend` | tasteskill v2, the anti-slop frontend skill. Art direction for websites, distilled from a study of 247 curated gallery sites (One Page Love, Awwwards Sites of the Day). Deals researched directions (idea, composition, type, palette,… | [Taste Skill](#source-design-taste) |
| `figma` | Use the Figma MCP server to fetch design context, screenshots, variables, and assets from Figma, and to translate Figma nodes into production code. Trigger when a task involves Figma URLs, node IDs, design-to-code implementation, or Figma… | [OpenAI Skills / Codex](#source-openai-skills) |
| `figma-design-analysis` | Analyze a Figma design, FigJam board, screenshot, or exported design into screen inventories, user flows, component states, and design tokens before implementation. | [figma-design-analysis / SKILL.md](skills/ui-ux-design/figma-design-analysis/SKILL.md) |
| `generative_ui` | How to render rich interactive HTML widgets inline in the chat or as standalone artifacts. Use this skill when you want to show the user diagrams, data visualizations, interactive controls, educational walkthroughs, or any rich visual… | [Google Antigravity — built-in](#source-antigravity-core) |
| `page-mascot` | Put a cursor-tracking mascot on a page -- a chibi character that turns its head toward the pointer and reacts when clicked. Picks one of the fifty-two drawn characters and wires up the React component, or draws a new one (with your own… | [Page Mascot](#source-page-mascot) |
| `ui` | Explore, build, and refine UI. Use when the request involves interface design, design systems, layout, visual style, or UI critique. | [ui.sh — remote UI skill](#source-uidotsh) |
| `ui-ux-pro-max` | UI/UX design intelligence for web, mobile, and desktop. This skill should be used when designing, building, reviewing, or fixing interfaces, including pages, components, design systems, accessibility, interaction, responsive layout,… | [UI/UX Pro Max](#source-ui-ux-pro-max) |
| `web-design-guidelines` | Review UI code for Web Interface Guidelines compliance. Use when asked to "review my UI", "check accessibility", "audit design", "review UX", or "check my site against best practices". | [Vercel Agent Skills](#source-vercel-agent-skills) |

[⬆️ Mục lục](#contents)

<a id="domain-software-engineering"></a>

## 💻 Lập trình & kiến trúc

Frontend, backend, mobile, framework, ngôn ngữ, API và cấu trúc mã nguồn.

| Skill | Công dụng | Nguồn / nội dung |
|---|---|---|
| `add-python-version-support` | Guide changes required when a project adds a newer Python version above its current tested ceiling while preserving its existing minimum. Use when asked to support, test, certify, or prepare for a newer Python release at the upper end of… | [Pylance](#source-pylance) |
| `ai-gateway` | Vercel AI Gateway guidance for setup, model discovery, authentication, routing, fallbacks, BYOK, budgets, spend reporting, observability, compatible APIs, and coding-agent configuration. Use when adding AI Gateway to an app, migrating… | [Vercel Plugin](#source-vercel-plugin) |
| `ai-sdk` | Answer questions about the AI SDK and help build AI-powered features. Use when developers: (1) Ask about AI SDK functions like generateText, streamText, ToolLoopAgent, embed, or tools, (2) Want to build AI agents, chatbots, RAG systems, or… | [Vercel Plugin](#source-vercel-plugin) |
| `android-cli` | Provides instructions for installing and using the `android` CLI. The `android` command-line tool is a critical tool for Android development and helps you create new Android projects, run Android apps on devices, manage and interact with… | [Antigravity plugin: Android](#source-agy-android-cli-plugin) |
| `android-dev` | Build, run, inspect, and lightly automate Android apps with the android-emulator MCP tools. | [ZCode Official Plugins](#source-zcode) |
| `android-device-hub` | Instructions for working with the Android Device Hub sidecar, which lists, starts, stops, creates and removes Android Virtual Devices (AVDs), lists physical devices connected to adb, and lets the user mirror and control any of them (video,… | [Antigravity plugin: Android](#source-agy-android-cli-plugin) |
| `auth` | Authentication integration guidance — Clerk (native Vercel Marketplace), Descope, and Auth0 setup for Next.js applications, plus Sign in with Vercel, Vercel Passport, and Vercel KMS. Covers proxy.ts auth patterns, sign-in/sign-up flows,… | [Vercel Plugin](#source-vercel-plugin) |
| `bootstrap` | Project bootstrapping orchestrator for repos that depend on Vercel-linked resources (databases, auth, and managed integrations). Use when setting up or repairing a repository so linking, environment provisioning, env pulls, and first-run… | [Vercel Plugin](#source-vercel-plugin) |
| `build-agents` | Default guidance for building AI agents. Use for generic requests to build, create, scaffold, design, architect, or implement an AI agent, agent app, tool-calling agent, durable agent, multi-agent system, or scheduled agent. | [Vercel Plugin](#source-vercel-plugin) |
| `chat-sdk` | Vercel Chat SDK expert guidance. Use when building multi-platform chat bots — Slack, Telegram, Microsoft Teams, Discord, Google Chat, GitHub, Linear — with a single codebase. Covers the Chat class, adapters, threads, messages, cards,… | [Vercel Plugin](#source-vercel-plugin) |
| `chrome-extensions` | Build and publish Chrome Extensions using Manifest V3 best practices. Use this skill whenever the user asks to create, modify, debug, or understand Chrome browser extensions, add-ons, or anything involving the Chrome Extensions API.… | [Antigravity plugin: Modern Web Guidance](#source-agy-modern-web-guidance-plugin) |
| `compose-preview` | Instructions for the Android Compose Preview sidecar, which renders Jetpack Compose @Preview functions with `android preview render` and shows them in the Android Compose Preview pane. Use it when the user wants to see a Compose preview,… | [Antigravity plugin: Android](#source-agy-android-cli-plugin) |
| `create-a-backend` | Backend architecture guidance. Use when planning, building, or migrating an API or backend; choosing between Functions, Services, containers, Workflow, Queues, and Marketplace databases; or selecting a supported backend framework or… | [Vercel Plugin](#source-vercel-plugin) |
| `create-canvas` | Create a project Copilot extension canvas for the current workspace. | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `cross-platform-paths` | Critical patterns for cross-platform path handling in this VS Code extension. Windows vs POSIX path bugs are the #1 source of issues. Use this skill when reviewing or writing path-related code. | [Python Environments](#source-python-envs) |
| `design-an-interface` | Generate multiple radically different interface designs for a module using parallel sub-agents. Use when user wants to design an API, explore interface options, compare module shapes, or mentions "design it twice". | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `drop-python-version-support` | Guide changes required when a project drops one or more oldest supported Python versions and raises its minimum supported version. Use when asked to remove the oldest supported runtimes, raise the minimum Python requirement, modernize code… | [Pylance](#source-pylance) |
| `eve` | eve framework guidance for durable AI agents and agent-powered applications. Use when creating, editing, or debugging an eve project, when the user explicitly asks for eve, or when the build-agents skill has selected eve as the default… | [Vercel Plugin](#source-vercel-plugin) |
| `extension-to-functions-codebase` | Skill for converting an installed Firebase Extension (or extension source) into a standalone Cloud Functions for Firebase codebase or publishable npm package, including V1 to V2 trigger upgrades, lifecycle hooks, and declarative security | [Antigravity plugin: Firebase](#source-agy-firebase) |
| `firebase-ai-logic-basics` | Official skill for integrating Firebase AI Logic (Gemini API) into web applications. Covers setup, multimodal inference, structured output, and security. | [Antigravity plugin: Firebase](#source-agy-firebase) |
| `firebase-auth-basics` | Guide for setting up and using Firebase Authentication. Use this skill when the user's app requires user sign-in, user management, or secure data access using auth rules. | [Antigravity plugin: Firebase](#source-agy-firebase) |
| `firebase-basics` | Provides foundational Firebase CLI setup, CLI installation, version checks (`firebase-tools@latest --version`), CLI login (including --no-localhost), project creation, project selection (`firebase use`), and app config file downloads… | [Antigravity plugin: Firebase](#source-agy-firebase) |
| `firebase-remote-config-basics` | Manages Firebase Remote Config templates, feature flags, loading strategies, and SDKs (Android, iOS). Use when downloading/deploying remoteconfig JSON templates, managing version history/feature flags, setting in-app defaults,… | [Antigravity plugin: Firebase](#source-agy-firebase) |
| `flags-sdk` | Set up and use feature flags and A/B tests with the Flags SDK (`flags` npm package) and Vercel Flags. Use when installing or configuring the SDK, adding a new or existing flag, wiring `vercelAdapter` (OIDC or SDK keys), declaring flags… | [Vercel Plugin](#source-vercel-plugin) |
| `google-antigravity-sdk` | Design, implement, and debug autonomous AI agents and multi-agent systems using the Google Antigravity (AGY) SDK. ACTIVATE this skill when the user wants to create, configure, or orchestrate Google Antigravity agents. | [Antigravity plugin: Google Antigravity SDK](#source-agy-google-antigravity-sdk) |
| `ios-dev` | Build, run, inspect, and lightly automate iOS simulator apps with the ios-simulator MCP tools. | [ZCode Official Plugins](#source-zcode) |
| `knowledge-update` | Corrects outdated LLM knowledge about the Vercel platform and introduces new products. Injected at session start. | [Vercel Plugin](#source-vercel-plugin) |
| `microfrontends` | Guide for building, configuring, and deploying microfrontends on Vercel. Use this skill when the user mentions microfrontends, multi-zones, splitting an app across teams, independent deployments, cross-app routing, incremental migration,… | [Vercel Plugin](#source-vercel-plugin) |
| `modern-web-guidance` | Search tool for modern web development best practices. MANDATORY: Execute FIRST for all HTML/CSS and clientside JS tasks. Do NOT skip — web APIs evolve rapidly and training weights contain obsolete patterns. Trigger immediately for: -… | [Antigravity plugin: Modern Web Guidance](#source-agy-modern-web-guidance-plugin) |
| `next-best-practices` | Next.js best practices - file conventions, RSC boundaries, data patterns, async APIs, metadata, error handling, route handlers, image/font optimization, bundling | [Vercel Plugin](#source-vercel-plugin) |
| `next-cache-components` | Next.js 16 Cache Components guidance — PPR, use cache directive, cacheLife, cacheTag, updateTag, and migration from unstable_cache. Use when implementing partial prerendering, caching strategies, or migrating from older Next.js cache… | [Vercel Plugin](#source-vercel-plugin) |
| `next-forge` | next-forge expert guidance — production-grade Turborepo monorepo SaaS starter by Vercel. Use when working in a next-forge project, scaffolding with `npx next-forge init`, or editing @repo/* workspace packages. | [Vercel Plugin](#source-vercel-plugin) |
| `next-upgrade` | Upgrade Next.js to the latest version following official migration guides and codemods. Use when upgrading Next.js versions, running codemods, or migrating between major releases. | [Vercel Plugin](#source-vercel-plugin) |
| `nextjs` | Next.js App Router expert guidance. Use when building, debugging, or architecting Next.js applications — routing, Server Components, Server Actions, Cache Components, layouts, middleware/proxy, data fetching, rendering strategies, and… | [Vercel Plugin](#source-vercel-plugin) |
| `pylance-docs` | Use when the user explicitly asks for the Pylance docs skill, or when an answer depends on current official Pylance documentation for settings, diagnostics, configuration, troubleshooting, feature behavior, or supported workflows. | [Pylance](#source-pylance) |
| `pylance-refactoring` | Use when the user explicitly asks for the Pylance refactoring skill, or when they want named automated Python refactorings applied to one file, many files, a workspace, a folder subset, or a composed cleanup workflow such as workspace-wide… | [Pylance](#source-pylance) |
| `python-add-type-annotations` | Use when the user explicitly asks for the Python type annotation skill, or when they want to make their own Python source type-safe by adding inline type annotations to one file, a set of files, or a package/workspace in bulk — annotating… | [Pylance](#source-pylance) |
| `python-fact-grounded-coding` | Use when the user explicitly asks for the Python fact-grounded coding skill, or when a Python coding, debugging, explanation, or bug-fix task should be grounded in verified Pylance facts, runtime values, diagnostics, selected interpreter… | [Pylance](#source-pylance) |
| `python-manager-discovery` | Environment manager-specific discovery patterns and known issues. Use when working on or reviewing environment discovery code for conda, poetry, pipenv, pyenv, or venv. | [Python Environments](#source-python-envs) |
| `python-type-inference` | Use when the user explicitly asks for the Python type inference skill, or when a task needs the single correct type for a specific Python symbol — a function return, parameter, module-level value, or class/instance field — and that type… | [Pylance](#source-pylance) |
| `python-write-stubs` | Use when the user explicitly asks for the Python stub-writing skill, wants to create or improve `.pyi` type stubs for a third-party Python package, or needs partial stubs under a workspace `typings/` directory without modifying installed… | [Pylance](#source-pylance) |
| `queues` | Vercel Queues guidance — durable topics with at-least-once delivery, independent consumer groups, retries, delays, and idempotency keys via @vercel/queue (JS) or vercel-queue (Python). Use when deferring background work, buffering traffic,… | [Vercel Plugin](#source-vercel-plugin) |
| `react-best-practices` | React best-practices reviewer for TSX files. Triggers after editing multiple TSX components to run a condensed quality checklist covering component structure, hooks usage, accessibility, performance, and TypeScript patterns. | [Vercel Plugin](#source-vercel-plugin) |
| `routing-middleware` | Vercel Routing Middleware guidance — request interception before cache, rewrites, redirects, personalization. Works with any framework. Supports Edge, Node.js, and Bun runtimes. Use when intercepting requests at the platform level. | [Vercel Plugin](#source-vercel-plugin) |
| `runtime-cache` | Vercel Runtime Cache API guidance — ephemeral per-region key-value cache with tag-based invalidation. Shared across Functions, Routing Middleware, and Builds. Use when implementing caching strategies beyond framework-level caching. | [Vercel Plugin](#source-vercel-plugin) |
| `settings-precedence` | VS Code settings precedence rules and common pitfalls. Essential for any code that reads or writes settings. Covers getConfiguration scope, inspect() vs get(), and multi-workspace handling. | [Python Environments](#source-python-envs) |
| `setup-ts-deep-modules` | Wire dependency-cruiser into a TypeScript repo so each package is a deep module — implementation hidden in subfolders, reachable only through its entry-point files. User-invoked. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `shadcn` | shadcn/ui expert guidance — CLI, component installation, composition patterns, custom registries, theming, Tailwind CSS integration, and high-quality interface design. Use when initializing shadcn, adding components, composing product UI,… | [Vercel Plugin](#source-vercel-plugin) |
| `sites` | Use Sites when the user wants a website built for them (including a landing page, portfolio, dashboard, portal, tracker, hub, game, event registration, or tool), requests changes to a website already built with Sites, wants to publish a… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `sites-remix` | Remix a Site built with the Sites plugin into a new Site. Use when the user has identified the source Site and asks to remix it. | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `turbopack` | Turbopack expert guidance. Use when configuring the Next.js bundler, optimizing HMR, debugging build issues, or understanding the Turbopack vs Webpack differences. | [Vercel Plugin](#source-vercel-plugin) |
| `typescript-setup` | How to set up a new TypeScript project | [typescript-setup / SKILL.md](skills/software-engineering/typescript-setup/SKILL.md) |
| `typescript-update` | Guidance for updating to the newer versions of TypeScript. Use this when you need to upgrade TypeScript or as part of a larger dependency update process. | [typescript-update / SKILL.md](skills/software-engineering/typescript-update/SKILL.md) |
| `uv` | Checks whether the uv Python package manager is installed and installs it if missing. Ensures uv is on PATH. Use when another skill requires uv as a prerequisite. | [Antigravity plugin: Science](#source-agy-science) |
| `vercel-composition-patterns` | React composition patterns that scale. Use when refactoring components with boolean prop proliferation, building flexible component libraries, or designing reusable APIs. Triggers on tasks involving compound components, render props,… | [Vercel Agent Skills](#source-vercel-agent-skills) |
| `vercel-functions` | Vercel Functions expert guidance — Node.js/Bun/Python runtimes, Fluid Compute, long-duration (30 min) functions, large functions (5 GB bundles), Docker/OCI container images, plan limits, streaming, WebSockets, and Cron Jobs. Use when… | [Vercel Plugin](#source-vercel-plugin) |
| `vercel-react-best-practices` | React and Next.js performance optimization guidelines from Vercel Engineering. This skill should be used when writing, reviewing, or refactoring React/Next.js code to ensure optimal performance patterns. Triggers on tasks involving React… | [Vercel Agent Skills](#source-vercel-agent-skills) · [Vercel Plugin](#source-vercel-plugin) |
| `vercel-react-native-skills` | React Native and Expo best practices for building performant mobile apps. Use when building React Native components, optimizing list performance, implementing animations, or working with native modules. Triggers on tasks involving React… | [Vercel Agent Skills](#source-vercel-agent-skills) |
| `vercel-services` | Configure and troubleshoot Vercel Services for multiple frontends and backends in one project. Use when composing a polyglot or multi-service application on one Vercel deployment; defining the `services` key, service-targeted rewrites, or… | [Vercel Plugin](#source-vercel-plugin) |
| `workflow` | Creates durable, resumable workflows using Vercel's Workflow SDK. Use when building workflows that need to survive restarts, pause for external events, retry on failure, or coordinate multi-step operations over time. Triggers on mentions… | [Vercel Plugin](#source-vercel-plugin) |
| `xcode-project-setup` | Safely modifies Xcode projects (.pbxproj) to add Swift Packages and link files. Use this skill whenever an iOS project needs dependencies installed (e.g. Firebase, Alamofire). | [Antigravity plugin: Firebase](#source-agy-firebase) |

Chưa xác minh được nguồn cài tương ứng cho `typescript-setup`, `typescript-update`; bản lưu được giữ để tra cứu.

[⬆️ Mục lục](#contents)

<a id="domain-testing-quality"></a>

## 🧪 Kiểm thử & chất lượng

Review code, QA, kiểm thử tự động, debug, đánh giá agent và hiệu năng.

| Skill | Công dụng | Nguồn / nội dung |
|---|---|---|
| `a11y-debugging` | Uses Chrome DevTools MCP for accessibility (a11y) debugging and auditing based on web.dev guidelines. Use when testing semantic HTML, ARIA labels, focus states, keyboard navigation, tap targets, and color contrast. | [Antigravity plugin: Chrome DevTools](#source-agy-chrome-devtools-plugin) |
| `benchmark-agents` | Advanced AI agent benchmark scenarios that push Vercel's cutting-edge platform features — Workflow SDK, AI Gateway, MCP, Chat SDK, Queues, Flags, Sandbox, and multi-agent orchestration. Designed to stress-test skill injection for complex,… | [Vercel Plugin](#source-vercel-plugin) |
| `benchmark-e2e` | End-to-end benchmark suite for vercel-plugin. Runs realistic projects through skill injection, launches dev servers, verifies everything works, analyzes conversation logs, and produces an improvement report for overnight self-improvement… | [Vercel Plugin](#source-vercel-plugin) |
| `benchmark-sandbox` | Run vercel-plugin eval scenarios in Vercel Sandboxes instead of local WezTerm panels. Provisions ephemeral microVMs with Claude Code + plugin pre-installed, runs benchmark prompts, extracts hook artifacts, and produces coverage reports. | [Vercel Plugin](#source-vercel-plugin) |
| `benchmark-testing` | Create and launch benchmark test projects to exercise vercel-plugin skill injection across realistic scenarios. Sets up isolated directories, installs the plugin, and spawns WezTerm panes running Claude Code with crafted prompts. | [Vercel Plugin](#source-vercel-plugin) |
| `code-review` | Perform a code review of the current session's changes. Use when the user requests a code review via the Run Code Review button in the Changes toolbar. | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `cookie-debugging` | Uses Chrome DevTools MCP for inspecting, debugging, and testing cookies, session state, authentication issues, and cookie consent compliance. Use when diagnosing 401/403 errors, authentication redirects, session expiration,… | [Antigravity plugin: Chrome DevTools](#source-agy-chrome-devtools-plugin) |
| `debug-failing-test` | Debug a failing test using an iterative logging approach, then clean up and document the learning. | [Python Environments](#source-python-envs) |
| `dogfood` | Systematically explore and test a web application to find bugs, UX issues, and other problems. Use when asked to "dogfood", "QA", "exploratory test", "find issues", "bug hunt", "test this app/site/platform", or review the quality of a web… | [Vercel Agent Browser](#source-vercel-browser) |
| `generate-snapshot` | Generate a codebase health snapshot for technical debt tracking and planning. Analyzes git history, code complexity, debt markers, and dependencies to identify hotspots and refactoring priorities. | [Python Environments](#source-python-envs) |
| `memory-leak-debugging` | Diagnoses and resolves memory leaks in JavaScript/Node.js applications. Use when a user reports high memory usage, OOM errors, or wants to capture, compare, or inspect heap snapshots with Chrome DevTools MCP memory tools. | [Antigravity plugin: Chrome DevTools](#source-agy-chrome-devtools-plugin) |
| `migrate-to-shoehorn` | Migrate test files from `as` type assertions to @total-typescript/shoehorn. Use when user mentions shoehorn, wants to replace `as` in tests, or needs partial test data. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `plugin-audit` | Audit vercel-plugin performance on real-world projects. Extracts tool calls from Claude Code conversation logs, tests hook matching against actual inputs, identifies pattern coverage gaps, and checks plugin cache staleness. Use when asked… | [Vercel Plugin](#source-vercel-plugin) |
| `ponytail` | Forces the simplest solution that works, with lite, full (default), and ultra modes. Use for any coding task (writing, fixing, refactoring, reviewing, or designing code, or choosing dependencies), or when the user says "ponytail", "be… | [Ponytail](#source-ponytail) · [ponytail / SKILL.md](skills/testing-quality/ponytail/SKILL.md) |
| `pylance-python-profiling` | Use when the user wants to profile Python code with Pylance: capture CPU time (Tachyon), trace calls (sys.monitoring), or memory (Memray); profile a whole run or a specific region between two source locations; add sub-region markers; and… | [Pylance](#source-pylance) |
| `qa` | Interactive QA session where user reports bugs or issues conversationally, and the agent files GitHub issues. Explores the codebase in the background for context and domain language. Use when user wants to report bugs, do QA, file issues… | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `review-agent` | Perform a read-only, defect-first review of a specified code change and return every actionable finding. Use when another agent delegates review of uncommitted changes, a base-branch diff, a commit, or custom review instructions. | [OpenAI Skills / Codex](#source-openai-skills) |
| `run-e2e-tests` | Run E2E tests to verify complete user workflows like environment discovery, creation, and selection. Use this before releases or after major changes. | [Python Environments](#source-python-envs) |
| `run-integration-tests` | Run integration tests to verify that extension components work together correctly. Use this after modifying component interactions or event handling. | [Python Environments](#source-python-envs) |
| `run-smoke-tests` | Run smoke tests to verify extension functionality in a real VS Code environment. Use this when checking if basic features work after changes. | [Python Environments](#source-python-envs) |
| `suggest-fix-issue` | Given the details of an issue, suggests a fix for the issue. | [GitHub Pull Requests](#source-github-pr) |
| `vercel-plugin-eval` | Run live eval sessions against the vercel-plugin to verify hook behavior, skill injection, dedup correctness, and coverage. Launches real Claude Code sessions via WezTerm, monitors debug logs, and produces a structured coverage report. | [Vercel Plugin](#source-vercel-plugin) |
| `verification` | Full-story verification — infers what the user is building, then verifies the complete flow end-to-end: browser → API → data → response. Triggers on dev server start and 'why isn't this working' signals. | [Vercel Plugin](#source-vercel-plugin) |
| `web-gui-tester` | Use the browser automation tooling available in the session to test web frontends interactively in a purely GUI-based, black-box manner: simulate real user clicks, text input, scrolling, and other actions; use screenshots for visual… | [ZCode Official Plugins](#source-zcode) |

### 💬 Prompt liên quan

- [review-branch](prompts/review-branch.md).

[⬆️ Mục lục](#contents)

<a id="domain-git-project-management"></a>

## 🔀 Git & quản lý công việc

Commit, merge, pull request, release, issue và quy trình Linear/GitHub.

| Skill | Công dụng | Nguồn / nội dung |
|---|---|---|
| `act-on-feedback` | Act on user feedback attached to the current session. Use when the user submits feedback on the session's changes via the Submit Feedback button. | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `address-pr-comments` | Address review comments (including Copilot comments) on the active pull request. Use when: responding to PR feedback, fixing review comments, resolving PR threads, implementing requested changes from reviewers, addressing code review,… | [GitHub Pull Requests](#source-github-pr) |
| `commit` | Commit staged or unstaged changes with an AI-generated commit message that matches the repository's existing commit style. Use when the user asks to 'commit', 'commit changes', 'create a commit', 'save my work', or 'check in code'. | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `create-draft-pr` | Create a draft pull request for the current session. Use when the user wants to open a draft PR with the session's changes. | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `create-pr` | Create a pull request for the current session. Use when the user wants to open a PR with the session's changes. | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `create-pull-request` | Create a GitHub Pull Request from the current or specified branch. Use when: opening a PR, submitting code for review, creating a draft PR, publishing a branch as a pull request, proposing changes to a repository. | [GitHub Pull Requests](#source-github-pr) |
| `form-github-search-query` | Forms a GitHub search query based on a natural language query and the type of search (issue or PR). This skill helps users create effective search queries to find relevant issues or pull requests on GitHub. | [GitHub Pull Requests](#source-github-pr) |
| `git-guardrails-claude-code` | Set up Claude Code hooks to block dangerous git commands (push, reset --hard, clean, branch -D, etc.) before they execute. Use when user wants to prevent destructive git operations, add git safety hooks, or block git push/reset in Claude… | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `linear-worktree` | Implement a Linear issue in an isolated Git worktree, validate the change, and prepare the requested commit, pull request, review, or QA handoff using the target repository's conventions. | [linear-worktree / SKILL.md](skills/git-project-management/linear-worktree/SKILL.md) |
| `merge` | Merge changes from the topic branch to the merge base branch. Use when the user wants to merge their session's work back to the base branch. | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `permissioned-github` | Guidelines for interacting with GitHub and request permissions from the user when commands fail due to restrictions in the agent environment. | [Google Antigravity — built-in](#source-antigravity-core) |
| `release` | Release vercel-plugin — run gates, bump version, generate artifacts, commit, and push. Use when asked to "release", "ship", "bump and push", or "cut a release". | [Vercel Plugin](#source-vercel-plugin) |
| `resolving-merge-conflicts` | Use when you need to resolve an in-progress git merge/rebase conflict. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `run-pre-commit-checks` | Run the mandatory pre-commit checks before committing code. Includes lint, type checking, and unit tests. MUST be run before every commit. | [Python Environments](#source-python-envs) |
| `setup-pre-commit` | Set up Husky pre-commit hooks with lint-staged (Prettier), type checking, and tests in the current repo. Use when user wants to add pre-commit hooks, set up Husky, configure lint-staged, or add commit-time formatting/typechecking/testing. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `show-github-search-result` | Summarizes the results of a GitHub search query in a human friendly markdown table that is easy to read and understand. ALWAYS use this skill when displaying the results of a GitHub search query. | [GitHub Pull Requests](#source-github-pr) |
| `summarize-github-issue-pr-notification` | Summarizes the content of a GitHub issue, pull request (PR), or notification, providing a concise overview of the main points and key details. ALWAYS use the skill when asked to summarize an issue, PR, or notification. | [GitHub Pull Requests](#source-github-pr) |
| `sync` | Sync the current session branch with its upstream branch, or publish the current session branch to a remote. Use when the user asks to sync a branch, pull latest changes, rebase onto upstream, push current branch, publish branch, or set… | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `sync-upstream` | Update a stale session branch by rebasing onto the latest origin. Use when the upstream has moved significantly and the session needs to catch up, resolving conflicts by preserving upstream changes and adapting session work to fit. | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `update-pr` | Update the pull request for the current session. Use when the user wants to push new changes to an existing PR. | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |

[⬆️ Mục lục](#contents)

<a id="domain-devops-operations"></a>

## 🚀 Hạ tầng & vận hành

Triển khai, CI/CD, môi trường, bảo mật, mạng, giám sát và xử lý sự cố.

| Skill | Công dụng | Nguồn / nội dung |
|---|---|---|
| `access-protected-vercel-deployment` | Access and test Vercel deployments protected by Vercel Authentication, SSO, or Deployment Protection. Use when curl, agent-browser, Playwright, or another automated request reaches a Vercel login or protection page; when a protected… | [Vercel Plugin](#source-vercel-plugin) |
| `cdn-caching` | Debug Vercel CDN caching — cache hit rate, stale content, revalidation behavior, ISR + PPR, per-request cache reasons (cacheReason) and PPR state (ppr_state), and costs. | [Vercel Plugin](#source-vercel-plugin) |
| `credentials` | Instructions for handling API keys and credentials safely, verifying their presence, and prompting the user to add them if missing using a safe protocol. | [Antigravity plugin: Science](#source-agy-science) |
| `custom-metrics` | Emit and query Vercel Custom Metrics. Use when instrumenting application or business measurements in Vercel Functions, using metric() from @vercel/functions, choosing metric names and attributes, or querying emitted values with vc metrics. | [Vercel Plugin](#source-vercel-plugin) |
| `debug-optimize-lcp` | Guides debugging and optimizing Largest Contentful Paint (LCP) using Chrome DevTools MCP tools. Use this skill whenever the user asks about LCP performance, slow page loads, Core Web Vitals optimization, or wants to understand why their… | [Antigravity plugin: Chrome DevTools](#source-agy-chrome-devtools-plugin) |
| `deployments-cicd` | Vercel deployment and CI/CD expert guidance. Use when deploying, promoting, rolling back, inspecting deployments, building with --prebuilt, or configuring CI workflow files for Vercel. | [Vercel Plugin](#source-vercel-plugin) |
| `domains` | Search, register, connect, transfer, and renew domain names on Vercel using the CLI or Domains Registrar API. Use for domain availability and pricing, custom domains, DNS records, nameservers, ownership verification, and domain orders. | [Vercel Plugin](#source-vercel-plugin) |
| `env-vars` | Vercel environment variable expert guidance. Use when working with .env files, vercel env commands, Secret or Config variable types, OIDC tokens, or managing environment-specific configuration. | [Vercel Plugin](#source-vercel-plugin) |
| `firebase-app-hosting-basics` | Deploys and manages full-stack web applications (Next.js, Angular) with Server-Side Rendering (SSR) using Firebase App Hosting. Use when deploying Next.js/Angular apps, configuring apphosting.yaml or firebase.json apphosting blocks,… | [Antigravity plugin: Firebase](#source-agy-firebase) |
| `firebase-crashlytics` | Comprehensive guide for Firebase Crashlytics, including provisioning and SDK usage. Use this skill when the user needs help setting up Crashlytics, adding crash reporting, or using the Crashlytics SDK in their application. | [Antigravity plugin: Firebase](#source-agy-firebase) |
| `firebase-hosting-basics` | Deploys and configures classic Firebase Hosting for static websites, single-page apps (SPAs), and microservices. Use when deploying static sites/SPAs, setting up custom domains, configuring firebase.json hosting settings (redirects,… | [Antigravity plugin: Firebase](#source-agy-firebase) |
| `firebase-security-rules-auditor` | Audits Firebase (Firestore, Cloud Storage) security rules for vulnerabilities, privilege escalation, role bypasses, create vs update inconsistencies, resource exhaustion, type safety, size limits, and hasOnly ownership checks. Use when… | [Antigravity plugin: Firebase](#source-agy-firebase) |
| `fix-ci` | Fix the failed CI checks for the current session. Use when the user requests a CI fix via the Fix Checks button in the Changes toolbar. | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `generate-run-commands` | Generate or modify run commands for the current session. Use when the user wants to set up or update run commands that appear in the session's Run button. | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `homepage-seo-performance` | Measure homepage SEO and browser performance for a supplied website or local deployment, create a baseline or comparable before/after report, and distinguish static HTML findings from runtime measurements. | [homepage-seo-performance / SKILL.md](skills/devops-operations/homepage-seo-performance/SKILL.md) |
| `querying-axiom` | Queries Axiom for observability data. Use when user mentions Axiom, traces, spans, APL, monitors, telemetry, latency, p99. | [querying-axiom / SKILL.md](skills/devops-operations/querying-axiom/SKILL.md) |
| `vercel-cli` | Deploy, manage, inspect, and troubleshoot Vercel projects from the command line. Use for Vercel deployments, Vercel Toolbar comments, build failures, projects and teams, environment variables, domains and DNS, logs, metrics, Speed… | [Vercel Plugin](#source-vercel-plugin) |
| `vercel-connect` | Vercel Connect expert guidance for securely obtaining scoped credentials for third-party services on behalf of apps or users. Use when wiring up provider API access, OAuth, API-key services, MCP servers, triggers, framework adapters, or… | [Vercel Plugin](#source-vercel-plugin) |
| `vercel-deploy` | Deploy applications and websites to Vercel. Use this skill when the user requests deployment actions such as "Deploy my app", "Deploy this to production", "Create a preview deployment", "Deploy and give me the link", or "Push this live".… | [Vercel Agent Skills](#source-vercel-agent-skills) |
| `vercel-firewall` | Vercel Firewall expert guidance — automatic DDoS mitigation, the Vercel WAF (custom rules, IP blocking, managed rulesets, rate limiting), Attack Mode, system bypass, bot management, and the `vercel firewall` CLI. Use when configuring… | [Vercel Plugin](#source-vercel-plugin) |
| `vercel-sandbox` | Run untrusted or AI-generated code in ephemeral Firecracker microVMs with @vercel/sandbox. Create a VM, run commands, read/write files, expose ports, snapshot and resume. Use for AI agents, code execution, builds, and isolated… | [Vercel Plugin](#source-vercel-plugin) |

[⬆️ Mục lục](#contents)

<a id="domain-data-analytics"></a>

## 📊 Dữ liệu & phân tích

SQL, cơ sở dữ liệu, schema, truy vấn, phân tích số liệu và trực quan hóa.

| Skill | Công dụng | Nguồn / nội dung |
|---|---|---|
| `atlas-stream-processing` | Manages MongoDB Atlas Stream Processing (ASP) workflows. Handles workspace provisioning, data source/sink connections, processor lifecycle operations, debugging diagnostics, and tier sizing. Supports Kafka, Atlas clusters, S3, HTTPS, and… | [MongoDB for VS Code](#source-mongodb) |
| `firebase-data-connect` | Builds and deploys Firebase SQL Connect (aka Firebase Data Connect) backends with PostgreSQL securely. Use when designing schemas with tables and relations, writing authorized queries and mutations, configuring real-time data updates, or… | [Antigravity plugin: Firebase](#source-agy-firebase) |
| `firebase-firestore` | Sets up, manages, queries, and configures Cloud Firestore databases (Standard/Enterprise edition), including data modeling, security rules, indexes, and SDK integrations (Web, Python, iOS, Android, Flutter). Use when creating/listing… | [Antigravity plugin: Firebase](#source-agy-firebase) |
| `firestore-rules-creation` | Designs, authors, refactors, and hardens production-grade Cloud Firestore Security Rules (firestore.rules). IMPORTANT: If subagent delegation AND the firestore-rules-author subagent are available in your environment, delegate authoring… | [Antigravity plugin: Firebase](#source-agy-firebase) |
| `mongodb-connection` | Optimize MongoDB client connection configuration (pools, timeouts, patterns) for any supported driver language. Use this skill when working/updating/reviewing on functions that instantiate or configure a MongoDB client (eg, when calling… | [MongoDB for VS Code](#source-mongodb) |
| `mongodb-natural-language-querying` | Generate read-only MongoDB queries (find) or aggregation pipelines using natural language, with collection schema context and sample documents. Use this skill whenever the user asks to write, create, or generate MongoDB queries, wants to… | [MongoDB for VS Code](#source-mongodb) |
| `mongodb-query-optimizer` | Help with MongoDB query optimization and indexing. Use only when the user asks for optimization or performance: "How do I optimize this query?", "How do I index this?", "Why is this query slow?", "Can you fix my slow queries?", "What are… | [MongoDB for VS Code](#source-mongodb) |
| `mongodb-schema-design` | MongoDB schema design patterns and anti-patterns. Use when designing data models, reviewing schemas, migrating from SQL, or troubleshooting performance issues caused by schema problems. Triggers on "design schema", "embed vs reference",… | [MongoDB for VS Code](#source-mongodb) |
| `mongodb-search-and-ai` | Guides MongoDB users through implementing and optimizing Atlas Search (full-text), Vector Search (semantic), and Hybrid Search solutions. Use this skill when users need to build search functionality for text-based queries (autocomplete,… | [MongoDB for VS Code](#source-mongodb) |
| `supabase` | Use when doing ANY task involving Supabase. Triggers: Supabase products (Database, Auth, Edge Functions, Realtime, Storage, Vectors, Cron, Queues); client libraries and SSR integrations (supabase-js, @supabase/ssr) in Next.js, React,… | [Supabase Agent Skills](#source-supabase) |
| `supabase-postgres-best-practices` | Postgres best practices maintained by Supabase, for Postgres running anywhere. Load this skill BEFORE writing or changing anything that lives in a Postgres database: creating or altering tables and columns (including choosing column… | [Supabase Agent Skills](#source-supabase) |
| `vercel-storage` | Vercel storage expert guidance — Blob, Global Config (formerly Edge Config), and Marketplace storage (Neon Postgres, Upstash Redis). Use when choosing, configuring, or using data storage with Vercel applications. | [Vercel Plugin](#source-vercel-plugin) |
| `visualize` | Create visualizations and interactive tools directly in conversation. Proactively use to show how something works; explore 'what happens when', 'what changes', or 'help me understand'; compare or inspect; create simulations, maps, charts,… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |

### 💬 Prompt liên quan

- [You are annotating Prisma schema columns with BigQuery descriptions](prompts/schema-annotator.md).

[⬆️ Mục lục](#contents)

<a id="domain-agents-automation"></a>

## 🤖 AI agent & tự động hóa

MCP, skill/plugin, cấu hình agent, browser/computer use và workflow tự động.

| Skill | Công dụng | Nguồn / nội dung |
|---|---|---|
| `agent-browser` | Browser automation CLI for AI agents. Use when the user needs to interact with websites, including navigating pages, filling forms, clicking buttons, taking screenshots, extracting data, testing web apps, or automating any browser task.… | [Vercel Agent Browser](#source-vercel-browser) |
| `agent-customization` | **WORKFLOW SKILL** — Create, update, review, fix, or debug VS Code agent customization files (.instructions.md, .prompt.md, .agent.md, SKILL.md, copilot-instructions.md, AGENTS.md). USE FOR: saving coding preferences; troubleshooting why… | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `agy-customizations` | Comprehensive guide and reference for the Antigravity Customization System. Use to explain how customizations work, their loading priority, discovery mechanisms, and to guide the creation of skills, rules, plugins, hooks, and MCP servers. | [Google Antigravity — built-in](#source-antigravity-core) |
| `antigravity-guide` | Provides a comprehensive guide, quick reference, and sitemap for Google Antigravity (AGY), including the Antigravity CLI (agy), Antigravity 2.0, Antigravity IDE, Python SDK, slash commands, keybindings, and customizations (skills, rules,… | [Google Antigravity — built-in](#source-antigravity-core) |
| `automation` | Interactive guide to design and create a scheduled background automation. Use this skill when the user wants to create an automated or recurring scheduled task (e.g. "summarize my emails every morning", "every Monday send me a to-do… | [Google Antigravity — built-in](#source-antigravity-core) |
| `built-in-browser` | Read this skill before the first step that uses the built-in browser, the browser pane inside the Claude desktop app (also called the in-app browser, the browser pane, Claude's browser, or "your own browser"), whose tools are named… | [Claude Cowork — built-in skills](#source-claude-cowork) |
| `chrome-browser` | Read this skill before the first step that uses Claude in Chrome, the browser extension whose tools are named mcp__claude-in-chrome__* (also called Chrome, the browser extension, or the external browser) and which acts in the person's real… | [Claude Cowork — built-in skills](#source-claude-cowork) |
| `chrome-devtools` | Uses Chrome DevTools via MCP for efficient debugging, troubleshooting and browser automation. Use when debugging web pages, automating browser interactions, analyzing performance, or inspecting network requests. This skill does not apply… | [Antigravity plugin: Chrome DevTools](#source-agy-chrome-devtools-plugin) |
| `claude-handoff` | Hand the current conversation off to a fresh background agent that picks up the work immediately. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `computer-use` | Use when a task needs a native desktop app's own UI or the OS. For anything inside a web page, use Browser Use. Main agent only. | [ZCode Official Plugins](#source-zcode) · [Claude Cowork — built-in skills](#source-claude-cowork) |
| `configure-mongodb-mcp` | Guide users through configuring key MongoDB MCP server options. Use this skill when a user wants to set up or modify their MongoDB MCP server configuration. | [MongoDB for VS Code](#source-mongodb) |
| `consolidate-memory` | Reflective pass over your memory files — merge duplicates, fix stale facts, prune the index. | [Claude Cowork — built-in skills](#source-claude-cowork) |
| `control-browser` | Use when opening, navigating, inspecting, testing, clicking, typing, filling, screenshotting, or verifying web pages and local HTTP targets (localhost, 127.0.0.1, ::1) inside ZCode, including browser/web-UI automation, rendered-page… | [ZCode Official Plugins](#source-zcode) |
| `diagnosing-commands` | Use to diagnose and fix ZCode custom slash-command (/command) configuration problems in the ZCode client. Applies when a command is missing, is overridden by a higher-precedence command of the same name, has a frontmatter parse error, is… | [ZCode Official Plugins](#source-zcode) |
| `diagnosing-hooks` | Use to diagnose and fix ZCode hook configuration problems in the ZCode client. Applies when a hook does not trigger, an event name is wrong, a matcher does not match a tool name, a script is not executable, template variables are not… | [ZCode Official Plugins](#source-zcode) |
| `diagnosing-mcp` | Use to diagnose and fix ZCode MCP (Model Context Protocol) server configuration problems in the ZCode client. Applies when an MCP server will not connect, its tools (mcp__server__tool) do not appear, it shows as disabled or failed,… | [ZCode Official Plugins](#source-zcode) |
| `diagnosing-plugins` | Use to diagnose and fix ZCode plugin and marketplace problems in the ZCode client. Applies when a plugin is not listed, adding a marketplace or installing a plugin fails, a plugin is enabled but its skills or commands are missing, a… | [ZCode Official Plugins](#source-zcode) |
| `diagnosing-skills` | Use to diagnose and fix ZCode skill configuration problems in the ZCode client. Applies when a skill is not discovered, is installed but does not trigger automatically, is shadowed by a higher-precedence skill of the same name, is disabled… | [ZCode Official Plugins](#source-zcode) |
| `explain-usage` | Explain where this session's tokens went, with one simple chart in plain language. Use when the user says things like "explain my usage", "where did my tokens go", or asks for a usage breakdown. | [Claude Cowork — built-in skills](#source-claude-cowork) |
| `find-skills` | Helps users discover and install agent skills when they ask questions like "how do I do X", "find a skill for X", "is there a skill that can...", or express interest in extending capabilities. This skill should be used when the user is… | [Vercel Skills CLI / find-skills](#source-vercel-skills-cli) |
| `import-memory` | Import a memory export from another AI assistant into Claude's memory — conversationally, additively, and with the content treated as data. | [Claude Cowork — built-in skills](#source-claude-cowork) |
| `marketplace` | Vercel Marketplace expert guidance — discovering, installing, and managing third-party integrations via the `vercel integration` CLI. Use when building any app that needs an external capability without a dedicated skill — commerce (stores,… | [Vercel Plugin](#source-vercel-plugin) |
| `migrate-customizations` | Guide a safe, reversible migration of VS Code local agent customizations when launched from the Agent Customizations Migrations page with VS Code-generated migration context. | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `migrate-workflows` | Automatically migrate legacy workflows to modern skills across global and workspace configurations. Scans for existing workflows, creates target SKILL.md files, and safely archives old workflow files. | [Google Antigravity — built-in](#source-antigravity-core) |
| `mongodb-mcp-setup` | Guide users through configuring key MongoDB MCP server options. Use this skill when a user has the MongoDB MCP server installed but hasn't configured the required environment variables, or when they ask about connecting to MongoDB/Atlas… | [MongoDB for VS Code](#source-mongodb) |
| `morning` | Render the user's morning brief as a styled HTML artifact, or set it up as a recurring weekday task. Use only when the user explicitly asks to run, see, or set up their morning brief, or if they invoke /morning by name. A question about… | [Claude Cowork — built-in skills](#source-claude-cowork) |
| `openai-docs` | Use for Codex models/pricing, scheduled tasks, skills, settings, setup, troubleshooting, customization, automations, and self-knowledge—including 'you,' 'your,' 'this app,' or 'this coding agent' when they refer to Codex—and for OpenAI… | [OpenAI Skills / Codex](#source-openai-skills) |
| `plugin` | How to manage and create plugins — namespaced bundles of skills, agents, rules, MCP servers and hooks that install, enable and disable as a single unit. Use this skill when the user wants to enable, disable, install or uninstall a plugin,… | [Google Antigravity — built-in](#source-antigravity-core) |
| `plugin-creator` | Create or update ZCode plugin source and a local test marketplace, then guide the user to add, install, update and try it in the app. Use for new plugins or changes to an existing plugin's capabilities, manifest or local distribution. | [ZCode Official Plugins](#source-zcode) |
| `plugin-management` | Discover and suggest relevant plugins, inspect app permissions and dependencies, and manage plugin connections or removal. Use when the user asks about plugins or when a task would materially benefit from an external app, account, service,… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `restore-legacy-sessions` | Use when ZCode needs to inspect, plan, or execute restoration of old ACP-era ZCode sessions from ~/.zcode/v2/sessions into the new ZCode task/session stores. Trigger when the user wants to choose a previous agent, select a workspace to… | [ZCode Official Plugins](#source-zcode) |
| `run-workflow` | How to write and run a dynamic workflow script with the `run_workflow` tool: a Python script that orchestrates many agents with `agent`, `parallel`, `pipeline`, and `phase`. Use when a task splits into many independent or staged pieces of… | [Google Antigravity — built-in](#source-antigravity-core) |
| `schedule` | Create or update a scheduled task that runs automatically. Use when the user says things like "every day", "each morning", "remind me in an hour", "run this at noon", or wants to reschedule an existing task. | [Claude Cowork — built-in skills](#source-claude-cowork) |
| `setup-claude` | Guided setup — install role-matched plugins, connect your tools, try a skill. | [Claude Cowork — built-in skills](#source-claude-cowork) |
| `setup-cowork` | Guided setup — install role-matched plugins, connect your tools, try a skill. | [Claude Cowork — built-in skills](#source-claude-cowork) |
| `skill-creator` | Create new skills, modify and improve existing skills, and measure skill performance. Use when users want to create a skill from scratch, edit, or optimize an existing skill, run evals to test a skill, benchmark skill performance with… | [Claude Cowork — built-in skills](#source-claude-cowork) · [OpenAI Skills / Codex](#source-openai-skills) · [ZCode Official Plugins](#source-zcode) |
| `skill-installer` | Install Codex skills into $CODEX_HOME/skills from a curated list or a GitHub repo path. Use when a user asks to list installable skills, install a curated skill, or install a skill from another repo (including private repos). | [OpenAI Skills / Codex](#source-openai-skills) |
| `troubleshoot` | Investigate unexpected chat agent behavior by analyzing direct debug logs in JSONL files. Use when users ask why something happened, why a request was slow, why tools or subagents were used or skipped, or why instructions/skills/agents did… | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `troubleshooting` | Uses Chrome DevTools MCP and documentation to troubleshoot connection and target issues. Trigger this skill when list_pages, new_page, or navigate_page fail, or when the server initialization fails. | [Antigravity plugin: Chrome DevTools](#source-agy-chrome-devtools-plugin) |
| `ui-plugin-navigation` | Discover UI plugin panels relevant to the current task and surface a one-click pill in chat to open (toggle) them in the side pane. Use when a running UI plugin's panel would help with what the user is doing, or right after the user… | [Google Antigravity — built-in](#source-antigravity-core) |
| `update-skills` | Create or update repository skills and instructions when major learnings are discovered during a session. Use when the user says "learn!", when a significant pattern or pitfall is identified, or when reusable domain knowledge should be… | [VS Code / GitHub Copilot — built-in skills](#source-vscode-builtins) |
| `vercel-agent` | Vercel Agent guidance — dashboard and Slack chat, code review, production investigation, approved actions, and product installation. Use when configuring or working with Vercel's AI assistant. | [Vercel Plugin](#source-vercel-plugin) |
| `workflow-skill-creator` | Distills a completed user workflow or interaction into a reusable agent skill. Use when the user asks to turn their workflow, interaction, or multi-step process into a skill, or when they say "make this a skill", "create a skill from what… | [Antigravity plugin: Science](#source-agy-science) |
| `writing-great-skills` | Reference for writing and editing skills well — the vocabulary and principles that make a skill predictable. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `zcode-configuration-guide` | Use when configuring ZCode's extension resources (MCP servers, slash commands, skills, hooks, and plugins) or instruction files such as AGENTS.md in the ZCode client. Explains where each resource is configured at the user and workspace… | [ZCode Official Plugins](#source-zcode) |

[⬆️ Mục lục](#contents)

<a id="domain-content-media"></a>

## ✍️ Nội dung & media

Viết bài, marketing, mạng xã hội, ảnh, video và nhân vật hoạt hình.

| Skill | Công dụng | Nguồn / nội dung |
|---|---|---|
| `create-pet` | Create, repair, validate, preview, upload, or activate an animated v2 pet in ChatGPT Work mode from a character idea, brand cue, or reference image. Use for new ChatGPT Pets, custom mascots, non-pixel styles, and unattached sprite sheets… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `edit-article` | Edit and improve articles by restructuring sections, improving clarity, and tightening prose. Use when user wants to edit, revise, or improve an article draft. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `imagegen` | Generate or edit raster images when the task benefits from AI-created bitmap visuals such as photos, illustrations, textures, sprites, mockups, or transparent-background cutouts. Use when Codex should create a brand-new image, transform an… | [OpenAI Skills / Codex](#source-openai-skills) |
| `marketing-plan` | Build an actionable marketing plan for a product, service, or personal brand using the user's goals, audience, offer, budget, channels, and timeline, without depending on a product catalog or platform-specific tool. | [marketing-plan / SKILL.md](skills/content-media/marketing-plan/SKILL.md) |
| `pets` | List, inspect, select, download, or delete animated pets in ChatGPT Work mode. Use for an explicit pet in ChatGPT or established ChatGPT Pets context. Exclude real-world and other-app pets; clarify before invoking. | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `update-pet` | Inspect, validate, preview, repair, or update a custom pet in ChatGPT Work mode, including its name, description, or sprite sheet. Use for a pet in ChatGPT or established ChatGPT Pets context. Exclude real-world and other-app pets; clarify… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `writing-beats` | Writing, exploit — assemble raw material into a journey of beats, grounding each term before a beat leans on it. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `writing-fragments` | Writing, explore — mine raw fragments, no structure yet. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `writing-shape` | Writing, exploit — shape raw material into an article, paragraph by paragraph. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |

### 💬 Prompt liên quan

- [Prompt tối ưu cho AI tạo ảnh – Portfolio Game Card](prompts/portfolio-game-card.md).

[⬆️ Mục lục](#contents)

<a id="domain-documents-office"></a>

## 📄 Tài liệu & công việc văn phòng

Word/PDF, bảng tính, slide, biểu mẫu, template và ghi chép.

| Skill | Công dụng | Nguồn / nội dung |
|---|---|---|
| `artifact-template-analytics-dashboard` | Create a spreadsheet using the Analytics Dashboard template and its retained reference file. Use when the user selects or names Analytics Dashboard. Monitor acquisition, engagement, retention, revenue, and conversion funnel KPIs with… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-business-review` | Create a presentation using the Business Review template and its retained reference file. Use when the user selects or names Business Review. Review business performance, KPIs, segment results, strategic priorities, decisions, and outlook. | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-design-report` | Create a document using the Design Report template and its retained reference file. Use when the user selects or names Design Report. Produce design reports with an executive summary, key findings, implications, recommendations, and… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-experiment-analysis` | Create a document using the Experiment Analysis template and its retained reference file. Use when the user selects or names Experiment Analysis. Analyze experiments with hypotheses, methodology, results, interpretation, limitations, and… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-financial-budget` | Create a spreadsheet using the Financial Budget template and its retained reference file. Use when the user selects or names Financial Budget. Model actuals, budget and scenario forecasts, variances, cash runway, and departmental plans. | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-investment-committee-memo` | Create a document using the Investment Committee Memo template and its retained reference file. Use when the user selects or names Investment Committee Memo. Prepare investment committee memos with the thesis, transaction details,… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-legal-memorandum` | Create a document using the Legal Memorandum template and its retained reference file. Use when the user selects or names Legal Memorandum. Draft legal memoranda with the issue, brief answer, relevant facts, analysis, and conclusion. | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-market-trends-report` | Create a presentation using the Market Trends Report template and its retained reference file. Use when the user selects or names Market Trends Report. Communicate market or industry trends, supporting evidence, implications, and… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-minimal-letterhead` | Create a document using the Minimal Letterhead template and its retained reference file. Use when the user selects or names Minimal Letterhead. Write professional business letters with sender, recipient, message, and signature fields in a… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-operating-calendar` | Create a spreadsheet using the Operating Calendar template and its retained reference file. Use when the user selects or names Operating Calendar. Plan annual and monthly operating milestones, campaigns, launches, deadlines, and recurring… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-operating-review` | Create a presentation using the Operating Review template and its retained reference file. Use when the user selects or names Operating Review. Run weekly operating reviews with scorecards, functional updates, risks, decisions, and action… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-project-kickoff` | Create a presentation using the Project Kickoff template and its retained reference file. Use when the user selects or names Project Kickoff. Align teams on project goals, scope, roles, milestones, risks, and the working model. | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-project-tracker` | Create a spreadsheet using the Project Tracker template and its retained reference file. Use when the user selects or names Project Tracker. Manage workstreams, tasks, owners, status, priority, dates, launch pulse, and a Gantt schedule. | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-sales-pipeline` | Create a spreadsheet using the Sales Pipeline template and its retained reference file. Use when the user selects or names Sales Pipeline. Track opportunities, stages, owners, deal sizes, probabilities, forecasts, next steps, and risks. | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-simple-dark-mode` | Create a presentation using the Simple Dark Mode template and its retained reference file. Use when the user selects or names Simple Dark Mode. Create clean dark-mode presentations with bold typography, simple sections, charts, and imagery. | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-simple-light-mode` | Create a presentation using the Simple Light Mode template and its retained reference file. Use when the user selects or names Simple Light Mode. Create clean light-mode presentations with spacious typography, simple sections, charts, and… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-strategy-memorandum` | Create a document using the Strategy Memorandum template and its retained reference file. Use when the user selects or names Strategy Memorandum. Present strategic context, choices, rationale, risks, milestones, and a clear recommendation. | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-system-design` | Create a document using the System Design template and its retained reference file. Use when the user selects or names System Design. Document system architecture, requirements, components, data flows, APIs, tradeoffs, and operational… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-team-alignment` | Create a presentation using the Team Alignment template and its retained reference file. Use when the user selects or names Team Alignment. Facilitate team offsites and planning with context, goals, priorities, decisions, and action items. | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `artifact-template-three-statement-forecast` | Create a spreadsheet using the Three-Statement Forecast template and its retained reference file. Use when the user selects or names Three-Statement Forecast. Build an integrated income statement, balance sheet, and cash flow forecast with… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `docs` | docs (editable docs people share and comment on; the default for any document, named as a doc or not: a document, report, proposal, resume, cover letter, letter, contract, policy, form, template, worksheet, essay, handbook, guide, how-to,… | [Claude Cowork — built-in skills](#source-claude-cowork) |
| `documents` | Create, edit, redline, and comment on `.docx`, Word, and Google Docs-targeted document artifacts inside the container, with a strict render-and-verify workflow. Use `render_docx.py` to generate page PNGs (and optional PDF) for visual QA,… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `docx` | Complete DOCX document creation, editing, and analysis capabilities with support for revisions, comments, formatting preservation, and text extraction. Also handles Word format conversion: legacy .doc → .docx, DOCX → PDF, DOCX → images… | [ZCode Official Plugins](#source-zcode) · [Claude Cowork — built-in skills](#source-claude-cowork) |
| `excel-live-control` | Control an open or active Microsoft Excel workbook through the ChatGPT add-in or connected session. Use when the user tags the Microsoft Excel app in Codex or follows up on an established live Excel task. Do not use for standalone… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `google-workspace` | Read this before the first Google Drive, Docs, Sheets or Slides connector call whenever the task creates or changes a Google file. Use this skill whenever the user wants to create or change a Google Doc, Sheet or Slides file in their… | [Claude Cowork — built-in skills](#source-claude-cowork) |
| `obsidian-vault` | Search, create, and manage notes in the Obsidian vault with wikilinks and index notes. Use when user wants to find, create, or organize notes in Obsidian. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `pdf` | Professional PDF toolkit covering four production workflows: reports, creative visuals, academic LaTeX, and existing PDF processing. Routes automatically by document type and supports reports, posters, papers, resumes, extraction, merging,… | [ZCode Official Plugins](#source-zcode) · [ChatGPT / Codex — plugin skills](#source-openai-plugins) · [Claude Cowork — built-in skills](#source-claude-cowork) |
| `pptx` | Use this skill any time a presentation file is the primary input or output. Covers: creating new .pptx decks from scratch or from an outline/document (pptxgenjs / python-pptx); editing and restyling an existing .pptx; reading and… | [ZCode Official Plugins](#source-zcode) · [Claude Cowork — built-in skills](#source-claude-cowork) |
| `Presentations` | Read, create or edit PowerPoint or Google Slides decks. Use for presentation, slide deck, PowerPoint, PPT, PPTX, or Google Slides requests. | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `Spreadsheets` | Use skill when user requests to create, modify, analyze, visualize, or work with spreadsheet files (`.xlsx`, `.xls`, `.csv`, `.tsv`) or Google Sheets with formulas, formatting, charts, tables, and recalculation. Do not use for live… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `template-creator` | Create or update a reusable personal Codex artifact-template skill. Use when the user invokes $template-creator or asks in natural language to create a reusable template from a reference document, presentation, spreadsheet, Google Docs,… | [ChatGPT / Codex — plugin skills](#source-openai-plugins) |
| `xlsx` | Use this skill any time a spreadsheet file is the primary input or output. This means any task where the user wants to: open, read, edit, or fix an existing .xlsx, .xlsm, .csv, or .tsv file; create a new spreadsheet from scratch or from… | [ZCode Official Plugins](#source-zcode) · [Claude Cowork — built-in skills](#source-claude-cowork) |

[⬆️ Mục lục](#contents)

<a id="domain-research-science"></a>

## 🔬 Nghiên cứu khoa học & học thuật

Tìm tài liệu nghiên cứu, sinh học, hóa học, cơ sở dữ liệu khoa học và khảo cứu.

| Skill | Công dụng | Nguồn / nội dung |
|---|---|---|
| `alphafold-database-fetch-and-analyze` | Retrieve and analyze AlphaFold predicted structures for a protein. Use when the user provides a specific UniProt Accession ID and wants structural confidence metrics (pLDDT), domain boundary analysis, or disorder assessment. Do not use if… | [Antigravity plugin: Science](#source-agy-science) |
| `alphagenome-atlas-website-links` | Constructs deep-links and URLs for the AlphaGenome Atlas website. Supports generating single-variant exploration links (1-based VCF-style coordinates), genomic locus views (1-based closed chr:start-end), candidate summary tables, and… | [Antigravity plugin: Science](#source-agy-science) |
| `alphagenome-single-variant-analysis` | Analyzes genetic variant effects on gene expression (RNA-seq), chromatin accessibility (DNASE), histone marks (ChIP), and transcription factors using the AlphaGenome API. Use when the user asks about non-coding variant effects,… | [Antigravity plugin: Science](#source-agy-science) |
| `alphagenome-variant-impact-score` | Score, annotate, and analyze the functional impact of genetic variants using AlphaGenome Variant Impact (AVI) scores. Query variants in chr:pos:ref>alt format, annotate VCF/tabular callsets, perform saturation mutagenesis window scans… | [Antigravity plugin: Science](#source-agy-science) |
| `biomolecular-structure-viewer` | Interactive 3D biomolecular structure viewer via Mol*. Renders 3D molecular structures from local workspace files (.cif, .mmcif, .pdb) or conversation artifacts, and manages user 3D annotations and highlighted residues. Use when the user… | [Antigravity plugin: Science](#source-agy-science) |
| `chembl-database` | Query the ChEMBL database for bioactive molecules, drug targets, bioactivity data, approved drugs, and chemical structures. Use when the user asks about compounds, targets, IC50/Ki values, drug mechanisms, or structure searches. | [Antigravity plugin: Science](#source-agy-science) |
| `clinical-trials-database` | Query ClinicalTrials.gov via APIv2. Use when you want to search for trials by condition, drug, location, status, or phase; retrieve trial details by NCT ID; check eligibility/inclusion criteria; count trials across conditions or time… | [Antigravity plugin: Science](#source-agy-science) |
| `clinvar-database` | Use when needing clinical significance, pathogenicity classifications (e.g., Pathogenic, Benign, VUS), clinical evidence rationales, or finding "hard positive" benchmark controls for human genomic variants. | [Antigravity plugin: Science](#source-agy-science) |
| `dbsnp-database` | Use when you want to look up, map, and search for short genetic variants (SNPs, indels) in NCBI's dbSNP database. Resolves between rsIDs, genomic coordinates in VCF format, and HGVS strings. For an rsID, returns variant type, gene… | [Antigravity plugin: Science](#source-agy-science) |
| `deep-research` | Use this skill when the user's prompt requires (1) researching a topic across multiple sources, comparing options or alternatives, analyzing trends or history, understanding markets or industries, or reviewing literature or studies and (2)… | [Claude Cowork — built-in skills](#source-claude-cowork) |
| `embl-ebi-ols` | Query and search the EMBL-EBI Ontology Lookup Service (OLS) for biomedical ontology terms, definitions, and hierarchies across 250+ ontologies (e.g., GO, DOID, HP). Use when the user asks to search for terms, retrieve details, navigate… | [Antigravity plugin: Science](#source-agy-science) |
| `encode-ccres-database` | Query the ENCODE Registry of cis-Regulatory Elements (cCREs) via the SCREEN GraphQL API, or make custom queries to the ENCODE Portal REST API for experiments and files (ChIP-seq peaks, etc.). Use when you want to query regulatory… | [Antigravity plugin: Science](#source-agy-science) |
| `ensembl-database` | Query the Ensembl database to resolve gene, transcript, and protein IDs, fetch genomic or protein sequences, retrieve gene structures (exons), and get variant consequence and effect predictions (VEP). Use this skill as a primary ID… | [Antigravity plugin: Science](#source-agy-science) |
| `foldseek-structural-search` | Performs 3D structural searches of proteins against various databases (PDB, AlphaFold, CATH, MGnify, etc.) using the Foldseek API. Use ONLY when the user provides a physical 3D coordinate file (.cif, .mmcif, or .pdb) and wants to find… | [Antigravity plugin: Science](#source-agy-science) |
| `gnomad-database` | Query the Genome Aggregation Database (gnomAD). Use when determining the rarity or allele frequency of specific genetic variants, retrieving gene constraint metrics (pLI, LOEUF) to assess loss-of-function intolerance, finding variants in a… | [Antigravity plugin: Science](#source-agy-science) |
| `gtex-database` | Use when you want to retrieve quantitative RNA expression data and variant eQTL information from the GTEx (Genotype-Tissue Expression) Project across 54 non-diseased tissue sites. | [Antigravity plugin: Science](#source-agy-science) |
| `human-protein-atlas-database` | Use when you want to retrieve semi-quantitative protein expression and spatial localisation data from the Human Protein Atlas (HPA). | [Antigravity plugin: Science](#source-agy-science) |
| `interpro-database` | Identify domains, families, and sites in proteins; find all proteins in a family or sharing a domain; explore species distribution for a domain; annotate genomes with protein families and GO terms. InterPro combines 14 databases (e.g.,… | [Antigravity plugin: Science](#source-agy-science) |
| `jaspar-database` | Query the JASPAR database for Transcription Factor (TF) binding profiles. Use when retrieving Position Frequency Matrices (PFMs) or Position Weight Matrices (PWMs) for specific TFs, resolving gene symbols to JASPAR Matrix IDs, or getting… | [Antigravity plugin: Science](#source-agy-science) |
| `literature-search-arxiv` | Search for scientific papers, preprints, and publications on arXiv. Extract metadata, abstracts, and download full-text PDFs or HTML versions of papers. Use when the user asks to find research papers, literature, or specific arXiv IDs. | [Antigravity plugin: Science](#source-agy-science) |
| `literature-search-biorxiv` | Browse, filter, and download life sciences, biology, and medical preprints from bioRxiv and medRxiv. Supports fetching paper metadata by DOI, and browsing by date range with category and keyword filters. Keyword filtering is local, so date… | [Antigravity plugin: Science](#source-agy-science) |
| `literature-search-europepmc` | Search Europe PMC for scientific literature and download open-access full texts and PDFs. Retrieve full-text XML/plain text by PMCID, get citation lists and bibliography. | [Antigravity plugin: Science](#source-agy-science) |
| `literature-search-openalex` | Query the OpenAlex scholarly database for research papers, authors, institutions, topics, sources, publishers, funders, geo-locations, and keywords. Use when searching academic papers, resolving DOIs, downloading open-access PDFs, finding… | [Antigravity plugin: Science](#source-agy-science) |
| `ncbi-sequence-fetch` | Retrieve protein and nucleotide sequences from NCBI databases using E-utilities. Supports direct accession lookup, CDS translation, gene+organism search, locus lookup, PubMed-linked sequences, patent protein extraction, and organism+length… | [Antigravity plugin: Science](#source-agy-science) |
| `openfda-database` | Query, search, and download data from the openFDA API for drugs, devices, foods, tobacco, cosmetics, animal and veterinary products, substances, and transparency data. Use for FDA adverse events, recalls, labeling, approvals, shortages,… | [Antigravity plugin: Science](#source-agy-science) |
| `opentargets-database` | Query Open Targets Platform for target-disease associations, drug target discovery, tractability/safety data, genetics/omics evidence, known drugs, for therapeutic target identification. | [Antigravity plugin: Science](#source-agy-science) |
| `pdb-database` | Use when you want to search for or download experimentally-determined 3D structures for biomolecules (proteins, nucleic acids, bound ligands). Supports searching by sequence similarity, structure similarity, chemical and other attributes.… | [Antigravity plugin: Science](#source-agy-science) |
| `predictingthepast` | Ancient text restoration, attribution, dating, contextualization, and embedding via Aeneas (Latin) / Ithaca (Ancient Greek). Use when asked to "restore", "attribute", "date", "contextualize", "find parallels", "where was it written", "when… | [Antigravity plugin: Science](#source-agy-science) |
| `protein-sequence-msa` | Performs multiple sequence alignment of proteins with EBI Clustal Omega. Use when you need to align multiple sequences to assess similarity, domain conservation, or key residue conservation. Supports up to 4000 sequences and a maximum file… | [Antigravity plugin: Science](#source-agy-science) |
| `protein-sequence-similarity-search` | Searches for homologous protein sequences using MMseqs2 (fast, default) or BLAST (comprehensive, fallback). Trigger this whenever the user provides a protein sequence or FASTA file and asks to find homologues, sequence matches, or wants to… | [Antigravity plugin: Science](#source-agy-science) |
| `pubchem-database` | Query PubChem, search by name/CID/SMILES, retrieve properties, similarity/substructure searches, bioactivity, for cheminformatics. Use when a user asks about a specific chemical, drug, or molecule. | [Antigravity plugin: Science](#source-agy-science) |
| `pubmed-database` | Search PubMed for scientific literature, including published clinical trials. Fetch abstracts and full text. Link published research to biological databases (gene, protein, nucleotide, PubChem) to discover associations between papers and… | [Antigravity plugin: Science](#source-agy-science) |
| `pymol` | Visualize, analyze, and render protein and molecular structures using PyMOL. Use when the user wants to create images of protein structures, perform structural alignments or superposition, measure distances or contacts, highlight binding… | [Antigravity plugin: Science](#source-agy-science) |
| `quickgo-database` | Query the QuickGO and Evidence & Conclusion Ontology (ECO) REST API. Use this when you need to map genes to biological processes, molecular functions, or cellular components, find genes associated with a specific pathway/GO term, or… | [Antigravity plugin: Science](#source-agy-science) |
| `reactome-database` | Query the Reactome database (Analysis and Content Services). Use when the user asks about pathway analysis, gene list enrichment, retrieving results by token, finding unmapped or not-found identifiers, mapping identifiers, reaction… | [Antigravity plugin: Science](#source-agy-science) |
| `string-database` | Query the STRING database for protein-protein interactions (PPIs), functional enrichment, and homology. Use when the user asks about interactions between specific proteins, interaction evidence, confidence scores, protein interaction… | [Antigravity plugin: Science](#source-agy-science) |
| `ucsc-conservation-and-tfbs` | Fetch Evolutionary Conservation scores (phyloP, phastCons) and Transcription Factor Binding Sites (TFBS) from the UCSC Genome Browser. Use when analyzing whether genomic variants or regions are evolutionarily conserved, functionally… | [Antigravity plugin: Science](#source-agy-science) |
| `unibind-database` | Queries the UniBind database for experimentally validated transcription factor (TF) binding sites. Use when retrieving direct TF-DNA interaction datasets, downloading binding site coordinates (BED/FASTA) for local analysis, or listing… | [Antigravity plugin: Science](#source-agy-science) |
| `uniprot-database` | Access protein metadata, function, taxonomy, and sequences across UniProtKB, UniParc, and UniRef. Use when searching for proteins, mapping identifiers, or retrieving functional annotations and publications. Don't use for sequence… | [Antigravity plugin: Science](#source-agy-science) |

[⬆️ Mục lục](#contents)

<a id="domain-planning-learning"></a>

## 🧠 Tư duy, lập kế hoạch & học tập

Phản biện ý tưởng, làm rõ yêu cầu, thiết kế kế hoạch và học qua trao đổi.

| Skill | Công dụng | Nguồn / nội dung |
|---|---|---|
| `ask-matt` | Ask which skill or flow fits your situation. A router over the skills in this repo. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `grill-me` | A relentless interview to sharpen a plan or design. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `grilling` | Grill the user relentlessly about a plan, decision, or idea. Use when the user wants to stress-test their thinking, or uses any 'grill' trigger phrases. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `loop-me` | Grill me about specs for the workflows I want to build, within this workspace. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `request-refactor-plan` | Create a detailed refactor plan with tiny commits via user interview, then file it as a GitHub issue. Use when user wants to plan a refactor, create a refactoring RFC, or break a refactor into safe incremental steps. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `scaffold-exercises` | Create exercise directory structures with sections, problems, solutions, and explainers that pass linting. Use when user wants to scaffold exercises, create exercise stubs, or set up a new course section. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `teach` | Teach the user a new skill or concept, within this workspace. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `to-questionnaire` | Turn a decision you can't fully answer into a questionnaire for someone else to fill in. | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `ubiquitous-language` | Extract a DDD-style ubiquitous language glossary from the current conversation, flagging ambiguities and proposing canonical terms. Saves to UBIQUITOUS_LANGUAGE.md. Use when user wants to define domain terms, build a glossary, harden… | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |
| `wizard` | Generate an interactive bash wizard that walks a human through a manual procedure — third-party setup, a one-off migration, an A→B state transition — opening URLs, capturing values, confirming each step, and writing .env files and GitHub… | [Matt Pocock / Skills for Real Engineers](#source-mattpocock) |

### 💬 Prompt liên quan

- [skill-requirements-interviewer](prompts/skill-requirements-interviewer.md).

[⬆️ Mục lục](#contents)

<a id="installation"></a>

## 📦 Nguồn và cách cài

Các hướng dẫn dưới đây dùng để tra cứu. Cài đặt mới có thể lấy nội dung khác bản đã kiểm kê; chọn đúng agent, gói và phiên bản theo upstream. Những skill đi kèm ứng dụng hoặc plugin không nhất thiết có lệnh cài riêng.

<a id="source-agy-android-cli-plugin"></a>

### Antigravity plugin: Android

Nguồn: [Antigravity plugin: Android](https://antigravity.google/docs/marketplace/).

Trong Google Antigravity, mở Customizations / Plugins và chọn plugin `android-cli-plugin`. Xem hướng dẫn marketplace upstream.

<a id="source-agy-chrome-devtools-plugin"></a>

### Antigravity plugin: Chrome DevTools

Nguồn: [Antigravity plugin: Chrome DevTools](https://github.com/ChromeDevTools/chrome-devtools-mcp).

Trong Google Antigravity, mở Customizations / Plugins và chọn plugin `chrome-devtools-plugin`. Xem hướng dẫn marketplace upstream.

<a id="source-agy-firebase"></a>

### Antigravity plugin: Firebase

Nguồn: [Antigravity plugin: Firebase](https://github.com/firebase/agent-skills).

Trong Google Antigravity, mở Customizations / Plugins và chọn plugin `firebase`. Xem hướng dẫn marketplace upstream.

<a id="source-agy-google-antigravity-sdk"></a>

### Antigravity plugin: Google Antigravity SDK

Nguồn: [Antigravity plugin: Google Antigravity SDK](https://antigravity.google/docs/marketplace/).

Trong Google Antigravity, mở Customizations / Plugins và chọn plugin `google-antigravity-sdk`. Xem hướng dẫn marketplace upstream.

<a id="source-agy-modern-web-guidance-plugin"></a>

### Antigravity plugin: Modern Web Guidance

Nguồn: [Antigravity plugin: Modern Web Guidance](https://github.com/GoogleChrome/modern-web-guidance).

Trong Google Antigravity, mở Customizations / Plugins và chọn plugin `modern-web-guidance-plugin`. Xem hướng dẫn marketplace upstream.

<a id="source-agy-science"></a>

### Antigravity plugin: Science

Nguồn: [Antigravity plugin: Science](https://antigravity.google/use-cases/science).

Trong Google Antigravity, mở Customizations / Plugins và chọn plugin `science`. Xem hướng dẫn marketplace upstream.

<a id="source-awesome-design"></a>

### Awesome Claude Design

Nguồn: [Awesome Claude Design](https://github.com/VoltAgent/awesome-claude-design).

Theo hướng dẫn cài skill trong README upstream; dữ liệu DESIGN.md lấy từ cùng repository.

<a id="source-openai-plugins"></a>

### ChatGPT / Codex — plugin skills

Nguồn: [ChatGPT / Codex — plugin skills](https://developers.openai.com/plugins/concepts/plugins).

Dùng plugin/khả năng tương ứng trong ChatGPT hoặc Codex. Quyền truy cập plugin phụ thuộc tài khoản. Các runtime tích hợp không có lệnh cài skill độc lập.

Các gói đã thấy gồm Sites, Work Pets, Visualize, Plugin Management, OpenAI Templates và runtime Documents/PDF/Presentations/Spreadsheets/Template Creator. Runtime tích hợp được dùng qua sản phẩm tương ứng; chưa xác nhận gói cài SKILL.md độc lập cho từng runtime.

<a id="source-claude-cowork"></a>

### Claude Cowork — built-in skills

Nguồn: [Claude Cowork — built-in skills](https://support.claude.com/en/articles/13345190-get-started-with-claude-cowork).

Dùng Claude Cowork; đây là các skill đi kèm phiên/ứng dụng được tìm thấy trên máy. Chưa xác nhận gói SKILL.md độc lập.

<a id="source-design-motion"></a>

### Design Motion Principles

Nguồn: [Design Motion Principles](https://github.com/kylezantos/design-motion-principles).

```sh
npx skills add kylezantos/design-motion-principles
```

<a id="source-github-pr"></a>

### GitHub Pull Requests

Nguồn: [GitHub Pull Requests](https://marketplace.visualstudio.com/items?itemName=GitHub.vscode-pull-request-github).

Cài extension `GitHub.vscode-pull-request-github` trong editor tương thích. Skill nội bộ/phát triển extension cần đúng phiên bản và không nhất thiết hiện thành slash command.

<a id="source-antigravity-core"></a>

### Google Antigravity — built-in

Nguồn: [Google Antigravity — built-in](https://antigravity.google/).

Cài hoặc cập nhật Google Antigravity; đây là skill đi kèm ứng dụng, không có lệnh cài skill riêng.

<a id="source-mattpocock"></a>

### Matt Pocock / Skills for Real Engineers

Nguồn: [Matt Pocock / Skills for Real Engineers](https://github.com/mattpocock/skills).

```sh
npx skills@latest add mattpocock/skills
```

<a id="source-mongodb"></a>

### MongoDB for VS Code

Nguồn: [MongoDB for VS Code](https://marketplace.visualstudio.com/items?itemName=mongodb.mongodb-vscode).

Cài extension `mongodb.mongodb-vscode` trong editor tương thích. Skill nội bộ/phát triển extension cần đúng phiên bản và không nhất thiết hiện thành slash command.

<a id="source-openai-skills"></a>

### OpenAI Skills / Codex

Nguồn: [OpenAI Skills / Codex](https://github.com/openai/skills).

Skill hệ thống đi kèm Codex; skill curated như figma lấy từ catalog openai/skills. Xem README upstream.

<a id="source-page-mascot"></a>

### Page Mascot

Nguồn: [Page Mascot](https://github.com/nilbuild/page-mascot).

```sh
npx skills add nilbuild/page-mascot --skill page-mascot
```

<a id="source-ponytail"></a>

### Ponytail

Nguồn: [Ponytail](https://github.com/DietrichGebert/ponytail).

Theo INSTALL.md upstream, chọn đúng agent. Bản hiện tại có thể khác bản đã kiểm kê.

<a id="source-pylance"></a>

### Pylance

Nguồn: [Pylance](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-pylance).

Cài extension `ms-python.vscode-pylance` trong editor tương thích. Skill nội bộ/phát triển extension cần đúng phiên bản và không nhất thiết hiện thành slash command.

<a id="source-python-envs"></a>

### Python Environments

Nguồn: [Python Environments](https://marketplace.visualstudio.com/items?itemName=ms-python.vscode-python-envs).

Cài extension `ms-python.vscode-python-envs` trong editor tương thích. Skill nội bộ/phát triển extension cần đúng phiên bản và không nhất thiết hiện thành slash command.

<a id="source-supabase"></a>

### Supabase Agent Skills

Nguồn: [Supabase Agent Skills](https://github.com/supabase/agent-skills).

```sh
npx skills add supabase/agent-skills
```

<a id="source-design-taste"></a>

### Taste Skill

Nguồn: [Taste Skill](https://github.com/Leonxlnx/taste-skill).

```sh
npx skills add Leonxlnx/taste-skill --skill design-taste-frontend
```

<a id="source-uidotsh"></a>

### ui.sh — remote UI skill

Nguồn: [ui.sh — remote UI skill](https://ui.sh/).

Thiết lập tích hợp từ ui.sh theo hướng dẫn của dịch vụ. Skill trên máy chỉ là wrapper tải nội dung uidotsh://ui qua MCP; cần kết nối dịch vụ, không có bộ nội dung độc lập trong file đã kiểm kê.

<a id="source-ui-ux-pro-max"></a>

### UI/UX Pro Max

Nguồn: [UI/UX Pro Max](https://github.com/nextlevelbuilder/ui-ux-pro-max-skill).

```sh
npm install -g ui-ux-pro-max-cli
uipro init --ai universal --global
```

<a id="source-vercel-browser"></a>

### Vercel Agent Browser

Nguồn: [Vercel Agent Browser](https://github.com/vercel-labs/agent-browser).

```sh
npx skills add vercel-labs/agent-browser
```

<a id="source-vercel-agent-skills"></a>

### Vercel Agent Skills

Nguồn: [Vercel Agent Skills](https://github.com/vercel-labs/agent-skills).

```sh
npx skills add vercel-labs/agent-skills
```

<a id="source-vercel-plugin"></a>

### Vercel Plugin

Nguồn: [Vercel Plugin](https://github.com/vercel/vercel-plugin).

```sh
npx plugins add vercel/vercel-plugin
```

<a id="source-vercel-skills-cli"></a>

### Vercel Skills CLI / find-skills

Nguồn: [Vercel Skills CLI / find-skills](https://github.com/vercel-labs/skills).

```sh
npx skills add vercel-labs/skills --skill find-skills
```

<a id="source-vscode-builtins"></a>

### VS Code / GitHub Copilot — built-in skills

Nguồn: [VS Code / GitHub Copilot — built-in skills](https://github.com/microsoft/vscode/tree/main/src/vs/sessions/skills).

Cài hoặc cập nhật VS Code và GitHub Copilot; đây là các skill đi kèm bề mặt agent, không phải skill cá nhân tự tạo.

<a id="source-zcode"></a>

### ZCode Official Plugins

Nguồn: [ZCode Official Plugins](https://cdn-zcode.z.ai/zcode/official-plugin/marketplace.json).

Cài plugin tương ứng trong marketplace chính thức của ZCode. Các skill được cung cấp trong gói plugin, thay vì cài từng SKILL.md riêng.

Registry được ghi nhận từ cấu hình cài đặt; endpoint CDN chưa truy cập được trong lần đối chiếu nguồn.

<a id="upstream-changes"></a>

## 🔄 Lưu ý về các tên upstream đã thay đổi

Theo [CHANGELOG của Matt Pocock](https://github.com/mattpocock/skills/blob/main/CHANGELOG.md). Muốn lấy bản cũ, kiểm tra tag/lịch sử upstream thay vì dùng selector tên cũ với bản latest.

| Tên trong danh mục | Tình trạng upstream |
|---|---|
| `design-an-interface` | Đã gộp vào codebase-design. |
| `edit-article` | Skill personal đã bị loại khỏi gói hiện tại. |
| `obsidian-vault` | Skill personal đã bị loại; nội dung cũ có đường dẫn vault riêng của tác giả. |
| `qa` | Đã gộp vào triage / to-tickets. |
| `request-refactor-plan` | Đã gộp vào to-spec / improve-codebase-architecture. |
| `resolving-merge-conflicts` | Đã bị loại khỏi plugin từ v1.3.0; upstream không đưa skill thay thế. |
| `ubiquitous-language` | Đã được thay bằng domain-modeling. |
| `writing-great-skills` | Đã đổi tên thành writing-for-agents. |

<a id="maintenance"></a>

## 📝 Cấu trúc và cập nhật danh mục

```text
README.md             # Danh mục theo lĩnh vực, công dụng và nguồn cài
skills/<lĩnh-vực>/     # Các skill dùng chung được lưu trực tiếp
prompts/              # Prompt độc lập
```

Chỉnh sửa trực tiếp README để bổ sung hoặc cập nhật danh mục:

- Đặt skill/prompt vào lĩnh vực phù hợp, ghi công dụng và nguồn tham khảo.
- Với skill có nguồn cài bên ngoài, dẫn tới nguồn và hướng dẫn cài tương ứng.
- Với nội dung được lưu trong repo, liên kết trực tiếp tới file trong `skills/` hoặc `prompts/`.
- Khi thêm, đổi tên hoặc xóa mục, cập nhật số lượng và liên kết liên quan.

Bản cài mới có thể khác nội dung từng kiểm kê. Việc có file hoặc nguồn cài không chứng minh skill đang được bật hoặc đã được thực thi.
