<h1 align="center">Hi, I'm Fahmid Arman</h1>

<p align="center">
  <strong>Computer Science graduate, BRAC University</strong><br>
  Backend Engineering • Applied AI • Full-Stack Development • Open Source
</p>

<p align="center">
  <a href="mailto:fahmid.brac@gmail.com">
    <img src="https://img.shields.io/badge/-Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://www.linkedin.com/in/fahmid-arman/">
    <img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://github.com/Fahmid-Arman">
    <img src="https://img.shields.io/badge/-GitHub-181717?style=flat&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="https://leetcode.com/u/Fahmid_Arman/">
    <img src="https://img.shields.io/badge/-LeetCode-FFA116?style=flat&logo=leetcode&logoColor=black" alt="LeetCode">
  </a>
</p>

---

## About Me

I graduated with a BSc in Computer Science from **BRAC University, Bangladesh**, in **September 2026**.

My primary interests are **backend engineering, full-stack development, applied AI, developer tools, and data-driven systems**. I learn by building practical software and working across the development lifecycle, including API design, database modeling, testing, documentation, containerization, and continuous integration.

My recent work includes a grounded RAG system for codebase understanding, a full-stack clinic operations platform, a MERN student marketplace, a database-backed alumni networking platform, and an undergraduate machine learning thesis on apartment price prediction in Dhaka.

I contribute to open-source AI projects and have **33 merged pull requests** across Pipecat, AnythingLLM, Docling, txtai, Pydantic Logfire, mem0 and Agno.

---

## Current Focus

- Building backend and applied AI systems
- Working with RAG, LLMs, vector search, BM25, and reranking
- Developing APIs with FastAPI, Django REST Framework, and Node.js
- Building full-stack applications with React and TypeScript
- Improving software quality through testing, Docker, CI/CD, and clean engineering practices
- Fixing bugs in open-source AI frameworks such as Pipecat, AnythingLLM and Docling
- Strengthening data structures, algorithms, and problem-solving skills

---

## Technical Skills

**Languages:** Python, SQL, JavaScript, TypeScript, C, C++  
**Backend & Frontend:** FastAPI, Django REST Framework, Node.js, Express.js, React, Tailwind CSS, Vite  
**Databases & AI:** PostgreSQL, MongoDB, MySQL, Milvus Lite, RAG, LLMs, BM25, Vector Search, Reranking, SHAP  
**Tools:** Git, Docker, GitHub Actions, CI/CD, pytest, REST APIs, Linux  

---

## Open Source Contributions

**33 merged pull requests** in open-source AI projects as of November 2026. Most are bug fixes with regression tests, written to each project's contribution guidelines.

