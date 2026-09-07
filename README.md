<div align="center">

<img src="./assets/profile-header.svg" width="100%" alt="Ammar Bin Yasir — AI Automation Engineer, AI Agents, n8n and RAG" />

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=600&size=21&duration=2800&pause=850&color=FF1738&center=true&vCenter=true&repeat=true&width=760&lines=I+build+AI+agents+that+do+useful+work.;I+automate+workflows+with+n8n+and+APIs.;I+create+grounded+knowledge+systems+with+RAG.;AI+is+useful+when+it+connects+to+real+workflows." alt="Typing animation describing Ammar's work" />
</a>

<p>
  <a href="#-what-i-build"><img src="https://img.shields.io/badge/What_I_Build-FF1738?style=for-the-badge&logo=probot&logoColor=white" alt="What I build" /></a>
  <a href="#-featured-systems"><img src="https://img.shields.io/badge/Featured_Systems-111111?style=for-the-badge&logo=github&logoColor=FF1738" alt="Featured systems" /></a>
  <a href="#-automation-lab"><img src="https://img.shields.io/badge/Automation_Lab-111111?style=for-the-badge&logo=n8n&logoColor=FF1738" alt="Automation lab" /></a>
  <a href="#-connect"><img src="https://img.shields.io/badge/Connect-111111?style=for-the-badge&logo=minutemailer&logoColor=FF1738" alt="Connect" /></a>
</p>

