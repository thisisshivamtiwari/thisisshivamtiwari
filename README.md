# Shivam Tiwari

Applied AI engineer and co-founder. I build forecasting, pricing and LLM-agent systems that run in production for paying customers.

[LinkedIn](https://linkedin.com/in/thisisshivamtiwari) · [Email](mailto:shivamtiwari.1527@gmail.com) · Birmingham, UK

## Now

- **Applied AI Product Lead, RBS** (since February 2026). Building AI agents, agentic-coding workflows and MCP tooling used across RBS's products, and extending KnowMyHotel with new property-management-system integrations and competitor-set and local-events data.
- **M.Sc. Data Science and AI**, joint degree from IIT Madras and the University of Birmingham, finishing January 2027.

## Background

In 2023 I co-founded **Retvens**, a hotel revenue-management AI company, and ran its technology. It grew to 2,000+ paying hotels across five countries and a team of 20+, and was acquired by RBS in February 2026; I led the technical due diligence. Before that I built end-to-end encrypted chat for Android at Thotnr and worked on SQL data pipelines and test automation at Infosys.

## Selected work

| Project | What it is | My part |
|---|---|---|
| [KnowMyHotel](https://knowmyhotel.com) | AI revenue manager giving nightly room-rate suggestions to about 200 subscribed hotels | Built the occupancy forecaster: a LightGBM, XGBoost and Prophet ensemble tuned with Optuna and walk-forward validation, K-Means++ clustering for hotels with no history, and 15 leakage-safe lag and rolling features. Pricing changes were A/B-tested on live room rates, with up to 120% revenue uplift at select hotels. |
| [HotelAuditReport](https://hotelauditreport.com) | Automated revenue audits for hotels | Anomaly detection across PMS, channel-manager and OTA data, replacing consultant-led audits. |
| [Nautilus AI](https://github.com/thisisshivamtiwari/nautilusai) | Winner, Nutanix Hackathon at IIT Madras | Autonomous cloud-operations agent: live telemetry, anomaly detection, an on-premise LLM with RAG, and YAML remediation through the Nutanix Prism API. Cut time to resolution from 4–6 hours to under 30 seconds in the live demo. |
| [ExcelLLM](https://github.com/thisisshivamtiwari/excelllm-be) ([frontend](https://github.com/thisisshivamtiwari/excelllm-fe)) | Research internship, Walmart Center for Tech Excellence, IIT Madras | Multi-agent LLM framework that turns spreadsheet-driven workflows at small businesses into agent pipelines. |
| Hotel voice agent | Prototype, Retvens | English and Hindi booking and guest-service calls against a live PMS (Whisper, LangGraph, ElevenLabs). Shelved before launch because the cost per call was too high. |
| [kaushalbot](https://github.com/thisisshivamtiwari/kaushalbot) | Telegram agent for LinkedIn posts | Orchestrator and worker agents on LangChain and Gemini, with LinkedIn sign-in and MongoDB. |

Also: finalist, UKFinnovator Innovation Competition at Imperial College London (LLM and multi-agent pipeline for ESG data).

## Stack

**AI and ML:** Python, PyTorch, scikit-learn, LightGBM, XGBoost, Prophet, Optuna, LangGraph, LangChain, MCP, RAG
**Product engineering:** TypeScript, React, Next.js, Vite, Tailwind CSS, Node.js, Express, FastAPI, PHP, MongoDB, Redis, MySQL
**Mobile:** Kotlin, Java, Jetpack Compose, Firebase
**Infrastructure:** Docker, Airflow, Nginx, Linux, Git
