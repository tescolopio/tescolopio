# Tim Escolopio

**Security & Compliance Program Manager | AI Security Architect | Open Source Developer**

Charlotte, NC · [3dtsus@gmail.com](mailto:3dtsus@gmail.com) · [LinkedIn](https://linkedin.com/in/tescolopio)

---

## What I'm Building

### [Code Scalpel](https://github.com/tescolopio/code-scalpel) 🔬

**Deterministic code analysis for AI agents** — because LLMs shouldn't guess at code structure.

Code Scalpel treats source code as graphs, not text. Using Program Dependence Graphs (PDG) and symbolic execution via Z3, it enables AI coding agents to perform surgical modifications without hallucinating changes to unrelated code.

**Benchmark Results (December 2024):**

| Claim | Evidence |
|-------|----------|
| Token Efficiency | **94.5% reduction** — 18x compression factor (6,411 → 108 tokens best case) |
| Cache Performance | **2,909x average speedup** (exceeds original 200x claim; 6,341x max) |
| Vulnerability Detection | **88.2% accuracy**, 0% false positive rate |
| Surgical Extraction | **93% context reduction** in refactoring workflows |

**Per-Category Detection:**
- Command Injection (CWE-78): 100%
- SQL Injection (CWE-89): 80%
- Code Injection (CWE-94): 80%
- Insecure Deserialization (CWE-502): 80%
- Path Traversal (CWE-22): 100%
- Weak Cryptography (CWE-327): 100%

All benchmarks are reproducible — run `python evidence/run_all_benchmarks.py` to validate.

**The Problem It Solves:**

Current AI coding tools stuff entire codebases into prompts, burning tokens on irrelevant code and producing hallucinated fixes. Code Scalpel extracts only the semantically relevant code — the target function, its callers, dependencies, and tests — reducing a 368-line context to 25 lines while preserving everything the LLM needs.

**Stack:** Python · AST · PDG · Z3 Symbolic Execution · MCP Protocol · FastMCP  
**Integrations:** Claude, Cursor, CrewAI, Autogen, LangChain  
**Status:** v1.3.0 on PyPI · MIT License · [Documentation](https://github.com/tescolopio/code-scalpel)

---

## Background

10+ years in IT security and compliance across financial services, technology, and logistics. Currently supporting Global Information Security at Bank of America (via TEKSystems), focused on Data Loss Prevention and compliance program acceleration.

**Recent Work:**
- Accelerated iCCR exam readiness from initial assessment to exam-ready status under tight timelines
- Implemented SOC 2 and ISO 27001 compliance frameworks from ground zero at a startup
- Reduced unauthorized data exposure 50% through M365 DLP policies across multinational operations
- Led 4 enterprise AI implementations increasing information accessibility by 50%

**Technical Focus:**
- **Security:** Microsoft Purview, Defender XDR, Intune, Entra ID, DLP architecture
- **Cloud:** Azure (primary), AWS, Terraform, ARM templates
- **Code Analysis:** AST manipulation, PDG construction, symbolic execution, taint analysis
- **AI/ML:** LangChain, LangGraph, Azure OpenAI, RAG architectures, MCP protocol

---

## Other Projects

**Terms Guardian** — Browser extension using NLP to analyze and grade Terms of Service documents. Extracts key clauses, provides readability scores (A-F), and summarizes complex legal language.

**Hunt Master Academy** — AI-powered hunting education platform with personalized curriculum generation.

**3D Tech Solutions LLC** — My consulting practice delivering AI + cybersecurity solutions for startups and enterprises.

---

## Let's Connect

**Interested in:**
- Open source collaboration on Code Scalpel (TypeScript support, VS Code extension, additional language analyzers)
- BISO / Director of Security Engineering roles combining security strategy with AI implementation
- Advisory work on AI security architecture and compliance for ML systems

**Open to:** Full-time, consulting, or OSS contributions.

---

*Building the deterministic foundation for AI-assisted development.*
