# Tim Escolopio

**Compliance & Security | AI Tools & Systems Architect | Open Source Developer**

Charlotte, NC · [3dtsus@gmail.com](mailto:3dtsus@gmail.com) · [LinkedIn](https://linkedin.com/in/tescolopio)

---

## Current Focus

Building tools that make AI agents precise instead of probabilistic. My thesis: the path to reliable AI-assisted development runs through deterministic pre-processors, not larger context windows.

---

## Featured Project

### [Code Scalpel](https://github.com/tescolopio/code_scalpel_community) 🔬

**MCP Server for AI Agents — Surgical Code Operations**

Code Scalpel is the precision toolkit that lets AI agents analyze and modify code safely. Instead of feeding entire codebases into prompts, it surgically extracts only what's needed — the target function, its dependencies, and relevant context — using AST analysis, Program Dependence Graphs, and Z3 symbolic execution.

**Internal Benchmark Results (December 2025):**

| Metric | Result | Evidence |
|--------|--------|----------|
| Token Efficiency | **94.5% reduction** | 18.3x compression (6,411 → 108 tokens best case) |
| Cache Performance | **2,909x speedup** | Average across operations; 6,341x max |
| Vulnerability Detection | **70.0% accuracy** | 51.67% detection rate, high precision on core CWEs |
| Surgical Extraction | **98% token savings** | Extract 16-line function: 5,000 → 110 tokens |

**Core Security Detection (100% Detection Rate):**

| Category | CWE | Status |
|----------|-----|--------|
| Command Injection | CWE-78 | ✅ Validated |
| Code Injection | CWE-94 | ✅ Validated |
| Insecure Deserialization | CWE-502 | ✅ Validated |
| Weak Cryptography | CWE-327 | ✅ Validated |

*Additional coverage: SQL Injection (80%), Path Traversal, XSS, SSRF*

All benchmarks reproducible: `python evidence/run_all_benchmarks.py`

**The Problem It Solves:**
AI coding tools typically dump entire files into context windows, burning tokens on irrelevant code. This leads to hallucinated edits, broken dependencies, and wasted API costs. Code Scalpel gives agents 22 specialized tools to extract exactly what they need — reducing context from 368 lines to 25 lines while preserving correctness.

**22 Specialized Tools:**
- **Surgical Extraction & Analysis**: `extract_code`,`analyze_code`,`get_project_map`, `get_symbol_references`,`get_call_graph`, `get_file_context`, `get_cross_file_dependencies`,`code_policy_check`
- **Taint-Based Security**: `security_scan`,`unified_sink_detect`, `cross_file_security_scan`, `scan_dependencies`,`type_evaporation_scan`,`get_graph_neighborhood`
- **Safe Modification**: `update_symbol`, `rename_symbol`,`simulate_refactor`,`validate_paths`
- **Verification & Testing**: `crawl_project`, `symbolic_execute`, `generate_unit_tests`,`verify_policy_integrity`

**Stack:** Python · Tree-sitter · AST · PDG · Z3 Theorem Prover · MCP Protocol  
**Integrations:** Claude Desktop, GitHub Copilot, Cursor, CrewAI, Autogen, LangChain  
**Status:** v3.3.0 (v1.0 releasing January 2026) · [PyPI](https://pypi.org/project/code-scalpel/) · MIT License · 4,700+ tests · 95%+ coverage

🔗 [Documentation](https://github.com/tescolopio/code_scalpel_community)

---

## Other Projects

### [Mind and Machine](https://github.com/tescolopio/mind-and-machine) 📚
*Bridging Human Cognition to AI Agents for AGI Systems*

A book exploring how human cognitive architecture — conscious, subconscious, and unconscious agents working in concert — can inform AI agent design. Examines frameworks like AutoGen, CrewAI, and MetaGPT through a cognitive science lens.

**Published:** Introduction, Chapter 1 (The Human Mind as a System of Agents)  
**In Development:** Learning & Memory, Emotion & Decision-Making, Metacognition

---

### [Mind Wars](https://github.com/tescolopio/mind-wars) 🎮
*Async Multiplayer Cognitive Games Platform*

A mobile platform for private group cognitive competitions — Family Mind Wars, Friends Mind Wars, Office Mind Wars. Turn-based gameplay across iOS 14+ and Android 8+.

**Status:** Phase 1 MVP Complete  
- 15 games across 5 cognitive categories
- Full authentication & multiplayer lobby system
- Offline mode with SQLite persistence
- 126+ tests (100% pass rate)
- ~18,100 lines of production code

---

### [Terms Guardian](https://github.com/tescolopio/terms-guardian) 📋
*Browser Extension for Legal Document Analysis*

NLP-powered browser extension that analyzes Terms of Service and Privacy Policies. Provides readability grades (A-F), section-by-section summaries, key clause extraction, and uncommon legal term definitions.

**Features:**
- User Rights Index (URI) scoring system
- Parallel analysis pipeline for performance
- Multi-browser support (Chrome, Edge, Firefox)

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
