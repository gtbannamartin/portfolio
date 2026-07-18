# Build Record — Martin O. Pieters

A documented record of systems I have designed, built, and shipped across three decades — from industrial optimization models to production agentic AI. Some code lives in this account (private and public); some lives in institutional environments; some predates my use of GitHub entirely. Everything listed here is real, and I am glad to walk through the architecture of any of it.

**Legend:** 🟢 live in production · 🔵 code on this account · 📐 specification complete, build in progress · 🏛️ code in institutional/client environment · 📼 pre-GitHub era (documentation only)

---

## Current & Active (2024–2026)

### 🟢🔵 PathwayAI — Agentic Workforce Navigation Platform (2025–present)
Live at [djmpinstitute.org/pathwayai](https://djmpinstitute.org/pathwayai). Five-agent architecture on Google Gemini that continuously monitors ten publicly available federal workforce databases and matches residents to personalized technology-career pathways. Delivered via web, mobile, and SMS.
**Architecture highlights:** Cloudflare Worker proxy fronting the model API (key isolation, request shaping) · Google Apps Script telemetry bridge logging engagement data to Sheets (GET-based, CORS-constrained, domain-locked) · governed end-to-end by TCAF™.
**Stack:** Gemini API, Cloudflare Workers/Pages, JavaScript, Apps Script.

### 🟢🔵 DJMP Institute Website & Deployment Pipeline (2024–present)
Production website for a 501(c)(3) at [djmpinstitute.org](https://djmpinstitute.org). GitHub → Cloudflare Pages CI with a versioned staging discipline (working `_Active` files → clean `_Live` files → archive) and cache-purge deployment protocol.
**Stack:** HTML/CSS/JS, Cloudflare Pages, GitHub.

### 📐 AccessBridge — Disability-Inclusive Civic Navigation *(in development, 2026)*
Sibling TCAF™ instantiation to PathwayAI, aimed at disability services navigation. Architecture specification complete; build in progress.

### 📐 Grant Intelligence — Funder Scoring & Pipeline Infrastructure (2026)
Internal scoring methodology (under empirical validation) and pipeline tracking applied across a 10-funder portfolio including AWS, Google.org, and federal programs. Structured document automation and decision-support tooling. Operating internally; repository migration pending.

### 🔵 AI Curriculum Engineering — BroSE 2023–2026
Four consecutive years as AI/STEM instructor for CSUN's Brotherhood of Scholarship and Excellence residential leadership program. The 2026 build: a 100+ slide programmatically-assembled curriculum (GANs, deepfakes, agentic AI, AI industry economics) with embedded interactive activities, delivered to 27 students, including a live PathwayAI production demo.

---

## Research Code (institutional environments)

### 🏛️ Deep-Learning Computer Vision for Materials Discovery — Northwestern University (2022)
Research Associate (one of four selected). ML and end-to-end deep learning for microstructure and physical-property inferencing of toughened polymers; materials-discovery acceleration platform developed in collaboration with Ford.

### 🏛️ Error-Embedded DNN Framework for MRI & Predictive Glucose Monitoring — Illinois Institute of Technology (2019–2020)
Research Fellow. Deep neural network MRI schemes with a data-integrity framework for error-embedded training pairs; extended to predictive continuous-glucose-monitoring algorithms for automated insulin delivery (U.S.–Japan collaboration with Gifu University and UChicago Medical Center). Peer-reviewed ISMRM publication.

---

## Legacy Systems (pre-GitHub era)

### 📼 Stay Safe App — Civic Safety Routing (2017)
Led the Push Excel Saturday Academy student team — the education arm of Rainbow PUSH Coalition — that built a civic AI tool layering Chicago gun-violence data over Google Maps to generate safer routes home for CPS students. Unveiled at Rainbow PUSH's 46th Annual International Convention; covered by ABC7 Chicago and the Chicago Sun-Times. The direct intellectual precursor to PathwayAI.

### 📼 Smart-City Surveillance Analytics — Operation Virtual Shield III/IV (2009)
Project management and coordination on Chicago's $217M citywide integration of 3,000+ cameras into a centralized real-time analytics network (Public Building Commission, via Milhouse Engineering).

### 📼 Industrial Optimization & Financial Modeling — Kraft Foods / Amoco (1994–2004)
A decade of statistical modeling, process optimization, and financial model development across refining, utilities, and food manufacturing: $12M optimization portfolio at Kraft; $0.5–6M utilities projects and lost-opportunity tracking models at Amoco; reverse-osmosis system implementations at both.

---

## A note on lost work

Several project repositories from 2015–2023 were never migrated to remote hosting and were lost with local hardware. I document them here rather than let them vanish from the record; where artifacts survive (reports, publications, media coverage, deployed descendants), they are linked. The lesson was learned: everything now ships to this account, same day.

---

📧 martinopieters@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/martin-pieters-86550517) · 🌐 [djmpinstitute.org](https://djmpinstitute.org)
