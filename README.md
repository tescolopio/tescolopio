# Tim Escolopio

**Compliance & Security | AI Tools & Systems Architect | Open Source Developer**

Charlotte, NC · [3dtsus@gmail.com](mailto:3dtsus@gmail.com) · [LinkedIn](https://linkedin.com/in/tescolopio)

---

## Current Focus

Building tools that make AI agents precise instead of probabilistic. My thesis: the path to reliable AI-assisted development runs through deterministic pre-processors, not larger context windows.

---

## Featured Project

### [Code Scalpel](https://github.com/3D-Tech-Solutions/code-scalpel)

**MCP Server for AI Agents — Surgical Code Operations**

Code Scalpel is a precision toolkit developed at [3D Tech Solutions LLC](https://github.com/3D-Tech-Solutions) that allows AI agents to analyze and modify code safely. Instead of feeding entire codebases into prompts and wasting context windows, it surgically extracts only what is needed—the target function, its dependencies, and relevant context—using AST analysis, Program Dependence Graphs, and Z3 symbolic execution.

**The Problem It Solves:**
AI coding tools typically dump entire files into context windows, burning tokens on irrelevant code. This leads to hallucinated edits, broken dependencies, and high API costs. Code Scalpel gives agents specialized tools to extract exactly what they need, reducing token usage by up to 99% (e.g., 10,000 tokens down to 50) while preserving correctness.

**Performance & Efficiency:**

| Metric | Result | Impact |
|--------|--------|--------|
| Token Efficiency | **99% reduction** | 10,000 tokens → 50 tokens per query |
| Cost Savings | **20x reduction** | Drastically lowers LLM API billing |
| Context Focus | **High Precision** | Extracts exact AST nodes, not text blocks |

**Security Detection Capabilities (Taint-Based Analysis):**

| Category | CWE | Status |
|----------|-----|--------|
| Command Injection | CWE-78 | Validated |
| Code Injection | CWE-94 | Validated |
| SQL/NoSQL Injection | CWE-89 | Validated |
| Cross-Site Scripting | CWE-79 | Validated |
| Path Traversal | CWE-22 | Validated |

**23 Specialized Tools:**
- **Extraction & Analysis:** `extract_code`, `analyze_code`, `get_file_context`, `get_symbol_references`, `get_cross_file_dependencies`
- **Project Architecture:** `get_call_graph`, `get_project_map`, `get_graph_neighborhood`, `crawl_project`
- **Taint-Based Security:** `security_scan`, `cross_file_security_scan`, `scan_dependencies`, `unified_sink_detect`, `type_evaporation_scan`
- **Safe Modification:** `update_symbol`, `rename_symbol`, `simulate_refactor`
- **Verification & Testing:** `symbolic_execute`, `generate_unit_tests`
- **Policy & System:** `code_policy_check`, `verify_policy_integrity`, `validate_paths`, `get_capabilities`

**Stack:** Python · Tree-sitter · AST · PDG · Z3 Theorem Prover · FastMCP  
**Integrations:** Claude Desktop, GitHub Copilot, Cursor, CrewAI, Autogen, LangChain  
**Status:** v1.4.0 (Released February 2026) · [PyPI](https://pypi.org/project/code-scalpel/) · MIT License · 7,200+ tests · 95%+ coverage  

🔗 [Website](https://codescalpel.dev) | 🔗 [Documentation](https://github.com/3D-Tech-Solutions/code-scalpel/tree/main/docs) | 🔗 [Repository](https://github.com/3D-Tech-Solutions/code-scalpel)

---

## Other Projects

### [Folder Bridge](https://github.com/tescolopio/obsidian_folderbridge)

A Obsidian community plugin that lets you mount arbitrary folders (local, network, cloud‑sync) into your vault as “virtual” notes.
It transparently mirrors file changes both ways and tags them so your normal Obsidian workflow still works.
I built it to treat external resources as first‑class, searchable parts of a vault without copying or breaking sync.

Use for code snippets, reference docs, or any directory you want indexed by Obsidian.

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

**Current:** Security Consultant supporting Global Information Security at Bank of America (via TEKSystems), focused on Data Loss Prevention and compliance program acceleration.

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

**Certifications:** Certified ScrumMaster (CSM)

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
