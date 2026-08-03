<div align="center">

# Hi, I'm Jonathan Torres 👋

### Civil Engineer building software for construction, engineering and operations

**AEC Software · Computational Engineering · Applied AI · Offline-First Systems**

[![GitHub](https://img.shields.io/badge/GitHub-Mamut1195-181717?style=flat-square\&logo=github)](https://github.com/Mamut1195)
![Ecuador](https://img.shields.io/badge/Based_in-Ecuador-FFDD00?style=flat-square)
![Focus](https://img.shields.io/badge/Focus-AEC_Technology-2563EB?style=flat-square)

</div>

---

## About me

I am a **civil engineer and software builder** working at the intersection of:

* construction and infrastructure
* software architecture
* computational engineering
* artificial intelligence
* business operations

Through **MAMUT Systems**, I design and build software for real engineering and operational problems, especially for small and medium-sized construction companies in Latin America.

My goal is not to build generic CRUD applications or thin AI wrappers.

I am interested in systems where:

* domain knowledge is encoded explicitly
* deterministic engines perform critical calculations
* AI agents orchestrate tools and workflows
* decisions remain traceable and auditable
* software continues working under real field conditions

> **Engineering logic at the core. AI as an interface, orchestrator and force multiplier.**

---

## What I am building

### 🏗️ MAMUT Systems

An ecosystem of software products and engineering tools for the AEC industry.

Areas under development include:

* construction cost estimation and APU workflows
* project planning and scheduling
* field progress and production control
* materials, labor and equipment management
* Earned Value Management and S-curves
* technical reports and engineering workflows
* BIM and IFC-based data extraction
* AI-assisted engineering analysis

The products are designed primarily for the operational reality of construction companies in **Ecuador and Latin America**.

---

### 🤖 Civil Copilot

An AI-assisted platform for civil engineering and construction workflows.

Its architecture combines:

* specialized engineering agents
* retrieval-augmented generation
* technical knowledge bases
* deterministic calculation tools
* report generation
* workflow orchestration
* audit trails and evidence
* multi-project and multi-tenant capabilities

The objective is not to let an LLM improvise engineering results, but to make AI interact with **validated tools, rules, standards and structured project data**.

---

### 📊 Construction Management Software

Offline-first tools for managing construction projects in environments where connectivity cannot be assumed.

Current areas of focus:

* daily field logs
* project progress
* quantities and production
* costs and budgets
* personnel and machinery
* photo evidence
* KPIs and dashboards
* synchronization and conflict handling
* mobile and desktop field workflows

---

### 🧮 Engineering Engines

I am exploring the development of deterministic engineering engines, primarily in **Rust and C++**, for areas such as:

* geotechnical analysis
* hydraulic and fluid simulations
* structural optimization
* transmission tower design
* numerical methods
* BIM and IFC processing
* engineering verification against technical standards

These engines are intended to remain independent from any specific UI, API or AI provider.

The long-term model is:

```text
User
  ↓
AI agent or engineering application
  ↓
Typed tool / MCP interface
  ↓
Deterministic engineering engine
  ↓
Traceable calculations, warnings and evidence
```

---

## Engineering principles

I prefer pragmatic architectures that can evolve without becoming unnecessarily complex.

```text
Modular monolith before microservices
Domain models before generic CRUD
Deterministic logic before LLM improvisation
Offline-first when the field requires it
Explicit workflows before invisible automation
Observability and auditability from the beginning
Simple infrastructure until scale proves otherwise
```

I care particularly about:

* clean and modular architecture
* domain-driven system design
* typed boundaries and contracts
* data consistency
* synchronization strategies
* background jobs and queues
* multi-tenant isolation
* testing and engineering validation
* maintainability over novelty
* measurable product outcomes

---

## Main technology stack

### Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square\&logo=python\&logoColor=white)
![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square\&logo=rust\&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square\&logo=typescript\&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square\&logo=cplusplus\&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square\&logo=postgresql\&logoColor=white)

### Backend and application architecture

![Django](https://img.shields.io/badge/Django-092E20?style=flat-square\&logo=django\&logoColor=white)
![Django Ninja](https://img.shields.io/badge/Django_Ninja-0C4B33?style=flat-square)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square\&logo=fastapi\&logoColor=white)
![Pydantic](https://img.shields.io/badge/Pydantic-E92063?style=flat-square\&logo=pydantic\&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-37814A?style=flat-square\&logo=celery\&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square\&logo=redis\&logoColor=white)

Primary backend direction:

```text
Django + Django Ninja
PostgreSQL + pgvector
Redis + Celery
Pydantic-based contracts
Modular monolith architecture
```

### Frontend and desktop

![Vue.js](https://img.shields.io/badge/Vue_3-4FC08D?style=flat-square\&logo=vuedotjs\&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square\&logo=vite\&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square\&logo=tailwindcss\&logoColor=white)
![Tauri](https://img.shields.io/badge/Tauri-24C8D8?style=flat-square\&logo=tauri\&logoColor=white)

Typical frontend stack:

```text
Vue 3 + TypeScript
Vite
TanStack Query
Pinia
Tailwind CSS
Tauri for desktop applications
xeokit for IFC/BIM visualization
```

### Data and offline-first systems

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square\&logo=postgresql\&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square\&logo=sqlite\&logoColor=white)
![ElectricSQL](https://img.shields.io/badge/ElectricSQL-Local--first-7C3AED?style=flat-square)
![PGlite](https://img.shields.io/badge/PGlite-Postgres_in_WASM-336791?style=flat-square)

Topics I actively explore:

* local-first and offline-first architecture
* optimistic updates
* synchronization protocols
* conflict resolution
* eventual consistency
* local PostgreSQL with PGlite
* browser and desktop persistence
* resilient field data collection

### Applied AI

![AI](https://img.shields.io/badge/AI-Applied,_not_decorative-8B5CF6?style=flat-square)
![MCP](https://img.shields.io/badge/MCP-Tool_Integration-111827?style=flat-square)
![RAG](https://img.shields.io/badge/RAG-Engineering_Knowledge-059669?style=flat-square)

My AI work focuses on:

* structured tool calling
* agent harnesses
* specialized subagents
* retrieval-augmented generation
* engineering knowledge systems
* model routing and evaluation
* memory and context management
* MCP integrations
* deterministic tool execution
* cost, latency and reliability measurement

I treat language models as replaceable infrastructure.
The domain model, business rules, engineering logic and evidence must remain inside the system.

---

## Infrastructure and delivery

![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square\&logo=docker\&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square\&logo=githubactions\&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square\&logo=linux\&logoColor=black)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square\&logo=nginx\&logoColor=white)

Current deployment approach:

```text
Dockerized applications
VPS infrastructure
Coolify
Nginx / Traefik
CI/CD with GitHub Actions
PostgreSQL, Redis and background workers
Monitoring, logging and backups
```

---

## Current areas of study

* software architecture and distributed systems
* Rust for reliable engineering software
* modern C++ for scientific computing
* computational mechanics and numerical methods
* CFD and hydraulic simulation
* BIM and IFC interoperability
* construction economics and project controls
* optimization algorithms
* AI agent architecture and evaluation
* software commercialization for the AEC industry

---

## The problems I want to solve

I am especially interested in projects involving:

* construction technology
* civil engineering software
* BIM and IFC workflows
* computational engineering
* offline-first field applications
* technical standards and rules engines
* engineering automation
* explainable AI-assisted decisions
* optimization of engineering designs
* operational software for Latin American companies

---

## Collaboration

I am open to collaborating with:

* civil and structural engineers
* construction professionals
* BIM and IFC developers
* scientific computing engineers
* Rust, Python and C++ developers
* AEC software companies
* researchers working on computational engineering
* founders building serious vertical software

Particularly when the project combines **engineering knowledge, software architecture and real operational impact**.

---

<div align="center">

### Building engineering software from Ecuador for Latin America and the world.

**Jonathan Torres · @Mamut1195**

</div>

