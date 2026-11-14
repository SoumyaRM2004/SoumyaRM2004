<div align="center">

# Soumyaranjan Mohapatra

### AI Engineer • Backend Developer • Data & Analytics Engineer

**Building practical AI systems, intelligent data applications, and reliable backend services.**

<br>

<a href="https://github.com/SoumyaRM2004">
  <img src="https://img.shields.io/badge/GitHub-SoumyaRM2004-181717?style=for-the-badge&logo=github" alt="GitHub">
</a>
<a href="https://www.linkedin.com/in/srmohapatra">
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn">
</a>
<a href="mailto:soumyasrm04@gmail.com">
  <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
</a>

<br><br>

<img src="https://komarev.com/ghpvc/?username=SoumyaRM2004&style=for-the-badge&color=0e7490&label=PROFILE+VIEWS" alt="Profile views">

</div>

---

# About Me

I'm a **Computer Science & Engineering graduate** focused on building practical software around **AI, backend systems, data engineering, and analytics**.

My recent work has moved beyond traditional ML notebooks toward complete systems involving:

- **Agentic AI and multi-agent workflows**
- **RAG and vector search**
- **LangGraph orchestration**
- **FastAPI backend services**
- **PostgreSQL / MySQL data systems**
- **ETL and analytics pipelines**
- **Production-oriented testing and validation**

I enjoy taking a business or operational problem and turning it into a system with a clear architecture, reliable data flow, APIs, and measurable behavior.

### Current Focus

```text
Agentic AI
     ↓
LangGraph + RAG + LLM Workflows
     ↓
FastAPI + PostgreSQL
     ↓
Data Engineering + Analytics
     ↓
Production-oriented AI Systems
```

---

# Featured Projects

## 01 — OpsGuard Copilot

### Enterprise Incident Response Self-RAG Copilot

<a href="https://github.com/SoumyaRM2004/OpsGuard_Copilot">
<img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github" alt="View OpsGuard">
</a>

**What it solves**

OpsGuard is an agentic incident-response system designed to help engineers investigate production incidents while reducing unsupported or hallucinated troubleshooting guidance.

### Core capabilities

- Self-reflective RAG workflow
- Dynamic retrieval routing
- Document relevance grading
- Query rewriting when retrieval fails
- Evidence-grounded answer verification
- Persistent incident memory
- External web-search fallback
- LangGraph workflow orchestration
- FastAPI backend

### Architecture

```text
                    Incident / Question
                           │
                           ▼
                  ┌─────────────────┐
                  │  Query Router   │
                  └────────┬────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │ Retrieval Layer │
                  └────────┬────────┘
                           │
                           ▼
                  ┌─────────────────┐
                  │ Relevance Grade │
                  └────────┬────────┘
                           │
                  ┌────────┴────────┐
                  │                 │
             Relevant          Insufficient
                  │                 │
                  ▼                 ▼
             LLM Answer       Query Rewrite
                  │                 │
                  └────────┬────────┘
                           ▼
                  ┌─────────────────┐
                  │ Answer Verify   │
                  └────────┬────────┘
                           ▼
                     Final Response
```

**Stack**

`Python` `LangGraph` `RAG` `FastAPI` `Pinecone` `Groq` `Tavily`

---

# 02 — IncidentPilot

### Multi-Agent Production Incident Investigation System

<a href="https://github.com/SoumyaRM2004/IncidentPilot-Multi-Agent-Production-Incident-Response-System">
<img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github" alt="View IncidentPilot">
</a>

IncidentPilot coordinates specialized agents to investigate production incidents using logs, metrics, deployment information, and operational runbooks.

### Investigation Flow

```text
                   Incident Alert
                         │
                         ▼
                 ┌───────────────┐
                 │   Supervisor  │
                 └───────┬───────┘
                         │
          ┌──────────────┼──────────────┐
          ▼              ▼              ▼
       Logs Agent    Metrics Agent   Deploy Agent
          │              │              │
          └──────────────┼──────────────┘
                         ▼
                  Runbook RAG Agent
                         │
                         ▼
                 Root Cause Analysis
                         │
                         ▼
                Evidence Verification
                         │
                         ▼
                  Remediation Plan
                         │
                         ▼
              Human Approval Required
```

### Engineering Highlights

- Dynamic multi-agent orchestration
- Evidence-grounded RCA
- Deterministic evidence verification
- Semantic LLM verification
- Runbook retrieval using vector search
- Human-in-the-loop remediation
- FastAPI REST backend
- Streamlit investigation dashboard
- Automated test suite

**Stack**

`Python` `LangGraph` `FastAPI` `Qdrant` `PostgreSQL` `SQLAlchemy` `Streamlit` `Pytest`

