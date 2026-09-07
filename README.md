<div align="center">

<img src="./assets/profile-header.svg" width="100%" alt="Ammar Bin Yasir — AI Automation Engineer" />

<br>

<a href="#about"><img src="https://img.shields.io/badge/ABOUT-0b0b0b?style=for-the-badge&logo=readme&logoColor=FF1738" alt="About" /></a>
<a href="#featured-work"><img src="https://img.shields.io/badge/PROJECTS-0b0b0b?style=for-the-badge&logo=github&logoColor=FF1738" alt="Projects" /></a>
<a href="#automation-lab"><img src="https://img.shields.io/badge/AUTOMATIONS-0b0b0b?style=for-the-badge&logo=n8n&logoColor=FF1738" alt="Automations" /></a>
<a href="#toolkit"><img src="https://img.shields.io/badge/TOOLKIT-0b0b0b?style=for-the-badge&logo=stackshare&logoColor=FF1738" alt="Toolkit" /></a>

<br><br>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=19&duration=2800&pause=900&color=FF1738&center=true&vCenter=true&repeat=true&width=760&lines=Building+AI+agents+that+do+useful+work.;Automating+workflows+with+n8n+and+APIs.;Creating+grounded+knowledge+systems+with+RAG.;Connecting+intelligence+to+real+business+processes." alt="Animated introduction" />
</a>

</div>

---

<a id="about"></a>

## `01. ABOUT`

<table>
<tr>
<td width="58%" valign="middle">

### Hi, I'm Ammar 👋

I'm an **AI Automation Engineer** building AI agents, n8n workflows, RAG knowledge systems, and API-driven automations.

I focus on the part that turns an AI demo into a useful system: connecting models to data, tools, decisions, and real outputs.

```yaml
role: AI Automation Engineer
focus:
  - AI agents
  - n8n automation
  - RAG systems
  - API integration
currently_building: reliable, grounded AI workflows
```

</td>
<td width="42%" align="center" valign="middle">

<img src="./assets/ai-workflow-visual.svg" width="100%" alt="AI agent connected to documents, n8n, APIs and outputs" />

</td>
</tr>
</table>

> **My rule:** AI should not only generate text. It should understand context, use the right tools, produce validated output, and move work forward.

---

## `02. WHAT I BUILD`

<table>
<tr>
<td width="33%" valign="top">

### 🤖 AI Agents

Research assistants, task-focused agents, tool use, structured outputs, and evidence-grounded responses.

</td>
<td width="33%" valign="top">

### ⚡ Automation

n8n workflows, scheduled pipelines, webhooks, REST APIs, Discord, WordPress, and third-party integrations.

</td>
<td width="33%" valign="top">

### 📚 RAG

Document ingestion, embeddings, Qdrant vector search, scoped retrieval, and private knowledge assistants.

</td>
</tr>
</table>

```text
TRIGGER  →  ORCHESTRATE  →  REASON  →  RETRIEVE  →  VALIDATE  →  ACT
 event         n8n          LLM         RAG          rules       output
```

---

<a id="featured-work"></a>

## `03. FEATURED WORK`

<details open>
<summary><strong>📚 Grounded Knowledge Workspace</strong> — private, scoped RAG</summary>
<br>

Upload company documents, create assistants, and control exactly which sources each assistant may search. Retrieval is constrained by tenant and selected document IDs.

`n8n` `Qdrant` `Gemini` `Supabase` `RAG` `TypeScript`

