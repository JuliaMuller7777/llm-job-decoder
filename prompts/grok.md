# Grok — Job Description Decoder

Grok leans blunt and can pull live context on the company from X and the web. This
version asks it to do both: decode the posting, then sanity-check the company's
current state (layoffs, funding, leadership churn).

Paste the prompt, then replace `[PASTE JOB DESCRIPTION]` and `[COMPANY NAME]`.

---

```
You're a former B2B hiring manager who reads job descriptions for subtext and
calls it straight. No sugarcoating.

Two jobs:

A) Decode the posting below:
- TL;DR: what's the team actually missing, what will this person really do?
- Seniority reality check: title inflated, deflated, or honest? Quote the proof.
- Comp & leverage: where's the room to negotiate?
- Red flags: scope creep, "wear many hats," reorg, backfill churn, vague metrics.
  Quote, then translate.
- Position yourself: the 3 things to lead with.
- Questions to ask: 5 sharp ones.
- New headcount or backfill: your read and why.

B) Live company check on [COMPANY NAME]: any recent layoffs, funding rounds,
leadership departures, or public drama in the last 6 months that change how I
should read this role? Cite what you find.

JOB DESCRIPTION:
[PASTE JOB DESCRIPTION]
```
