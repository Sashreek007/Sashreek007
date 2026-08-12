<div align="center">

## hey, I'm Sashreek

**backend systems · applied AI · 3rd-year Computing Science @ University of Alberta**

<a href="https://sashreek-addanki.vercel.app/"><img src="https://img.shields.io/badge/portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
<a href="https://www.linkedin.com/in/sashreek-addanki-121471257/"><img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://leetcode.com/u/Sashreek_18/"><img src="https://img.shields.io/badge/leetcode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"></a>
<a href="https://monkeytype.com/profile/Shrek6791"><img src="https://img.shields.io/badge/monkeytype-E2B714?style=for-the-badge&logo=monkeytype&logoColor=black" alt="MonkeyType"></a>
<a href="mailto:sashreek.addanki@gmail.com"><img src="https://img.shields.io/badge/email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>

</div>

I build backend systems, and the part I actually enjoy is the tradeoff hunting. Cache here or index there. Consistency now or throughput later. Do I need the queue at all. Most of what I know about system design I learned by building the thing, watching it fall over, and finding out why, which turns out to be a much better teacher than any diagram.

Most of that work lives in Go and Java. A service that diagnoses production outages by correlating traces, metrics, and deploy events into a small evidence packet before a model ever sees it, and a stateless API-key service that resolves rate limiting, quotas, and metering in a single atomic Redis round trip. I benchmark before I optimize, and I publish what the run produced rather than what I wanted it to, including the fault class my own engine is worst at.

### stack

**Languages**

![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

**Backend & frameworks**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![nginx](https://img.shields.io/badge/nginx-009639?style=flat-square&logo=nginx&logoColor=white)

**Data**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-FF4438?style=flat-square&logo=redis&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FFCD00?style=flat-square&logo=chromatic&logoColor=black)

**Infra & tooling**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS CDK](https://img.shields.io/badge/AWS_CDK-FF9900?style=flat-square&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Neovim](https://img.shields.io/badge/Neovim-57A143?style=flat-square&logo=neovim&logoColor=white)
![Prometheus](https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white)

**AI**

![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=flat-square&logo=huggingface&logoColor=black)
![Spring AI](https://img.shields.io/badge/Spring_AI-6DB33F?style=flat-square&logo=spring&logoColor=white)
![MCP](https://img.shields.io/badge/Model_Context_Protocol-000000?style=flat-square&logo=anthropic&logoColor=white)
![Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white)

### things I've built

| Project | Stack | What it is |
| --- | --- | --- |
| **[Replay](https://github.com/Sashreek007/Replay)** | Java 25, Spring Boot, PostgreSQL, React, OpenTelemetry | Diagnoses why a production service broke. Walks the trace-derived dependency graph, detects when the trouble started, and returns a ranked root cause where every claim cites a real telemetry signal. The model is one stage out of nine. |
| **[mint](https://github.com/Sashreek007/mint)** | Go, Redis, PostgreSQL, Lua, nginx, Prometheus | API key validation, rate limiting, quotas, and metering in one stateless service. 41% lower p99, 52% more throughput, 376x fewer Postgres writes. Ships with a stdlib-only Go SDK. |
| **[Spam Detection Bot](https://github.com/UndergraduateArtificialIntelligenceClub/Spam-Detection-Discord-Bot)** | Python, discord.py, Hugging Face | Kills scam and phishing messages in a ~1,000-member Discord on send. Two-path detector: a pretrained RoBERTa classifier plus ~35 hand-written regex rules. Spam went from roughly daily to roughly monthly. |
| **[ClubMate AI](https://github.com/UndergraduateArtificialIntelligenceClub/Clubmate-AI)** | Python, Gemini, LangChain, ChromaDB, FastAPI, Next.js | Club-admin assistant on a hand-rolled agent loop calling ~21 tools across 5 MCP servers, with RAG over club docs. Led a team of 4. 287 tests gate every merge. |
| **[Career Co-Pilot](https://github.com/Sashreek007/career-savers_CareerCo-Pilot)** | Python, FastAPI, React, Playwright, Gemini | Unifies 4 job boards behind one adapter interface, dedupes overlapping postings, and applies in your own Chrome over the DevTools Protocol, pausing whenever a form field is ambiguous. |
| **[DoomScroller](https://github.com/Sashreek007/Doom-Scroller-by-Commit-and-Pray)** | TypeScript, Chrome Extension APIs | A Chrome extension for people who open a new tab and lose 40 minutes to a feed they didn't choose. |

<sub>currently building a durable execution engine for AI agents (TypeScript, Postgres, AWS CDK) that survives a crash mid-workflow without replaying side effects</sub>