[Repository →](https://github.com/AmmarBinYasir489/grounded-knowledge-workspace)

</details>

<details open>
<summary><strong>🔎 AI Research Assistant</strong> — evidence before answers</summary>
<br>

A research agent that discovers current sources, evaluates evidence, and produces cited, confidence-aware summaries.

`Python` `FastAPI` `Ollama` `Gemini` `Search APIs`

[Repository →](https://github.com/AmmarBinYasir489/ai-research-assistant)

</details>

<details>
<summary><strong>🧭 CodeRecall</strong> — grounded developer memory</summary>
<br>

Understands Git repositories, helps recover unfinished work, and answers codebase questions using file and line evidence.

`Python` `Git` `Grounded AI` `Developer Tools`

[Repository →](https://github.com/AmmarBinYasir489/coderecall)

</details>

<details>
<summary><strong>💳 Expense AI</strong> — natural language to validated records</summary>
<br>

Converts everyday financial messages into structured transactions and supports budgets, loans, analytics, and Q&A grounded in saved data.

`Gemini` `Next.js` `Supabase` `PostgreSQL` `Zod`

[Repository →](https://github.com/AmmarBinYasir489/expense-ai)

</details>

<details>
<summary><strong>🥗 Nourish</strong> — multimodal nutrition analysis</summary>
<br>

Analyzes meal photos, returns validated nutrition estimates, and turns confirmed meals into reusable templates.

`Gemini Vision` `Next.js` `Supabase` `PostgreSQL` `Zod`

[Repository →](https://github.com/AmmarBinYasir489/calories-counter)

</details>

<div align="right">

[View all repositories →](https://github.com/AmmarBinYasir489?tab=repositories)

</div>

---

<a id="automation-lab"></a>

## `04. AUTOMATION LAB`

<table>
<tr>
<td width="33%" valign="top">

### 📰 News → Discord

Researches recent AI news, filters and summarizes the findings, then delivers a structured Discord update.

`Schedule` `Research` `LLM` `Discord`

</td>
<td width="33%" valign="top">

### 🎬 YouTube → WordPress

Transforms a YouTube link into a structured WordPress article with a generated featured image.

`YouTube` `AI Content` `Image` `WordPress`

</td>
<td width="33%" valign="top">

### 📖 Docs → Qdrant

Extracts and chunks documents, creates embeddings, and stores scoped vectors for grounded retrieval.

`Documents` `Embeddings` `Qdrant` `RAG`

</td>
</tr>
</table>

<details>
<summary><strong>Open the automation pipeline</strong></summary>
<br>

```mermaid
flowchart LR
    A[Trigger] --> B[n8n]
    B --> C[Collect data]
    C --> D[AI processing]
    D --> E{Validate}
    E -->|Valid| F[Discord / WordPress / Qdrant]
    E -->|Retry| D

    style B fill:#ff1738,color:#fff,stroke:#ff1738
    style E fill:#111,color:#fff,stroke:#ff1738
```

</details>

---

<a id="toolkit"></a>

## `05. TOOLKIT`

<div align="center">

### Intelligence & Orchestration

![n8n](https://img.shields.io/badge/n8n-111111?style=for-the-badge&logo=n8n&logoColor=FF1738)
![Gemini](https://img.shields.io/badge/Gemini-111111?style=for-the-badge&logo=googlegemini&logoColor=FF1738)
![Ollama](https://img.shields.io/badge/Ollama-111111?style=for-the-badge&logo=ollama&logoColor=FF1738)
![Qdrant](https://img.shields.io/badge/Qdrant-111111?style=for-the-badge&logo=qdrant&logoColor=FF1738)

### Engineering

![Python](https://img.shields.io/badge/Python-111111?style=for-the-badge&logo=python&logoColor=FF1738)
![FastAPI](https://img.shields.io/badge/FastAPI-111111?style=for-the-badge&logo=fastapi&logoColor=FF1738)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-111111?style=for-the-badge&logo=postgresql&logoColor=FF1738)
![Supabase](https://img.shields.io/badge/Supabase-111111?style=for-the-badge&logo=supabase&logoColor=FF1738)
![TypeScript](https://img.shields.io/badge/TypeScript-111111?style=for-the-badge&logo=typescript&logoColor=FF1738)
![Next.js](https://img.shields.io/badge/Next.js-111111?style=for-the-badge&logo=nextdotjs&logoColor=FF1738)

</div>

---

## `06. ACTIVITY`

<div align="center">

<img width="98%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=AmmarBinYasir489&theme=radical" alt="Ammar's GitHub contribution summary" />

<img width="49%" src="https://github-readme-stats.vercel.app/api?username=AmmarBinYasir489&show_icons=true&hide_border=true&bg_color=0d1117&title_color=ff1738&icon_color=ff1738&text_color=d8d5d2" alt="Ammar's GitHub statistics" />
<img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=AmmarBinYasir489&layout=compact&hide_border=true&bg_color=0d1117&title_color=ff1738&text_color=d8d5d2" alt="Ammar's most used languages" />

<img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=AmmarBinYasir489&bg_color=0d1117&color=d8d5d2&line=ff1738&point=ffffff&area=true&hide_border=true" alt="Ammar's GitHub activity graph" />

</div>

---

## `07. NOW`

- Building task-focused agents that use tools and evidence
- Designing n8n workflows for research and content operations
- Developing private knowledge systems with controlled retrieval
- Improving validation, security, and maintainability in AI workflows

---

<div align="center">

### Have a repetitive process or disconnected set of tools?

**Let's turn it into an intelligent workflow.**

[![Explore my work](https://img.shields.io/badge/EXPLORE_MY_WORK-FF1738?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AmmarBinYasir489?tab=repositories)

<br><br>

<sub>Build the workflow · Ground the intelligence · Validate the result</sub>

</div>
