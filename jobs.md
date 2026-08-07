# Internship Search — Run Log

**Last run:** 2026-08-07 00:47 UTC
**Candidate:** Shubh Bohra (3rd-year CS-Design, Dayananda Sagar College of Engineering)
**Status:** ⚠️ No results this run — see below

## What happened

This run could not fetch any live LinkedIn postings. Every Apify actor call
(`cheap_scraper/linkedin-job-scraper`, `valig/linkedin-jobs-scraper`, and
`apify/rag-web-browser` as a fallback) failed with the same error:

```
Monthly usage hard limit exceeded
```

This is an account-level Apify billing/usage cap, not an actor-specific or
query-specific issue — it blocks all scraping on this account until the cap
resets or is raised. No job data could be retrieved.

Separately, the Google Sheet deliverable ("Internship Search") could not be
created either: the Google Drive connector is installed on this account but
is not enabled for this session (`enabledInChat: false`), so no Sheets/Drive
tools were available to call.

## What was NOT done

Per the run's instructions, **no listings were fabricated**. Rather than pad
this file with invented postings, it's left empty of results for this run.

## Next steps

- Raise or reset the Apify monthly usage limit (check the Apify console
  billing page), then re-run the search.
- Enable the Google Drive connector for this session/project so the
  "Internship Search" Google Sheet can be created and kept in sync.

## Search criteria (for reference, unchanged run to run)

**Target roles:** AI Engineering Intern, Machine Learning Intern, Python
Developer Intern, Backend Engineering Intern, Generative AI Intern

**Locations:** Bengaluru (on-site/hybrid), Remote (India-based, extra weight
to international/foreign companies), Work From Home

**Filters:** Active postings (ideally ≤7 days old), legitimate product
companies / well-funded startups (Series B+) / YC-backed / strong
engineering culture preferred over generic recruiters, staffing agencies and
spammy/duplicate listings excluded, "intern" listings that actually require
years of professional experience excluded. LLM/RAG/voice-AI/backend-Python
roles weighted highest given the Tez Health and FloatChat AI resume evidence.

---

*Previous run archives, if any, are in `runs/`.*
