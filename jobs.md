# Internship Search — 2026-08-15 00:47 UTC

**Status: Run blocked — no listings collected this run.**

This was an automated run of the internship search for Shubh Bohra (target roles: AI Engineering / Machine Learning / Python Developer / Backend Engineering / Generative AI Intern; locations: Bengaluru on-site/hybrid, Remote-India, WFH).

## What happened

1. **Apify LinkedIn scraper unavailable.** Both `cheap_scraper/linkedin-job-scraper` and `curious_coder/linkedin-jobs-scraper` returned:
   > `Monthly usage hard limit exceeded`

   This is an account-level Apify usage cap, not an actor-specific issue (confirmed by testing two different actors). No search could be executed, so **no job data was retrieved this run**.

2. **Google Sheet not updated.** The Google Drive connector is installed on this account but is not enabled for this session/chat (`enabledInChat: false`), so the "Internship Search" Google Sheet could not be created or updated. No spreadsheet tool call was made.

## Per the run's own rules

The instructions for this task explicitly say not to fabricate listings and to say so plainly if the scraper returns nothing usable. In line with that: **no jobs are listed below.** Nothing here should be read as "zero matching internships exist" — it means the search could not run.

## To unblock the next run

- Raise or reset the Apify account's monthly usage limit (Apify console → billing/usage limits), or reduce `maxItems` well below the current cap if the limit is close.
- Enable the **Google Drive** connector for this chat/session so the "Internship Search" Google Sheet can be created/updated.

Once both are resolved, the next scheduled run will attempt the full search again and append a new dated section here.

---

*Previous runs: none — this is the first run recorded in this file.*
