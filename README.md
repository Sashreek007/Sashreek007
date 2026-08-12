### hey, I'm Sashreek

I build backend systems, and the part I actually enjoy is the tradeoff hunting. Cache here or index there. Consistency now or throughput later. Do I need the queue at all. Most of what I know about system design I learned by building the thing, watching it fall over, and finding out why, which turns out to be a much better teacher than any diagram.

Right now that means writing services in Go and Java, measuring them honestly, and refusing to publish the number I was hoping for instead of the number I got.

When I'm not doing that I'm on LeetCode, or on MonkeyType convincing myself that typing fast is a personality trait. It is.

<a href="https://sashreek-addanki.vercel.app/"><img src="https://img.shields.io/badge/portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a>
<a href="https://www.linkedin.com/in/sashreek-addanki-121471257/"><img src="https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
<a href="https://leetcode.com/u/LEETCODE_USERNAME/"><img src="https://img.shields.io/badge/leetcode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" alt="LeetCode"></a>
<a href="https://monkeytype.com/profile/MONKEYTYPE_USERNAME"><img src="https://img.shields.io/badge/monkeytype-E2B714?style=for-the-badge&logo=monkeytype&logoColor=black" alt="MonkeyType"></a>
<a href="mailto:sashreek.addanki@gmail.com"><img src="https://img.shields.io/badge/email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>

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
