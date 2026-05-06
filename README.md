<!-- Hero — solid black, no gradient. Typography-led. -->
<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=rect&color=0a0a0a&height=200&section=header&text=Roshan%20Kharel&fontSize=64&fontColor=f5f5f5&fontAlignY=43&desc=AI%20Engineer%20%E2%80%94%20Building%20production%20LLM%20systems&descAlignY=66&descSize=17" width="100%" alt="Roshan Kharel — AI Engineer" />
</div>

<!-- Animated tagline (resume-anchored, narrower to avoid clipping) -->
<div align="center">
  <a href="https://geekyroshan.tech">
    <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=18&duration=3500&pause=900&color=58A6FF&center=true&vCenter=true&width=640&lines=5%2B+years+building+production+LLM+systems.;Multi-tenant+agent+platforms+%C2%B7+GDPR-compliant.;Voice+agents+in+3+languages+%C2%B7+sub-4s+latency.;RAG+%C2%B7+LangGraph+%C2%B7+agent+orchestration.;Currently+%40+AllysAI+%C2%B7+Open+to+remote+roles." alt="What I build" />
  </a>
</div>

<br/>

<!-- Contact — monochrome flat-square -->
<div align="center">
  <a href="https://geekyroshan.tech"><img src="https://img.shields.io/badge/Website-geekyroshan.tech-e6edf3?style=flat-square&logo=googlechrome&logoColor=e6edf3&labelColor=0d1117" alt="Website" /></a>
  <a href="https://www.linkedin.com/in/rroshankharel"><img src="https://img.shields.io/badge/LinkedIn-rroshankharel-e6edf3?style=flat-square&logo=linkedin&logoColor=e6edf3&labelColor=0d1117" alt="LinkedIn" /></a>
  <a href="https://twitter.com/realroshan2001"><img src="https://img.shields.io/badge/X-%40realroshan2001-e6edf3?style=flat-square&logo=x&logoColor=e6edf3&labelColor=0d1117" alt="X" /></a>
  <a href="mailto:connectwithroshann@gmail.com"><img src="https://img.shields.io/badge/Email-connectwithroshann%40gmail.com-e6edf3?style=flat-square&logo=gmail&logoColor=e6edf3&labelColor=0d1117" alt="Email" /></a>
  <img src="https://komarev.com/ghpvc/?username=geekyroshan&label=Profile+Views&color=58a6ff&style=flat-square" alt="Profile Views" />
</div>

---

### `> whoami`

