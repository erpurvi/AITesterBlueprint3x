# AI Testing practice for QA

A project-driven course for QA engineers to use LLMs as real testing tools — prompts, agents, RAG, and MCP.

---

## Chapters at a Glance

| Chapters | Details |
|----------|---------|
| [Chapter 01 — LLM Basics](chapter_01_LLM_Basics/Notes.md) | How attention works — interactive visualisers of the Transformer paper. |
| [Chapter 02 — Prompt Engineering for QA](chapter_02_Prompt_Eng/) | RICE-POT framework, anti-hallucination rules, test-case generation from a PRD, a Selenium framework built from a prompt, 6 reusable templates. |
| [Chapter 03 — B.L.A.S.T. Jira Test Plan Generator](chapter_03_BLAST_FW_JIRA_AI_AGENT/) | A React + Express app that turns a Jira ticket into a formal QA test plan via GROQ. |
| [Chapter 04 — n8n + Local AI Agents](chapter_04_AI_Agents_n8n/) | Importable n8n workflows, a local content dashboard (ContentForge), a scheduled social-post agent, and a resume-tailor skill. |
| [Chapter 05 — AI Agents with LangFlow](chapter_05_AI_Agents_LangFlow/) | Visual low-code agents — Flaky Test Analyzer, Bug Triage, API Contract Validator — published as REST APIs. |
| [Chapter 06 — AI Social Media Content](chapter_06_AI_Social_Media_Content_Creation/) | One idea → 7 platform templates (YouTube, Reel, Post, Carousel, Medium, Blog, LinkedIn). |
| [Chapter 07 — RAG](chapter_07_RAG/) | RAG Explorer app, n8n + LangFlow RAG flows, and an Advanced RAG pipeline (hybrid retrieval + reranking over 5,000 test cases). |
| [Chapter 08 — QABuddy.ai](chapter_08_QABuddyAI/Plan.md) | Multi-source hybrid RAG: one cited answer across 10 QA knowledge sources, with a chat UI and VPS deployment pack. |
| [Chapter 09 — MCP Basics](chapter_09_MCP_Basics/MCP.md) | What MCP is and why it exists — protocol, roles, primitives, transports, security. Read before chapter 10. |
| [Chapter 10 — Build an MCP Server](chapter_10_MCP_Creation_VIBE/testcase-creator-mcp/README.md) | A FastMCP server exposing 5,000 test cases as tools, resources, and prompts. |
| [Chapter 11 — Python for Testers](chapter_11_Python_Learning/ex_01_Python_Basics/Lab001_Hello.py) | Hands-on Python labs from `print()` to OOP, exceptions, collections, and pytest. |
| [Chapter 12 — CrewAI Test Analyst](chapter_12_CrewAI/01_test_analyst_Agent.py) | A QA Analyst agent that turns a requirement into 5–10 P0 test cases. |
| [Chapter 13 — Jira QA Crew](chapter_13_CREW_AI_QA_Pipeline/) | A Streamlit app where 4 CrewAI agents produce analysis, test plan, cases, and Playwright automation from Jira tickets — 260 tests, no live Jira. |
| [Chapter 14 — LLM Evaluation](chapter_14_LLM_Eval/README.md) | Why `assertEquals` breaks on generated text — golden datasets, LLM-as-judge, faithfulness, thresholds. |
| [Chapter 16 — E2E AI QA Pipeline](chapter_16_E2E_QA_Pipeline/E2E_QA_Pipeline.md) | The capstone blueprint: Jira story → test plan → cases → Playwright automation → execution → RCA dashboard. |
| [Project — Job Tracker AI](Project_Job_TRACKERAI/README.md) | A local-first React Kanban board for job applications (IndexedDB, drag-and-drop, JSON backup). |

> Note: there is no chapter 15 — the course jumps from 14 to 16.

---

## Repository Layout

```
chapter_01_LLM_Basics/                     Transformer + attention visualisers
chapter_02_Prompt_Eng/                     RICE-POT prompts, 2 projects, 6 templates
chapter_03_BLAST_FW_JIRA_AI_AGENT/         Jira → test plan generator (React + Express)
chapter_04_AI_Agents_n8n/                  n8n workflows, ContentForge, resume-tailor skill
chapter_05_AI_Agents_LangFlow/             LangFlow QA agents + React UI
chapter_06_AI_Social_Media_Content_Creation/   7 platform content templates
chapter_07_RAG/                            RAG Explorer, n8n/LangFlow flows, Advanced RAG
chapter_08_QABuddyAI/                      Multi-source hybrid RAG QA brain
chapter_09_MCP_Basics/                     MCP concepts (reading chapter)
chapter_10_MCP_Creation_VIBE/              FastMCP server over 5,000 test cases
chapter_11_Python_Learning/                Python fundamentals labs for testers
chapter_12_CrewAI/                         CrewAI test analyst + bug triage agents
chapter_13_CREW_AI_QA_Pipeline/            Jira QA Crew — Streamlit app, 4 agents
chapter_14_LLM_Eval/                       LLM evaluation concepts
chapter_16_E2E_QA_Pipeline/                End-to-end AI QA pipeline blueprint
Project_Job_TRACKERAI/                     Local-first job application tracker
```

---

## Author

- **Author:** Purvi B
- **GitHub:** [github.com/erpurvi](https://github.com/erpurvi)
