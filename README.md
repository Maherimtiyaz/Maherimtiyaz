<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:6366f1,50:a78bfa,100:22d3ee&height=200&section=header&text=Mahek%20Fatima&fontColor=ffffff&fontSize=42&fontAlignY=32&animation=fadeIn&desc=Backend%20Engineer%20|%20Python%20·%20FastAPI%20·%20PostgreSQL%20·%20LLM%20Systems&descSize=15&descColor=c4b5fd&descAlignY=58" width="100%"/>

</div>

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=800&color=6366F1&center=true&vCenter=true&multiline=true&width=750&height=100&lines=Backend+Engineer+%F0%9F%9A%80;Building+multi-tenant+APIs+%26+LLM-powered+backends;Python+%C2%B7+FastAPI+%C2%B7+PostgreSQL+%C2%B7+TypeScript+%C2%B7+Docker;Webhook-driven+async+pipelines+%7C+Voice+AI+infrastructure;Ship+it.+Debug+it.+Learn+from+it." alt="Typing SVG" />

</div>

<div align="center">

<img src="https://komarev.com/ghpvc/?username=Maherimtiyaz&style=flat-square&color=6366f1&label=Profile+Views&base=1200" alt="Profile Views"/>
<img src="https://img.shields.io/github/followers/Maherimtiyaz?style=flat-square&color=a78bfa&logo=github&label=Follow" alt="Followers"/>
<img src="https://img.shields.io/github/stars/Maherimtiyaz?style=flat-square&color=22d3ee&logo=github&label=Stars" alt="Stars"/>
<img src="https://img.shields.io/badge/Status-Open_to_Work-22c55e?style=flat-square&logo=verified&logoColor=white" alt="Status"/>

</div>

---

<div align="center">
<h2>
<img src="https://media.giphy.com/media/WUlplcMpOCEmTGBtBW/giphy.gif" width="30"> About Me
</h2>
</div>

<table>
<tr>
<td width="65%">

```python
class MahekFatima:
    """Backend Engineer who builds production-ready systems."""

    def __init__(self):
        self.name = "Mahek Fatima"
        self.role = "Backend Engineer @ Cloud Nova"
        self.location = "Jaipur, India 🇮🇳"

        self.code = ["Python", "TypeScript", "JavaScript", "SQL"]
        self.backend = ["FastAPI", "Node.js", "WebSockets", "Celery", "JWT/RBAC"]
        self.databases = ["PostgreSQL", "Redis", "MongoDB", "SQLAlchemy", "Drizzle"]
        self.ai = ["OpenAI", "Anthropic", "RAG", "LLM Tool Calling"]
        self.devops = ["Docker", "GitHub Actions", "Render", "pytest", "Vitest"]

        self.architecture = [
            "Multi-tenant APIs with tenant isolation",
            "Webhook-driven async pipelines",
            "RAG systems with embedding retrieval",
            "Voice AI (Twilio/Vapi/LiveKit)",
        ]

    def currently(self):
        return {
            "building": "Voice Agent Platform — 7-tool LLM framework",
            "learning": "Voice AI — STT/TTS pipelines, LiveKit",
            "grinding": "Neetcode 150 — 2 problems/day",
            "seeking": "Remote backend engineering roles 🚀"
        }
```

</td>
<td width="35%" align="center">

<br/>

<img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="220"/>

<br/><br/>

<img src="https://img.shields.io/badge/🏢-Cloud_Nova-6366f1?style=for-the-badge&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/🎓-Jaipur_India-ef4444?style=for-the-badge&logoColor=white" />
<br/>
<img src="https://img.shields.io/badge/📧-mahekimtiyaz7@gmail.com-ea4335?style=for-the-badge&logo=gmail&logoColor=white" />

</td>
</tr>
</table>

---

<div align="center">
<h2>
<img src="https://media.giphy.com/media/TEnXkcsHrP4YadChgy/giphy.gif" width="30"> Experience
</h2>
</div>

<div align="center">

| 🏢 | **Cloud Nova** — Early-stage Startup |
|:---|:---|
| 📅 | *Apr 2026 – May 2026* |
| 💼 | *Backend Engineer* |