---

# 03 — RideOps AI Analytics Agent

### Multi-Agent Analytics & ETL Platform

<a href="https://github.com/SoumyaRM2004/RideOps_AI_Analytics_Agent">
<img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github" alt="View RideOps">
</a>

RideOps combines natural-language analytics, SQL generation, ETL, external weather data, and PostgreSQL into an AI-powered analytics platform.

### What it can do

**SQL Analytics Agent**

```text
Natural Language Question
          ↓
       Router
          ↓
     SQL Analyst
          ↓
   SQL Generation
          ↓
   Query Validation
          ↓
    Security Review
          ↓
   PostgreSQL Query
          ↓
     Visualization
```

**ETL Agent**

```text
Open-Meteo API
      ↓
   Extraction
      ↓
    Pandas
      ↓
Transformation
      ↓
Duplicate Prevention
      ↓
  PostgreSQL
      ↓
Analytics
```

### Features

- Natural-language-to-SQL analytics
- SQL validation
- LLM security review
- Interactive charts
- Database explorer
- Weather ETL pipeline
- External data enrichment
- Multi-agent LangGraph workflow

**Stack**

`Python` `LangGraph` `FastAPI` `PostgreSQL` `Pandas` `Chart.js`

---

# 04 — AI Patient Front Desk

### Multi-Tenant Clinic Backend

<a href="https://github.com/SoumyaRM2004/ai-patient-front-desk">
<img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github" alt="View AI Patient Front Desk">
</a>

A backend foundation for a multi-tenant clinic platform covering authentication, doctors, services, patients, working hours, and appointment management.

### Engineering Highlights

- JWT authentication
- Multi-tenant data isolation
- PostgreSQL database
- Doctor and service management
- Patient management
- Appointment lifecycle management
- Availability calculation
- Timezone-aware scheduling
- Conflict detection
- Concurrency-safe booking
- Alembic migrations
- Automated testing

### Booking Logic

```text
Appointment Request
        │
        ▼
Doctor Working Hours
        │
        ▼
Service Duration
        │
        ▼
Candidate Slot Generation
        │
        ▼
Existing Booking Check
        │
        ▼
Database Lock
        │
        ▼
Safe Appointment Creation
```

**Stack**

`Python` `FastAPI` `PostgreSQL` `SQLAlchemy` `Pydantic` `Alembic` `Pytest`

---

# 05 — Manufacturing MES Production System

### Production & Downtime Management Platform

<a href="https://github.com/SoumyaRM2004/Manufacturing_Production_-_Downtime_Management">
<img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github" alt="View Manufacturing Project">
</a>

A Manufacturing Execution System-inspired application for managing machines, production orders, and downtime events.

### Features

- Machine management
- Production order management
- Downtime tracking
- Automatic downtime duration calculation
- SQL-based downtime analytics
- REST APIs
- Pydantic validation
- MySQL relational database
- Interactive dashboard
- Swagger/OpenAPI documentation

**Architecture**

```text
Bootstrap Dashboard
        │
        ▼
     REST API
        │
        ▼
     FastAPI
        │
 ┌──────┴──────┐
 │             │
Models      Schemas
 │             │
 └──────┬──────┘
        ▼
     MySQL
```

**Stack**

`Python` `FastAPI` `MySQL` `SQLAlchemy` `Bootstrap`

---

# 06 — Payment Settlement Reconciliation

### E-Commerce Payment Audit & Reconciliation

<a href="https://github.com/SoumyaRM2004/E-Commerce-Payment-Settlement-Reconciliation-System">
<img src="https://img.shields.io/badge/View%20Repository-181717?style=for-the-badge&logo=github" alt="View Payment Reconciliation">
</a>

An analytical reconciliation system for identifying discrepancies between e-commerce order records and payment gateway settlement records.

### What it analyzes

- Missing settlements
- Duplicate transactions
- Gateway fee variance
- Refund variance
- Orphan bank credits
- Settlement discrepancies
- Cross-month settlement differences
- Potential financial leakage

### Reconciliation Pipeline

```text
OMS Transactions
       │
       ├───────────────┐
       │               │
       ▼               ▼
Gateway Records    Bank Settlement
       │               │
       └───────┬───────┘
               ▼
        Transaction Match
               │
               ▼
       Expected Settlement
               │
               ▼
        Variance Analysis
               │
               ▼
       Exception Classification
               │
               ▼
        Business Insights
```

**Stack**

`Python` `SQL` `Pandas` `Data Analysis` `Financial Reconciliation`

---

# Technical Skills

<div align="center">

### Programming

<img src="https://skillicons.dev/icons?i=python,java" alt="Python Java">

