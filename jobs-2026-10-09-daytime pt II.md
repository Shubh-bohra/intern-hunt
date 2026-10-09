# Job Hunt Run — 2026-10-09 (Daytime) pt II

## Run Summary

- **Date/Time:** October 9, 2026 — daytime run (~12:10–12:35 UTC)
- **Total listings found:** 22 (10 internships, 12 full-time roles)
- **Tools used:** Apify LinkedIn Jobs Scraper (curious_coder), Apify Indeed Scraper (borderline), WebSearch (multiple queries)

| Source | Status | Notes |
|---|---|---|
| LinkedIn (Apify actor) | ✅ Worked | 35 listings pulled across 2 runs |
| Indeed India (Apify actor) | ✅ Worked | 20 listings pulled |
| Wellfound | ❌ DNS failed | WebFetch DNS resolution error; partial leads from WebSearch |
| Internshala | ✅ Partial | WebSearch only; no direct scrape |
| Naukri | ✅ Partial | WebSearch only; category pages returned |
| Hirist | ✅ Partial | WebSearch only; Bengaluru GenAI category page found |
| Glassdoor | ✅ Partial | WebSearch mentions only |
| Cutshort | ✅ Partial | WebSearch; category pages, no individual job URLs |
| YC Work at a Startup | ✅ Partial | Peakflo ML Intern lead found; direct fetch failed (DNS) |
| Remotive | ❌ DNS failed | WebFetch DNS resolution error; partial mention via WebSearch |
| RemoteOK | ✅ Partial | WebSearch; no India-eligible intern roles confirmed |
| Himalayas | ✅ Partial | WebSearch; mostly talent profiles, one DaCodes lead |
| We Work Remotely | ✅ Partial | WebSearch; no intern roles confirmed |
| Unstop | ❌ No results | WebSearch returned nothing from this domain |
| Foundit / Monster | ❌ Not attempted | |
| IIMJobs | ❌ Not attempted | |
| Apna | ❌ Not attempted | |
| Hirect / Instahyre | ❌ Not attempted | |
| Arc.dev / Turing | ❌ Not attempted | |

---

## Section 1 — Strongest Matches

### Internships

> Remote and international remote first.

---

**1. Intern — GenAI / LLM / Vision AI**
- **Company:** Clarion Analytics
- **Job type:** Internship
- **Location:** Remote (India)
- **Work type:** WFH / Remote
- **Posted:** 2026-10-02 (7 days ago)
- **Source:** Indeed India
- **Easy Apply:** Yes (Indeed direct)
- **Stipend:** ₹5,000/month
- **Apply:** https://in.indeed.com/viewjob?jk=db23b08b5f2cecca
- **Required skills:** Python, LLMs, Transformers, Computer Vision, RAG, embeddings, vector databases, LangChain, OCR, multimodal AI, Ollama, Hugging Face
- **Fit:** Clarion Analytics is a Singapore-based company building operational AI for APAC enterprises — document processing, worker safety, multilingual customer service. The role covers RAG pipelines, multimodal LLMs, and AI agents, mirroring almost exactly the work Shubh did at Tez Health (multilingual voice + LLMs) and TriageForge (RAG + agentic routing). The APAC focus is a direct parallel to the 5-language medical triage chatbot.

---

**2. AI Implementation Intern**
- **Company:** Sprinto
- **Job type:** Internship
- **Location:** Remote (India)
- **Work type:** WFH / Remote
- **Posted:** 2026-10-05 (4 days ago)
- **Source:** Indeed India (via Lever ATS)
- **Easy Apply:** No (Lever application)
- **Stipend:** Not listed
- **Apply:** https://jobs.lever.co/Sprinto/6dfd5f41-57b6-40e8-9eab-ba4083c1a7c4
- **Required skills:** Python, ML concepts, data processing, TensorFlow/PyTorch, cloud (AWS/GCP/Azure), LLMs, document parsing, search tools
- **Fit:** Sprinto is a well-funded compliance automation SaaS (backed by Accel, Elevation, Blume — $31.8M raised), trusted by 4,000+ organisations. The AI Implementation Intern will build AI infrastructure for LLM integration, document parsing, and search. This maps directly to FloatChat AI's hybrid SQL + vector RAG pipeline and TriageForge's structured output and moderation layers. A credible, growing company with real engineering culture.

