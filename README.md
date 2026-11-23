<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A66C2,100:111827&height=190&section=header&text=Mohamed%20Khaled&fontSize=52&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=AI%20Engineer&descAlignY=60&descSize=22" alt="Mohamed Khaled banner" width="100%">

<a href="https://github.com/mohamedkhaled5543"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1200&color=0A66C2&center=true&vCenter=true&width=700&lines=AI+Engineer;Generative+AI+%C2%B7+LLMs+%C2%B7+AI+Agents;AI+Automation+%C2%B7+RAG+%C2%B7+n8n;Building+intelligent+systems+for+real+problems" alt="Typing intro"></a>

**Building intelligent systems that turn real-world problems into practical AI solutions.**

Cairo, Egypt · Final-year Computer Science Student — Helwan National University

<p>
  <a href="https://www.linkedin.com/in/mkhaled-ai"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:mohamedeissa651@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://mohamedkhaledportfolio1.netlify.app"><img src="https://img.shields.io/badge/Portfolio-Visit-111827?style=for-the-badge&logo=firefox&logoColor=white" alt="Portfolio"></a>
  <a href="https://github.com/mohamedkhaled5543"><img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>

<p>
  <a href="#featured-projects">Projects</a> ·
  <a href="#graduation-project--edupilot-ai">EduPilot AI</a> ·
  <a href="#technical-skills">Skills</a> ·
  <a href="#github-statistics">Stats</a> ·
  <a href="#connect-with-me">Contact</a>
</p>

</div>

---

## About Me

I'm a final-year Computer Science student at **Helwan National University, Egypt**, focused on becoming an AI Engineer.

My work sits at the intersection of **Machine Learning, Generative AI, LLM applications, and intelligent automation**. I enjoy taking an idea beyond a notebook: designing the workflow, connecting models and tools, building APIs, and creating applications that address practical problems.

I'm especially interested in systems that combine language models with retrieval, structured business logic, and automation — where engineering decisions matter as much as the model itself.

- **Career direction:** AI Engineering
- **Interested in:** Generative AI, LLMs, Agentic AI, NLP, Machine Learning, Deep Learning, and AI Automation
- **Approach:** Learn by building, evaluate honestly, and improve through iteration
- **Currently building:** EduPilot AI, a multi-agent learning and assessment platform

## Current Focus

- Building reliable LLM applications with retrieval-augmented generation (RAG).
- Designing AI agents that use tools while respecting explicit business rules.
- Developing practical automation workflows with n8n.
- Strengthening ML, NLP, and deep learning foundations.
- Turning AI prototypes into usable applications and backend services.

---

## Featured Projects

A selection of projects that best represent the kind of systems I build. The order reflects my current portfolio priorities.

<details>
<summary><b>01 · CampaignForge AI</b></summary>


**AI-powered marketing campaign generation**

My flagship Generative AI project. CampaignForge transforms a product brief into a coherent marketing campaign: it understands the product, retrieves relevant guidance from a marketing knowledge base, develops strategic directions, and generates platform-specific content for Instagram and TikTok, including an AI-generated advertising image.

**What it demonstrates**
- RAG over a marketing knowledge base.
- LLM-powered product understanding and campaign strategy.
- Multiple strategic directions with a consistent campaign state.
- Structured outputs and backend API integration.

`Python` `FastAPI` `LangChain` `RAG` `FAISS` `Sentence Transformers` `Mistral-Nemo` `Gemini` `Pydantic` `Docker`

