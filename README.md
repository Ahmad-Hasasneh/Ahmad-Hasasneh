<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2d4a,100:26639b&height=180&section=header&text=Ahmad%20Hasasneh&fontSize=48&fontColor=ffffff&animation=fadeIn&fontAlignY=35&desc=Artificial%20Intelligence%20Engineer&descAlignY=57&descSize=18" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3000&pause=800&color=26639B&center=true&vCenter=true&width=700&lines=Building+AI+systems+that+reach+real+users;LLM+Applications+%7C+RAG+%7C+Agents;Arabic+NLP+%7C+Computer+Vision;9XAI+Fellow+%40+Al+Hussein+Technical+University" alt="Typing SVG" />
</a>

<br/><br/>

<a href="https://www.linkedin.com/in/ahmad-hasasneh">
  <img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>
<a href="mailto:ahmad_hasasneh@outlook.com">
  <img src="https://img.shields.io/badge/Email-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" alt="Email"/>
</a>

</div>

<br/>

### `>` whoami

AI Engineer and **9XAI Fellow** at **Al Hussein Technical University (HTU)**, building AI
platforms for government clients at national scale.

```yaml
role:      AI Engineer · 9XAI Fellow
focus:     [ LLM applications, RAG, multi-agent systems, Arabic NLP ]
building:  government platforms at national scale
education: B.Sc. AI & Robotics — BAU · GPA 3.88/4.00 · 1st in class
before:    AI Prompt Engineer — training & evaluating LLMs
location:  Amman, Jordan
```

<br/>

---

<div align="center">

## Projects

*Click any project to expand*

</div>

<details>
<summary><b>&nbsp;Citizen Engagement Platform</b>&nbsp;&nbsp;<code>Government</code>&nbsp;&nbsp;<img src="https://img.shields.io/badge/RAG-26639b?style=flat-square"/> <img src="https://img.shields.io/badge/Arabic%20NLP-26639b?style=flat-square"/> <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white"/></summary>

<br/>

> Citizens report problems and ask questions through a web portal and messaging channels. The system
> reads each submission, decides its subject and urgency, and routes it to the responsible entity.

**What I built**

| | |
|---|---|
| **Retrieval stack, end to end** | Corpus preparation, section-aware chunking, embeddings, a `pgvector` store, retrieval with a relevance gate |
| **Grounded answering** | Streamed answers carrying a citation on every reply, in Arabic and English, escalating to complaint filing when it cannot answer |
| **Classification & routing** | Arabic transformer classifier paired with an LLM arbiter to settle disagreements and auto-correct miscategorised submissions |
| **Production** | OTP authentication, PII masking, staged deployments, an additional messaging channel at full parity |

<a href="https://github.com/Ahmad-Hasasneh/citizen-engagement-platform"><b>Read more →</b></a>

</details>

<details>
<summary><b>&nbsp;Legal Intelligence Platform</b>&nbsp;&nbsp;<code>Government</code>&nbsp;&nbsp;<img src="https://img.shields.io/badge/Knowledge%20Graph-26639b?style=flat-square"/> <img src="https://img.shields.io/badge/Neo4j-4581C3?style=flat-square&logo=neo4j&logoColor=white"/> <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white"/></summary>

<br/>

> Search and question answering over national legislation, with conflict detection between a
> regulation and the laws around it, both those in force and those still coming.

**What I built**

| | |
|---|---|
| **Interface** | The platform's frontend and its wiring to the backend services |
| **Legal assistant** | Answers legal questions in Arabic and English with a citation back to the source article |
| **Retrieval quality** | Diagnosing wrong results and correcting the indexing and relationship linking behind them |

<a href="https://github.com/Ahmad-Hasasneh/legal-intelligence-platform"><b>Read more →</b></a>

</details>

<details>
<summary><b>&nbsp;Course Production Platform</b>&nbsp;&nbsp;<code>Higher Education</code>&nbsp;&nbsp;<img src="https://img.shields.io/badge/Full%20Stack-26639b?style=flat-square"/> <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/> <img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white"/></summary>

<br/>

> Runs an online course from the moment a dean decides it should exist through to publication,
> across many roles and gated review stages.