| Project | What it is | Merged PRs |
|---|---|---|
| [Pipecat](https://github.com/pipecat-ai/pipecat) | Framework for real-time voice and multimodal AI agents | [13](https://github.com/pipecat-ai/pipecat/pulls?q=is%3Apr+author%3AFahmid-Arman+is%3Amerged) |
| [AnythingLLM](https://github.com/Mintplex-Labs/anything-llm) | AI application with RAG, agents and chat integrations | [13](https://github.com/Mintplex-Labs/anything-llm/pulls?q=is%3Apr+author%3AFahmid-Arman+is%3Amerged) |
| [Docling](https://github.com/docling-project/docling) | Document conversion for AI workflows | [2](https://github.com/docling-project/docling/pulls?q=is%3Apr+author%3AFahmid-Arman+is%3Amerged) |
| [txtai](https://github.com/neuml/txtai) | Embeddings database and AI framework | [2](https://github.com/neuml/txtai/pulls?q=is%3Apr+author%3AFahmid-Arman+is%3Amerged) |
| [Pydantic Logfire](https://github.com/pydantic/logfire) | Observability SDK for Python | [1](https://github.com/pydantic/logfire/pulls?q=is%3Apr+author%3AFahmid-Arman+is%3Amerged) |
| [mem0](https://github.com/mem0ai/mem0) | Memory layer for AI agents | [1](https://github.com/mem0ai/mem0/pulls?q=is%3Apr+author%3AFahmid-Arman+is%3Amerged) |
| [Agno](https://github.com/agno-agi/agno) | Framework for building AI agents | [1](https://github.com/agno-agi/agno/pulls?q=is%3Apr+author%3AFahmid-Arman+is%3Amerged) |

### Selected fixes

- **Pipecat:** the JSON bus serializer sent string enums such as DTMF keys as plain strings, so DTMF frames broke between Redis and PGMQ workers ([#6560](https://github.com/pipecat-ai/pipecat/pull/6560)). An event handler that removed itself made the next handler for the same event skip ([#6543](https://github.com/pipecat-ai/pipecat/pull/6543)). Azure Voice Live usage metrics now include cached and audio token counts ([#6559](https://github.com/pipecat-ai/pipecat/pull/6559)).
- **AnythingLLM:** agent flow JSON bodies did not end a string at a quote that follows an escaped backslash ([#7018](https://github.com/Mintplex-Labs/anything-llm/pull/7018)). Prompt-based tool calls rejected `null` and JSON string arguments ([#7006](https://github.com/Mintplex-Labs/anything-llm/pull/7006)). Tool schemas with local `$ref` pointers to other properties were not resolved ([#7009](https://github.com/Mintplex-Labs/anything-llm/pull/7009)).
- **Docling:** the JATS backend dropped the text of inline `<term>` elements ([#5177](https://github.com/docling-project/docling/pull/5177)), and the AsciiDoc backend kept the ` +` hard line break marker as literal text ([#5175](https://github.com/docling-project/docling/pull/5175)).
- **txtai:** graph `SIMILAR()` clauses matched the wrong nodes when content storage was disabled, which is the default ([#1516](https://github.com/neuml/txtai/pull/1516)).

---

### mem0 TypeScript SDK

Added Google Cloud Vertex AI embedding provider support to the mem0 TypeScript SDK through a merged upstream pull request.

The contribution covered provider implementation, configuration support, unit tests, and documentation.

**Tech:** TypeScript, Google Cloud Vertex AI, Embeddings, SDK Development  
**Pull Request:** [mem0ai/mem0#5882](https://github.com/mem0ai/mem0/pull/5882)

---

### Agno AI Agent Framework

Contributed a merged pull request that improved `CustomApiTools` authorization-header handling to prevent unintended API key forwarding when no base URL is configured.

The fix was backed by unit tests covering the affected authorization behavior.

**Tech:** Python, pytest, API Security  
**Pull Request:** [agno-agi/agno#8582](https://github.com/agno-agi/agno/pull/8582)

---

## Featured Projects

### CodeCompass — Grounded RAG System for Codebase Understanding

A local-first RAG system that indexes GitHub code, documentation, and issue/PR history to answer codebase questions with grounded citations to files, line ranges, and issues.

**Tech:** Python, FastAPI, Milvus Lite, Ollama, React, TypeScript, BM25, Reranking  
**Highlights:**

- Dense vector search and BM25 retrieval
- Reciprocal Rank Fusion
- Cross-encoder reranking
- Grounded answers with source citations
- 146 unit tests
- Strict mypy and ruff checks
- Docker and GitHub Actions CI

**Repository:** [CodeCompass](https://github.com/Fahmid-Arman/CodeCompass)

---

### CareFlow AI — Full-Stack Clinic Operations Platform

A full-stack clinic operations platform with role-based workflows for Admin, Front Desk, Triage Nurse, Doctor, and Diagnostics users.

**Tech:** Django REST Framework, PostgreSQL, React, TypeScript, Docker, Tailwind CSS  
**Highlights:**

- Role-based operational workflows
- Priority queueing
- Wait-time estimation
- Diagnostic flow planning
- Staff overrides
- Audit logging
- Automated tests
- Docker Compose setup
- Synthetic demonstration data

**Repository:** [CareFlow AI](https://github.com/Fahmid-Arman/careflow-ai)

---

### Campus Cart — BRACU Student Marketplace

A MERN marketplace developed by a four-member team for university students. I led the team and implemented the buyer-seller communication functionality.

**Tech:** MongoDB, Express.js, React, Node.js, Redux Toolkit, JWT, Multer  
**Highlights:**

- JWT authentication through HTTP-only cookies
- bcrypt password hashing
- Role-based student and admin access
- Buyer-seller messaging
- Unread-message tracking
- Reporting and moderation workflows
- Seller-scoped product CRUD
- Search, filtering, and pagination
- Multer image uploads

**Repository:** [Campus Cart](https://github.com/Fahmid-Arman/Campus-Cart-BRAC-University-Student-Marketplace)

---

### BRACU Alumni Connect — Alumni Networking Platform

A secure alumni networking platform built on a normalized MySQL schema with role-specific functionality.

**Tech:** PHP, MySQL, HTML, CSS  
**Highlights:**

- Role-specific search
- Messaging
- Event and mentorship workflows
- Prepared statements
- Password hashing
- CSRF protection

**Repository:** [BRACU Alumni Connect](https://github.com/Fahmid-Arman/BRACU-Alumni-Connect)

---

## Thesis

### Machine Learning-Based Apartment Price Prediction in Dhaka

Undergraduate thesis at BRAC University focused on predicting apartment prices in Dhaka using structural and location-based features.

Built a stacking ensemble on **9,167 cleaned apartment listings**, achieving:

- **R² = 0.867**
- **14.59% MAPE** on a held-out test set
- SHAP-based model interpretability
- Split-conformal prediction intervals

**Tech:** Python, scikit-learn, XGBoost, LightGBM, SHAP

---

## Problem Solving

- Solved **700+ problems** across LeetCode and Codeforces
- Focused on data structures, algorithms, and competitive programming

---

## Contact

<p align="center">
  <a href="mailto:fahmid.brac@gmail.com">
    <img src="https://img.shields.io/badge/-Email-D14836?style=flat&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://www.linkedin.com/in/fahmid-arman/">
    <img src="https://img.shields.io/badge/-LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="https://leetcode.com/u/Fahmid_Arman/">
    <img src="https://img.shields.io/badge/-LeetCode-FFA116?style=flat&logo=leetcode&logoColor=black" alt="LeetCode">
  </a>
</p>
