# Job Description Decoder — Prompt Pack

> What is that B2B job posting *actually* telling you? Paste any job description into your LLM of choice and get the subtext: seniority reality, comp signals, red flags, and how to position yourself.

One battle-tested prompt, tuned for each major model. Free. Copy, paste, decode.

[![GitHub stars](https://img.shields.io/github/stars/JuliaMuller7777/llm-job-decoder?style=social)](https://github.com/JuliaMuller7777/llm-job-decoder/stargazers)
[![License: MIT](https://img.shields.io/badge/License-MIT-black.svg)](LICENSE)

---

## Why this exists

Job descriptions are written by committee and read like marketing copy. The real signal — what the team is actually missing, how senior the role really is, whether comp has room, what will get you screened out — is buried. This pack pulls it out.

It's a lighter, free cousin of the [Job Signals Report](https://b2bmarketcraft.com), which runs a full 12-signal decode on a single posting.

## Pick your model

| Model | Best for | File |
|-------|----------|------|
| ChatGPT (GPT-5 / 4o) | Fast, structured JSON output | [prompts/chatgpt.md](prompts/chatgpt.md) |
| Claude (Opus / Sonnet) | Nuance, long postings, reasoning | [prompts/claude.md](prompts/claude.md) |
| Gemini (2.5) | Paste a *screenshot* of the posting | [prompts/gemini.md](prompts/gemini.md) |
| Grok | Blunt take + live company/X context | [prompts/grok.md](prompts/grok.md) |
| DeepSeek | Deep reasoning, near-zero cost | [prompts/deepseek.md](prompts/deepseek.md) |
| Perplexity | Verifies company claims with sources | [prompts/perplexity.md](prompts/perplexity.md) |

## How to use

1. Open the file for your model.
2. Copy the prompt.
3. Paste it, then drop the full job description underneath where it says `[PASTE JOB DESCRIPTION]`.
4. Read the decode.

## What you get back

- **TL;DR** — what they actually want, in two sentences
- **Seniority reality check** — is the title inflated, deflated, or honest
- **Comp & leverage signals** — where there's room to negotiate
- **Red flags** — scope creep, reorg risk, "wear many hats" tells
- **Position yourself** — the 3 things to lead with
- **Questions to ask** — 5 that make you look sharp
- **New headcount or backfill?** — the single most useful read

## License

MIT — use it, fork it, remix it. A star helps others find it.

---

## Go deeper

- **Full decode:** the [Job Signals Report](https://b2bmarketcraft.com) runs the complete 12-signal analysis on a single posting.
- **Site:** [b2bmarketcraft.com](https://b2bmarketcraft.com)

Built by **B2B Marketcraft**. If this saved you time, a ⭐ helps the next person find it.
