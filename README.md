# Tim Escolopio

**Security & Compliance Program Manager | AI Security Architect | Open Source Developer**

Charlotte, NC · [3dtsus@gmail.com](mailto:3dtsus@gmail.com) · [LinkedIn](https://linkedin.com/in/tescolopio)

---

## Current Focus

Building tools that make AI agents precise instead of probabilistic. My thesis: the path to reliable AI-assisted development runs through deterministic pre-processors, not larger context windows.

---

## Featured Project

### [Code Scalpel](https://github.com/tescolopio/code-scalpel) 🔬

**MCP Server Toolkit for AI Agents — Surgical Code Analysis**

Code Scalpel treats source code as graphs, not text. Using Program Dependence Graphs and Z3 symbolic execution, it enables AI coding agents to perform surgical modifications without hallucinating changes to unrelated code.

**Validated Benchmark Results (December 2025):**

| Metric | Result | Notes |
|--------|--------|-------|
| Token Efficiency | **94.5% reduction** | 18x compression (6,411 → 108 tokens best case) |
| Cache Performance | **2,909x speedup** | Exceeds original 200x claim; 6,341x max |
| Vulnerability Detection | **88.2% accuracy** | 0% false positive rate |
| Surgical Extraction | **93% context reduction** | In refactoring workflows |

**Detection by Vulnerability Type:**

| Category | Detection Rate |
|----------|----------------|
| Command Injection (CWE-78) | 100% |
| SQL Injection (CWE-89) | 100% |
| Code Injection (CWE-94) | 100% |
| Insecure Deserialization (CWE-502) | 100% |
| Weak Cryptography (CWE-327) | 100% |
| Path Traversal (CWE-22) | 100% |

All benchmarks reproducible: `python evidence/run_all_benchmarks.py`

**The Problem:**
Current AI coding tools stuff entire codebases into prompts, burning tokens on irrelevant code and producing hallucinated fixes. Code Scalpel extracts only semantically relevant code — the target function, callers, dependencies, and tests — reducing a 368-line context to 25 lines.

**Stack:** Python · AST · PDG · Z3 Symbolic Execution · MCP Protocol · FastMCP  
**Integrations:** Claude, Cursor, CrewAI, Autogen, LangChain  
**Status:** v1.3.0 on [PyPI](https://pypi.org/project/code-scalpel/) · MIT License · 1,669 tests passing · 95%+ coverage

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