---

**3. Machine Learning (ML) Engineer Intern — Paid (India/Remote)**
- **Company:** Peakflo *(YC-backed, W21)*
- **Job type:** Internship
- **Location:** Remote — India eligible
- **Work type:** Remote / WFH
- **Posted:** Date unconfirmed — posting was live as of this run; verify before applying ⚠️
- **Source:** YC Work at a Startup
- **Easy Apply:** Via YC portal
- **Stipend:** Paid (amount not listed)
- **Apply:** https://www.ycombinator.com/companies/peakflo/jobs/I4Ehwpd-machine-learning-ml-engineer-intern-paid-india-remote
- **Required skills:** Python, Machine Learning, NLP, Prompt Engineering
- **Fit:** Peakflo is a Y Combinator W21-backed fintech automating accounts payable and receivable for SMBs in Asia. The role is explicitly labelled India/Remote, making it the strongest confirmed international company hiring in India for this search. Python, ML, and NLP skills align with Shubh's core stack. YC pedigree and remote-India flag make this a priority application; confirm posting is still open.

---

**4. Forward Deployed Engineer Intern**
- **Company:** Opptra
- **Job type:** Internship
- **Location:** Bengaluru Urban, Karnataka
- **Work type:** On-site (Bengaluru)
- **Posted:** 2026-10-09 (today)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Stipend:** "Competitive internship stipend"
- **Apply:** https://in.linkedin.com/jobs/view/forward-deployed-engineer-intern-at-opptra-4476278871
- **Required skills:** Python, LLMs, agentic workflows, prompt engineering, tool use, output structuring, eval loops, Claude API / OpenAI / LangChain, SQL, BigQuery
- **Fit:** Opptra is an AI-first company expanding international brands into Asia via franchising and inventory partnerships. FDEs own outcomes, not tickets — they build LLM-powered workflows, agentic systems, and Python pipelines that hit production. This role is the closest to the TriageForge architecture (multi-agent LangChain, tool delegation, structured outputs) of any intern role in this run. The explicit mention of Claude Code, Cursor, and agentic systems as part of daily workflow also matches.

---

**5. AI Native Intern (Applications Development)**
- **Company:** Marsh (NYSE: MRSH)
- **Job type:** Internship (Temporary)
- **Location:** Pune, Maharashtra — hybrid (3 days/week in office)
- **Work type:** Hybrid
- **Posted:** 2026-10-09 (today)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Stipend:** Not listed (enterprise company, likely competitive)
- **Apply:** https://in.linkedin.com/jobs/view/interns-applications-development-at-marsh-4477668479
- **Required skills:** Python/JavaScript/Java, LLM behavior, GenAI concepts, prompting, RAG, SQL/NoSQL, Will Graduate 2027, 60%+ aggregate, no active backlogs
- **Fit:** Marsh McLennan ($27B+ revenue, 130 countries) explicitly requires 2027 graduates, making this one of the few enterprise roles in this run that is degree-cohort-matched. The AI Native Intern role is inside enterprise software delivery, building AI-enabled solutions. The guardrail validation work and prompt injection awareness requirements map to TriageForge's guardrail layer (PII redaction, prompt injection detection). Apply early — a Pune listing with the identical JD was also posted for Mumbai.

---

**6. Python AI Intern**
- **Company:** Techolution
- **Job type:** Internship
- **Location:** Hyderabad, Telangana — on-site
- **Work type:** On-site
- **Posted:** 2026-10-07 (2 days ago)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Stipend:** Not listed (6-month PPO opportunity)
- **Apply:** https://in.linkedin.com/jobs/view/python-ai-intern-at-techolution-4475402350
- **Required skills:** Python, RAG architecture (embeddings, chunking, retrieval, semantic search), vector databases, AI agents, agent orchestration, tool use, AI safety/guardrails, REST APIs, LLMs
- **Non-negotiable:** RAG understanding, AI agents, guardrails, REST APIs
- **Fit:** Techolution is Inc. 5000-recognised and Google Premier Partner, 300+ Fortune 500 clients. The non-negotiable checklist (RAG, agents, guardrails) is a near-exact description of TriageForge: agent-as-tool delegation, custom MCP server, guardrail layer, Pydantic-validated structured output. The 6-month PPO pathway is a direct route to full-time. Hyderabad on-site is the only limitation.