**What I built**

| | |
|---|---|
| **The entire frontend** | A screen for every role the pipeline needs, in Arabic and English with full right-to-left support |
| **AI layer** | Drafts course content from the instructor's own material, scores publication readiness, reviews against an international quality rubric |
| **Document editor** | Version history, comments anchored to the text, sanitisation, and sign-off wired into the pipeline so a studio booking cannot proceed without it |
| **Multi-owner model** | Per-unit ownership and live-synced AI drafting, removing concurrent-write data loss by design rather than locking |

<a href="https://github.com/Ahmad-Hasasneh/course-production-platform"><b>Read more →</b></a>

</details>

<details>
<summary><b>&nbsp;Crisis Simulation Engine</b>&nbsp;&nbsp;<code>Research</code>&nbsp;&nbsp;<img src="https://img.shields.io/badge/Multi--Agent-26639b?style=flat-square"/> <img src="https://img.shields.io/badge/Guardrails-26639b?style=flat-square"/> <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/></summary>

<br/>

> An LLM agent swarm where an analyst, verifier, critique and commander work a scenario and check
> each other, over a data layer built from real infrastructure and public sources.

**What I built**

| | |
|---|---|
| **Data foundation** | Layered data taxonomy, a quality scoring pipeline, and failure injectors for testing behaviour under bad input |
| **Model client** | Provider-agnostic and async, with retries, exponential backoff, fallback and routing between reasoning and extraction models |
| **Memory** | Persistent episodic memory, semantic search over past runs, dependency graph lookup for upstream and downstream effects |
| **Safety** | Agent guardrails with pre- and post-execution validation, plus a supervision dashboard |

<a href="https://github.com/Ahmad-Hasasneh/crisis-simulation-engine"><b>Read more →</b></a>

</details>

<details>
<summary><b>&nbsp;Intelligent Traffic Light</b>&nbsp;&nbsp;<code>Graduation Project</code>&nbsp;&nbsp;<img src="https://img.shields.io/badge/Computer%20Vision-26639b?style=flat-square"/> <img src="https://img.shields.io/badge/YOLOv8-111F68?style=flat-square"/> <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white"/></summary>

<br/>

> Traffic lights that respond to real traffic instead of a fixed cycle.

**What I built**

| | |
|---|---|
| **Detection & tracking** | YOLOv8 detection with Deep SORT tracking across frames, producing per-approach vehicle counts and stopped-vehicle detection |
| **Adaptive timing** | Green time allocated to the busier direction rather than a fixed turn |
| **2026 rebuild** | A live SUMO simulation of a real Amman intersection, driven by live traffic data, built for a 9XAI hackathon |

<a href="https://github.com/Ahmad-Hasasneh/Graduation_Project_Demo"><b>Read more →</b></a>

</details>

<br/>

---

<div align="center">

## Tech Stack

<img src="https://skillicons.dev/icons?i=python,fastapi,tensorflow,sklearn,opencv,postgres,redis,docker,nextjs,react,ts,js,cpp,java,go,git&perline=8" alt="Tech stack"/>

</div>

<br/>

---

<div align="center">

## GitHub

<img height="160" src="https://github-readme-stats.vercel.app/api?username=Ahmad-Hasasneh&show_icons=true&count_private=true&hide_border=true&title_color=26639b&icon_color=26639b&text_color=555555&bg_color=ffffff" alt="GitHub stats"/>
<img height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Ahmad-Hasasneh&layout=compact&hide_border=true&title_color=26639b&text_color=555555&bg_color=ffffff&langs_count=8" alt="Top languages"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=Ahmad-Hasasneh&theme=github-light&hide_border=true&color=26639b&line=26639b&point=0f2d4a&area=true" width="95%" alt="Activity graph"/>

</div>

<br/>

---

<div align="center">

**Most of my work sits in private repositories.**
The projects above are described at the level their agreements allow — happy to go deeper in conversation.

<br/>

<a href="https://www.linkedin.com/in/ahmad-hasasneh">
  <img src="https://img.shields.io/badge/Let's%20talk-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
</a>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:26639b,100:0f2d4a&height=100&section=footer" width="100%"/>

</div>
