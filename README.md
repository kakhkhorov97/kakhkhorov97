![Sean Kakhkhorov | Full-stack development, applied AI and DevOps](assets/profile-banner.svg)

# Sean Kakhkhorov

**Full-stack developer | Applied AI and DevOps**

I build web applications, document-review tools, and source-grounded AI assistants. I have 3+ years of professional web development experience, covering interfaces, APIs, data modelling, authentication, and Linux deployments.

Based in **Suwon, South Korea**, and open to opportunities in Korea. I work in English, Korean, and Uzbek.

[Portfolio](https://www.sean-kakhkhorov.site) · [Email](mailto:kakhkhorov97@gmail.com) · [CreatorHub live](https://creatorhub.site)

## Selected projects

### [CreatorHub](https://creatorhub.site)
**Solo project · Live**

A multilingual creator-discovery platform for Korea. I designed, built, and deployed the frontend, backend, and infrastructure.

- Next.js, TypeScript, Apollo Client, NestJS, GraphQL, Socket.IO, and MongoDB.
- Private project inquiries, live chat, creator workspaces, moderation, and social sign-in.
- Transaction-backed request keys and unique indexes prevent duplicate submissions; a notification worker uses leases and checkpoints for restart recovery.
- Gemini answers grounded in public site content, automated checks, and Docker/Nginx releases with health checks and image rollback.

[Backend](https://github.com/kakhkhorov97/CreatorHub) · [Frontend](https://github.com/kakhkhorov97/CreatorHub-next)

### [CargoCheck AI](https://github.com/kakhkhorov97/cargocheck-ai)
**Development project · Shipping-document review**

A workspace for comparing commercial invoices and packing lists, checking extracted values against originals, and recording reviewer decisions.

- React/TypeScript and NestJS, with Poppler/Tesseract extraction and optional Gemini structured extraction.
- Deterministic quantity, unit, and decimal-arithmetic checks, source references, field confirmation, review history, and PDF report export.
- PostgreSQL JSONB transaction persistence and BullMQ/Redis integration, tested during development alongside live Gemini extraction.

The current database adapter stores state in one transaction-locked JSONB row. Extracted values require human review; a completed review is not shipment approval.

### [Lexara](https://github.com/kakhkhorov97/Lexara)
**Collaborative project · Contributor**

I helped another developer build this document Q&A platform. We pushed our shared work through my collaborator's account; this repository is a fork of [MakhmudSD/Lexara](https://github.com/MakhmudSD/Lexara).

The platform uses Python/FastAPI, React/Vite, PostgreSQL, SQLAlchemy/Alembic, OpenAI, and pgvector with BM25/RRF retrieval. It organizes documents into workspaces and returns answers with source references.

[Public site](https://lexara-top.vercel.app)

### [Korea Visa Assistant](https://github.com/kakhkhorov97/korea-visa-rag)
**In development · English/Korean retrieval assistant**

- Article-aware Korean legal-text chunking, Kiwi tokenization, and visa-code preservation.
- BM25 and Chroma vector retrieval combined with Reciprocal Rank Fusion.
- A shared engine for FastAPI web and Telegram interfaces, with cited-answer and no-key search modes.
- Evaluation tools for hit@k, recall@k, and MRR. Data labelling, published evaluation results, and public deployment remain in progress.

### Sofiya Bookstore
**Earlier project**

React/Redux Toolkit storefront and Express/MongoDB API, with basket and order tracking, reader JWT authentication, and an EJS catalogue administration panel.

[Frontend](https://github.com/kakhkhorov97/Sofiya-react) · [Backend](https://github.com/kakhkhorov97/Sofiya-Bookstore)

## Skills and tools

| Area | Technologies and practices |
| --- | --- |
| Languages | TypeScript, JavaScript, Python, SQL, HTML, CSS/SCSS |
| Frontend | React, Next.js, Vite, Apollo Client, Redux Toolkit, TanStack Query, Material UI, Tailwind CSS, Bootstrap |
| APIs and authentication | Node.js, NestJS, Express, FastAPI, GraphQL, REST, Socket.IO, JWT, OAuth, sessions, role and ownership checks |
| Databases and jobs | MongoDB/Mongoose, PostgreSQL/JSONB, MySQL, Redis, BullMQ, transactions, indexes, optimistic concurrency |
| Applied AI and retrieval | Gemini API, OpenAI API, structured extraction, RAG, BM25, Chroma, RRF, Kiwi, Poppler, Tesseract |
| DevOps | Ubuntu/Linux, Docker, Docker Compose, Nginx, PM2, GitHub Actions, Cloudflare, DNS/TLS, health checks and rollback |
| Testing and quality | Jest, Supertest, pytest, integration tests, API contract checks, TypeScript checks, ESLint, Prettier, Postman, Git |
| AI-assisted development | Claude Code, Codex, Cursor, repository instructions, human review, automated checks |

Lexara's platform stack also includes SQLAlchemy, Alembic, and pgvector. Its project description separates shared platform capabilities from my individual contribution.

## Professional background

- **IT Local · Full-stack Web Developer · June 2023 to January 2026.** Built and maintained websites for 20+ client companies in a team of 4+ developers. Worked on frontend and backend features, database queries, CI deployments, and 5-15 Ubuntu servers.
- **Atlantis Investment · Backend Developer · May to December 2022.** Built Express/MongoDB APIs, authentication, uploads, and indexed search while studying.
- **Chonnam National University · B.A. in International Trade.** Studied mainly in Korean.

## Contact

[Portfolio](https://www.sean-kakhkhorov.site) · [Email](mailto:kakhkhorov97@gmail.com) · [Telegram](https://t.me/kakhkhoro_v) · [KakaoTalk](http://qr.kakao.com/talk/5QImFOjS32KtvaTC9ro2dgB9hDE-)