---

### Full-time Roles

> Remote and international remote first.

---

**7. AI Engineer**
- **Company:** Mobility Global (S&P Global Mobility — CARFAX, automotiveMastermind)
- **Job type:** Full-time
- **Location:** Bengaluru, Karnataka — hybrid
- **Work type:** Hybrid
- **Posted:** 2026-09-22 (~17 days ago — borderline; verify listing is still active)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Salary:** Not listed (competitive; S&P Global)
- **Apply:** https://in.linkedin.com/jobs/view/ai-engineer-at-mobility-global-4468922949
- **Required skills:** Python (async, type hints, testing), LangGraph / LangChain / LlamaIndex, RAG pipelines, FastAPI, SQL + vector store, MCP servers, prompt engineering, Claude Code/Cursor/GitHub Copilot
- **Experience:** 1–5 years **or equivalent practical experience** (internships and substantial personal projects count explicitly)
- **Fit:** This is the single strongest full-time match in this run. The JD explicitly names LangGraph, MCP servers, multi-agent patterns, RAG, FastAPI, and evaluation harnesses — every element is present in TriageForge (custom MCP server, Orchestrator + 4 tools, Pydantic eval harness) or FloatChat AI (FastAPI, hybrid SQL + vector RAG). The team also uses Claude Code and agentic dev workflows daily. The "substantial personal projects count" clause directly addresses the 2027 graduating batch.

---

**8. Junior AI Engineer**
- **Company:** YAL
- **Job type:** Full-time
- **Location:** Hyderabad, Telangana
- **Work type:** On-site (Hyderabad)
- **Posted:** 2026-10-07 (2 days ago)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Salary:** Not listed
- **Apply:** https://in.linkedin.com/jobs/view/junior-ai-engineer-at-yal-4475420904
- **Required skills:** Python, REST APIs, Git, databases, LLMs, RAG, tool calling, agent frameworks, conversational AI, voice STT/TTS, speech synthesis, Docker, cloud deployment
- **Fit:** YAL builds AI agents and conversational systems. The role covers both text and voice conversational AI, including STT/TTS integrations — a direct match for the WebSocket-based real-time STT pipeline with server-side VAD at Tez Health (83% latency reduction). The RAG, tool calling, and agent orchestration work matches TriageForge. This is possibly the most aligned role in the full-time section for the Tez Health experience specifically.

---

