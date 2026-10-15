<h1 align="center">Hi, I'm Alejandro 👋</h1>
<h3 align="center">AI Engineer · Software Engineer · Mathematician</h3>

<p align="center">
  <a href="https://www.linkedin.com/in/alejandro-quintero-mejia/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:alejandroquinteromejia@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://myportfolio-alejo-mejia.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-111111?style=flat&logo=vercel&logoColor=white" alt="Portfolio"></a>
  <a href="https://twitter.com/BatmathDev"><img src="https://img.shields.io/badge/@BatmathDev-000000?style=flat&logo=x&logoColor=white" alt="X"></a>
  <img src="https://img.shields.io/badge/📍_Medellín,_Colombia-555555?style=flat" alt="Location">
</p>

I build LLM-powered applications designed to work beyond the demo: multi-agent pipelines with validated structured outputs, RAG systems grounded in real documents, full-stack AI products, and end-to-end observability that shows how every answer was produced.

- 🤖 **AI Engineer** — LLMs, RAG, agents and LLMOps with Python, LangChain, OpenAI and Claude.
- 🧩 **Software Engineer** — complete products: architecture, integration, deployment and the end user. Former Full Stack instructor at Henry.
- 📐 **Mathematician** (Universidad de Antioquia) — I approach problems with rigor, from backpropagation to system design.

🔭 Open to **AI Engineer**, **LLM Engineer** and **Junior ML Engineer** roles.

---

## 🛠️ What I build

| Area | Focus |
|---|---|
| **Multi-Agent Systems** | Orchestration, intent routing, agent handoffs and LLM-as-a-judge evaluation with LangChain |
| **LLM Pipelines** | Multi-stage generation with prompt caching, durable retries and live streaming to the UI |
| **RAG** | Chunking, embeddings, vector search (Chroma, FAISS) and source-traceable answers |
| **Reliable LLM outputs** | Structured outputs, Pydantic / Zod validation, retry logic and prompt engineering |
| **LLMOps** | Tracing, token, latency and cost monitoring with Langfuse and Inngest; testing with pytest |

---

## ⭐ Featured AI projects

### ⚖️ [LegalMove — Autonomous Multi-Agent Contract Comparison](https://github.com/HX-AQuintero/autonomous-multi-agent-system)
Compares an original contract against its amendment, both provided as **scanned images**, and returns a validated JSON report of the changed sections, the legal topics affected and a summary of the changes. GPT-4o Vision transcribes each contract, a **Contextualization Agent** maps how sections correspond, and an **Extraction Agent** classifies every addition, deletion and modification. Double validation (structured outputs + Pydantic) with retries, and every run traced in Langfuse. Built for a scenario where a compliance team spent 40+ hours a week on this by hand.
<br>`GPT-4o Vision` `LangChain` `Pydantic` `Langfuse` `tenacity` `Python`

### 🎬 Screenplay → Higgsfield AI Prompt Pipeline · *freelance, private repo*
Full-stack Claude pipeline that turns a feature-length screenplay (PDF / TXT / Fountain) into scene-by-scene cinematic video prompts, each paired with reference images matched automatically from Google Drive. A **world bible** keeps characters and locations consistent across ~400 prompts; a tiered matcher (character → location → embeddings) attaches assets. Multi-user auth with **scene-level task assignment**, prompts streamed live to the browser, and Inngest monitoring to retry failures on the fly. ~$4 in API costs per feature film thanks to prompt caching.
<br>`Anthropic Claude` `Next.js` `TypeScript` `Inngest` `Supabase` `Prisma` `Google Drive API`

### 🧭 [Intelligent Routing Multi-Agent System](https://github.com/HX-AQuintero/multi-agent-system)
Classifies customer queries by department (HR, IT, Finance) with structured outputs and routes them to a domain-specific **RAG agent**, with a human fallback for low-confidence cases. An **Evaluator Agent** (LLM-as-a-judge) scores relevance, completeness and accuracy, all inside a single Langfuse trace per query.
<br>`LangChain` `Chroma` `Pydantic` `Langfuse` `OpenAI`

### 🔎 [Deep Research Clone](https://github.com/HX-AQuintero/chatGPT-deep-research-clone)
Streamlit research assistant that goes from a topic to a well-cited report: asks clarifying questions, plans targeted searches, iterates with OpenAI's Responses API `web_search` tool until the goal is met, and exports the report as Markdown, TXT or PDF.
<br>`OpenAI Responses API` `Streamlit` `ReportLab` `Python`

### 🏨 [Conversational Recommendation System with AWS Bedrock Agents](https://github.com/HX-AQuintero/Conversational-Recommendation-System)
Serverless recommender built on AWS Bedrock with Claude Sonnet. A **Supervisor Agent** interprets intent and delegates to specialized sub-agents (hotels vs. Airbnb, fine dining vs. casual), prompting for missing context and filtering S3 data in real time through Lambda.
<br>`AWS Bedrock` `Claude` `AWS Lambda` `S3` `Python`

