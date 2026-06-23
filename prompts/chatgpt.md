# ChatGPT (GPT-5 / 4o) — Job Description Decoder

GPT is fast and clean with explicit structure. This version asks for a short
narrative decode plus a compact JSON block you can save or feed into a tracker.

Paste everything below, then replace `[PASTE JOB DESCRIPTION]` with the full posting.

---

```
Act as a former B2B hiring manager and recruiter who reads job descriptions for
subtext, not surface. Be blunt and specific. Do not flatter me.

Decode the job description at the end. First give me a readable decode with these
sections, then a JSON block.

DECODE:
- TL;DR: in two sentences, what is the team actually missing and what will this
  person really do day to day?
- Seniority reality check: title inflated, deflated, or honest? Quote the phrases
  that prove it (scope, reporting line, budget, headcount).
- Comp & leverage: where is there room to negotiate? Flag "competitive salary,"
  a missing range, equity language, band compression.
- Red flags: scope creep, "wear many hats," reorg, backfill churn, vague metrics.
  Quote the phrase, then translate it.
- Position yourself: the 3 things to lead with to get screened IN.
- Questions to ask: 5 sharp ones that signal seniority.
- New headcount or backfill: your best read and why.

Then output:
```json
{
  "title_honesty": "inflated | deflated | honest",
  "real_seniority": "",
  "comp_leverage": "low | medium | high",
  "top_red_flag": "",
  "headcount_read": "new | backfill | unclear",
  "fit_score_if_marketer": "1-10",
  "lead_with": ["", "", ""]
}
```

JOB DESCRIPTION:
[PASTE JOB DESCRIPTION]
```
