![Sean Kakhkhorov | Full-Stack Developer (AI & DevOps)](assets/profile-banner.svg)

# Sean Kakhkhorov

Full-stack developer building web applications, document-review tools and source-grounded AI assistants. My work covers interfaces, APIs, authentication, data models and deployment, with 2 years 10 months of professional web development.

Based in Suwon, South Korea, and open to opportunities in Korea. I work in English, Korean and Uzbek.

[Portfolio & resumes](https://sean-kakhkhorov.site) · [Email](mailto:kakhkhorov97@gmail.com) · [Telegram](https://t.me/kakhkhoro_v)

## Selected projects

All five are live: four solo projects and one collaborative project.

| Project | Purpose and current status | Inspect |
| --- | --- | --- |
| CreatorHub | Live creator discovery, multilingual portfolios, private inquiries and messaging. Solo project. | [Demo](https://creatorhub.site) · [Backend](https://github.com/kakhkhorov97/CreatorHub) · [Frontend](https://github.com/kakhkhorov97/CreatorHub-next) |
| Sofiya Bookstore | Live bookstore demo. Next.js/NestJS, PostgreSQL and a Gemini RAG book concierge. Demo stock/orders and test payments; legacy version preserved separately. | [Demo](https://sofiya.store) · [Monorepo](https://github.com/kakhkhorov97/Sofiya-Bookstore/tree/v2) · [Legacy frontend](https://github.com/kakhkhorov97/Sofiya-react) |
| Korea Visa Assistant | Live public beta for selected official Korean visa sources. English/Korean answers, quotations, citations and keyword source search. | [Demo](https://korea-visa-rag-jwq77bpivq-uc.a.run.app/) · [Code](https://github.com/kakhkhorov97/korea-visa-rag) |
| CargoCheck AI | Live early shipping-document review app: Gemini extraction, human field review, deterministic comparison and PDF reports. | [Demo](https://cargocheck-ai-web.vercel.app) · [Code](https://github.com/kakhkhorov97/cargocheck-ai) |
| Lexara | Live collaborative document Q&A platform with cited answers. I contributed to the FastAPI backend. | [Demo](https://lexara-top.vercel.app) · [Fork](https://github.com/kakhkhorov97/Lexara) |

CreatorHub demonstrates transaction-backed retry protection, notification-worker recovery and manual paired Docker/Nginx releases with health-checked image rollback (293 automated checks, Oct 2026). Sofiya combines a Next.js/NestJS bookstore with PostgreSQL, hybrid catalogue search and Gemini book recommendations (hit@5 100%, MRR 0.95 on 45 questions). Korea Visa Assistant combines Korean keyword and vector retrieval and restores its Cloud Run index without startup embedding calls (hybrid hit@5 0.969, MRR 0.935 on 32 synthetic, source-labelled questions). CargoCheck combines Gemini document extraction, human field review and deterministic comparison.

CargoCheck remains an early build: bulk confirmation does not save pending field edits, and uploaded originals use ephemeral storage. Retrieval scores do not measure legal-answer accuracy. Sofiya’s live site uses demo stock and orders with test payments; the earlier React/Express version is preserved separately. The project repositories contain detailed architecture, setup and evaluation records.

## More about Lexara

**Collaborative project · Contributor**

I worked on the FastAPI backend of this document Q&A platform: API endpoints, upload processing, database models and Alembic migrations. We pushed our shared work through my collaborator's account; this repository is a fork of [MakhmudSD/Lexara](https://github.com/MakhmudSD/Lexara).

The platform uses Python/FastAPI, React/Vite, PostgreSQL, SQLAlchemy/Alembic, OpenAI, and pgvector with BM25/RRF retrieval. It organizes documents into workspaces and returns answers with source references.

## Demonstrated skills

- Web applications: TypeScript, React/Next.js, NestJS/Express, FastAPI, GraphQL/REST, authentication and real-time messaging.
- Documents and retrieval: Gemini/OpenAI integrations, structured extraction, OCR, Korean tokenization, BM25, vector retrieval, retrieval evaluation and source inspection.
- Data and operations: MongoDB, PostgreSQL, Redis/BullMQ, transactions, Docker, Linux/Nginx, GitHub Actions, Cloud Run, Vercel and Render.

## Professional background

- IT Local · Full-stack Web Developer · November 2023 to February 2026. Built and maintained websites for 20+ client companies in a team of 4+ developers. Worked on frontend and backend features, database queries, CI deployments and 5-15 Ubuntu servers.
- Atlantis Investment · Backend Developer · April to September 2023. Built Express/MongoDB APIs, authentication, uploads and indexed search while studying.
- Chonnam National University · B.A. in International Trade. Studied mainly in Korean.

[Portfolio & resumes](https://sean-kakhkhorov.site) · [Email](mailto:kakhkhorov97@gmail.com) · [KakaoTalk](http://qr.kakao.com/talk/5QImFOjS32KtvaTC9ro2dgB9hDE-)