### Backend & Databases

<img src="https://skillicons.dev/icons?i=fastapi,postgres,mysql,sqlite" alt="FastAPI PostgreSQL MySQL SQLite">

### AI & Data

<img src="https://skillicons.dev/icons?i=tensorflow,pytorch" alt="TensorFlow PyTorch">

<br>

<img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain">
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangGraph">
<img src="https://img.shields.io/badge/RAG-0F766E?style=for-the-badge" alt="RAG">
<img src="https://img.shields.io/badge/Vector%20Search-155E75?style=for-the-badge" alt="Vector Search">

### Data & Analytics

<img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
<img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
<img src="https://img.shields.io/badge/Scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="Scikit-learn">
<img src="https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black" alt="Power BI">
<img src="https://img.shields.io/badge/Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white" alt="Excel">

### Engineering

<img src="https://skillicons.dev/icons?i=git,github,docker" alt="Git GitHub Docker">
<img src="https://img.shields.io/badge/Pytest-0A9EDC?style=for-the-badge&logo=pytest&logoColor=white" alt="Pytest">

</div>

---

# Other Projects

### Machine Learning & Data

| Project | Description |
|---|---|
| [Customer CLV Prediction](https://github.com/SoumyaRM2004/Customer-CLV-Prediction) | RFM segmentation and Customer Lifetime Value prediction using ensemble ML models and SHAP |
| [Bitcoin Risk Analytics](https://github.com/SoumyaRM2004/Bitcoin-Sentiment-Analysis) | Market risk analytics combining price, sentiment, public interest, and volatility signals |
| [Plant Species Identification](https://github.com/SoumyaRM2004/Plant-Species-Identification) | Computer vision system for plant identification using image processing and ML/DL |
| [SearchEngine](https://github.com/SoumyaRM2004/SearchEngine) | Streamlit search application combining web search with AI-generated summaries |
| [Heart Failure Prediction](https://github.com/SoumyaRM2004/Heart-Failure-Minor-Project-I) | Predictive modeling project for heart failure risk |

---

# Experience & Background

### Education

**B.Tech — Computer Science & Engineering**  
GIET University, Gunupur  
**2022 – 2026**

### Areas of Experience

- Data Analytics
- Data Science
- Machine Learning
- Backend Development
- API Development
- AI/LLM Applications
- Business Intelligence

---

# Certifications & Learning

- **Data Science Internship** — Unified Mentor
- **The Joy of Computing Using Python** — NPTEL
- **Data Analytics** — Cognitive.ai
- **Excel** — Jobaaj Learning
- **Business Intelligence & Analytics** — NPTEL
- **Data Analytics Essentials** — Cisco

---

# GitHub Activity

<div align="center">

<img
  src="https://streak-stats.demolab.com?user=SoumyaRM2004&hide_border=true&theme=transparent"
  alt="SoumyaRM2004 GitHub contribution streak"
/>

</div>

<br>

<div align="center">

<a href="https://github.com/SoumyaRM2004?tab=repositories">
<img src="https://img.shields.io/badge/View%20All%20Repositories-181717?style=for-the-badge&logo=github" alt="View all repositories">
</a>

</div>

---

# Currently Exploring

```text
┌────────────────────────────────────────────────────┐
│                                                    │
│  Agentic AI                                       │
│       ↓                                            │
│  LangGraph + Multi-Agent Systems                  │
│       ↓                                            │
│  RAG + Vector Databases                            │
│       ↓                                            │
│  FastAPI + PostgreSQL                              │
│       ↓                                            │
│  Data Engineering + ETL                            │
│       ↓                                            │
│  Production-Ready AI Applications                  │
│                                                    │
└────────────────────────────────────────────────────┘
```

### Current Interests

`Agentic AI` · `RAG` · `LLM Applications` · `LangGraph` · `FastAPI` · `PostgreSQL` · `Data Engineering` · `AI Systems`

---

# Let's Connect

<div align="center">

If you're working on **AI systems, data platforms, backend engineering, or intelligent automation**, feel free to connect.

<br>

<a href="https://github.com/SoumyaRM2004">
<img src="https://img.shields.io/badge/GitHub-SoumyaRM2004-181717?style=for-the-badge&logo=github" alt="GitHub">
</a>

<a href="https://www.linkedin.com/in/srmohapatra">
<img src="https://img.shields.io/badge/LinkedIn-srmohapatra-0A66C2?style=for-the-badge&logo=linkedin" alt="LinkedIn">
</a>

<a href="mailto:soumyasrm04@gmail.com">
<img src="https://img.shields.io/badge/Email-soumyasrm04%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
</a>

<br><br>

### Code. Build. Analyze. Automate.

</div>