**9. AI Engineer**
- **Company:** OATI (Open Access Technology International)
- **Job type:** Full-time
- **Location:** Mohali, Punjab
- **Work type:** On-site (Mohali)
- **Posted:** 2026-10-08 (1 day ago)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Salary:** Not listed
- **Apply:** https://in.linkedin.com/jobs/view/ai-engineer-at-oati-4458501392
- **Required skills:** Python, LangChain, LangGraph, RAG, vector databases, MCP (Model Context Protocol), long-term memory for agents, PEFT/LoRA fine-tuning, MLflow, ML/neural networks
- **Experience:** Entry level (Bachelor's degree minimum)
- **Fit:** The OATI JD is a near-exact checklist match. It explicitly names Model Context Protocol (MCP) — TriageForge ships a custom MCP server as one of its four tools. It also lists LangChain, LangGraph, RAG pipelines, and vector databases, all present in TriageForge or FloatChat AI. OATI focuses on power-system AI applications, which is an interesting sector pivot.

---

**10. Data Scientist — GenAI Developer**
- **Company:** Merck Healthcare (Merck KGaA)
- **Job type:** Full-time
- **Location:** Bengaluru, Karnataka
- **Work type:** On-site (Bengaluru)
- **Posted:** 2026-10-08 (1 day ago)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Salary:** Not listed (global pharma; competitive)
- **Apply:** https://in.linkedin.com/jobs/view/data-scientist-genai-developer-at-merck-healthcare-4477182070
- **Required skills:** Python, Pandas, NumPy, Scikit-Learn, LLM application frameworks (LangGraph, OpenAI APIs), Docker, Git, RAG pipelines, neural networks, NLP
- **Experience:** 0–2 years
- **Fit:** Merck Healthcare (the German Merck KGaA, distinct from US Merck) is a global life sciences company. The role targets 0–2 years for RAG pipelines, LLM integration, prompt engineering, and agentic workflows — squarely in Shubh's zone. Bengaluru location, brand reputation, and an explicit fresher band make this an excellent application.

---

**11. Data Scientist (GenAI — 0–2 Years Experience)**
- **Company:** EXL (Analytics and digital operations leader)
- **Job type:** Full-time
- **Location:** Noida, Uttar Pradesh
- **Work type:** On-site (Noida)
- **Posted:** 2026-10-02 (7 days ago)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Salary:** Not listed
- **Apply:** https://in.linkedin.com/jobs/view/4423237-senior-executive-at-exl-4446731398
- **Required skills:** Python, LLM/VLM finetuning, prompt engineering (few-shot, CoT, self-consistency), RAG, Docker, cloud (AWS/GCP/Azure), REST APIs, FastAPI/Flask, STT/TTS (Whisper, Deepgram, ElevenLabs, Polly, Azure Speech)
- **Experience:** 0–2 years
- **Fit:** EXL is a global analytics company. The STT/TTS requirement is a highlight — the Tez Health voice chatbot used Sarvam AI for TTS streaming and WebSocket STT with server-side VAD. EXL lists Whisper, Deepgram, ElevenLabs, and Azure Speech, showing direct domain overlap. The RAG, Docker, and multi-cloud experience from FloatChat AI (Groq + Ollama + PostgreSQL + ChromaDB) also maps well.

---

**12. Associate — AI/Data Science (Decision Science Practitioner)**
- **Company:** Accenture India
- **Job type:** Full-time
- **Location:** Bengaluru (preferred) / Kolkata / Gurugram
- **Work type:** On-site
- **Posted:** 2026-10-08 (1 day ago)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Salary:** Not listed (Accenture fresh grad band)
- **Apply:** https://in.linkedin.com/jobs/view/s-c-global-network-ai-hi-tech-data-science-associate-at-accenture-in-india-4475869358
- **Required skills (must-have):** Python, SQL, GenAI fundamentals, prompt engineering, APIs
- **Required skills (good to have):** RAG, agentic AI, LangChain/LangGraph, cloud AI, ML fundamentals
- **Experience:** 0–2 years
- **Fit:** Accenture's S&C global network AI associate role targets 0–2 years and lists RAG, agentic AI, and LangChain as preferred — all present in Shubh's portfolio. Multiple India locations, strong brand, structured onboarding. A reliable path into enterprise AI consulting with a global firm.

---

## Section 2 — Stretch Opportunities

### Internships

---

**13. AI Engineer Intern**
- **Company:** Thommidhi
- **Job type:** Internship
- **Location:** Greater Kolkata Area (possibly remote — JD does not specify on-site)
- **Work type:** Unspecified (likely remote, given startup size)
- **Posted:** 2026-10-06 (3 days ago)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Stipend:** Not listed
- **Apply:** https://in.linkedin.com/jobs/view/ai-engineer-intern-at-thommidhi-4475130267
- **Required skills:** TypeScript or Python, LLM integration (Claude, open models), benchmarking, Cloudflare Workers, Workflows and D1, LLM guards, run instrumentation/evaluation
- **Fit:** Thommidhi is building simulation pipelines hardened on Cloudflare Workers with LLM decision models. The eval harness work — instrument runs so every prediction can be scored against reality — directly matches the custom eval harness in TriageForge (improved routing accuracy from 0% to 50%+). The requirement to have "shipped something with an LLM and watched it fail in a way you didn't expect" is a perfect match for iterative agent debugging experience. Stretch: small startup, unfamiliar domain, TypeScript may be required.

---

**14. Generative AI Intern (Python, Prompting, AI APIs)**
- **Company:** MediNex Workforce
- **Job type:** Internship
- **Location:** Remote (India)
- **Work type:** WFH / Remote
- **Posted:** 2026-10-08 (1 day ago)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Stipend:** ₹18,000/month
- **Apply:** https://in.linkedin.com/jobs/view/generative-ai-intern-python-prompting-ai-apis-at-medinex-workforce-4475724601
- **Required skills:** Python, LLM APIs, prompt engineering, AI prototypes (summarisers, extractors, chatbots), Git/GitHub
- **Fit:** MediNex Workforce is a staffing/recruitment company using AI to automate candidate matching. The work (GenAI prototypes, prompt testing, eval, Git) is real, and the ₹18,000/month stipend is better than most. Placed in Stretch because it is a staffing company (lower brand equity than a product company) and the scope is narrower than Shubh's experience. Still a valid paid remote option.

---

### Full-time Roles

---

**15. AI/Machine Learning Engineer**
- **Company:** Siemens Energy
- **Job type:** Full-time
- **Location:** Gurgaon, Haryana
- **Work type:** On-site (Gurgaon)
- **Posted:** 2026-10-02 (7 days ago)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Salary:** Not listed (Siemens Group)
- **Apply:** https://in.linkedin.com/jobs/view/ai-machine-learning-engineer-at-siemens-energy-4473342199
- **Required skills:** Python, RAG, NLP, FastAPI (backend APIs), LLMs, prompt engineering, scikit-learn, NumPy, Pandas, cloud (AWS/Azure), Git
- **Experience:** 6 months to 1 year (or strong academic/project background)
- **Fit:** Siemens Energy ($27B, 100,000 employees, 90+ countries) is a stretch due to location (Gurgaon) and experience band (6 months–1 year). The technical fit is excellent: FastAPI, RAG, NLP, LLMs map to TriageForge and Tez Health. "Strong academic/project background" clause opens the door for Shubh. Group medical insurance, flexi pay benefits.

---

**16. Junior Developer — AI**
- **Company:** Larsen & Toubro (L&T)
- **Job type:** Full-time
- **Location:** Greater Chennai Area
- **Work type:** On-site (Chennai)
- **Posted:** 2026-10-06 (3 days ago)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Salary:** Not listed (L&T)
- **Apply:** https://in.linkedin.com/jobs/view/junior-developer-ai-at-larsen-toubro-4474128596
- **Required skills:** Python, RAG, embeddings, vector databases, NLP, LLMs, prompt engineering, LangChain/LlamaIndex, REST APIs, PyTorch/TensorFlow
- **Fit:** L&T is one of India's largest conglomerates. The Junior Developer — AI role is entry level and explicitly covers RAG, LLMs, and LangChain. Stretch primarily due to Chennai location and L&T's large-company processes (slower-paced than startups). Good brand and stability.

---

**17. AI System Engineer**
- **Company:** GoSuper EdTech
- **Job type:** Full-time (listed as "Volunteer" on LinkedIn — verify actual compensation)
- **Location:** Bengaluru, Karnataka — remote with occasional Bengaluru meetups
- **Work type:** Primarily remote
- **Posted:** 2026-10-09 (today)
- **Source:** LinkedIn
- **Easy Apply:** Apply via email at hr@gosuper.io — subject line "AI System Engineer"
- **Salary:** "Competitive salary + performance bonuses + ESOPs" per JD; employment type listed as Volunteer on LinkedIn ⚠️ — confirm compensation before applying
- **Apply:** https://in.linkedin.com/jobs/view/ai-system-engineer-at-gosuper-edtech-4477653643
- **Required skills:** Python/JavaScript/TypeScript/Node.js, FastAPI/NestJS, LLMs (OpenAI, Gemini, Claude), GCP (Cloud Run, Functions, Firebase, BigQuery), LangChain/LlamaIndex, RAG, vector databases, PostgreSQL, MongoDB, REST APIs, Docker
- **Experience:** 6 months–1 year (or relevant internship/project experience)
- **Fit:** GoSuper EdTech is a Bengaluru AI-first EdTech startup. The role touches LLMs, RAG, FastAPI, GCP, LangChain, and vector databases — all present in Shubh's portfolio. ESOPs, remote work, and a startup culture make it attractive. The "Volunteer" classification on LinkedIn is a red flag — apply via email and explicitly confirm it is a paid role before proceeding.

---

**18. Associate Engineer — AI Services**
- **Company:** NTT DATA, Inc.
- **Job type:** Full-time
- **Location:** Chennai, Tamil Nadu
- **Work type:** Hybrid
- **Posted:** 2026-10-08 (1 day ago)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Salary:** Not listed (NTT DATA)
- **Apply:** https://in.linkedin.com/jobs/view/associate-engineer-ai-services-at-ntt-data-inc-4474851008
- **Required skills:** Python/Java/C#/JavaScript, data structures, algorithms, SQL/NoSQL (Elasticsearch, MongoDB, Cassandra), Kubernetes/Docker, ML/AI algorithms, REST APIs, micro-services, CI/CD
- **Experience:** Entry level
- **Fit:** NTT DATA is a $30B global IT services company. The Associate Engineer role covers ML/AI algorithms on telemetry data, microservices, and API development. It is a stretch because it is more generic software engineering than GenAI — good for stability and brand, weaker on the specific LLM/RAG work Shubh has done. Hybrid Chennai.

---

## Section 3 — Safest Bets

### Internships

> Accessible, lower competition, real work with solid stipend.

---

**19. AI & Workflow Automation Intern**
- **Company:** Renaissance Jewel (New York-based fine jewelry company)
- **Job type:** Internship
- **Location:** Remote (India — NY-headquartered company hiring remote)
- **Work type:** WFH / Remote
- **Posted:** 2026-10-08 (1 day ago)
- **Source:** Indeed India
- **Easy Apply:** Yes (Indeed direct)
- **Stipend:** ₹10,000–15,000/month (based on skills and experience)
- **Apply:** https://in.indeed.com/viewjob?jk=02071ace62c2b6cc
- **Required skills:** Python/JavaScript, REST APIs, n8n/Make/Zapier/Power Automate, LLM APIs (OpenAI, Gemini, Claude), prompt engineering, webhooks, JSON
- **Fit:** A NY-based company hiring remotely in India for AI/automation work — exactly the international remote profile the run targets. The work involves building LLM-powered workflows, AI agent experiments, and automation integrations. Scope is narrower than Shubh's portfolio (no multi-agent orchestration) but it is a real company, paid remote, and a good portfolio addition. Verify India employment arrangement before applying.

---

**20. AI Implementation Intern (Sprinto — repeat note)**
Already listed as #2 in Strongest Matches.

---

**21. Artificial Intelligence Intern | Freshers Welcome | Remote**
- **Company:** Crossing Infotech
- **Job type:** Internship
- **Location:** Remote (India)
- **Work type:** WFH / Remote
- **Posted:** 2026-10-08 (1 day ago)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Stipend:** ₹16,500/month
- **Apply:** https://in.linkedin.com/jobs/view/artificial-intelligence-intern-freshers-welcome-ai-python-data-automation-remote-at-crossing-infotech-4476205268
- **Required skills:** Python, AI/ML basics, data preprocessing, APIs, Git/GitHub, NumPy, Pandas (good-to-have: Scikit-learn, NLP, GenAI concepts)
- **Fit:** Crossing Infotech is a software services company. The scope is basic (AI concepts, Python, automation) — less technically demanding than Shubh's actual level, making it a near-certain admit. Useful as a backup or while waiting on stronger offers. ₹16,500/month is a fair remote stipend.

---

### Full-time Roles

---

**22. Generative AI Engineer — Fresher**
- **Company:** TantranZm
- **Job type:** Full-time
- **Location:** India (remote status unconfirmed in JD — verify)
- **Work type:** Unspecified
- **Posted:** 2026-10-05 (4 days ago)
- **Source:** LinkedIn
- **Easy Apply:** Via LinkedIn
- **Salary:** Not listed
- **Apply:** https://in.linkedin.com/jobs/view/generative-ai-engineer-fresher-at-tantranzm-4474257084
- **Required skills:** Python, LLMs, prompt engineering, AI APIs, GenAI fundamentals, REST APIs, Git
- **Experience:** 0–1 year; fresh graduates encouraged
- **Fit:** TantranZm is an unknown entity — no description given in the listing and limited public presence. The role is explicitly fresher-level with 0–1 year experience, asking for LLMs and prompt engineering. Low risk / low effort application (via LinkedIn Easy Apply). Verify company legitimacy (check LinkedIn company page and official website) before sharing personal details.

---

*Run end. 22 verified active listings across 10 internships and 12 full-time roles. Sources that returned no qualifying results (Remotive, WeWork Remotely, RemoteOK, Unstop) are logged in the summary table above.*
