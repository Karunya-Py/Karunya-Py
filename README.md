<div align="center">

<img src="assets/banner.png" width="340" alt="A laptop showing a terminal prompt, next to a mug of coffee">

# Karunya Muddana

**AI engineer · agents, MCP servers, and the tooling around them**

B.Tech CS (AI & ML) at GITAM, Hyderabad · CGPA 9.15

[Website](https://karunya-muddana.github.io) · [LinkedIn](https://www.linkedin.com/in/karunya-muddana/) · [karunya.muddana@outlook.com](mailto:karunya.muddana@outlook.com)

</div>

---

I build AI systems that have to work on someone's real data, every day. Mostly that means agents that use tools, MCP servers that give them access to live systems, and the evaluation that tells me whether any of it is right.

Since 2024 I've freelanced for a chemical manufacturer in Hyderabad. I built them an assistant that answered staff questions about their Excel data in plain English and pointed at the exact cell behind every number. They used it daily until they moved to an ERP.

> **New account, fresh start.** My old GitHub account is gone, so this one starts at zero. The projects below are being rebuilt and pushed here one at a time.

## What I've built

| Project | What it does | Stack |
|---|---|---|
| **Native** | A self-hosted agent workbench. Reads documents, runs Python in a network-disabled Docker sandbox, and writes `.docx` / `.xlsx` / `.pptx`. When a provider rate-limits, it falls back through five model providers down to a local model, so a run never stops. Built for Smart India Hackathon 2026. | LangGraph · FastAPI · Docker · Ollama · RAG |
| **ExcelMCP** | MCP server with 11 tools that reads live workbooks through Microsoft Graph and cites the file, sheet, and cell behind every answer. The engine behind the manufacturer's assistant. | FastMCP · Microsoft Graph · FastEmbed · Pandas |
| **[engraph](https://pypi.org/project/engraph/)** | Graph-based memory for Claude Code that lasts between sessions. `pip install engraph` | Python · MCP |
| **CBSE Gazette Analyzer** | Turns the board's raw result gazettes into Excel and PDF analytics. Used by teachers at 2 schools for 600+ students. | Python · Pandas |
| **House price model** | Benchmarked 11 models on one split; the tuned best prices 79% of houses within 10% of sale price. | scikit-learn · XGBoost · LightGBM |

## Fixes in other people's code

- ✅ **[ipython/ipython #15431](https://github.com/ipython/ipython/pull/15431)** (merged): WebP detection and size parsing in `display.Image`
- ✅ **[git-cola/git-cola #1654](https://github.com/git-cola/git-cola/pull/1654)** (merged): report errors when opening a repository fails
- ⏳ **[collective/icalendar #1886](https://github.com/collective/icalendar/pull/1886)** (in review): `vUTCOffset.from_ical` misreading unsigned offsets
- ⏳ **[scikit-learn #35124](https://github.com/scikit-learn/scikit-learn/pull/35124)** (in review): make `Bunch.copy` return a `Bunch`

## Stack

**Daily:** Python, FastAPI, Supabase / PostgreSQL, vanilla JS, Docker, Git

**AI:** LLM agents, MCP, LangGraph, RAG, embeddings and vector search, OCR, LLM evaluation, Ollama

**ML:** PyTorch, scikit-learn, XGBoost, LightGBM, Pandas, NumPy

**Also:** TypeScript, three.js, SQL, C++ (competitive programming), Java, GitHub Actions, Google Cloud

## Right now

- Rebuilding my projects on this account, starting with ExcelMCP and Native
- Lining up a contribution to MCP tool retrieval in Gemini CLI
- Solving DSA problems in C++

---

<div align="center">
<sub>Open to internships, freelance agent work, and good open-source issues. Email gets the fastest reply.</sub>
</div>
