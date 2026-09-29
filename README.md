<!-- Profile README for github.com/thisisshivamtiwari.
     Copy this file AND the assets/ folder into the repo named thisisshivamtiwari. -->

<p align="center">
  <img src="assets/hero.svg" width="100%" alt="Shivam Tiwari — Applied AI Engineer, co-founder of Retvens (acquired 2026), M.Sc. Data Science & AI at IIT Madras × University of Birmingham" />
</p>

<p align="center">
  <a href="https://linkedin.com/in/thisisshivamtiwari"><img src="https://img.shields.io/badge/LinkedIn-thisisshivamtiwari-0F5C5A?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:shivamtiwari.1527@gmail.com"><img src="https://img.shields.io/badge/Email-Say%20hello-16181D?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/IIT%20Madras-M.Sc.%20DS%20%26%20AI-8B1A1A?style=for-the-badge" alt="IIT Madras — M.Sc. Data Science & AI" />
</p>

## About

I'm an engineer-founder. In 2023 I co-founded **Retvens**, a hotel revenue-management AI company. We grew it to **2,000+ paying hotel customers** across five countries, and in February 2026 I led it through its **acquisition by RBS Software Solutions**.

Along the way I built the forecasting engine that priced rooms every night for ~200 subscribed hotels, hired a 20+ person team, and made the hardest call a builder makes: shutting down an AI product that worked, because it didn't pay.

Now I'm back in the lab at **IIT Madras** (joint M.Sc. with the University of Birmingham), going deeper on LLM agents, forecasting and the full-stack products that carry them to real users.

<p align="center">
  <img src="assets/stats.svg" width="100%" alt="2,000+ paying hotel customers · ~200 hotels on subscription · acquired 2026 · incidents resolved in under 30 seconds" />
</p>

## Career

<p align="center">
  <img src="assets/career.svg" width="100%" alt="Career timeline: Infosys (2020), Thotnr (2022), co-founded Retvens (2023), Nutanix Hackathon winner (2025), IIT Madras × University of Birmingham (2025), Walmart CTE research intern (2025), Retvens acquired by RBS (2026)" />
</p>

## Shipped to production

| Product | What it does | What I built |
|---|---|---|
| [**KnowMyHotel**](https://knowmyhotel.com) | AI revenue manager: nightly room-rate suggestions for ~200 subscribed hotels | Occupancy forecaster: **LightGBM + XGBoost + Prophet** ensemble tuned with Optuna, K-Means++ for hotels with no history, 15 leakage-safe lag features. Pricing changes A/B-tested on live room rates, up to **120% revenue uplift** at select hotels. |
| [**HotelAuditReport**](https://hotelauditreport.com) | Automated revenue audits, bought by most of our 2,000+ paying customers | Anomaly detection across PMS, channel-manager and OTA data that replaced consultant-led audits. |

## Built, measured, shelved

> [!NOTE]
> **Hotel voice concierge** — took booking and guest-service calls in English and Hindi against a live PMS.
> `Whisper` → tool-calling LLM on a `LangGraph` state machine → `ElevenLabs`.
> It worked. We shut it down before launch because the cost per call was too high to sustain.
> Knowing when *not* to ship is part of the job.

## Open work

| Repository | What it is |
|---|---|
| [**nautilusai**](https://github.com/thisisshivamtiwari/nautilusai) 🏆 | **Nutanix Hackathon winner.** Autonomous cloud-ops agent: telemetry → anomaly detection → on-prem LLM + RAG → YAML remediation through the Prism API. Incidents resolved in **under 30 s**, down from 4–6 h. |
| [**excelllm-be**](https://github.com/thisisshivamtiwari/excelllm-be) · [**fe**](https://github.com/thisisshivamtiwari/excelllm-fe) | Multi-agent LLM framework that turns spreadsheet-driven MSME workflows into agent pipelines. Walmart CTE, IIT Madras. |
| [**kaushalbot**](https://github.com/thisisshivamtiwari/kaushalbot) | Telegram agent that drafts and refines LinkedIn posts: orchestrator/worker agents on LangChain + Gemini, LinkedIn OIDC, MongoDB. |
| [**neetcode-submissions**](https://github.com/thisisshivamtiwari/neetcode-submissions) | Fundamentals, kept sharp daily. |

## Stack

<p align="center">
  <img src="assets/tech-stack-icons.svg" width="100%" alt="Tech stack: LangGraph, LangChain, MCP, ElevenLabs, Gemini, Python, PyTorch, TensorFlow, scikit-learn, Optuna, TypeScript, React, Next.js, Vite, Tailwind CSS, Node.js, Express, FastAPI, Django, Spring, PHP, MongoDB, Redis, MySQL, Kotlin, Java, Jetpack Compose, Flutter, Firebase, Docker, Airflow, Nginx, Git, Linux, Postman, Figma" />
</p>

<p align="center"><sub><code>~/shivam $ exit 0</code> &nbsp;·&nbsp; built things that shipped, sold, and got acquired</sub></p>
