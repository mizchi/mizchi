# mizchi

Software engineer building compilers, runtimes, and verification tools for AI-assisted development.

Web / Node.js とフロントエンドの性能改善を出発点に、現在は言語処理系、WebAssembly、静的解析、fuzzing、形式手法、CI・テスト基盤を開発しています。

## Current focus

- Programming languages, compilers, parsers, and runtimes
- WebAssembly and portable execution environments
- Static analysis, fuzzing, and formal verification
- Developer tools and verification pipelines for coding agents
- TypeScript / Node.js / frontend performance

## Featured projects

### Understand code

- [**similarity**](https://github.com/mizchi/similarity) — High-performance, AST-based code similarity detection for TypeScript/JavaScript and other languages.
- [**markdown.mbt**](https://github.com/mizchi/markdown.mbt) — CST-based incremental Markdown parser for JS, Wasm, and native; CommonMark 652/652 with updates up to 42x faster.

### Verify behavior

- [**uneffect**](https://github.com/mizchi/uneffect) — Gradual effect specifications, Hoare-style contracts, and temporal models for existing TypeScript.
- [**vlmkit**](https://github.com/mizchi/vlmkit) — Deterministic frontend verification for humans and coding agents: visual regression, accessibility, responsive boundaries, and scripted flows.

### Run efficiently

- [**vibe-lang**](https://github.com/mizchi/vibe-lang) — A selfhost-only, effect-typed language whose parser, type checker, and Wasm code generator are written in the language itself.
- [**actrun**](https://github.com/mizchi/actrun) — A local GitHub Actions runner built with MoonBit, with a `gh`-compatible CLI.
- [**crater**](https://github.com/mizchi/crater) — A small headless browser target driven by Playwright over WebDriver BiDi, built with MoonBit for JS, native, and Wasm.

## MoonBit contributions

Active contributor to the official [MoonBit repositories](https://github.com/search?q=org%3Amoonbitlang+author%3Amizchi+is%3Apr&type=pullrequests), with 100+ PRs across `moonbitlang/core`, `async`, `x`, `wasm5`, `parser`, and related projects.

My contributions focus on standard-library performance and correctness: SIMD / v128, JSON, strings and bytes, UTF encoding, collections, async / HTTP, and WebAssembly tooling.

## Writing and talks

- [Zenn](https://zenn.dev/mizchi) — AI-assisted engineering, programming languages, formal methods, WebAssembly, and frontend infrastructure
- [Speaker Deck](https://speakerdeck.com/mizchi)
- [Presentations on connpass](https://connpass.com/user/mizchi/presentation/)

## Experience

- Freelance Software Engineer & Consultant (2024–present)
- PLAID, Software Engineer (2019–2023)
- Freelance Frontend Engineer & Consultant (2016–2019)
- Quipper / Increments / Aiming, Software Engineer (2012–2016)

## Links

- [LinkedIn](https://jp.linkedin.com/in/koutaro-chikuba-a3bb8393)
- [mizchi.dev](https://mizchi.dev/)

<details>
<summary>All OSS projects</summary>

<!-- PORTFOLIO_START -->
## OSS Projects

| Repository | Description | Stars | Language | Updated |
| --- | --- | --- | --- | --- |
| [similarity](https://github.com/mizchi/similarity) |  | 844 | Rust | 2026-11-15 |
| [actrun](https://github.com/mizchi/actrun) | GitHub Actions compatible local runner | 673 | MoonBit | 2026-11-08 |
| [explainer](https://github.com/mizchi/explainer) |  | 466 | HTML | 2026-11-14 |
| [skills](https://github.com/mizchi/skills) | Agent skills by mizchi, distributed via APM | 423 | JavaScript | 2026-11-16 |
| [luna.mbt](https://github.com/mizchi/luna.mbt) | Experimental: Declarative UI Framework for Moonbit | 173 | MoonBit | 2026-10-21 |
| [jev-lint](https://github.com/mizchi/jev-lint) | lint text in code by jev scorerer | 132 | TypeScript | 2026-11-12 |
| [markdown.mbt](https://github.com/mizchi/markdown.mbt) | Markdown Parser for incremental update | 104 | MoonBit | 2026-10-31 |
| [js.mbt](https://github.com/mizchi/js.mbt) | Moonbit Js bindings | 79 | MoonBit | 2026-11-09 |
| [crater](https://github.com/mizchi/crater) |  | 76 | MoonBit | 2026-11-08 |
| [jev-playground](https://github.com/mizchi/jev-playground) |  | 73 | TypeScript | 2026-10-06 |
| [pkfire](https://github.com/mizchi/pkfire) | Typed task runner with Bazel-style incremental caching, configured in Pkl. | 53 | MoonBit | 2026-10-03 |
| [vibe-lang](https://github.com/mizchi/vibe-lang) |  | 49 | Shell | 2026-11-12 |
| [chaosbringer](https://github.com/mizchi/chaosbringer) | Chaos engineering for Playwright tests | 49 | TypeScript | 2026-11-13 |
| [vlmkit](https://github.com/mizchi/vlmkit) | VRT + Semantic Verification Harness — Visual regression testing with a11y semantic verification, AI reasoning, and multi-step goal runner | 43 | TypeScript | 2026-11-13 |
| [jev-test-filter](https://github.com/mizchi/jev-test-filter) | Score every test against a git diff with Jev, and emit the filter arguments vitest, node:test, Playwright, cargo test and go test already understand | 37 | TypeScript | 2026-10-21 |
| [flaker](https://github.com/mizchi/flaker) |  | 24 | MoonBit | 2026-11-08 |
| [ts.mbt](https://github.com/mizchi/ts.mbt) | typescript <-> moonbit bridge generator | 22 | MoonBit | 2026-11-12 |
| [mars.mbt](https://github.com/mizchi/mars.mbt) | Hono-inspired HTTP framework for MoonBit | 21 | MoonBit | 2026-10-16 |
| [kagura](https://github.com/mizchi/kagura) | 2D-first game engine for MoonBit inspired by Ebiten | 20 | MoonBit | 2026-11-09 |
| [tui.mbt](https://github.com/mizchi/tui.mbt) | Terminal UI library for MoonBit | 19 | MoonBit | 2026-10-18 |
| [npm_typed.mbt](https://github.com/mizchi/npm_typed.mbt) |  | 16 | MoonBit | 2026-11-09 |
| [uneffect](https://github.com/mizchi/uneffect) | Gradual effect, contract, async-safety, and temporal checking for existing TypeScript. | 15 | TypeScript | 2026-09-29 |
| [mizchi](https://github.com/mizchi/mizchi) |  | 14 |  | 2026-11-02 |
| [formal-methods-playground](https://github.com/mizchi/formal-methods-playground) | Playground for comparing formal methods tools on realistic app-engineering cases | 12 | Alloy | 2026-11-15 |
| [mutator](https://github.com/mizchi/mutator) | Diff-driven mutation testing for Vitest (oxc instrumentation, result reuse) | 11 | TypeScript | 2026-11-16 |
| [cloudflare.mbt](https://github.com/mizchi/cloudflare.mbt) |  | 8 | MoonBit | 2026-11-04 |
| [parquet](https://github.com/mizchi/parquet) | Parquet reader/writer for MoonBit. | 6 | MoonBit | 2026-09-24 |
| [image-mbt](https://github.com/mizchi/image-mbt) | image codec primitives for MoonBit | 5 | MoonBit | 2026-11-10 |
| [taraba](https://github.com/mizchi/taraba) | Small Promise-first Rust/Wasm runtime for JavaScript hosts, with std and no_std support | 5 | JavaScript | 2026-11-10 |
| [signals.mbt](https://github.com/mizchi/signals.mbt) |  | 5 | MoonBit | 2026-10-05 |
| [moon-pprof](https://github.com/mizchi/moon-pprof) | MoonBit profiling toolkit: pprof output for wasm-gc / wasm / js / native backends. Includes Rust crates and npm package for symbol demangling + Firefox-Profiler → pprof conversion. | 5 | Rust | 2026-09-21 |
| [admiral](https://github.com/mizchi/admiral) | Declarative CLI builder for MoonBit, inspired by gunshi | 5 | MoonBit | 2026-09-17 |
| [three-mbt](https://github.com/mizchi/three-mbt) | Typed Three.js bindings for MoonBit (mizchi/three) | 5 | MoonBit | 2026-09-13 |
| [sqlike](https://github.com/mizchi/sqlike) | MoonBit SQLite subset and browser offline synchronization with IndexedDB and LTX | 4 | TypeScript | 2026-11-16 |
| [css](https://github.com/mizchi/css) | Standalone CSS parser, selector, cascade and computed-style engine for MoonBit (extracted from mizchi/crater) | 4 | MoonBit | 2026-10-19 |
| [pixelmatch](https://github.com/mizchi/pixelmatch) | Fast pixel-level image comparison library for MoonBit/WASM | 4 | MoonBit | 2026-10-18 |
| [playwright.mbt](https://github.com/mizchi/playwright.mbt) | Playwright-compatible API built on WebDriver BiDi | 4 | MoonBit | 2026-09-11 |
| [idealis](https://github.com/mizchi/idealis) | Portable verification toolkit driven by formal models, with Rust/Wasm, TypeScript and Go. | 3 | TypeScript | 2026-11-16 |
| [process_pool.mbt](https://github.com/mizchi/process_pool.mbt) |  | 3 | MoonBit | 2026-10-05 |
| [moonlight](https://github.com/mizchi/moonlight) |  | 3 | MoonBit | 2026-09-23 |
| [check-arxiv-2504-17033](https://github.com/mizchi/check-arxiv-2504-17033) | 論文「Breaking the Sorting Barrier」(arXiv:2504.17033)の最短経路アルゴリズム検証実装 | 3 | Rust | 2026-09-23 |
| [jev-lexer](https://github.com/mizchi/jev-lexer) | Language-agnostic syntax highlighter: split like gpu-lexer, classify every part with Jev, render Shiki-compatible tokens, HTML and ANSI | 3 | TypeScript | 2026-09-20 |
| [v8.mbt](https://github.com/mizchi/v8.mbt) | MoonBit bindings for V8 aimed at prototyping MoonBit-first runtimes in the style of Node or Deno. | 3 | MoonBit | 2026-09-09 |
| [font](https://github.com/mizchi/font) | moonbit font rendering for ttf/otf/ttc/otc/woff/woff2 | 2 | MoonBit | 2026-08-15 |
| [flatbuffers.mbt](https://github.com/mizchi/flatbuffers.mbt) | FlatBuffers implementation for MoonBit | 2 | MoonBit | 2026-10-25 |
| [moomaid](https://github.com/mizchi/moomaid) |  | 2 | MoonBit | 2026-10-03 |
| [pkspec](https://github.com/mizchi/pkspec) | [experimental] Language-agnostic test runner extending pkl test — design notebook | 2 | Pkl | 2026-10-03 |
| [starlint](https://github.com/mizchi/starlint) |  | 2 | MoonBit | 2026-10-03 |
| [world-narrative](https://github.com/mizchi/world-narrative) |  | 2 | TypeScript | 2026-10-03 |
| [walz-lang](https://github.com/mizchi/walz-lang) | A small typed language extending WAT for Wasm GC | 1 | Rust | 2026-11-12 |
| [bitflow](https://github.com/mizchi/bitflow) |  | 1 | MoonBit | 2026-10-05 |
| [wit.mbt](https://github.com/mizchi/wit.mbt) | WIT (WebAssembly Interface Types) parser and resolver in MoonBit | 1 | MoonBit | 2026-09-10 |
| [veri](https://github.com/mizchi/veri) | Formal verification foundations for MoonBit | 1 | MoonBit | 2026-11-10 |
| [prdt](https://github.com/mizchi/prdt) | prdt impl | 1 | MoonBit | 2026-09-25 |
| [x](https://github.com/mizchi/x) |  | 1 | MoonBit | 2026-11-08 |
| [differentiable_ecs](https://github.com/mizchi/differentiable_ecs) | Game-agnostic parameter optimizer using CMA-ES for balance tuning (MoonBit) | 1 | MoonBit | 2026-11-08 |
| [sandbox.mbt](https://github.com/mizchi/sandbox.mbt) |  | 1 | MoonBit | 2026-11-10 |
| [codegen.mbt](https://github.com/mizchi/codegen.mbt) |  | 1 | MoonBit | 2026-10-05 |
| [tempfile.mbt](https://github.com/mizchi/tempfile.mbt) | Temporary file and directory management for MoonBit | 1 | MoonBit | 2026-10-05 |
| [webnn-mbt](https://github.com/mizchi/webnn-mbt) | WebNN backend and TFLite inference runtime for MoonBit | 1 | MoonBit | 2026-09-16 |
| [modeling-playground](https://github.com/mizchi/modeling-playground) | Procedural 3D modeling playground with a shared Three.js GLB viewer, character animation and interactive IK | 1 | TypeScript | 2026-09-10 |
| [isle](https://github.com/mizchi/isle) | A compiler-first UI language with resumable interactions, static analysis and portable Web Components. | 0 | JavaScript | 2026-11-08 |
| [playground](https://github.com/mizchi/playground) |  | 0 | Rust | 2026-11-15 |
| [metalic](https://github.com/mizchi/metalic) | GPU-first language frontend and Nanopass research for Apple Metal | 0 | TypeScript | 2026-11-15 |
| [sample-webapp-2026](https://github.com/mizchi/sample-webapp-2026) | Vite + React dashboard and Hono API reference project for flaker and vrt | 0 | TypeScript | 2026-08-25 |
| [mcp-oauth-playground](https://github.com/mizchi/mcp-oauth-playground) | MCP OAuth playground on Cloudflare Workers with Void, React, and Hono | 0 | TypeScript | 2026-11-12 |
| [converge_audit](https://github.com/mizchi/converge_audit) | Adversarial checkpoint auditing for local-first replicated state | 0 | MoonBit | 2026-10-18 |
| [pnpm-scoped-fetch-demo](https://github.com/mizchi/pnpm-scoped-fetch-demo) | Scoped pnpm fetch and dependency cache group experiments for GitHub Actions | 0 | JavaScript | 2026-11-02 |
| [mwac](https://github.com/mizchi/mwac) |  | 0 | MoonBit | 2026-10-18 |
| [oci_wasm](https://github.com/mizchi/oci_wasm) | WebAssembly package registry client (OCI Distribution) | 0 | MoonBit | 2026-10-05 |
| [webdriver.mbt](https://github.com/mizchi/webdriver.mbt) |  | 0 | MoonBit | 2026-10-05 |
| [similarity.mbt](https://github.com/mizchi/similarity.mbt) |  | 0 | MoonBit | 2026-10-05 |
| [wasi_interface](https://github.com/mizchi/wasi_interface) | WASI Preview2/Preview3 contract definitions for host integration boundaries. | 0 | MoonBit | 2026-10-05 |
| [bend-playground](https://github.com/mizchi/bend-playground) | Bend 2 notes, experiments, and C comparisons | 0 | Python | 2026-10-03 |
| [cf-example](https://github.com/mizchi/cf-example) |  | 0 | TypeScript | 2026-10-02 |
| [nodeproj20261002](https://github.com/mizchi/nodeproj20261002) |  | 0 | TypeScript | 2026-10-02 |
| [stream-studio](https://github.com/mizchi/stream-studio) | Lean入門：偶数 + 奇数 = 奇数 — 音声・字幕・図・コードを同期再生するWeb教材 | 0 | HTML | 2026-10-01 |
| [jev-persona-memory](https://github.com/mizchi/jev-persona-memory) |  | 0 | TypeScript | 2026-09-26 |
| [playground-private](https://github.com/mizchi/playground-private) |  | 0 |  | 2026-09-24 |
| [jev-playground-moba](https://github.com/mizchi/jev-playground-moba) |  | 0 | MoonBit | 2026-09-23 |
| [gfx-mbt](https://github.com/mizchi/gfx-mbt) |  | 0 | MoonBit | 2026-09-18 |
| [jev-gomoku](https://github.com/mizchi/jev-gomoku) |  | 0 | MoonBit | 2026-09-30 |
| [odenctl](https://github.com/mizchi/odenctl) |  | 0 | TypeScript | 2026-09-15 |

*Updated: 2026-11-16*
<!-- PORTFOLIO_END -->

</details>
