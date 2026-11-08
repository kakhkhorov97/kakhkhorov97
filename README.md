Sean Kakhkhorov | Full-Stack Developer (AI & DevOps)

Sean Kakhkhorov
Full-stack developer building web applications, document-review tools and source-grounded AI assistants. My work covers interfaces, APIs, authentication, data models and deployment, with about 3 years of professional web development.

Based in Suwon, South Korea, and open to opportunities in Korea. I work in English, Korean and Uzbek: I completed my full bachelor’s degree in Korean and can handle technical interviews in Korean.

Work authorization: Bachelor’s degree from a Korean university; eligible to change to an E-7 visa upon hiring.

Portfolio & resumes · Email

Selected projects
All five are live: four solo projects and one collaborative project.

Project	Purpose and current status	Inspect
CreatorHub	Live creator discovery, multilingual portfolios, private inquiries and messaging. Solo project.	Demo · Backend · Frontend
Sofiya Bookstore	Live bookstore demo. Next.js/NestJS, PostgreSQL and a Gemini RAG book concierge. Demo stock/orders and test payments; legacy version preserved separately.	Demo · Monorepo · Legacy frontend
Korea Visa Assistant	Live public beta for selected official Korean visa sources. English/Korean answers, quotations, citations and keyword source search.	Demo · Code
CargoCheck AI	Live early shipping-document review app: Gemini extraction, human field review, deterministic comparison and PDF reports.	Demo · Code
Lexara	Live collaborative document Q&A platform with cited answers. I contributed to the FastAPI backend.	Demo · Fork
CreatorHub demonstrates transaction-backed retry protection, notification-worker recovery and manual paired Docker/Nginx releases with health-checked image rollback (293 automated checks, Oct 2026). Sofiya combines a Next.js/NestJS bookstore with PostgreSQL, hybrid catalogue search and Gemini book recommendations (hit@5 100%, MRR 0.95 on 45 questions). Korea Visa Assistant combines Korean keyword and vector retrieval and restores its Cloud Run index without startup embedding calls (hybrid hit@5 0.969, MRR 0.935 on 32 synthetic, source-labelled questions). CargoCheck combines Gemini document extraction, human field review and deterministic comparison.

CargoCheck remains an early build: bulk confirmation does not save pending field edits, and uploaded originals use ephemeral storage. Retrieval scores do not measure legal-answer accuracy. Sofiya’s live site uses demo stock and orders with test payments; the earlier React/Express version is preserved separately. The project repositories contain detailed architecture, setup and evaluation records.

More about Lexara
Collaborative project · Contributor

I worked on the FastAPI backend of this document Q&A platform: API endpoints, upload processing, database models and Alembic migrations. We pushed our shared work through my collaborator's account; this repository is a fork of MakhmudSD/Lexara.

The platform uses Python/FastAPI, React/Vite, PostgreSQL, SQLAlchemy/Alembic, OpenAI, and pgvector with BM25/RRF retrieval. It organizes documents into workspaces and returns answers with source references.

Demonstrated skills
Web applications: TypeScript, React/Next.js, NestJS/Express, FastAPI, GraphQL/REST, authentication and real-time messaging.
Documents and retrieval: Gemini/OpenAI integrations, structured extraction, OCR, Korean tokenization, BM25, vector retrieval, retrieval evaluation and source inspection.
Data and operations: MongoDB, PostgreSQL, Redis/BullMQ, transactions, Docker, Linux/Nginx, GitHub Actions, Cloud Run, Vercel and Render.
Professional background
IT Local · Full-Stack Web Developer · Tashkent · September 2023 to April 2026 (full-time, contract ended). B2B web agency with about 20 staff; I was part of a core team of 4 developers serving 20+ client companies.
Built an apartment-sales client's admin dashboard (Next.js, React/MUI, GraphQL, MongoDB) with 4 developers, owning role-based access control (Super Admin / Manager / Sales Staff), the inventory GraphQL API and update mutations, and the admin table UI.
Replaced manual SSH deploys (15–20 min) with GitHub Actions CI/CD (4–5 min); the team adopted it as a template on 5+ sites.
Grew from 5 to 15 Ubuntu servers (Nginx reverse proxy, SSL renewal, DNS, PM2, Docker, UFW/SSH hardening, automated backups).
Cut catalogue search from about 3–5 s to under 1 s with compound indexes and cursor-based pagination.
Traced an out-of-memory outage to uploads buffered in memory and added upload limits and PM2 auto-restart; fixed 3–4 major outages and wrote API/deploy docs and a handover.
Golden Valley Investment (formerly Atlantis Investment) · Junior Backend Developer · April to September 2023 (remote, project-based contract). Maintained a Tashkent real-estate company's existing Express.js/MongoDB backend: bug fixes, small features, JWT/session auth, file uploads and MongoDB indexes for search and pagination.
Chonnam National University · B.A. in International Trade (국제무역학과) · September 2019 to August 2023. Taught entirely in Korean.
Portfolio & resumes · Email · KakaoTalk
