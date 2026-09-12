# Max Gornostayev

**Software Architect** · Remote

20+ years in web and mobile development. React Native, React, Node.js, TypeScript, Go, Flutter.
In recent years mostly mobile — iOS and Android apps taken from architecture to store release.

I code alongside AI agents every day. The hard part isn't the prompt — it's giving them clear boundaries and a way to check their own work.

💼 [LinkedIn](https://www.linkedin.com/in/gornostayev/)

---

## Open source

- **[react-native-matrix](https://github.com/maxweb4u/react-native-matrix)** — typed components and hooks for Matrix chat: session, room encryption, timeline, 12 ready components. Zero runtime dependencies, integration tests against Synapse. TypeScript, MIT · [npm](https://www.npmjs.com/package/react-native-matrix)
- **[ebook_parser](https://github.com/maxweb4u/ebook_parser)** — parses EPUB and FB2 into one document model. Format detection by magic bytes, transparent `.fb2.zip` handling, lazy sentence and word segmentation, a cheap metadata-only path. Dart, MIT · [pub.dev](https://pub.dev/packages/ebook_parser)
- **[boxglb](https://github.com/maxweb4u/boxglb)** — glTF 2.0 / GLB from axis-aligned boxes with zero dependencies. Writes per-face normals and world-scale planar UVs, which none of the alternatives do — so the model takes a texture without unwrapping it by hand. Python, MIT · [PyPI](https://pypi.org/project/boxglb/)
- **[mcp-memorybank](https://github.com/maxweb4u/mcp-memorybank)** — MCP server over a project knowledge base: routing without reading the documents, gated writes, SSoT and broken-link checks, and drift between the docs and the code. 15 tools. TypeScript, MIT · [npm](https://www.npmjs.com/package/@maxweb4u/mcp-memorybank) · listed on [mcpservers.org](https://mcpservers.org)

## Pet projects

- **TeaderBook** — an e-reader for language learners. FB2 and EPUB, translation on tap: single tap for the sentence, double tap for the word, plus an explanation of the context. Three translation engines, offline and online. Flutter + MobX on the client, Go and SQLite on the server, LLM calls proxied through the backend.
- **imgToHomestyler** — photos of cabinet furniture become 3D models. The decision that shapes everything: **the model returns data, not code**. A vision LLM fills in a JSON spec of the construction; a deterministic generator builds the geometry. The same spec yields a byte-identical model, and a failure looks like a schema mismatch rather than quietly assembled garbage. Python, FastAPI, glTF/GLB · [Telegram bot](https://t.me/hs_model_generate_bot)
- **Passix** — a password manager where sync keys never reach the server. XChaCha20-Poly1305, X25519, HKDF-SHA256, Argon2. Flutter + Go.
- **Idelog** — capture ideas before they fade. Speech recognition runs offline, on device. Flutter, Whisper GGML, sqflite · [App Store](https://apps.apple.com/us/app/idelog/id6761336520) · [Google Play](https://play.google.com/store/apps/details?id=com.maxesoft.idelo)
- **Simple Focus Reminder** — a full-screen nudge back to work. Swift, AppKit, macOS · [Mac App Store](https://apps.apple.com/us/app/simple-focus-reminder/id6483003136)
- **Feed Triage Agent** — an agent that turns a job feed into decisions. Collects via a browser extension (Cloudflare detects CDP browsers), filters with rules before any model call; a human approves in Telegram. TypeScript, Fastify, Prisma.

---

<sub>Some of this code is closed — those entries link to the stores instead. Happy to go deeper on any of the architecture decisions.</sub>

