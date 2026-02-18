<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=240&text=Cameron%20Warren&fontAlign=50&fontAlignY=42&color=0:0b1f16,50:123c2d,100:1f6f50&fontColor=e8fff6&animation=fadeIn&desc=AI%20Research%20Analyst%20•%20Full-Stack%20Engineer%20•%20Systems%20Architect&descAlign=50&descAlignY=65" />
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/cameronwarren-73a0192b2"><img src="https://img.shields.io/badge/LinkedIn-0b1f16?style=for-the-badge&logo=linkedin&logoColor=5cffb2" /></a>
  <a href="mailto:cwarre33@uncc.edu"><img src="https://img.shields.io/badge/Email-0b1f16?style=for-the-badge&logo=gmail&logoColor=5cffb2" /></a>
  <img src="https://komarev.com/ghpvc/?username=cwarre33&style=for-the-badge&color=0b1f16&label=Profile+Views" />
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1000&color=5CFFB2&center=true&vCenter=true&width=700&lines=Turning+15s+searches+into+500ms+experiences;Building+AI+that+ships+to+production;From+embeddings+to+enterprise+architecture" />
</p>

<br>

## 👋 About Me

AI Research Analyst at **Furnitureland South** (the world's largest furniture store) and CS graduate from **UNC Charlotte**. I build AI systems that actually get used—not just demos, but production platforms handling real users and real scale.

My work spans the full stack of AI engineering: from designing **AWS serverless architectures** to building **conversational AI with Microsoft Copilot Studio** to optimizing **vector search pipelines** that turned a 15-second search into a sub-500ms experience.

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<br>

## 🚀 Production Systems I've Built

### SofaScope — AI Visual Search Platform
**[🔗 Live Demo](https://sofascope.furniturelandsouth.com)**

<table>
<tr>
<td width="55%">

Visual similarity search across 120K+ furniture products. Upload an image → get instant matches based on *what it looks like*, not just keywords.

**The problem:** Sales reps needed to find "that sofa the customer saw somewhere" in a massive catalog.

**The solution:** CLIP embeddings + FAISS vector search + optimized inference = magic.

</td>
<td width="45%">

```
Performance Impact
─────────────────────────────
Latency:     15s → <500ms (30x)
Method:      Keywords → Semantic
Scale:       120K+ products
Relevance:   ✨ Actually works
```

</td>
</tr>
</table>

**Technical highlights:**
- CLIP-based dual image/text embeddings
- FAISS with optimized index structures
- Evaluated Milvus for filtered metadata queries
- Dockerized microservices architecture
- FastAPI backend, React frontend

---

### SellSmart — Enterprise Conversational AI

<table>
<tr>
<td width="55%">

AI assistant for sales reps built on **Microsoft Copilot Studio**, integrated with NetSuite ERP for live vendor data, promotions, pricing, and customer history.

**Deployed to production** — used daily by the sales team.

</td>
<td width="45%">

```
Capabilities
─────────────────────────────
• Vendor promotions lookup
• Real-time pricing (w/ tariffs)
• Customer sales history
• Lead times & availability
• NetSuite deep-linking
```

</td>
</tr>
</table>

**Technical highlights:**
- Microsoft Copilot Studio topic/flow architecture
- Boomi API integration for live NetSuite data
- SuiteQL queries for complex vendor lookups
- Analytics pipeline for usage insights
- Designed data sync automation (replaced manual CSV uploads)

---

### AWS Transcription Pipeline — Serverless Architecture

<table>
<tr>
<td width="55%">

Designed and prototyped an automated call transcription system for Zendesk support tickets using OpenAI Whisper on AWS.

Built local backfill tooling that processed **3-6 months of historical call recordings**.

</td>
<td width="45%">

```
Architecture (Designed)
─────────────────────────────
API Gateway
    ↓
Lambda (Ingest)
    ↓
S3 (Temp, 7-day TTL)
    ↓
SQS Queue
    ↓
ECS Fargate (Whisper)
    ↓
Lambda (Write-back)
```

</td>
</tr>
</table>

**Technical highlights:**
- Benchmarked `faster-whisper` models (tiny → medium) for cost/accuracy tradeoffs
- Compared against Azure Speech Services
- Built local Python app for Zendesk → Whisper → transcript attachment pipeline
- Documented cost projections and ECS sizing recommendations

---

### Stella Bot — Customer-Facing Chatbot

After-hours conversational AI on the company website. Handles FAQs, guides users through processes, and intelligently routes to human agents.

- Knowledge base article creation for coverage gaps
- Conversational flow design for complex tasks
- Intent refinement and entity recognition improvements
- QA testing with real inquiry data

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<br>

## ⚙️ Tech Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,typescript,react,fastapi,docker,aws,postgres,git&theme=dark" />
</p>

<details>
<summary><b>📋 Full Breakdown</b></summary>
<br>

| Category | Technologies |
|----------|-------------|
| **Languages** | Python, TypeScript, JavaScript, SQL (SuiteQL), Java |
| **AI/ML** | CLIP, FAISS, Whisper, Embedding pipelines, Vector search |
| **Backend** | FastAPI, Node.js, Spring, RESTful APIs |
| **Frontend** | React, Next.js, HTML/CSS |
| **Cloud & Infra** | AWS (Lambda, S3, SQS, ECS Fargate, API Gateway), Docker |
| **Integrations** | NetSuite, Zendesk, Microsoft Copilot Studio, Boomi |
| **Tools** | Git, Jira, VS Code |

</details>

<br>

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=cwarre33&show_icons=true&theme=dark&bg_color=0b1f16&title_color=5cffb2&text_color=e8fff6&icon_color=5cffb2&border_color=123c2d" height="165" />
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=cwarre33&theme=dark&background=0b1f16&ring=5cffb2&fire=5cffb2&currStreakLabel=5cffb2&border=123c2d" height="165" />
</p>

<br>

## 🔬 Other Projects

| Project | Description |
|---------|-------------|
| **[Resume & Pitch Agent](https://github.com/Astroid45/GenAI-FinalProject)** | AI app that optimizes resumes for specific jobs and generates pitch decks |
| **[ARC-AGI Benchmarking](https://github.com/cwarre33/arc-agi-benchmarking)** | Testing LLM baselines on the ARC-AGI reasoning benchmark |
| **[Algo Vault](https://github.com/cwarre33/algo-vault)** | Polyglot algorithm implementations (Go, TS, Python, JS, C#, C++) |

<br>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<br>

## 🧭 What I'm Focused On

```python
current_work = {
    "🔍 Search & Retrieval": "Vector databases, semantic search, sub-second latency",
    "🤖 Conversational AI": "Enterprise chatbots that integrate with real systems",
    "☁️ Cloud Architecture": "Serverless pipelines, cost-optimized ML inference",
    "🔗 System Integration": "Making AI work with NetSuite, Zendesk, and legacy systems",
    "📊 AI Analytics": "Understanding how AI tools are actually being used"
}
```

<br>

## 🎓 Education & Certifications

**B.S. Computer Science** — UNC Charlotte (Dec 2026)

<p>
  <img src="https://img.shields.io/badge/AWS_Cloud_Foundations-232F3E?style=flat-square&logo=amazonaws&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-000000?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Data_&_AI_Foundations-0078D4?style=flat-square&logo=codecademy&logoColor=white" />
</p>

<br>

## 💬 Let's Connect

I'm always interested in discussing AI systems that ship, search infrastructure, or interesting engineering challenges.

<p align="center">
  <i>"The best AI is the AI that gets used."</i>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&height=100&color=0:0b1f16,50:123c2d,100:1f6f50&section=footer" />
</p>
