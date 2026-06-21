# Tracker Schema

`JOB_APPLICATION_TRACKER.xlsx` is the only tracker workbook.

## Sheets

- `Summary`: high-level counts and notes.
- `AI`: AI, ML, data science, data platform, LLM, and analytics roles.
- `SDE`: Java, full-stack, backend, cloud, platform, and software engineering roles.
- `Blockers`: roles needing Vineesha review or manual action.

## AI And SDE Columns

| Column | Meaning |
|---|---|
| Date Added | Date the role was added to the tracker. |
| Company | Company name. |
| Role | Job title. |
| Location | Job location or remote status. |
| Status | `Submitted`, `Gmail Draft Created`, `Prepared`, `Already Applied`, `Skipped`, or `Blocked`. |
| Source | LinkedIn, company site, Greenhouse, Workday, Lever, Indeed, referral, etc. |
| Job URL | Official job or application URL. |
| Resume Used | Java Full Stack resume or Generative AI resume. |
| Work Authorization | H4 EAD; sponsorship-needed questions default to No. |
| Draft Link / Notes | Gmail draft note, confirmation proof, cover letter note, or application note. |
| Next Action | What Vineesha should review or do next. |

## Blockers Columns

| Column | Meaning |
|---|---|
| Date Added | Date the blocker was recorded. |
| Company | Company name. |
| Role | Job title. |
| Blocker Type | CAPTCHA, private info, legal attestation, assessment, unavailable resume upload, account issue, duplicate, ineligible, other. |
| Details | Non-sensitive explanation. |
| Next Action | What Vineesha needs to review or complete. |
| Job URL | Official URL. |

## Privacy

Never store passwords, Gmail codes, tokens, API keys, SSN, DOB, passport, payment details, or private email content in the tracker.
