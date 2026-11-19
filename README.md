# Grant writing skills

Simulated reviewers and a writing coach for four funding programmes that matter to postdocs in Germany:

| Skill | Programme |
|---|---|
| [`erc-stg-reviewer`](skills/erc-stg-reviewer/SKILL.md) | ERC Starting Grant |
| [`dfg-sachbeihilfe-reviewer`](skills/dfg-sachbeihilfe-reviewer/SKILL.md) | DFG Sachbeihilfe (incl. Eigene Stelle) |
| [`dfg-emmy-noether-reviewer`](skills/dfg-emmy-noether-reviewer/SKILL.md) | DFG Emmy Noether Programme |
| [`humboldt-lynen-reviewer`](skills/humboldt-lynen-reviewer/SKILL.md) | Humboldt Foundation, Feodor Lynen Research Fellowship |
| [`grant-proposal-coach`](skills/grant-proposal-coach/SKILL.md) | Writing coach for all four programmes |

Each reviewer critiques **your own draft** the way a sceptical expert and a broader panel member would: top issues ranked by severity, strengths, the hardest unanswered question, and a likely outcome.

The coach helps you **write** the proposal. It interviews you one question at a time, generates a deep-research prompt for the novelty check, builds an outline on the funder's template with a page budget, and drafts each section from your answers only. Missing facts are marked `[?]`. It does not write a proposal from a topic alone. If you are looking for a research question or hypothesis, its **idea mode** maps current open questions in your field and applies creativity techniques to generate candidates — you choose and own the result. Plan 30–45 minutes for the interview (about 20–30 short questions).

## Use it

**Any plan (recommended start):** create a Project in ChatGPT or Claude, or a Notebook in Copilot. Paste the text from the [`paste-ready`](paste-ready/) folder into the instructions. Upload the funder's current call documents as files. Then upload your draft and ask for a review.

**As a skill:** download the skill folder and upload it where your plan supports skills:
- ChatGPT: Skills / Plugins (availability depends on plan and workspace settings)
- Claude: Settings → Capabilities → Skills (upload as ZIP)
- Microsoft 365 Copilot: custom skills via OneDrive (requires the full Copilot licence)

## How to use the coach

- **As a skill:** upload the whole `skills/grant-proposal-coach` folder (as a ZIP), including `references/`. The coach loads the reference file for your programme by itself.
- **In a Project or Notebook:** paste [`paste-ready/grant-proposal-coach.md`](paste-ready/grant-proposal-coach.md) into the instructions and upload the reference file for your programme (plus `ideation.md` for idea mode) from [`skills/grant-proposal-coach/references/`](skills/grant-proposal-coach/references/) as a Project file, ideally together with the funder's current call documents. Without a reference file the coach asks for one before it states any limits or rules.
- Start with "I want to write a proposal". Answer in your own words; short answers are fine. When the draft is finished, run the matching reviewer on it in a new chat.
- DFG requires you to disclose the use of generative AI in the proposal. ERC and Humboldt currently do not. The coach reminds you at the end.

## Important

- **Only for your own drafts.** ERC reviewers may not use AI to assess proposals; DFG and Humboldt reviewers only under strict confidentiality rules. Never put other people's proposals into these tools.
- **Your unpublished idea leaves your computer** when you use a cloud service. Switch off training, prefer institutional accounts, or describe the core idea in abstract terms.
- **Rules change every call.** The skills are built from the official documents as of November 2026 (see [sources.md](sources.md)). Upload the current documents; they override what the skill knows.
- **A simulation, not a verdict.** Built from official funder documentation, not insider experience. It does not replace your grant office or a colleague's read.

## Contributing

Corrections and improvements are welcome — open an issue or a pull request.

## Licence

[CC BY 4.0](LICENSE) — reuse and adapt freely, with attribution.