![Profile views](https://komarev.com/ghpvc/?username=AmmarBinYasir489&style=flat-square&color=FF1738&label=PROFILE+VIEWS)

</div>

## `> whoami`

I'm **Ammar Bin Yasir**, an **AI Automation Engineer** who builds AI agents, n8n workflows, RAG knowledge systems, and API-driven automations.

I use full-stack technologies when an AI system needs a secure interface, backend, database, or deployment—but the goal is always the same: connect AI to a real process and make the result dependable.

```text
Understand the process → Design the workflow → Connect the tools → Validate the output
```

```python
ammar = {
    "role": "AI Automation Engineer",
    "building": ["AI agents", "n8n workflows", "RAG systems"],
    "integrating": ["LLMs", "APIs", "vector databases", "business tools"],
    "principle": "Useful AI must be grounded, testable, and connected to real work."
}
```

## 🤖 What I Build

<table>
<tr>
<td width="33%" valign="top">

### AI Agents

- Research assistants
- Task-focused agents
- Tool and API integration
- Structured AI outputs
- Evidence-grounded responses

</td>
<td width="33%" valign="top">

### n8n Automation

- Multi-step AI workflows
- Scheduled research pipelines
- Discord and WordPress automation
- Webhooks and REST APIs
- Content-processing systems

</td>
<td width="33%" valign="top">

### RAG Systems

- Private knowledge bases
- Document ingestion
- Qdrant vector search
- Scoped retrieval
- Source-grounded answers

</td>
</tr>
</table>

## 🧭 How My Systems Work

```mermaid
flowchart LR
    A[Business task] --> B{Automation layer}
    B -->|Events & schedules| C[n8n]
    B -->|Custom logic| D[Python / FastAPI]
    C --> E[AI model]
    D --> E
    E --> F{Knowledge needed?}
    F -->|Yes| G[Qdrant / RAG]
    F -->|No| H[Validated output]
    G --> H
    H --> I[Discord / WordPress / Web App / API]

    style A fill:#111,color:#fff,stroke:#FF1738
    style E fill:#FF1738,color:#fff,stroke:#FF1738
    style I fill:#111,color:#fff,stroke:#FF1738
```

## ✨ Featured Systems

<details open>
<summary><strong>📚 Grounded Knowledge Workspace — private RAG with controlled sources</strong></summary>
<br>

A document-backed AI workspace where users upload company knowledge, create assistants, and control exactly which documents each assistant may search.

**What makes it useful:** tenant-aware retrieval, assistant-specific document selection, duplicate detection, grounded answers, and coordinated document deletion.

**Stack:** `n8n` `Qdrant` `Gemini` `Supabase` `Next.js` `TypeScript`

[Explore the repository →](https://github.com/AmmarBinYasir489/grounded-knowledge-workspace)

</details>

<details open>
<summary><strong>🔎 AI Research Assistant — evidence before answers</strong></summary>
<br>

A research agent that searches current sources, evaluates evidence, and produces confidence-aware summaries with citations.

**What makes it useful:** research and response generation are separated, sources are ranked, and answers show supporting evidence instead of hiding it.

**Stack:** `Python` `FastAPI` `Ollama` `Gemini` `Search APIs`

[Explore the repository →](https://github.com/AmmarBinYasir489/ai-research-assistant)

</details>

<details>
<summary><strong>🧭 CodeRecall — grounded memory for software projects</strong></summary>
<br>

An evidence-backed developer memory system that understands Git repositories, helps recover unfinished work, and answers codebase questions with file and line references.

**Stack:** `Python` `Git` `Grounded AI` `Developer Tools`

[Explore the repository →](https://github.com/AmmarBinYasir489/coderecall)

</details>

<details>
<summary><strong>💳 Expense AI — natural language to structured financial data</strong></summary>
<br>

An AI-powered expense system that converts everyday messages into validated transactions and supports budgets, loans, analytics, and financial Q&A grounded in saved records.

**Stack:** `Gemini` `Next.js` `TypeScript` `Supabase` `PostgreSQL` `Zod`

[Explore the repository →](https://github.com/AmmarBinYasir489/expense-ai)

</details>

<details>
<summary><strong>🥗 Nourish — multimodal meal analysis</strong></summary>
<br>

An AI-assisted nutrition system that analyzes meal photos, returns validated nutrition estimates, and turns confirmed meals into reusable personal templates.

**Stack:** `Gemini Vision` `Next.js` `Supabase` `PostgreSQL` `Zod`

[Explore the repository →](https://github.com/AmmarBinYasir489/calories-counter)

</details>

## ⚡ Automation Lab

These workflows focus on reducing repetitive research and content operations.

<details>
<summary><strong>📰 AI News Research → Discord</strong></summary>
<br>

An n8n workflow that collects recent AI news, processes and summarizes the findings, then delivers a structured update to Discord.

`Scheduled trigger` → `Research` → `Filter` → `AI summary` → `Discord`

</details>

<details>
<summary><strong>🎬 YouTube → WordPress Article + Featured Image</strong></summary>
<br>

An n8n content workflow that accepts a YouTube link, processes the video's content, generates a structured article and featured image, and sends the result to WordPress.

`YouTube URL` → `Content extraction` → `Article generation` → `Featured image` → `WordPress`

</details>

<details>
<summary><strong>📖 Documents → Qdrant Knowledge Base</strong></summary>
<br>

An n8n-powered RAG pipeline for ingesting documents, creating embeddings, storing searchable chunks in Qdrant, and retrieving scoped context for grounded answers.

`Document` → `Extract` → `Chunk` → `Embed` → `Qdrant` → `Grounded answer`

</details>

> Workflow exports and screenshots should be published only after credentials, webhook URLs, account IDs, and private data have been removed.

## 🧰 Core Toolkit

<div align="center">

### AI, Agents & Automation

![n8n](https://img.shields.io/badge/n8n-090909?style=for-the-badge&logo=n8n&logoColor=FF1738)
![Gemini](https://img.shields.io/badge/Google_Gemini-090909?style=for-the-badge&logo=googlegemini&logoColor=FF1738)
![Ollama](https://img.shields.io/badge/Ollama-090909?style=for-the-badge&logo=ollama&logoColor=FF1738)
![Qdrant](https://img.shields.io/badge/Qdrant-090909?style=for-the-badge&logo=qdrant&logoColor=FF1738)
![Python](https://img.shields.io/badge/Python-090909?style=for-the-badge&logo=python&logoColor=FF1738)
![FastAPI](https://img.shields.io/badge/FastAPI-090909?style=for-the-badge&logo=fastapi&logoColor=FF1738)

### APIs, Data & Delivery

![REST API](https://img.shields.io/badge/REST_APIs-090909?style=for-the-badge&logo=fastapi&logoColor=FF1738)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-090909?style=for-the-badge&logo=postgresql&logoColor=FF1738)
![Supabase](https://img.shields.io/badge/Supabase-090909?style=for-the-badge&logo=supabase&logoColor=FF1738)
![Next.js](https://img.shields.io/badge/Next.js-090909?style=for-the-badge&logo=nextdotjs&logoColor=FF1738)
![TypeScript](https://img.shields.io/badge/TypeScript-090909?style=for-the-badge&logo=typescript&logoColor=FF1738)
![Vercel](https://img.shields.io/badge/Vercel-090909?style=for-the-badge&logo=vercel&logoColor=FF1738)

</div>

## 🎯 Current Focus

- Building task-focused AI agents and research assistants
- Designing reliable n8n and API-driven automations
- Creating private RAG systems with controlled retrieval
- Connecting multimodal AI to useful applications
- Improving validation, security, and maintainability in AI workflows

## 🤝 Connect

I'm interested in **AI agents, workflow automation, RAG systems, and practical AI integrations**.

If you are working on a process that involves repetitive research, documents, content, or disconnected tools, I would be happy to explore how AI and automation could improve it.

<div align="center">

[![GitHub](https://img.shields.io/badge/GitHub-AmmarBinYasir489-111111?style=for-the-badge&logo=github&logoColor=FF1738)](https://github.com/AmmarBinYasir489)
[![Repositories](https://img.shields.io/badge/Explore_Repositories-FF1738?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AmmarBinYasir489?tab=repositories)

<br>

<sub>Build the workflow. Ground the intelligence. Validate the result.</sub>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:050505,50:FF1738,100:050505&height=110&section=footer" width="100%" alt="Footer" />

</div>
