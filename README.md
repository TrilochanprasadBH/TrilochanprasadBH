<div align="center">

# Trilochanprasad B Hilli

### Founding AI Engineer · Production GenAI Systems

**Bengaluru, India** · [Portfolio](https://trilochanprasad.com) · [LinkedIn](https://www.linkedin.com/in/trilochanprasad-b-hilli-7a1871106/) · [Email](mailto:tptrilochanprasad@gmail.com) · **+91 95353 32999**

</div>

---

## About

Founding AI Engineer building production GenAI systems end to end. Sole engineer behind **Prajna**, live on Google Play: built crash-resumable AI pipelines and a multi-provider LLM gateway, reducing AI cost per story by **77%**.

Previously shipped **2 SaaS products solo with paying users** and led engineering across **4 international client engagements** in the EU, UK, and US.

---

## Experience

### Founding AI Engineer · XXAVI AI Tech
_Jul 2026 — Present · Bengaluru_

Sole engineer across backend, React Native app (live on Google Play), and admin panel.

- Architected a crash-resumable AI generation engine using PostgreSQL, SQS, a transactional outbox, and idempotent step checkpoints. A failure on image 6 of 7 reruns one image ($0.016), not the entire story ($0.11)—making retries **86% cheaper** with no lost or double-billed jobs.
- Designed multi-stage GenAI pipelines spanning prompt enhancement, story writing, character-reference creation, scene generation, LLM-as-a-judge, and PDF output. Generates a 7-image illustrated story in about **74 seconds**, maintaining character consistency across pages.
- Built a multi-provider AI gateway (OpenRouter → Gemini → OpenAI) with **under 70ms** overhead, per-provider/task circuit breakers, fail-fast handling, admin model switching without deployment, and a daily spend kill switch.
- Reduced AI cost per story by **77%**, from $0.48 to $0.11, by measuring cost per call and benchmarking image models. An LLM judge checks each image for 11% of its cost.
- Audited billing flows and fixed four billing bugs, including a webhook deadlock reproduced in 29 of 30 runs. Made credit debits atomic and refunds once-only at the database level.
- Implemented child-safe data handling: redacted sensitive data leaking through ORM error logs, built a redactor 90× faster than Pino's built-in, routed children's photo uploads directly to storage via presigned URLs, and automated deletion within 24 hours.
- Built **9 pipelines** on the same engine, including LLM translation and narration in multiple languages across three voice providers.

### Full Stack Developer · TheBrandwick.com
_Jan 2024 — Jun 2026 · Bengaluru_

Owned sprint planning, client communication, technical delivery, and execution across four international client engagements.

- **Quoka:** Shipped booking and FAQ systems with Next.js and REST APIs; achieved 90+ Web Vitals scores.
- **VastuWisdom:** Led product architecture and delivery; drove engineering decisions and mentored 2 engineers.
- **AlexandersFA:** Delivered a UK mortgage and tax consultancy platform from design to deployment; achieved 95+ SEO scores and improved user retention by over 35%.
- **AllUnity:** Developed frontend systems for a European stablecoin initiative, contributing to a 45% increase in conversion rates.

---

## Selected SaaS projects

### [ScoreResume](https://scoreresume.com) · AI-powered resume intelligence

Transforms resumes into measurable career outcomes: ATS readiness, interview performance, and job-fit intelligence. Solo-built and grown without paid marketing.

- Built async AI processing with BullMQ + Redis, exponential-backoff retries, and dead-letter handling.
- Developed semantic resume/JD matching and multi-dimensional AI scoring using pgvector, LangChain, and Gemini.
- Designed multi-tenant PostgreSQL with per-user data isolation and free/paid feature gating.
- Integrated DodoPayments with webhook signature validation and idempotent payment processing.
- Deployed on Hetzner with CI/CD, Cloudflare CDN, Sentry, and PostHog.

**18,000+** organic pageviews · **300+** free users · **25+** paying users · **<150ms** p95 API latency · **90+** Lighthouse/Web Vitals · **99%+** uptime

### [AttemptIQ](https://attemptiq.com) · UPSC diagnostic analytics

Full-stack SaaS that transforms mock-test performance into actionable readiness insights. Solo-built and grown without paid marketing.

- Designed a 23-table PostgreSQL schema with 5 materialized views to track question-level performance, topic mastery velocity, and trap susceptibility across sessions.
- Built an async BullMQ insight pipeline for non-blocking, personalized report generation.
- Implemented contextual performance insights using pgvector and historical user data.
- Built psychological performance tracking for session fatigue, trap-question susceptibility, and topic confidence decay.
- Implemented multi-tenant architecture with JWT auth, rate-limited endpoints, and per-user data isolation.

**12,000+** organic pageviews · **4,500+** questions solved · **15+** paying users · **<150ms** p95 API latency · **90+** Lighthouse/Web Vitals · **99%+** uptime

---

## Skills

- **Frontend:** React.js, React Native, Expo, Next.js, TypeScript, ShadCN, Tailwind CSS
- **Backend:** Node.js, PostgreSQL, MongoDB, Prisma, Drizzle, Redis/Valkey, BullMQ, REST APIs, oRPC, Zod, system design, async queues
- **AI / GenAI:** GenAI, LLM orchestration, multi-provider failover, image-generation pipelines, LLM-as-a-judge, RAG, pgvector, vector databases, prompt engineering, async AI pipelines, LangGraph, CrewAI, AWS Bedrock
- **Infrastructure:** AWS (EC2, RDS, SQS, S3, CloudFront, SES), Hetzner VPS, Cloudflare, CI/CD, Docker
- **Auth & billing:** JWT, Better Auth, DodoPayments, RevenueCat, webhook handling
- **Monitoring:** Sentry, PostHog, UptimeRobot, NetData, Pino

---

## Education

- **Full Stack Developer** — Masai School, Bengaluru · 2023
- **BE, Mechanical Engineering** — Don Bosco Institute of Technology, Bengaluru · 2017

## Achievements

- **2nd Place** — Frontier AI Buildathon
- **1st Prize** — State-Level Speech Competition, VTU (BE final year)
- **1st Prize** — District-Level Debate Competition (Class 10)

---

<div align="center">

**Building production AI systems, reliable GenAI pipelines, and useful products end to end.**

[trilochanprasad.com](https://trilochanprasad.com) · [Get in touch](mailto:tptrilochanprasad@gmail.com)

</div>
