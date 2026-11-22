# Hi 👋, I'm Emelian Chkaira

**Software Engineer · Flutter & Mobile · AI & Data** — MSc student in Business Analytics at the University of Bologna.
📍 Bologna, Italy · relocating to the **Netherlands** · 🗣️ Arabic (native), English (B2)

<p align="left">
  <a href="https://emelianchkaira.netlify.app" target="_blank"><img src="https://img.shields.io/badge/Portfolio-0E7490?style=for-the-badge&logo=netlify&logoColor=white" alt="Portfolio" /></a>
  <a href="https://linkedin.com/in/emelianchkaira" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-1E3A8A?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:emelianchkaira@gmail.com"><img src="https://img.shields.io/badge/Gmail-B91C1C?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail" /></a>
  <a href="https://drive.google.com/file/d/1PYwTuFZD-7OBwdc1wkQh5hgu_jyv-oMB/view?usp=sharing" target="_blank"><img src="https://img.shields.io/badge/CV-C2410C?style=for-the-badge&logo=readme&logoColor=white" alt="CV" /></a>
  <a href="https://drive.google.com/file/d/1Qi1OPAytFLLgxsQg-d86gRbhkiNNwGVV/view?usp=sharing" target="_blank"><img src="https://img.shields.io/badge/Oxford English Test-1D4ED8?style=for-the-badge&logo=googledrive&logoColor=white" alt="Oxford English Test" /></a>
</p>

Nearly five years of shipping production apps (10K+ users) in **Flutter**, plus **Python / FastAPI / PostgreSQL** and **React / TypeScript** for full-stack and AI work. Open to software engineering roles and internships in the Netherlands.

---

## ⭐ Featured project

### 🧭 [AI Career Tracker](https://github.com/emelian-chkaira/nl-career-tracker) — open-source job-search platform
Finds jobs from employer career pages and job boards, ranks them against your profile and CV, tailors the CV per job, and moves your pipeline from your inbox.

- **Hybrid search:** PostgreSQL 16 full-text (`tsvector`) fused with **pgvector HNSW** embeddings (384-d, fastembed ONNX) using Reciprocal Rank Fusion.
- **Crawler:** 11 ATS adapters, pooled **Playwright** browsers and **JobSpy** boards (LinkedIn, Indeed, Glassdoor, Google Jobs); robots.txt, rate limits and a crawl memory that skips dead links.
- **AI layer:** provider-agnostic LLM gateway (11 providers incl. Claude, OpenAI, Ollama) for fit scoring, read-only Gmail classification and CV tailoring, guarded by a **fact guard** that rejects invented numbers, employers and skills.
- **CV Studio:** import PDF / Word / LaTeX, live Tectonic PDF preview, Reactive Resume integration, and reviewable suggestions for missing keywords.
- **Stack:** FastAPI · SQLAlchemy 2 · Alembic · React 18 · TypeScript · 180+ backend tests.

