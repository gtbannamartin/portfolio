# Build Record — Martin O. Pieters

A documented record of systems I have designed, built, and delivered across three decades, from industrial optimization models to civic AI. Most current code sits in private repositories on this account; the first public repositories are being built in the open. Some work lives in institutional environments, and some predates my use of GitHub entirely. Everything listed here is real, and I am glad to walk through the architecture of any of it.

**Legend:** 🟢 live · 🔒 code in a private repository on this account (walkthrough on request) · 📐 specification complete, build in progress · 🏛️ institutional or client environment · 📼 pre-GitHub era (documentation only)

\---

## Current \& Active (2024–2026)

### 🟢🔒 PathwayAI — Civic AI Career-Pathway Assistant (2026–present)

Live at [djmpinstitute.org/pathwayai](https://djmpinstitute.org/pathwayai). Matches Chicago residents to technology career pathways. **v0 is live:** one structured Claude call behind a Cloudflare Worker that holds the API key, validates input, rate-limits, and checks the JSON output. It follows a specified five-agent supervisor design (Intake \& Profile Builder · Labor Market Analyst · Resource Matcher · Barrier Detector · Pathway Architect) with a human-in-the-loop oversight layer; the multi-agent build is underway. Governed by TCAF™.
**Stack:** Claude API, Cloudflare Workers/Pages, JavaScript.

### 📐 TCAF™ — Trustworthy Civic AI Framework (doctoral research, 2026)

A four-pillar governance architecture (Secure by Architecture · Ethical by Design · Equitable by Intent · Scalable by Design) for evaluating agentic AI in high-stakes civic deployments. Methodology under empirical validation.

### 🟢🔒 DJMP Institute Website \& Deployment Pipeline (2024–present, previously djmptechacademy.org)

Website for a Chicago 501(c)(3) at [djmpinstitute.org](https://djmpinstitute.org). GitHub → Cloudflare Pages deployment with a versioned staging discipline (working `\_Active` files → clean `\_Live` files → archive) and a cache-purge deployment protocol.
**Stack:** HTML/CSS/JS, Cloudflare Pages, GitHub.

### 📐 AccessBridge — Disability-Inclusive Civic Navigation *(in development, 2026)*

Sibling TCAF™ instantiation to PathwayAI, aimed at disability services navigation. Architecture specification complete; build in progress.

### Grant Intelligence — Funder Screening Workflow (2026)

An expert-led, AI-assisted workflow (Claude plus a structured Grant Scorecard) that screens funding sources and ranks fit for small organizations. A working method, not a software product; the scorecard methodology is under empirical validation.

### AI Curriculum — BroSE, California State University, Northridge (2023–2026)

Four years teaching AI in CSUN's BroSE residential leadership program. Built and delivered the AI curriculum, culminating in a 100+ slide program on GANs, deepfakes, agentic AI and AI economics for 27 students, with a live PathwayAI demo.

\---

## Research Code (institutional environments)

### 🏛️ Deep-Learning Computer Vision for Toughened Polymers — Northwestern University (2022)

Research Experience for Teachers (RET) Fellow, NU-MRSEC (NSF-funded; one of four selected). Deep-learning computer vision (transfer learning, VGG19) for fracture-surface analysis of toughened polymers from limited image data, in collaboration with Ford.

### 🏛️ Error-Embedded DNN Framework for MRI \& Predictive Glucose Monitoring — Illinois Institute of Technology (2019–2020)

Visiting Research Scientist (sabbatical), Biomedical Engineering, funded by an American Heart Association grant, with the University of Chicago. Deep neural networks for MRI with a data-integrity framework for error-embedded training pairs; extended to predictive continuous-glucose-monitoring algorithms for automated insulin delivery (with Gifu University, Japan, and UChicago Medical Center). Peer-reviewed ISMRM publication.

### 🏛️ Kinetic Model of Paint Hydrolysis — Northwestern University (2015)

RET Fellow, NU-MRSEC (one of six selected). Built a kinetic model of hydrolysis chemistry in aging oil-based paint, validated against experimental data and published.

\---

## Legacy Systems (pre-GitHub era)

### 📼 Stay Safe App — Civic Safety Routing (2017)

Led the Push Excel Saturday Academy student team (Push Excel is the education arm of Rainbow PUSH Coalition) that built a civic AI tool layering Chicago gun-violence data over Google Maps to route CPS students safely home. Unveiled at Rainbow PUSH's 46th Annual International Convention; covered by ABC7 Chicago and the Chicago Sun-Times. The direct precursor to PathwayAI.

### 📼 Smart-City Camera Network — Operation Virtual Shield III/IV (2009)

Project manager for Milhouse Engineering and, concurrently, Assistant Project Manager for the Public Building Commission of Chicago on Chicago's $217M citywide network linking 3,000+ cameras to central monitoring (IBM prime contractor).

### 📼 Industrial Optimization \& Financial Modeling — Kraft Foods / Amoco (1994–2004)

A decade of statistical modeling, process optimization, and financial model development across refining, utilities, and food manufacturing: $12M optimization portfolio at Kraft; $0.5–6M utilities projects and lost-opportunity tracking models at Amoco; reverse-osmosis system implementations at both.

\---

## A note on lost work

Several project repositories from 2015–2023 were never migrated to remote hosting and were lost with local hardware. I document them here rather than let them vanish from the record; where artifacts survive (reports, publications, media coverage, deployed descendants), they are linked. The lesson was learned: everything now ships to this account, same day.

\---

📧 martinopieters@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/martin-pieters-86550517) · 🌐 [djmpinstitute.org](https://djmpinstitute.org)