[View repository →](https://github.com/mohamedkhaled5543/CampaignForge)

</details>

<details>
<summary><b>02 · Smart Hotel Operations Automation</b></summary>


**End-to-end hotel workflow automation**

An n8n-based operations system that connects reservation management, room availability, housekeeping, guest checkout, payment recording, receipts, and daily reporting. It uses deterministic business rules for operational decisions instead of relying on an LLM where predictable logic is more appropriate.

**What it demonstrates**
- Multi-step workflow orchestration.
- Date-overlap logic for room availability and multi-room reservations.
- Checkout, payment, and duplicate-payment safeguards.
- Operational notifications and reporting.

`n8n` `Google Sheets` `Google Forms` `Gmail` `Telegram` `Workflow Automation`

[View repository →](https://github.com/mohamedkhaled5543/smart-hotel-operations-automation)

</details>

<details>
<summary><b>03 · AI Customer Support Automation</b></summary>


**LLM-assisted customer request handling**

A connected set of n8n workflows that receives customer emails, validates and classifies requests with an LLM, routes them to the appropriate handler, logs operational requests, sends customer responses, and alerts the team when a workflow fails.

**What it demonstrates**
- LLM classification with structured output.
- Conditional routing and reusable sub-workflows.
- Automated email and team notifications.
- Dedicated error-handling workflow.

`n8n` `OpenRouter` `LLM Agents` `JavaScript` `Gmail` `Google Sheets` `Telegram`

[View repository →](https://github.com/mohamedkhaled5543/ai-customer-support-automation)

</details>

<details>
<summary><b>04 · AI Order Cancellation Agent</b></summary>


**An agent with explicit business-rule safeguards**

A Telegram-based AI agent that handles order cancellation requests. It checks order and payment status through a dedicated eligibility workflow, asks the customer for explicit confirmation, and rechecks eligibility before changing the order record.

**What it demonstrates**
- Tool-using AI agent workflow.
- Persistent conversation memory.
- Separation of LLM interaction from deterministic business rules.
- Revalidation before executing a consequential action.

`n8n` `OpenRouter` `PostgreSQL` `Google Sheets` `Telegram`

[View repository →](https://github.com/mohamedkhaled5543/ai-order-cancellation-agent)

</details>

<details>
<summary><b>05 · Bilingual PDF RAG Q&A</b></summary>


**Ask questions about a document in Arabic or English**

A retrieval-augmented question-answering application built around a financial filing. It retrieves relevant document passages and responds in the language of the question, with answers grounded in the source document.

`Python` `RAG` `FAISS` `Mistral-7B` `Multilingual Embeddings` `Streamlit`

[View repository →](https://github.com/mohamedkhaled5543/bilingual-rag-pdf-qa)

</details>

<details>
<summary><b>06 · Network Attack Detector</b></summary>


**Machine learning for network traffic classification**

A Streamlit application that scores network-flow records and flags potentially malicious traffic using models trained on the UNSW-NB15 dataset. The repository reports a **0.837 test F1 score** for XGBoost and **0.96 attack recall**.

`Python` `Pandas` `Scikit-learn` `XGBoost` `Streamlit`

[Repository](https://github.com/mohamedkhaled5543/network-attack-detector) · [Live demo](https://network-attack-detector-gpvygc2guzznwdhsjbuxyh.streamlit.app/)

</details>

<details>
<summary><b>07 · Machine Learning Projects</b></summary>


A collection of applied ML projects covering regression, classification, model comparison, preprocessing, and evaluation.

- [Student Math Score Regression](https://github.com/mohamedkhaled5543/student-score-regression) — compares regression models with preprocessing and hyperparameter tuning.
- [Energy Consumption Predictor](https://github.com/mohamedkhaled5543/energy-consumption-predictor)
- [Loan Default Predictor](https://github.com/mohamedkhaled5543/loan-default-predictor)
- [Car Price Predictor](https://github.com/mohamedkhaled5543/car-price-predictor)
- [Fake News Detection](https://github.com/mohamedkhaled5543/Fake-News-Detection)
- [Sentiment API](https://github.com/mohamedkhaled5543/sentiment-api)

</details>


---

## Graduation Project · EduPilot AI

**Multi-Agent Intelligent Learning & Training Platform**

EduPilot AI is a graduation project focused on personalized learning, intelligent assessment, and student performance analytics. Its planned capabilities include a RAG-based learning tutor with source citations, assessment generation and grading, performance insights, and instructor assistance.

**Planned stack:** `Next.js` `TypeScript` `FastAPI` `PostgreSQL` `pgvector` `LLMs` `RAG` `LangGraph` `Docker`

[View repository →](https://github.com/mohamedkhaled5543/EduPilot-AI)

*Project status: initial setup and requirements phase. Features and technologies are presented as project scope, not as completed production capabilities.*

---

## Technical Skills

Technologies and areas I have worked with through projects and practical learning.

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,js,postgres,fastapi,nextjs,ts,docker,git,github,sklearn,pandas,numpy&perline=12" alt="Skill icons">
</p>

| Area | Technologies & Concepts |
|---|---|
| **Programming** | Python, SQL, JavaScript |
| **Data Science** | NumPy, Pandas, data preprocessing, exploratory data analysis |
| **Machine Learning** | Scikit-learn, regression, classification, model evaluation, feature engineering |
| **Deep Learning** | Neural networks, CNNs, transfer learning |
| **NLP** | Text preprocessing, embeddings, sentiment analysis, Transformers |
| **Generative AI** | LLM applications, prompt design, structured outputs |
| **RAG & Retrieval** | LangChain, FAISS, vector search, semantic embeddings |
| **AI Agents & Automation** | Tool-using agents, n8n, workflow orchestration, business-rule validation |
| **Backend & Apps** | FastAPI, Streamlit, REST APIs |
| **Databases & Data Tools** | PostgreSQL, Google Sheets |
| **Developer Tools** | Git, GitHub, Google Colab, Docker |

---

## GitHub Statistics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=mohamedkhaled5543&show_icons=true&hide_border=true&theme=github_dark&rank_icon=github" alt="GitHub statistics">
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=mohamedkhaled5543&layout=compact&hide_border=true&theme=github_dark" alt="Most used languages">

</div>

<div align="center">

<img height="165" src="https://streak-stats.demolab.com?user=mohamedkhaled5543&theme=github-dark-blue&hide_border=true" alt="GitHub streak">

</div>

## Contribution Activity

<div align="center">

<img src="https://github-readme-activity-graph.vercel.app/graph?username=mohamedkhaled5543&theme=github-compact&hide_border=true" alt="GitHub contribution activity graph" width="100%">

</div>

---

## Connect With Me

I'm interested in connecting with engineers, AI practitioners, recruiters, and teams building useful technology.

- **Email:** [mohamedeissa651@gmail.com](mailto:mohamedeissa651@gmail.com)
- **LinkedIn:** [linkedin.com/in/mkhaled-ai](https://www.linkedin.com/in/mkhaled-ai)
- **Portfolio:** [mohamedkhaledportfolio1.netlify.app](https://mohamedkhaledportfolio1.netlify.app)
- **GitHub:** [github.com/mohamedkhaled5543](https://github.com/mohamedkhaled5543)

---

<div align="center">

### From learning the fundamentals to engineering intelligent systems.

**Build with purpose. Learn continuously. Engineer what matters.**

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:111827,100:0A66C2&height=110&section=footer" width="100%" alt="footer">
