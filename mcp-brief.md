# MCP Research Brief

Prepared for the sprint-review tech brief. All facts below come from public sources (links at the bottom).

## What MCP is
- The **Model Context Protocol (MCP)** is an **open-source, open standard for connecting AI applications to external systems** — data sources (local files, databases), tools (search engines, calculators), and workflows (specialized prompts).
- Common analogy from the official docs: **"a USB-C port for AI applications"** — one standardized plug instead of a bespoke cable for every device.
- It standardizes the interface for reading files, executing functions, and handling contextual prompts, and enables **secure, two-way connections** between data sources and AI applications.

## Origin
- **Introduced by Anthropic**, announced **November 25, 2024** in the post "Introducing the Model Context Protocol".
- Created at Anthropic by engineers **David Soria Parra and Justin Spahr-Summers**.
- Motivation: before MCP, every new data source required its own custom connector (the "N×M integration problem"); MCP replaces those fragmented integrations with a single universal protocol, helping AI escape information silos and legacy systems.

## How it works (architecture)
- **MCP servers** expose data and tools; **MCP clients** are built into AI applications and connect to those servers; a host application can run multiple clients.
- Launched with three main components: the **specification + SDKs**, **local MCP server support in the Claude Desktop apps**, and an **open-source repository of reference MCP servers** (Google Drive, Slack, GitHub, Git, Postgres, Puppeteer, and others).

## Ecosystem and adoption
- **Early adopters:** Block and Apollo integrated MCP at launch; development-tool companies **Zed, Replit, Codeium, and Sourcegraph** worked with MCP to enhance their platforms.
- Following the announcement, major AI providers **OpenAI** (March 2025) and **Google DeepMind** (April 2025) adopted the protocol.
- Today MCP is supported across a broad range of clients, including **Claude, ChatGPT, Visual Studio Code, and Cursor** — build once, integrate everywhere.
- Official **SDKs exist in many languages**: TypeScript, Python, Java, Kotlin, C#, Go, PHP, Ruby, Rust, and Swift.
- The ecosystem is substantial: the `modelcontextprotocol/servers` repo (~90k stars), `python-sdk` (~24k stars), and `typescript-sdk` (~13k stars) at time of writing.
- Development is open and community-driven (public spec, contributing guide, community discussions, and SEPs — Specification Enhancement Proposals). Latest spec version at time of writing: **2026-07-28**.

## Official resources
- Project site / documentation: https://modelcontextprotocol.io
- Specification (latest): https://modelcontextprotocol.io/specification/latest
- GitHub organization (spec, SDKs, servers, inspector): https://github.com/modelcontextprotocol
- Reference server implementations: https://github.com/modelcontextprotocol/servers
- Original announcement: https://www.anthropic.com/news/model-context-protocol

## Sources
- Anthropic — "Introducing the Model Context Protocol" (Nov 25, 2024; launch components, early adopters, creators): https://www.anthropic.com/news/model-context-protocol
- Official MCP documentation ("What is the Model Context Protocol?", USB-C analogy, ecosystem support): https://modelcontextprotocol.io
- GitHub — modelcontextprotocol org page (spec, SDK list, repo star counts): https://github.com/modelcontextprotocol
- Wikipedia — "Model Context Protocol" (intro date, creators, OpenAI and Google DeepMind adoption, SDK languages): https://en.wikipedia.org/wiki/Model_Context_Protocol
- Google Cloud — "What is Model Context Protocol (MCP)? A guide" (Nov 2024 introduction): https://cloud.google.com/discover/what-is-model-context-protocol