AI Engineer with **5+ years** building production LLM systems across SaaS, voice AI, and real-time pipelines. Currently leading AI engineering at **[AllysAI](https://allysai.com)** — multi-tenant agent platforms, GDPR-compliant legal-tech RAG, and multimodal voice avatars demoed at **Dubai AI Summit 2026**.

Previously **founding engineer** at Magic Square (Web3 analytics, 90K+ events/day) and **software & blockchain engineer** at LunarCrush (social-crypto pipelines, 50K DAU). MTech in AI from **Tezpur University**.

Based in **Guwahati, India** · Open to **remote AI engineering roles** at companies building agentic systems, multimodal AI, or production LLM infrastructure.

---

### `> currently_building`

```text
○ AllysAgent  → Multi-tenant WhatsApp AI for GCC SMEs · 7-layer tenant isolation · live
○ Klavy       → French legal-tech SaaS · 14-node LangGraph · 760+ Légifrance docs · GDPR
○ Sarathi     → Multilingual gov voice agent · Assamese · Bodo · Hindi · sub-4s latency
```

---

### `> featured_work`

<table>
<tr>
<td valign="top" width="50%">

#### Klavy &nbsp;<a href="https://klavy-web-8x45q.ondigitalocean.app/"><sub>↗ live</sub></a>

<sub><b>AI Property Management SaaS · France · GDPR</b></sub>

14-node LangGraph agent over a French legal RAG corpus of **760+ Légifrance documents** (auto-refreshed weekly via PISTE API). Document-AI pipeline (DeepSeek OCR → LLM extraction → 0–100 risk scoring) for tenant verification. Stripe billing. Multi-channel (web + WhatsApp). Hosted on Azure France Central for data residency.

<sub>Next.js · FastAPI · LangGraph · Azure OpenAI · DeepSeek OCR · pgvector · Stripe</sub>

</td>
<td valign="top" width="50%">

#### AllysAgent &nbsp;<a href="https://agent.allysai.com"><sub>↗ live</sub></a>

<sub><b>Multi-Tenant WhatsApp AI · GCC SMEs · ~100K LOC</b></sub>

Hardened multi-tenant agent platform with **7-layer tenant isolation**: routing gate, distributed locks per tenant, per-tenant SQLite memory, AES-256-GCM credential vault with HKDF-derived keys, chrooted filesystem, prompt isolation. 8 production workflows — customer support, AR collection, daily brief, lead research, market intel.

<sub>Node.js · Fastify · OpenClaw · PostgreSQL · Redis · BullMQ · Claude · WhatsApp Cloud API</sub>

</td>
</tr>
<tr>
<td valign="top" width="50%">

#### SIMO — Multimodal AI Avatar &nbsp;<sub><b>Dubai AI Summit 2026</b></sub>

<sub><b>Real-time vision + voice · sub-3s response loop</b></sub>

Real-time interactive avatar combining **vision** (face, emotion, gesture detection via GPT-4 Vision + MediaPipe + face-api.js) and **voice** (Whisper STT + ElevenLabs TTS + HeyGen lip sync) with a sub-3-second response loop. Touchless interaction via gesture recognition. Multilingual (EN / AR / FR) with vision-based language switching.

<sub>TypeScript · React · WebSocket · GPT-4 Vision · MediaPipe · Whisper · ElevenLabs · HeyGen · Pinecone</sub>

</td>
<td valign="top" width="50%">

#### AllysAI Consulting Agent

<sub><b>Sub-4s end-to-end voice pipeline · barge-in support</b></sub>

Voice + text AI consultant with full pipeline under 4 seconds: **STT (300–500ms) → RAG (100–200ms) → GPT-4o-mini (500–800ms) → TTS (300–500ms)**. First sentence streams while the remainder synthesizes concurrently. Live lead-qualification metrics — readiness score, fit score, ROI projection.

<sub>TypeScript · React · WebSocket · Whisper · GPT-4o-mini · ElevenLabs · Pinecone</sub>

</td>
</tr>
<tr>
<td valign="top" width="50%">

#### SALAMA — UAE Crisis Intelligence

<sub><b>Concept → production in 1 week</b></sub>

Real-time crisis platform built and shipped during a live UAE emergency. Aggregates **10+ verified official sources**, fact-checks social-media claims via Claude API, tracks sentiment, answers natural-language queries with citations. SSE for live updates.

<sub>FastAPI · Next.js · Claude API · PostgreSQL · SSE</sub>

</td>
<td valign="top" width="50%">

#### Hyves — WhatsApp Market Pipeline

<sub><b>Production scraping infrastructure · live</b></sub>

Real-time WhatsApp message capture for a luxury watch trading marketplace. **Circuit-breaker** resilience, deduplication, contact metadata enrichment, batch writes. WAHA NOWEB engine for stability, LID resolution for participant identity, rate limiting and back-pressure.

<sub>Python · FastAPI · WAHA · SQLite · Google Sheets API · Next.js</sub>

</td>
</tr>
<tr>
<td valign="top" width="50%">

#### Fundora — AI/ML Modeling

<sub><b>Quant modelling experiments</b></sub>

Python ML research repository for fundamentals-driven modelling and signal generation. Feature engineering, model training pipelines, and backtesting infrastructure.

<sub>Python · pandas · scikit-learn · PyTorch</sub>

</td>
<td valign="top" width="50%">

#### Sarathi — Government Voice Agent

<sub><b>Live · regional-agent.sarathi.studio</b></sub>

Multilingual government voice assistant for **Assamese, Bodo, and Hindi**. Local STT (IndicConformer, ~0.5s) + RAG retrieval + Gemini LLM + local TTS (VITS ONNX). Cross-lingual RAG: regional-language queries match English source documents without translation. Runs on a $24/month server.

<sub>Python · FastAPI · ONNX Runtime · Pinecone · ChromaDB · Next.js</sub>

</td>
</tr>
</table>

---

### `> tech_stack`

**Languages**

<p>
  <img src="https://img.shields.io/badge/Python-0d1117?style=flat-square&logo=python&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/TypeScript-0d1117?style=flat-square&logo=typescript&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/SQL-0d1117?style=flat-square&logo=postgresql&logoColor=e6edf3&labelColor=0d1117" />
</p>

**LLM / AI Systems**

<p>
  <img src="https://img.shields.io/badge/OpenAI-0d1117?style=flat-square&logo=openai&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Anthropic-0d1117?style=flat-square&logo=anthropic&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Gemini-0d1117?style=flat-square&logo=googlegemini&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/LangChain-0d1117?style=flat-square&logo=langchain&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/LangGraph-0d1117?style=flat-square&logo=langchain&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/RAG-0d1117?style=flat-square&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Agent_Orchestration-0d1117?style=flat-square&logoColor=e6edf3&labelColor=0d1117" />
</p>

**Backend &amp; API**

<p>
  <img src="https://img.shields.io/badge/FastAPI-0d1117?style=flat-square&logo=fastapi&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Node.js-0d1117?style=flat-square&logo=nodedotjs&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/PostgreSQL-0d1117?style=flat-square&logo=postgresql&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Redis-0d1117?style=flat-square&logo=redis&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/WebSockets-0d1117?style=flat-square&logo=socketdotio&logoColor=e6edf3&labelColor=0d1117" />
</p>

**Vector &amp; Multimodal**

<p>
  <img src="https://img.shields.io/badge/pgvector-0d1117?style=flat-square&logo=postgresql&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Pinecone-0d1117?style=flat-square&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Qdrant-0d1117?style=flat-square&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Chroma-0d1117?style=flat-square&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Whisper-0d1117?style=flat-square&logo=openai&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/ElevenLabs-0d1117?style=flat-square&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/MediaPipe-0d1117?style=flat-square&logo=google&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/DeepSeek_OCR-0d1117?style=flat-square&logoColor=e6edf3&labelColor=0d1117" />
</p>

**Infra &amp; Deployment**

<p>
  <img src="https://img.shields.io/badge/Docker-0d1117?style=flat-square&logo=docker&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Kubernetes-0d1117?style=flat-square&logo=kubernetes&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/AWS-0d1117?style=flat-square&logo=amazonwebservices&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/Azure-0d1117?style=flat-square&logo=microsoftazure&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/GCP-0d1117?style=flat-square&logo=googlecloud&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/DigitalOcean-0d1117?style=flat-square&logo=digitalocean&logoColor=e6edf3&labelColor=0d1117" />
  <img src="https://img.shields.io/badge/GitHub_Actions-0d1117?style=flat-square&logo=githubactions&logoColor=e6edf3&labelColor=0d1117" />
</p>

---

### `> github_stats`

<div align="center">
  <img height="180" src="https://github-readme-stats.vercel.app/api?username=geekyroshan&show_icons=true&count_private=true&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=e6edf3" alt="GitHub Stats" />
  <img height="180" src="https://github-readme-stats.vercel.app/api/top-langs/?username=geekyroshan&layout=compact&langs_count=8&theme=github_dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=e6edf3" alt="Top Languages" />
</div>

<br/>

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=geekyroshan&theme=github-compact&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=e6edf3&area=true&area_color=58a6ff" alt="Activity Graph" />
</div>

<br/>

<!-- Contribution snake — generated by .github/workflows/snake.yml on the `output` branch -->
<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/geekyroshan/geekyroshan/output/github-snake-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/geekyroshan/geekyroshan/output/github-snake.svg" />
    <img alt="GitHub contribution snake" src="https://raw.githubusercontent.com/geekyroshan/geekyroshan/output/github-snake.svg" />
  </picture>
</div>

---

### `> writing`

> Long-form posts on agent orchestration, voice latency, and multimodal AI — coming soon at [geekyroshan.tech](https://geekyroshan.tech).

---

<div align="center">
  <sub>Built end-to-end · Live in production · Open for remote roles</sub>
</div>