</div>

| | |
|---|---|
| 🗄️ | Designed **database schema** & **SQLAlchemy ORM models** for the platform's data layer |
| ⚡ | Built **Celery ingestion tasks** with typed schemas for the data pipeline |
| 🔌 | Implemented core **FastAPI REST API** with **WebSocket** support |
| 🔍 | Added **change-detection gate** (`pipeline/change_detector.py`) to the pipeline |
| 🔐 | Integrated **Clerk authentication** (JWT validation) on protected routes |
| 🛡️ | Hardened API with **rate limiting**, **request logging**, and **API versioning** |
| 📧 | Built **email notification pipeline** on Resend SDK with integration tests |

---

<div align="center">
<h2>
<img src="https://media.giphy.com/media/juua9i2c2fA0AIp2iq/giphy.gif" width="30"> Shipped Projects
</h2>
</div>

<table>
<tr>
<td width="50%">

<div align="center">

### 🎙️ Voice Agent Platform
*Multi-Tenant SaaS for AI Phone Agents*

</div>

`Next.js` `TypeScript` `PostgreSQL` `Drizzle` `Twilio` `Vapi` `Zod` `Vitest`

- 🔗 **Twilio & Vapi webhook handlers** with idempotency ledger — provider retries never create duplicates
- 🏗️ **7-tool LLM function-calling** framework (Zod validation, org-scoped handlers, audit log)
- ✅ **100 Vitest tests** against in-memory Postgres (PGlite)
- 🔒 Tenant isolation from app's own records, not request payloads

<div align="center">
<img src="https://img.shields.io/badge/🟢_LIVE-22c55e?style=flat-square" />
</div>

</td>
<td width="50%">

<div align="center">

### 📄 AI-Powered Document API
*Production RAG Pipeline*

</div>

`Python` `FastAPI` `PostgreSQL` `OpenAI` `NumPy` `Docker`

- 📚 **RAG backend**: PDF ingestion → overlapping chunking → embedding retrieval → grounded Q&A
- 🔐 JWT auth with **response caching**
- 🐛 Debugged Render build & runtime failures (memory, deps, ephemeral disk)
- 🔄 Replaced FAISS with **PostgreSQL-stored embeddings** + NumPy cosine similarity

<div align="center">
<img src="https://img.shields.io/badge/🟢_LIVE-22c55e?style=flat-square" />
<a href="https://ai-powered-doc-api.onrender.com"><img src="https://img.shields.io/badge/→_Live_Demo-0ea5e9?style=flat-square" /></a>
</div>

</td>
</tr>
<tr>
<td width="50%">

<div align="center">

### 🗺️ Atlas
*Visual Product Map for Codebases*

</div>

`React` `Vite` `TypeScript` `Tailwind` `Zustand` `React Flow` `pdf-lib`

- 🌐 Turns GitHub repos into **interactive product graphs**
- 🔍 Node selection, flow tracing, complexity views
- 📥 GitHub import + JSON upload + **client-side PDF export**
- 🚫 No backend or database required

<div align="center">
<img src="https://img.shields.io/badge/🟢_LIVE-22c55e?style=flat-square" />
</div>

</td>
<td width="50%">

<div align="center">

### 📋 TaskOps
*Multi-Tenant Task Management API*

