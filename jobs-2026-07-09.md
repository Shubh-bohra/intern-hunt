# Internship Search — 2026-07-09

Automated LinkedIn sweep for Shubh Bohra (3rd-year CS-Design, Dayananda Sagar College of Engineering) targeting AI Engineering / ML / Python Backend / Generative AI internships in Bengaluru (on-site/hybrid) or remote-from-India.

**Source:** Apify `cheap_scraper/linkedin-job-scraper`, run against LinkedIn's own job-search URLs with `f_JT=I` (internship) + `f_TPR=r604800` (posted in the last 7 days), across 18 keyword variants ("AI Engineering Intern", "Machine Learning Intern", "LLM Intern", "RAG Intern", "Generative AI Intern", "Voice AI Intern", "Backend Developer Intern", etc.) and two location/work-type slices (Bengaluru on-site/hybrid; India-wide remote). ~1,120 unique raw postings were pulled and deduplicated; only 18 were tagged as genuine internships (title contains "intern", or LinkedIn's own `contractType`/`experienceLevel` = Internship) after LinkedIn's own internship filter, which is unreliable and returns mostly full-time/mid-senior roles by default. After excluding staffing agencies (WEBBOOST SOLUTION IT SERVICES), an internship-aggregator posting the same listing twice (internmo), a generic non-Bengaluru/non-remote posting (Milestone Technologies, Hyderabad), an "Expression of Interest" pipeline form rather than an open req (MRI Software), and out-of-target-city on-site roles with no confirmed remote option (Faclon Labs – Mumbai, Improva – Coimbatore), **9 real, active listings** survived.

This is a thin market for this exact intersection (AI/backend intern, Bengaluru or India-remote, last 7 days) — 9 is the honest count, not a padded one.

---

## Strongest Matches

