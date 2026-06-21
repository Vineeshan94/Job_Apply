# Blocker Playbook

Use this when an application cannot be safely prepared end to end.

## Manual Review Required

Stop and ask Vineesha when a role asks for:

- Passwords, credentials, or security questions.
- DOB, SSN, passport, driver's license, payment, bank, or tax information.
- Legal attestations that require personal confirmation.
- Background check, drug screen, or identity verification consent.
- Citizenship, clearance, export-control, or government eligibility details not already confirmed.
- Long assessments, coding tests, video/audio responses, references, or portfolio artifacts.
- CAPTCHA, hCaptcha, reCAPTCHA, or anti-abuse pages.

## Allowed Recovery

The assistant may:

- Try a different official job URL.
- Switch between the two provided resumes.
- Paste resume text into a manual resume field.
- Draft a concise answer from the resume and job description.
- Record a blocker in `JOB_APPLICATION_TRACKER.xlsx`.

## Not Allowed

The assistant must not send recruiter outreach emails without explicit approval, bypass CAPTCHA, invent private facts, submit applications with hard-stop blockers, or store sensitive information.