</div>

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Alembic` `JWT` `RBAC`

- 🏗️ REST API with **per-organization data isolation**
- 🔐 JWT authentication + RBAC
- 📊 Normalized schemas with **Alembic migrations**
- 🔄 CI running **pytest** on every push

</td>
</tr>
<tr>
<td width="50%">

<div align="center">

### 🔐 Auth Service
*Stateless JWT + Refresh Rotation*

</div>

`Python` `FastAPI` `JWT` `bcrypt` `OWASP` `pytest`

- 🔑 JWT access tokens with **refresh-token rotation**
- 🍪 HttpOnly-cookie refresh tokens + revocation
- 🛡️ RBAC with database-backed **token audit trail**
- ✅ OWASP-aligned pluggable microservice module

</td>
<td width="50%">

<div align="center">

### 💬 Real-Time Chat
*Async WebSocket Backend*

</div>

`Python` `FastAPI` `WebSockets` `PostgreSQL` `Docker`

- ⚡ Async WebSocket with **JWT-authenticated connections**
- 📡 Room-based broadcast, multi-room concurrent
- 🚀 **Indexed FK queries** — no sequential scans
- 🐳 Fully containerized with Docker

</td>
</tr>
</table>

---

<div align="center">
<h2>
<img src="https://media.giphy.com/media/QHE4gWI0QK5USLp0Qn/giphy.gif" width="30"> Tech Stack
</h2>
</div>

<div align="center">

**🖥️ Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)

</div>

<div align="center">

**⚡ Backend & APIs**

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=for-the-badge&logo=celery&logoColor=white)
![WebSockets](https://img.shields.io/badge/WebSockets-000?style=for-the-badge&logo=socket.io&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=for-the-badge&logo=jsonwebtokens&logoColor=white)

</div>

<div align="center">

**🗄️ Data & Storage**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![SQLAlchemy](https://img.shields.io/badge/SQLAlchemy-BB0000?style=for-the-badge&logo=python&logoColor=white)
![Drizzle](https://img.shields.io/badge/Drizzle-C5F547?style=for-the-badge&logo=drizzle&logoColor=black)

</div>

<div align="center">

**🤖 LLM / AI**

![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Anthropic](https://img.shields.io/badge/Anthropic-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-FF6F00?style=for-the-badge&logo=apache&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=chainlink&logoColor=white)

</div>

<div align="center">

**🐳 DevOps & Testing**

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=for-the-badge&logo=vitest&logoColor=white)

</div>

---

<div align="center">
<h2>
<img src="https://media.giphy.com/media/TFJ6qGnrmgG2jLpXbK/giphy.gif" width="30"> GitHub Analytics
</h2>
</div>

<div align="center">

<table>
<tr>
<td>

<p align="center">
<img height="180em" src="https://github-readme-stats.vercel.app/api?username=Maherimtiyaz&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true&bg_color=00000000" />
</p>

</td>
<td>

<p align="center">
<img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Maherimtiyaz&layout=compact&theme=tokyonight&hide_border=true&langs_count=8&bg_color=00000000" />
</p>

</td>
</tr>
</table>

</div>

<div align="center">

<img src="https://github-readme-streak-stats.herokuapp.com?user=Maherimtiyaz&theme=tokyonight&hide_border=true&date_format=j%20M%5B%20Y%5D&background=FFFEFE00&ring=6366F1&fire=22D3EE&currStreakLabel=A78BFA" alt="Streak Stats" />

</div>

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Maherimtiyaz&theme=tokyo-night&hide_border=true&area=true&bg_color=00000000&color=6366f1&line=a78bfa&point=22d3ee&area_color=6366f1&title_color=a78bfa" width="100%" alt="Activity Graph" />

</div>

<div align="center">

<img src="https://github-profile-trophy.vercel.app/?username=Maherimtiyaz&theme=tokyonight&no-frame=true&no-bg=true&row=1&column=7&title=Commits,Repositories,Followers,Stars,PullRequests,Issues,MultiLanguage" alt="Trophies" />

</div>

---

<div align="center">
<h2>
🐍 Contribution Snake
</h2>

<picture>
<source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Maherimtiyaz/Maherimtiyaz/output/github-contribution-grid-snake-dark.svg">
<source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Maherimtiyaz/Maherimtiyaz/output/github-contribution-grid-snake.svg">
<img alt="github contribution grid snake animation" src="https://raw.githubusercontent.com/Maherimtiyaz/Maherimtiyaz/output/github-contribution-grid-snake-dark.svg">
</picture>

<sub>⚠️ To enable the snake animation, set up [Platane/snk](https://github.com/Platane/snk) as a GitHub Action in your profile repo.</sub>

</div>

---

<div align="center">
<h2>
<img src="https://media.giphy.com/media/jOz35yxbuhvVQVrDXC/giphy.gif" width="30"> What I'm Up To
</h2>
</div>

<div align="center">

<table>
<tr>
<td width="33%">

<div align="center">

### 🔨 Building
**Voice Agent Platform**
Twilio/Vapi webhooks
LLM function calling
Idempotency ledgers

</div>

</td>
<td width="33%">

<div align="center">

### 🤖 Learning
**Voice AI Infrastructure**
STT/TTS pipelines
LiveKit integration
Real-time inference

</div>

</td>
<td width="33%">

<div align="center">

### 📖 Grinding
**Neetcode 150**
2 problems/day
No days off
DSA mastery

</div>

</td>
</tr>
<tr>
<td width="33%">

<div align="center">

### 🌐 Contributing
**FastAPI / Python OSS**
Merged PRs in YATL
& DeepAlpha
Open source advocate

</div>

</td>
<td width="33%">

<div align="center">

### 🏆 Hackathons
**GitLab Transcend**
Built CascadeAgent
Remediation work items
in GitLab

</div>

</td>
<td width="33%">

<div align="center">

### 🔍 Seeking
**Remote Backend Roles**
Engineering internships
Production systems
Scale & impact

</div>

</td>
</tr>
</table>

</div>

---

<div align="center">
<h2>
<img src="https://media.giphy.com/media/26gqZ4OnzX2aYp2DKI/giphy.gif" width="30"> Open Source & Hackathons
</h2>
</div>

<div align="center">

<table>
<tr>
<td width="33%">

<div align="center">

### ✅ YATL
**Merged PR**

Custom exception class for error handling in Python projects

<img src="https://img.shields.io/badge/PR-Merged-22c55e?style=flat-square" />

</div>

</td>
<td width="33%">

<div align="center">

### ✅ DeepAlpha
**Merged PR**

pytest-asyncio test infrastructure improvements

<img src="https://img.shields.io/badge/PR-Merged-22c55e?style=flat-square" />

</div>

</td>
<td width="33%">

<div align="center">

### 🏆 CascadeAgent
**GitLab Transcend**

Built with FastAPI — fanning out remediation work items

<img src="https://img.shields.io/badge/Hackathon-Complete-6366f1?style=flat-square" />

</div>

</td>
</tr>
</table>

</div>

---

<div align="center">
<h2>
<img src="https://media.giphy.com/media/LnQjpWaON8nhr21vNW/giphy.gif" width="30"> I Write Sometimes
</h2>

When I figure something out the hard way, **I write it down.**

[![Medium](https://img.shields.io/badge/Medium-@mahimaher343-12100E?style=for-the-badge&logo=medium&logoColor=white)](https://medium.com/@mahimaher343)

</div>

---

<div align="center">
<h2>
📬 Let's Connect
</h2>

<a href="https://mahekportfoliov2.vercel.app/" target="_blank">
<img src="https://img.shields.io/badge/🌐_Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white" />
</a>

<a href="https://linkedin.com/in/mahek-fatima" target="_blank">
<img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
</a>

<a href="https://x.com/itzmaherimtiyaz" target="_blank">
<img src="https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=x&logoColor=white" />
</a>

<a href="mailto:mahekimtiyaz7@gmail.com">
<img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
</a>

<a href="https://github.com/Maherimtiyaz" target="_blank">
<img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" />
</a>

</div>

---

<div align="center">

<img src="https://github-readme-quotes-bay.vercel.app/quote?theme=dark&animation=grow_out&font=Fira+Code&quote=Ship+it.+Debug+it.+Learn+from+it.+That%27s+how+you+grow.&author=Mahek+Fatima" alt="Dev Quote" />

</div>

---

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:22d3ee,50:a78bfa,100:6366f1&height=120&section=footer&animation=fadeIn&text=%F0%9F%9A%80%20ship%20it.%20debug%20it.%20learn%20from%20it.&fontColor=ffffff&fontSize=20&fontAlignY=75" width="100%"/>

</div>

<div align="center">

<sub>Built with ❤️ by **Mahek Fatima** | Jaipur, India 🇮🇳</sub>

<br/><br/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=gradient&customColorList=4&height=3&width=400" width="400"/>

</div>

