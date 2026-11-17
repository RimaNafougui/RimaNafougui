<h1 align="center">Rima Nafougui</h1>

<p align="center">
  <strong>Computer Science Student — Full-Stack, AI Integration & Data Engineering</strong><br/>
  Building scalable full-stack applications, AI-powered pipelines, and automated data systems.<br/>
  B.Sc. Computer Science — Université de Montréal · Montréal, QC
</p>

<p align="center">
  <a href="https://rimanafougui.com">Portfolio</a> ·
  <a href="https://linkedin.com/in/rima-nafougui">LinkedIn</a> ·
  <a href="mailto:nafouguirima@gmail.com">Email</a>
</p>

<p align="center">
   <strong>Seeking Summer 2027 internships</strong> — software engineering, ML systems, fintech
</p>

---

### About

I'm a Computer Science student at Université de Montréal (B.Sc., expected 2028), focused on AI/ML and data engineering. Before university, I led technology at a non-profit and worked as a freelance developer. Today I build full-stack and AI-integrated projects, from serverless ML pipelines to semantic search systems.

---

### Currently

- B.Sc. Computer Science — Université de Montréal
- Looking for Summer 2027 internships in software engineering, ML systems, or fintech
- Languages: French (native), Arabic (native), English (professional), Korean (learning)

---

### Experience

**Director of Technology** — Careforall.org (non-profit) · *Mar 2026 – Aug 2026*<br/>
Owned infrastructure, SEO, security, and email deliverability for the organization.

**Freelance Developer** — Independent · *Mar 2026 – Aug 2026*<br/>
Full-stack and AI-integrated web/mobile development for independent clients, specializing in RAG pipelines, vector search, and API integrations.

**Programming Tutor** — Cégep Ahuntsic / Freelance · *May 2025 – May 2026*<br/>
Tutored 15+ students weekly in Java, Python, JavaScript, SQL, Swift, and Kotlin.

---

### Technical Skills

| Category | Technologies |
| :--- | :--- |
| **Languages** | JavaScript / TypeScript, Python, Java, Swift, Kotlin, C#, PHP, Rust, SQL |
| **Frontend** | React, Next.js, Vue.js, Tailwind CSS, Framer Motion, SwiftUI |
| **Backend** | Node.js, Express, Spring Boot, ASP.NET, RESTful APIs |
| **Data & AI** | Supabase (pgvector), Vector Embeddings, RAG, Google Gemini, OpenAI API |
| **Databases** | PostgreSQL, MySQL, MongoDB, MS SQL Server |
| **DevOps & Cloud** | AWS (Lambda, ECR, API Gateway), Docker, GitHub Actions, Vercel, Railway |
| **Tools** | Git, Postman, Power BI, Figma, Unity, VS Code, Xcode, IntelliJ |

---

### Featured Projects

#### [ArXiv RAG Research Assistant](https://github.com/RimaNafougui/ArxivSearchEngine) · [Live demo](https://huggingface.co/spaces/RimaNafougui/ArxivSearchEngine)
Full-stack AI application that answers questions about AI/ML and quantitative finance research, using a Retrieval-Augmented Generation (RAG) architecture over arXiv papers.
- Idempotent ETL pipeline on a daily GitHub Actions schedule — fetches cs.AI / cs.LG / cs.CL / cs.CV and q-fin papers, chunks them, and stores embeddings in Supabase pgvector
- Hybrid search combining pgvector cosine similarity with full-text search (RRF fusion)
- Agentic query routing with gpt-4o-mini — decides to search, ask for clarification, or decline out-of-scope queries before touching the vector store
- Two-pass multi-hop retrieval, streaming answers, and a similarity-based confidence label with a top-3 sources sidebar
- Stack: Python, Supabase (pgvector), OpenAI API, Streamlit, FastAPI, GitHub Actions

#### [RCapsule — Smart Closet Manager](https://github.com/RimaNafougui/rcapsule) · [Live demo](https://rcapsule.com)
Full-stack wardrobe management application with AI-powered outfit recommendations and a serverless ML pipeline for real-time background removal.
- Containerized AWS Lambda + ECR pipeline processing 176MB ONNX models
- Chrome Extension with DOM scraping reducing manual data entry by 90%
- OpenAI API + OpenWeatherMap for weather-aware personalized suggestions
- Stack: Next.js, TypeScript, Supabase, PostgreSQL, AWS Lambda, NextAuth.js, OpenAI API

#### [ExpenseFlow — Personal Finance REST API](https://github.com/RimaNafougui/expenseflow)
Production-grade RESTful API for income and expense tracking with role-based access control and automated testing.
- JWT authentication with role-based authorization, pagination, and advanced filtering
- 18+ unit and integration tests (JUnit 5, Mockito, MockMvc) with JaCoCo coverage reporting
- Deployed to Railway with automated CI/CD via GitHub Actions
- Stack: Spring Boot 3, Java 21, PostgreSQL, JWT, Maven, JaCoCo

#### [Supply Chain Disruption Analytics](https://github.com/RimaNafougui/SupplyChainBI)
End-to-end BI pipeline analyzing 10,000+ global shipments to identify disruption patterns and support data-driven logistics decisions.
- Star schema data model with 50+ DAX measures for prescriptive analytics
- Uncovered selection bias masking $99K in mitigation value
- 4-page interactive Power BI dashboard with drill-through on $17M+ in annual shipping costs
- Stack: Power BI, Python, DAX

---

<p align="center">
  <sub>Rima Nafougui · 2026</sub>
</p>
