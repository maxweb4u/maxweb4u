# Maxim Gornostaev

**Senior Full Stack Developer** · Remote

20+ years in web and mobile development. React Native, React, Node.js, TypeScript, Go, Flutter.
Currently building mobile apps at [Showmojo](https://showmojo.com), including Bluetooth device integration and firmware fixes in C++.

I work with LLMs and agentic tooling every day — not as autocomplete, but as an executor that needs boundaries, a verifiable contract on its output, and somewhere cheap to be wrong.

💼 [LinkedIn](https://www.linkedin.com/in/gornostayev/)

---

## Published apps

| | What | Stack |
|---|---|---|
| **[Idelog](https://apps.apple.com/us/app/idelog/id6761336520)** · [Google Play](https://play.google.com/store/apps/details?id=com.maxesoft.idelo) | Capture ideas before they fade. Speech recognition runs **offline**, on device | Flutter, Whisper GGML, sqflite |
| **[Simple Focus Reminder](https://apps.apple.com/us/app/simple-focus-reminder/id6483003136)** | Full-screen nudge back to work | Swift, AppKit, macOS |

## Projects

**TeaderBook** — an e-reader for language learners. FB2 and EPUB, translation on tap: single tap for the sentence, double tap for the word, plus an explanation of the context. Three translation engines, offline and online. Flutter + MobX on the client, Go and SQLite on the server, LLM calls proxied through the backend.

**Agent Upwork** — an agent that watches a job feed and hands over a decision instead of a task. Collection runs as a browser extension inside an ordinary session: Cloudflare detects CDP-driven browsers, and that came out of experiment rather than documentation. Two rule stages filter before the first model call, so tokens are spent only on what rules cannot decide. Scoring is a single schema-constrained call. A human approves in Telegram. TypeScript, Fastify, Prisma, zod.

**imgToHomestyler** — photos of cabinet furniture become 3D models. The decision that shapes everything: **the model returns data, not code**. A vision LLM fills in a JSON spec of the construction; a deterministic generator builds the geometry. The same spec yields a byte-identical model, and a failure looks like a schema mismatch rather than quietly assembled garbage. Python, FastAPI, glTF/GLB. [Bot](https://t.me/hs_model_generate_bot)

**Passix** — a password manager where sync keys never reach the server. XChaCha20-Poly1305, X25519, HKDF-SHA256, Argon2. Flutter + Go.

## Open source

- **[react-native-matrix](https://github.com/maxweb4u/react-native-matrix)** — cross-platform client for matrix.org servers. React Native, MIT

<!-- Uncomment as each one ships: a link to nowhere is worse than a missing line.
- **ebook_parser** — parses EPUB and FB2 into one document model. Format detection by magic bytes, lazy sentence segmentation. Dart
- **boxglb** — glTF 2.0 / GLB from axis-aligned boxes. Zero dependencies. Python
- **memorybank-mcp** — MCP server over a project knowledge base: routing without reading documents, SSoT checks, new documents registered in the index. TypeScript
-->

---

<sub>Some of this code is closed — those entries link to the stores instead. Happy to go deeper on any of the architecture decisions.</sub>

