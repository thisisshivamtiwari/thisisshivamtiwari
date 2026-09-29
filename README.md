<!-- Profile README for github.com/thisisshivamtiwari (paste into the repo named thisisshivamtiwari). -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F5C5A,100:16181D&height=190&section=header&text=Shivam%20Tiwari&fontSize=52&fontColor=F6F3EC&fontAlignY=38&desc=Applied%20AI%20Engineer%20%C2%B7%20Co-founder%2C%20Retvens%20(acquired%202026)&descSize=18&descAlignY=60" alt="Shivam Tiwari — Applied AI Engineer, co-founder of Retvens (acquired 2026)" />
</p>

<h3 align="center">I build AI systems that have to pay for themselves.</h3>

<p align="center">
  <a href="https://linkedin.com/in/thisisshivamtiwari"><img src="https://img.shields.io/badge/LinkedIn-thisisshivamtiwari-0F5C5A?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:shivamtiwari.1527@gmail.com"><img src="https://img.shields.io/badge/Email-shivamtiwari.1527%40gmail.com-16181D?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  <img src="https://img.shields.io/badge/Based%20in-Birmingham%2C%20UK-B4400F?style=flat-square" alt="Based in Birmingham, UK" />
</p>

I co-founded a hotel revenue-management company, shipped machine learning to paying customers, shut down an AI product when the unit economics didn't work, and led the company through its acquisition. Today I'm doing an M.Sc. in Data Science & AI at **IIT Madras × University of Birmingham** and building agents, forecasting systems and the full-stack products around them.

<table>
  <tr>
    <td align="center" width="25%"><h2>2,000+</h2><sub>paying hotel customers across two AI products</sub></td>
    <td align="center" width="25%"><h2>~200</h2><sub>hotels on recurring subscription to KnowMyHotel</sub></td>
    <td align="center" width="25%"><h2>2026</h2><sub>Retvens acquired by RBS Software Solutions</sub></td>
    <td align="center" width="25%"><h2>&lt;30 s</h2><sub>cloud incident resolution, down from 4–6 h (hackathon winner)</sub></td>
  </tr>
</table>

### `$ git log --career --oneline`

```text
* 2026-02  (tag: acquired)  Retvens Services acquired by RBS Software Solutions — led technical due diligence
* 2025-11  AI Research Intern, Walmart Center for Tech Excellence, IIT Madras — multi-agent LLM framework for MSME spreadsheets (grade A)
* 2025-07  M.Sc. Data Science & AI — IIT Madras × University of Birmingham
* 2025     Winner, Nutanix Hackathon (IIT Madras) · Finalist, UKFinnovator (Imperial College London)
* 2023-04  (HEAD of Technology)  Co-founded Retvens Services — hotel revenue-management AI, 5 countries, 20+ person team
* 2022-10  Senior Associate, Engineering @ Thotnr — end-to-end encrypted chat in Kotlin on the Mesibo SDK
* 2020-11  Senior Operations Executive @ Infosys — SQL schemas for client data pipelines, Selenium UAT automation
```

### Shipped to production

| Product | What it does | What I built |
|---|---|---|
| [**KnowMyHotel**](https://knowmyhotel.com) | AI revenue manager: nightly room-rate suggestions for ~200 subscribed hotels | Occupancy forecaster — LightGBM + XGBoost + Prophet ensemble tuned with Optuna, K-Means++ for cold-start hotels, 15 leakage-safe lag features; pricing changes A/B-tested on live rates (up to 120% revenue uplift at select hotels) |
| [**HotelAuditReport**](https://hotelauditreport.com) | Automated revenue audits for hotels — most of our 2,000+ paying customers | Anomaly detection over PMS, channel-manager and OTA data, replacing consultant-led reviews |

### Built, measured, and shelved

> **Hotel voice concierge** — an agent that took booking and guest-service calls in English and Hindi against a live PMS: Whisper → tool-calling LLM on a LangGraph state machine → ElevenLabs.
> It worked. We shut it down before launch because the cost per call was too high to sustain.
> Knowing when *not* to ship is part of the job.

### Open work

| Repository | Summary |
|---|---|
| [**nautilusai**](https://github.com/thisisshivamtiwari/nautilusai) | 🏆 Nutanix Hackathon winner — autonomous cloud-ops agent: telemetry → anomaly detection → on-prem LLM + RAG → YAML remediation via the Prism API |
| [**excelllm-be**](https://github.com/thisisshivamtiwari/excelllm-be) · [**fe**](https://github.com/thisisshivamtiwari/excelllm-fe) | Multi-agent LLM framework that turns spreadsheet-driven MSME workflows into agent pipelines (Walmart CTE, IIT Madras) |
| [**kaushalbot**](https://github.com/thisisshivamtiwari/kaushalbot) | Telegram agent that drafts and refines LinkedIn posts — orchestrator/worker agents on LangChain + Gemini, LinkedIn OIDC, MongoDB |
| [**neetcode-submissions**](https://github.com/thisisshivamtiwari/neetcode-submissions) | Keeping the fundamentals sharp, one problem at a time |

### Stack

**AI & agents** &nbsp;
<img src="https://img.shields.io/badge/LangGraph-16181D?style=flat-square" alt="LangGraph" />
<img src="https://img.shields.io/badge/LangChain-16181D?style=flat-square" alt="LangChain" />
<img src="https://img.shields.io/badge/LlamaIndex-16181D?style=flat-square" alt="LlamaIndex" />
<img src="https://img.shields.io/badge/MCP-16181D?style=flat-square" alt="MCP" />
<img src="https://img.shields.io/badge/RAG-16181D?style=flat-square" alt="RAG" />
<img src="https://img.shields.io/badge/Whisper-16181D?style=flat-square" alt="Whisper" />
<img src="https://img.shields.io/badge/ElevenLabs-16181D?style=flat-square" alt="ElevenLabs" />

**Machine learning** &nbsp;
<img src="https://img.shields.io/badge/LightGBM-0F5C5A?style=flat-square" alt="LightGBM" />
<img src="https://img.shields.io/badge/XGBoost-0F5C5A?style=flat-square" alt="XGBoost" />
<img src="https://img.shields.io/badge/Prophet-0F5C5A?style=flat-square" alt="Prophet" />
<img src="https://img.shields.io/badge/Optuna-0F5C5A?style=flat-square" alt="Optuna" />

<p>
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,sklearn,ts,react,nextjs,vite,tailwind,nodejs,express,fastapi,php,mongodb,redis,mysql&perline=16" alt="Python, PyTorch, TensorFlow, scikit-learn, TypeScript, React, Next.js, Vite, Tailwind, Node.js, Express, FastAPI, PHP, MongoDB, Redis, MySQL" />
  <br />
  <img src="https://skillicons.dev/icons?i=kotlin,java,androidstudio,flutter,firebase,django,spring,docker,aws,nginx,git,linux,postman,figma&perline=16" alt="Kotlin, Java, Android Studio, Flutter, Firebase, Django, Spring, Docker, AWS, Nginx, Git, Linux, Postman, Figma" />
</p>

### Open to

Applied AI, forward-deployed and founding-engineer roles — especially where the model has to earn its keep.

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:16181D,100:0F5C5A&height=90&section=footer" alt="" />
</p>