[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/emelian-chkaira/nl-career-tracker) [![Mobile app](https://img.shields.io/badge/Mobile_app-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://github.com/emelian-chkaira/nl-career-tracker-mobile)

---

## 🛠️ Languages and tools

<p align="left">
  <strong>Backend, Data & AI</strong><br>
  <kbd><img src="https://skillicons.dev/icons?i=py,fastapi,postgres,mongodb,mysql,tensorflow,pytorch,matlab&perline=8" /></kbd>
</p>
<p align="left">
  <strong>Mobile & Frontend</strong><br>
  <kbd><img src="https://skillicons.dev/icons?i=flutter,dart,react,ts,js,kotlin,androidstudio&perline=7" /></kbd>
</p>
<p align="left">
  <strong>DevOps & Design</strong><br>
  <kbd><img src="https://skillicons.dev/icons?i=docker,kubernetes,azure,git,firebase,jenkins,figma,postman&perline=8" /></kbd>
</p>

<p align="left">
  <img src="https://img.shields.io/badge/Clean%20Architecture-111827?style=for-the-badge" />
  <img src="https://img.shields.io/badge/BLoC-0175C2?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/CI%2FCD-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white" />
  <img src="https://img.shields.io/badge/Agile-0A66C2?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LLM%20%2F%20RAG-059669?style=for-the-badge" />
  <img src="https://img.shields.io/badge/NLP-DB2777?style=for-the-badge" />
</p>

---

## 📱 Shipped products (Flutter)

| App | What it does | Where | Links |
|---|---|---|---|
| **Mumayaz** | Car plates & VIP numbers marketplace with a Preview-on-Car feature (Stripe, Apple Pay, Sentry) | UAE · KSA · Jordan | [App Store](https://apps.apple.com/us/app/mumayaz/id6789906640) · [Google Play](https://play.google.com/store/apps/details?id=com.metagate.mumayaz) |
| **S-Hub** 🏆 `10K+` | Plates & phone numbers marketplace with category and type search (Stripe, Apple Pay, Shorebird) | UAE | [App Store](https://apps.apple.com/us/app/s-hub-marketplace/id6455378185) · [Google Play](https://play.google.com/store/apps/details?id=com.metagate.splate.splate) |
| **DriveEstate** | Property, cars & premium numbers in one bilingual app (Google Maps, Pusher chat), launched 2026 | UAE | [App Store](https://apps.apple.com/us/app/driveestate/id6786304746) · [Google Play](https://play.google.com/store/apps/details?id=com.metagate.driveestate) |
| **Car Station** | Car rental with a driver: customer and driver apps (Mapbox, live tracking, MyFatoorah) | UAE | [Customer](https://play.google.com/store/apps/details?id=ae.metagate.carstation.user.car_station) · [Driver](https://play.google.com/store/apps/details?id=ae.metagate.carstation.driver.car_station) |
| **Yemnzil** `10K+` | Cars & real-estate marketplace with map and search filters | Yemen | [Google Play](https://play.google.com/store/apps/details?id=com.metagate.yemnzil) |
| **Plat** | Rare plates & VIP numbers with subscriptions, seller meetings and Stripe | UAE | [Google Play](https://play.google.com/store/apps/details?id=com.metagate.plate) |
| **HR Portals** `1K+` | Attendance, leave and overtime for multi-organisation teams; hand-punch machine sync | Middle East | [Google Play](https://play.google.com/store/apps/details?id=com.hr_portals.hr_portal) |
| **Sanctuary NL** | Mobile-first spa website with pricing, reviews, map and WhatsApp booking (WordPress) | Netherlands | [sanctuarys.nl](https://sanctuarys.nl) |

---

## 🔬 AI & research projects

#### 🌿 [ESG Guardian](https://github.com/emelian-chkaira/ESG-Guardian-Analysis-Website) — CSRD/ESRS compliance scoring · [Live demo](https://papaya-bublanina-0721f3.netlify.app)
Parses bank sustainability-report PDFs and runs 19 rule checks across 6 EU frameworks; scored Banco BPM's 2024 report 94.7/100. *React, TypeScript, pdf.js, rule engine, NLP.*

#### 🎮 [The Data Mystery](https://github.com/emelian-chkaira/The-Data-Mystery-GDPR-by-Gamification) — GDPR Article 9 card game · [Play](https://candid-valkyrie-10dcc5.netlify.app)
Card game against an AI opponent that teaches lawful processing of sensitive data, with a rule engine and guided scenarios. *React, TypeScript, Vite.*

#### 📊 Transactional Behaviour & RFM Analysis
Recency-Frequency-Monetary customer segmentation with KPI dashboards. *Python, pandas, SQL.*

#### 🏁 CISPA Hackathon — AI & Cybersecurity (Warsaw, May 2026)
**5th of 24 teams.** Led the Dataset Usage Cardinality Inference task on nine pre-trained ResNet models.

---

## 🎓 Education
- **MSc Business Analytics** — University of Bologna, Italy (2025 – expected 2027)
- **Artificial Intelligence Specialization** — University of Milan, Italy (2024)
- **BSc Software Engineering** — Al-Baath University, Syria (2019 – 2023)
