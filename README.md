# Max Gornostayev

**Software Architect** · Remote

20+ years in web and mobile development. React Native, React, Node.js, TypeScript, Go, Flutter.
In recent years mostly mobile and backend development — iOS and Android apps taken from architecture to store release, and the APIs and server logic behind them.

I code alongside AI agents every day. The hard part isn't the prompt — it's giving them clear boundaries and a way to check their own work.

💼 [LinkedIn](https://www.linkedin.com/in/gornostayev/)

---

## Open source

- **[react-native-matrix](https://github.com/maxweb4u/react-native-matrix)** — typed components and hooks for Matrix chat: session, room encryption, timeline, 12 ready components. Zero runtime dependencies, integration tests against Synapse. TypeScript, MIT · [npm](https://www.npmjs.com/package/react-native-matrix)
- **[ebook_parser](https://github.com/maxweb4u/ebook_parser)** — parses EPUB and FB2 into one document model. Format detection by magic bytes, transparent `.fb2.zip` handling, lazy sentence and word segmentation, a cheap metadata-only path. Dart, MIT · [pub.dev](https://pub.dev/packages/ebook_parser)
- **[boxglb](https://github.com/maxweb4u/boxglb)** — glTF 2.0 / GLB from axis-aligned boxes with zero dependencies. Writes per-face normals and world-scale planar UVs, which none of the alternatives do — so the model takes a texture without unwrapping it by hand. Python, MIT · [PyPI](https://pypi.org/project/boxglb/)
- **[mcp-memorybank](https://github.com/maxweb4u/mcp-memorybank)** — MCP server over a project knowledge base: routing without reading the documents, gated writes, SSoT and broken-link checks, and drift between the docs and the code. 15 tools. TypeScript, MIT · [npm](https://www.npmjs.com/package/@maxweb4u/mcp-memorybank) · listed on [mcpservers.org](https://mcpservers.org)
- **[react-native-jwt-io](https://github.com/maxweb4u/react-native-jwt-io)** — sign, verify and decode JWTs on the device in pure TypeScript: 14 algorithms (HMAC, RSA, RSA-PSS, ECDSA, EdDSA) on Hermes, no native module, synchronous API, `alg: none` never accepted, tested against Node's crypto and the Wycheproof vectors. On npm since 2017, ~12k downloads a month; the 2.0 rewrite is on the `next` tag. TypeScript, MIT · [npm](https://www.npmjs.com/package/react-native-jwt-io)

## Projects

- **TeaderBook** — an e-reader for language learners. FB2 and EPUB, translation on tap: single tap for the sentence, double tap for the word, plus an explanation of the context. Three translation engines, offline and online. Flutter + MobX on the client, Go and SQLite on the server, LLM calls proxied through the backend · [App Store](https://apps.apple.com/app/id6812052052)
- **imgToHomestyler** — photos of cabinet furniture become 3D models. The decision that shapes everything: **the model returns data, not code**. A vision LLM fills in a JSON spec of the construction; a deterministic generator builds the geometry. The same spec yields a byte-identical model, and a failure looks like a schema mismatch rather than quietly assembled garbage. Python, FastAPI, glTF/GLB · [Telegram bot](https://t.me/hs_model_generate_bot)
- **Passix** — a password manager where sync keys never reach the server. XChaCha20-Poly1305, X25519, HKDF-SHA256, Argon2. Flutter + Go.
- **Idelog** — capture ideas before they fade. Speech recognition runs offline, on device. Flutter, Whisper GGML, sqflite · [App Store](https://apps.apple.com/us/app/idelog/id6761336520) · [Google Play](https://play.google.com/store/apps/details?id=com.maxesoft.idelo)
- **Focus Reminder** — a full-screen nudge back to work. Swift, AppKit, macOS · [Mac App Store](https://apps.apple.com/us/app/simple-focus-reminder/id6483003136)
- **Feed Triage Agent** — an agent that turns a job feed into decisions. Collects via a browser extension (Cloudflare detects CDP browsers), filters with rules before any model call; a human approves in Telegram. TypeScript, Fastify, Prisma.
- **Blog Agent** — a Telegram agent that runs an indie studio's blog: a research model with web search, draft and polish on separate models, the cover image, publishing as one commit through the GitLab API, and the announcement tweet. Every step waits for human approval. Go, SQLite, calls routed across Gemini, OpenAI and Anthropic.

---

<sub>Some of this code is closed — those entries link to the stores instead. Happy to go deeper on any of the architecture decisions.</sub>

