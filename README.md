# Tim Escolopio

**Compliance & Security | AI Tools & Systems Architect | Open Source Developer**

Charlotte, NC · [3dtsus@gmail.com](mailto:3dtsus@gmail.com) · [LinkedIn](https://linkedin.com/in/tescolopio)

---

## Current Focus

Looking for new opportunities and/or partnerships in GRC, AI Development, and/or IT Secruity-related positions.

Building tools that make AI agents precise instead of probabilistic. My thesis: the path to reliable AI-assisted development runs through deterministic pre-processors, not larger context windows.

---

## Featured Project

### [Code Scalpel](https://github.com/3D-Tech-Solutions/code-scalpel)
**Code Scalpel — MCP Server for AI Agents and Surgical Code Operations**

Code Scalpel is an MCP server toolkit from [3D Tech Solutions LLC](https://github.com/3D-Tech-Solutions) that gives AI agents deterministic, structure-aware ways to inspect and modify code. Instead of dumping entire files into an LLM context window, it works at the AST, graph, and symbolic-execution layer to extract relevant code, trace dependencies, analyze risk, and verify changes before they land.

**What it solves**
Most AI coding workflows treat code as text: they read too much, miss dependencies, hallucinate edits, and waste tokens on irrelevant context. Code Scalpel replaces that with surgical operations such as symbol extraction, reference tracing, security scanning, safe symbol updates, and refactor simulation.

**Current snapshot**
- **Version:** v2.1.2
- **Core surface:** **22 core MCP tools** plus separate capability introspection
- **Language coverage:** broad multi-language support across current analysis and extraction surfaces, including Python, JavaScript, TypeScript, Java, C, C++, C#, Go, Kotlin, PHP, Ruby, Swift, and Rust
- **Current depth:** strongest parity today is in core parsing/extraction and selected analysis flows; some graph-oriented and advanced runtime surfaces are still language-dependent rather than fully uniform
- **Verification:** **7,575+ tests** and roughly **94.86% combined coverage**
- **Security focus:** taint-based detection for SQL/NoSQL injection, XSS, command injection, path traversal, dependency risk, and TypeScript type-safety erosion
- **Deployment model:** local/self-hosted, MIT licensed, designed for Claude Desktop, GitHub Copilot, Cursor, CrewAI, AutoGen, and LangChain

**Stack**
Python · MCP · Tree-sitter · AST/IR normalization · graph/dependency analysis · taint tracking · Z3 symbolic execution

🔗 [Website](https://codescalpel.dev) | 🔗 [Documentation](https://github.com/3D-Tech-Solutions/code-scalpel/tree/main/docs) | 🔗 [Repository](https://github.com/3D-Tech-Solutions/code-scalpel)

---

## Other Projects

### [Aegis OS](https://github.com/3D-Tech-Solutions/aegis-os)
*Open Governance Runtime for Enterprise AI Agents*

An open-source control plane for enterprise synthetic workforces. Each AI agent operates with a defined Role, Memory (short-term scratchpad + long-term vector store), Tools, and Constraints. The Governance Loop cycles through: Observe → Reason → Act → Audit → Learn. Compliance enforcement is built into the loop at the agent level, so organizations can deploy AI at scale without losing auditability or control.

Built for teams that need to answer: *"What did that agent do, why, and can we prove it was compliant?"*

**Stack:** Python · LangChain · Vector Store · Audit Logging
**Status:** Active development · MIT License

---

### [Folder Bridge](https://github.com/tescolopio/obsidian_folderbridge)
*Obsidian Community Plugin*

Mounts arbitrary folders (local, network, cloud-sync) into your Obsidian vault as virtual notes. Transparently mirrors file changes both ways and tags them so your normal Obsidian workflow still works. Built to treat external resources as first-class, searchable parts of a vault without copying or breaking sync. Useful for code snippets, reference docs, or any directory you want indexed by Obsidian.

**Published:** v0.3
**In Development:** Obsidian Android App Integration Compatibility

---

### [Terms Guardian](https://github.com/tescolopio/guard_tos)
*Browser Extension for Legal Document Analysis*

NLP-powered browser extension that analyzes Terms of Service and Privacy Policies. Provides readability grades (A-F), section-by-section summaries, key clause extraction, and uncommon legal term definitions.

**Features:**
- User Rights Index (URI) scoring system
- Parallel analysis pipeline for performance
- Multi-browser support (Chrome, Edge, Firefox)

---

### [Mind and Machine](https://github.com/tescolopio/mind-and-machine)
*Bridging Human Cognition to AI Agents for AGI Systems*

A book exploring how human cognitive architecture — conscious, subconscious, and unconscious agents working in concert — can inform AI agent design. Examines frameworks like AutoGen, CrewAI, and MetaGPT through a cognitive science lens.

**Published:** Introduction, Chapter 1 (The Human Mind as a System of Agents)
**In Development:** Learning & Memory, Emotion & Decision-Making, Metacognition

---

### [Mind Wars](https://github.com/tescolopio/mind-wars)
*Async Multiplayer Cognitive Games Platform*

A mobile platform for private group cognitive competitions — Family Mind Wars, Friends Mind Wars, Office Mind Wars. Turn-based gameplay across iOS 14+ and Android 8+.

**Status:** Phase 1 MVP Complete
- 15 games across 5 cognitive categories
- Full authentication & multiplayer lobby system
- Offline mode with SQLite persistence
- 126+ tests (100% pass rate)
- ~18,100 lines of production code

---

### Past Enterprise Projects
**The Knowledge Navigator** — React-based LLM+RAG application using Azure AI Services. Processed 1,600+ documents with ChatGPT 3.5, Azure Cognitive Search, and HNSW vector indexing. Increased enterprise information accessibility by 50%.

**Data Governance Guru** — Custom GPT for enterprise data governance consultation. Provided expert-level guidance on complex data governance challenges for potential customers.

---

## Background

10+ years in Operations, Regulatory Compliance, and IT security across financial services, technology, and logistics.

**Previous Highlights:**
- Accelerated iCCR exam readiness from initial assessment to exam-ready under tight timelines
- Built SOC 2 and ISO 27001 compliance programs from ground zero (Mattang)
- Reduced unauthorized data exposure 50% through M365 DLP policies across multinational operations
- Led 4 enterprise AI implementations increasing information accessibility by 50%

**Technical Focus:**
- **Security:** Microsoft Purview, Defender XDR, Intune, Entra ID, DLP architecture
- **Cloud:** Azure (primary), AWS, Terraform, ARM templates
- **Code Analysis:** AST, PDG construction, symbolic execution, taint analysis
- **AI/ML:** LangChain, LangGraph, Azure OpenAI, RAG architectures, MCP protocol

**Certifications:** CISA Coursework — In Progress (ISACA) · Certified ScrumMaster (CSM) · AI for Cybersecurity (LinkedIn) · Security Principals in Cloud Computing (Google)

---

## 3D Tech Solutions LLC
My consulting practice delivering AI + cybersecurity solutions. Focus areas include enterprise AI adoption, SOC 2/ISO 27001 implementation, and security architecture for startups entering enterprise markets.

---

## Let's Connect

**Interested in:**
- Open source collaboration on Code Scalpel (TypeScript support, VS Code extension, language analyzers)
- BISO / Director of Security Engineering roles combining security strategy with AI implementation
- Advisory work on AI security architecture and compliance for ML systems

**Open to:** Full-time, consulting, or OSS contributions.

---

*Building the deterministic foundation for AI-assisted development.*
