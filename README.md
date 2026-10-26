<div align="center">

# Hi, I'm Pratiksha Sanap 👋

**Full-Stack & Generative AI Engineer | Data Scientist**

Python • JavaScript • FastAPI • React • Data Science • GenAI

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/pratiksha-sanap)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/pratikshasanap)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:pratiksha.sanap@example.com)

</div>

## Overview

I build end-to-end software systems that combine machine learning models with production web architectures. My primary stack is Python and JavaScript. I design asynchronous backend APIs in FastAPI, interactive client interfaces in React, and practical Generative AI systems backed by vector search and data processing pipelines.

My focus is on production reliability: clean schemas, low-latency API responses, reproducible data pipelines, and streaming user interfaces that handle model outputs smoothly.

## Core Technical Stack

### Languages & Querying
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnubash&logoColor=white)

### Generative AI & Machine Learning
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![scikit-learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)

### Backend Engineering
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Pytest](https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white)

### Frontend Engineering
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## System Architecture Pattern

This architecture outlines how I connect frontend interfaces, asynchronous services, and AI/ML layers into a cohesive application:

```
+-------------------------------------------------------------------+
|                           React Client                            |
|     - Real-time token streaming via Server-Sent Events (SSE)      |
|     - Responsive UI components and dynamic state workflows        |
+---------------------------------+---------------------------------+
                                  | HTTP / SSE / WebSockets
+---------------------------------v---------------------------------+
|                       FastAPI Backend (Async)                     |
|     - Request validation with Pydantic v2                         |
|     - JWT authentication, rate limiting, and structured logging   |
|     - Celery / Redis workers for asynchronous background tasks    |
+----------------+----------------------------------+---------------+
                 |                                  |
+----------------v------------------+ +-------------v---------------+
|        Data & ML Engine           | |    GenAI & Retrieval Layer  |
|  - Data pipelines (Pandas, NumPy) | |  - Vector search (ChromaDB) |
|  - Statistical ML (scikit-learn)  | |  - RAG pipelines & chunking |
|  - Deep learning models (PyTorch) | |  - LLM agents & tool calling|
+-----------------------------------+ +-----------------------------+
```

## Engineering Capabilities

### Generative AI & Retrieval Systems
- **Retrieval-Augmented Generation (RAG):** I implement end-to-end RAG pipelines using document chunking strategies, dense embeddings, vector indexing, and similarity search to ground responses in private knowledge bases.
- **Agentic Workflows:** I construct agent systems using tool-calling patterns, enabling LLMs to run database queries, execute external APIs, and make multi-step decisions.
- **Evaluation & Guardrails:** I test LLM workflows for factual consistency, latency bottlenecks, and token consumption to ensure models perform predictably in production environments.

### FastAPI & Backend Architecture
- **Asynchronous I/O:** I build non-blocking REST and WebSocket endpoints in FastAPI using `async`/`await` patterns for high-concurrency workloads.
- **Data Validation & Contracts:** I enforce strict type validation through Pydantic v2 models, ensuring client data adheres to predictable contracts with auto-generated OpenAPI documentation.
- **Background Jobs & Caching:** I configure Redis for in-memory caching and session state, paired with Celery for long-running compute jobs such as batch embeddings and report generation.
- **Database Design:** I write relational schemas in PostgreSQL using async ORMs (SQLAlchemy, asyncpg) with database indexing and connection pooling.

### React & Frontend Development
- **Real-Time AI Streaming:** I build React interfaces that consume streaming token responses from LLMs via Server-Sent Events (SSE) and WebSockets.
- **State Management:** I structure application state using hooks, Context, and lightweight stores to keep components decoupled and responsive.
- **Clean UI & Responsive Layouts:** I build accessible, mobile-responsive interfaces using modern JavaScript and Tailwind CSS.

### Data Science & Machine Learning
- **Data Preparation & Analysis:** I clean, transform, and validate tabular datasets using Pandas and NumPy, preparing raw inputs for modeling.
- **Predictive Modeling:** I train and evaluate classification and regression models using scikit-learn, handling feature selection, cross-validation, and metric analysis.
- **Deep Learning Pipelines:** I develop neural network architectures in PyTorch for structured and unstructured data tasks.

## Featured Architecture Projects

### 1. Enterprise RAG Platform
An end-to-end question answering system over unstructured internal documentation.
- **Stack:** FastAPI, LangChain, React, ChromaDB, PostgreSQL, Docker
- **Implementation:** Custom chunking pipeline, dense embedding generation, hybrid search, and a React chat UI with source citation cards and token streaming.

### 2. High-Throughput ML Scoring Service
A containerized prediction API for real-time model inference.
- **Stack:** Python, FastAPI, scikit-learn, Redis, Docker, Pytest
- **Implementation:** Asynchronous prediction pipeline with request batching, model serialization via joblib, Redis caching for frequent queries, and 95%+ test coverage.

### 3. Agentic Workflow Engine
A tool-calling autonomous agent that processes user requests and queries multi-table databases.
- **Stack:** Python, OpenAI API, FastAPI, React, SQLite / PostgreSQL
- **Implementation:** Structured function calling, sandboxed query execution, validation loops, and dynamic results visualization on the frontend.

## GitHub Activity

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=pratikshasanap&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" alt="Pratiksha's GitHub Stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=pratikshasanap&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>

## Let's Connect

I am open to discussions about full-stack engineering, GenAI architectures, and data science collaborations.

- **LinkedIn:** [linkedin.com/in/pratiksha-sanap](https://linkedin.com/in/pratiksha-sanap)
- **Email:** [pratiksha.sanap@example.com](mailto:pratiksha.sanap@example.com)
- **GitHub:** [github.com/pratikshasanap](https://github.com/pratikshasanap)