| Match Score | Job Title | Company | Location | Work Type | Posted | Key Skills Match | Why This Fits | Application Link | Easy Apply | Notes/Concerns |
|---|---|---|---|---|---|---|---|---|---|---|
| 95 | Engineering Intern – Agentic AI | EpicureAI Labs | Bengaluru | On-site/Hybrid | 2026-07-09 | Multi-agent LLM systems, RAG over domain data, prompt engineering + eval, agent guardrails | Near-exact overlap with the FloatChat AI RAG pipeline and the dual-intent routing / LLM-skip logic built for Dr. Tez — this is production agent-pipeline work, not toy demos | [LinkedIn](https://in.linkedin.com/jobs/view/engineering-intern-agentic-ai-at-epicureai-labs-4437359406) | Yes | DPIIT-recognized startup but very small team (2–10 employees) — verify funding/stability before committing |
| 88 | AI Engineer (Intern) | Veena | Remote, India | Remote | 2026-07-05 | ML for audio pattern recognition, intelligent recommendations, real-time audio production tooling | Veena builds an AI-powered DAW — the audio-ML and real-time processing work parallels the sentence-level TTS streaming pipeline (Sarvam AI) that cut Time-to-First-Audio by 83% at Tez Health | [LinkedIn](https://in.linkedin.com/jobs/view/ai-engineer-at-veena-4436057030) | Yes | Very small team (2–10 employees); music/creative-tech domain rather than enterprise backend — confirm stipend and stage before applying |
| 82 | AI & Data Analytics Intern | ALP (Computational Finance, AI and Data Engineering) | Bengaluru | On-site (WFO) | 2026-07-07 | LLMs (OpenAI, Azure OpenAI, Claude, Gemini), RAG solutions, Python & SQL scripting, GenAI/ML concepts | Direct match to the hybrid SQL + vector RAG pipeline built for FloatChat AI, plus multi-LLM fallback experience (Groq/Ollama) transfers directly to this multi-provider LLM stack | [LinkedIn](https://in.linkedin.com/jobs/view/ai-data-analytics-intern-at-alp-computational-finance-ai-and-data-engineering-4434529453) | Yes | Boutique AI-for-audit consultancy (11–50 employees) — role blends Power BI/dashboarding with AI, slightly broader than pure engineering |
| 80 | Frappe Developer Intern | DeHaat | Bengaluru | On-site | 2026-07-08 | Python server scripts, API integrations, workflow/dashboard development on the Frappe/ERPNext framework | Well-funded agritech product company (1,001–5,000 employees) — strong Python backend fit even though the role isn't AI-specific, good resume-building brand next to the Tez Health FastAPI work | [LinkedIn](https://in.linkedin.com/jobs/view/frappe-intern-at-dehaat-4437037119) | Yes | Not an AI/LLM role — pure Python backend/ERP customization work |

## Stretch Opportunities

| Match Score | Job Title | Company | Location | Work Type | Posted | Key Skills Match | Why This Fits | Application Link | Easy Apply | Notes/Concerns |
|---|---|---|---|---|---|---|---|---|---|---|
| 78 | Language Research Intern (Indic Languages) | Chariot | Delhi | On-site | 2026-07-07 | Building/evaluating language datasets and test sets for Indic-language AI models, at a frontier lab selected under the IndiaAI Mission | Exceptional domain overlap with the 5-Indian-language dual-intent voice/text chatbot built at Tez Health — but it's on-site in Delhi with no remote option confirmed, outside the target location set | [LinkedIn](https://in.linkedin.com/jobs/view/language-research-intern-indic-languages-at-chariot-4436529463) | Yes | **Location mismatch (Delhi, on-site)** — only worth pursuing if open to relocating; otherwise the strongest domain fit in this whole list |
| 55 | AI Builder Intern | MyGenie | Delhi | On-site | 2026-07-07 | Building AI agents/tools with agentic coding tools (Claude Code/Codex) for internal PM & finance tooling | Agentic-coding culture is a reasonable stretch from the LLM/RAG background, but the product domain (construction-tech PM tooling) has no overlap with resume experience | [LinkedIn](https://in.linkedin.com/jobs/view/ai-builder-intern-at-mygenie-4436801202) | Yes | **Location mismatch (Delhi, on-site)**; construction-tech domain is unrelated to AI/RAG background — lower priority stretch |

## Safest Bets

| Match Score | Job Title | Company | Location | Work Type | Posted | Key Skills Match | Why This Fits | Application Link | Easy Apply | Notes/Concerns |
|---|---|---|---|---|---|---|---|---|---|---|
| 65 | Advanced Research Intern – Artificial Intelligence | GE Vernova | Bengaluru | On-site | 2026-07-08 | Machine learning research within a 400+ researcher Advanced Research org | Large, legitimate MNC brand for the resume; AI/ML research angle is relevant even if more academic than product-shipping | [LinkedIn](https://in.linkedin.com/jobs/view/ge-vernova-research-intern-at-ge-vernova-4438194766) | No (external) | Formal corporate ATS pipeline, likely competitive; research-heavy rather than product-engineering |
| 60 | SDET Intern | Automation Anywhere | Bengaluru | On-site | 2026-07-08 | Test automation for an Agentic Process Automation (APA) platform built on a Process Reasoning Engine + AI agents | Well-funded RPA/agentic-automation unicorn — strong brand and adjacent to the agent/LLM space, but the role itself is QA/test automation, not core dev | [LinkedIn](https://in.linkedin.com/jobs/view/sdet-intern-at-automation-anywhere-4438189538) | No (external) | Role is testing-focused (SDET), not backend/AI engineering — lower core-skill overlap despite the strong company |
| 55 | Intern (Next-Gen Visualization Platform) | GE HealthCare | Bengaluru | On-site | 2026-07-07 | Generic software/hardware development intern role, no explicit tech stack listed | Large, legitimate MedTech MNC for resume credibility; safe, low-risk brand-name internship | [LinkedIn](https://in.linkedin.com/jobs/view/intern-at-ge-healthcare-4437857603) | No (external) | Two near-identical postings found (same JD) — apply to one; JD gives no explicit Python/AI stack, lowest specificity of the list |

---

## Excluded (for transparency)

- **internmo** – "Artificial Intelligence Intern" posted twice, identical listing — reads as an internship-aggregator/marketplace account rather than a hiring company
- **WEBBOOST SOLUTION IT SERVICES** – "Data Science Intern" — generic IT-services/staffing naming pattern, excluded per staffing-agency rule
- **Milestone Technologies** – generic "Intern" title, Hyderabad (outside target locations), managed-services firm
- **MRI Software** – "AI Developer – Expression of Interest" — this is a talent-pipeline signup form, not an open requisition
- **Faclon Labs** (Mumbai) / **Improva** (Coimbatore) – on-site in cities outside the target set with no confirmed remote option

## Known limitations of this run

- **Google Sheet was not created.** The Google Drive/Sheets connector is installed on this account but not enabled for this session (`enabledInChat: false`), and no dedicated Sheets tool was available. Enable the Drive connector in Claude settings to let future runs push directly to the "Internship Search" sheet; until then this markdown file is the system of record.
- LinkedIn's own internship filter (`f_JT=I`) is unreliable — most raw search results were full-time/mid-senior roles despite the filter, so results here were confirmed by title/contract-type/experience-level text matching, not by the filter alone.