### 📄 [LLM Question-Answering App](https://github.com/HX-AQuintero/Q-A-LLM-Project) · [live demo](https://hx-aquintero-q-a-llm-project-chat-with-documents-r1x6vx.streamlit.app/)
Upload PDF, DOCX or TXT files and ask questions about them. Content is chunked, embedded and indexed in FAISS; the most relevant chunks are passed to GPT for context-aware answers.
<br>`OpenAI` `LangChain` `FAISS` `Streamlit`

<details>
<summary><b>More AI & ML work</b></summary>
<br>

- **[NovaHR FAQ Chatbot (RAG)](https://github.com/HX-AQuintero/novahr-faq-rag)** — retrieval over PDF, DOCX and TXT with Chroma, auditable sources in a structured JSON and an optional evaluator agent.
- **[Multi-Modal Content Generation Suite](https://github.com/HX-AQuintero/Multi-Modal-Content-Generation)** — Python code generation, text summarization (Claude) and image creation (Stable Diffusion) on AWS Bedrock, with outputs stored in S3.
- **[Multitasking Text Utility](https://github.com/HX-AQuintero/multitasking-text-utility)** — support assistant with an enforced JSON schema and per-run token, latency and cost tracking.
- **[Dog Vision](https://huggingface.co/spaces/Alejo1296/dog_vision)** — dog-breed image classification with TensorFlow / Keras, deployed on Hugging Face Spaces.
- **[Backpropagation Explained](https://github.com/HX-AQuintero/backpropagation-explained)** — building a neural network from scratch to understand the math behind training.

</details>

<details>
<summary><b>Full-stack web projects</b></summary>
<br>

- **[Tech Store E-commerce](https://tech-store-prod.vercel.app/)** — online store with category filters, wishlist and cart, Google login, simulated Mercado Pago checkout and an admin panel with sales stats, discounts and newsletters. `React` `Redux` `Node.js` `Express` `Sequelize` `PostgreSQL` `Tailwind CSS`
- **[Dogs App](https://dogs-app-jade.vercel.app/)** — SPA to browse, filter, sort and create 150+ dog breeds on top of an external API and a PostgreSQL database. `React` `Redux` `Node.js` `Express` `Sequelize`

</details>

---

## 🧰 Tech stack

**AI & LLM**
<br>
<img src="https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white">
<img src="https://img.shields.io/badge/OpenAI-412991?style=flat&logo=openai&logoColor=white">
<img src="https://img.shields.io/badge/Anthropic_Claude-191919?style=flat&logo=anthropic&logoColor=white">
<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat&logo=langchain&logoColor=white">
<img src="https://img.shields.io/badge/Langfuse-0A0A0A?style=flat">
<img src="https://img.shields.io/badge/Chroma-FF6446?style=flat">
<img src="https://img.shields.io/badge/FAISS-0467DF?style=flat&logo=meta&logoColor=white">
<img src="https://img.shields.io/badge/Pydantic-E92063?style=flat&logo=pydantic&logoColor=white">
<img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white">

**Machine Learning**
<br>
<img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white">
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikitlearn&logoColor=white">
<img src="https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white">
<img src="https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white">
<img src="https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white">

**Full-stack**
<br>
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=nextdotjs&logoColor=white">
<img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB">
<img src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white">
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat&logo=nestjs&logoColor=white">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white">
<img src="https://img.shields.io/badge/Supabase-3FCF8E?style=flat&logo=supabase&logoColor=white">
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat&logo=prisma&logoColor=white">
<img src="https://img.shields.io/badge/Inngest-0B0B0B?style=flat">
<img src="https://img.shields.io/badge/Go-00ADD8?style=flat&logo=go&logoColor=white">

**Cloud & Dev**
<br>
<img src="https://img.shields.io/badge/AWS_Bedrock_·_Lambda_·_S3-232F3E?style=flat&logo=amazonwebservices&logoColor=white">
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/pytest-0A9EDC?style=flat&logo=pytest&logoColor=white">
<img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white">
<img src="https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white">

---

## 📐 A little more about me

```python
alejandro = {
    "roles": ["AI Engineer", "Software Engineer", "Mathematician"],
    "education": [
        "Mathematician — Universidad de Antioquia",
        "AI Engineering — Henry",
        "Full Stack Web Development — Henry",
    ],
    "experience": ["Full Stack Instructor @ Henry", "E-learning Analyst @ Henry", "Math & Physics Teacher"],
    "how_i_work": ["structured problem-solving", "clear technical docs", "product mindset", "self-driven learning"],
    "hobbies": ["art", "tech", "science", "languages"],
}
```
