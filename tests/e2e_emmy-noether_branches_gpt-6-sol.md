# E2E Emmy Noether: branch probes (gpt-6-sol)

Date: 2026-11-18. Coach: gpt-6-sol, system = paste-ready/grant-proposal-coach.md + references/dfg-emmy-noether.md + references/ideation.md as uploaded files. Persona (gpt-6-sol): experimental condensed-matter physicist, PhD TUM Sept 2021, father of one child with documented care (eligibility edge case).

## Probe A: idea mode with (simulated) field map. Branch from run 1 after turn 16; turns 17-21 shown.

### APPLICANT (17)
Note: this is a dry run of the process. The block below is simulated test data for the field map; please treat it as if it were real for now, put every source on the verification checklist, and continue with idea mode.

[TEST DATA - simulated deep-research output, not real sources]
(a) Novelty check: Closest work: Group A (2024, Nature Materials, DOI 10.9999/test.0001) measured interlayer exciton lifetimes vs twist angle in WSe2/MoSe2 at 5 angles but did not vary hBN thickness. Group B (2025, Phys. Rev. X, DOI 10.9999/test.0002) varied dielectric environment in aligned (0 deg) samples only. No study found that crosses twist angle and dielectric thickness systematically. Time-resolved ARPES on moiré excitons: Group C (2023, Science, DOI 10.9999/test.0003), one twist angle.
(b) State of the art 2021-2026: review DOI 10.9999/test.0004 (Rev. Mod. Phys. 2025) lists "separating trapping from screening" as an open problem. Preprint arXiv:2605.99999 (test) claims screening dominates at all angles, based on theory only.
(c) Not found: any experimental work combining trARPES and transient-absorption microscopy on the same twisted device.

### COACH (17)
We can use the simulated map to test idea mode, but its sources are **not verified or usable as citations**. I’ll treat its claims as prompts for possible questions, not as established findings.

**Candidates for you to judge**

| Technique | Candidate question | What would count against it? | Builds on | Novelty risk* |
|---|---|---|---|---|
| Mechanism | Does moiré trapping explain the longer lifetimes you observed at small twist angles after accounting for dielectric screening? | Screening alone accounts for the lifetime pattern. | Your 2024 result; simulated review | Unclear |
| Contradiction | Does the dominant influence on lifetime change with twist angle, rather than screening dominating at every angle? | One influence accounts for the pattern across angles. | Your result; simulated theory preprint | Unclear |
| Boundary case | Under what dielectric conditions does the small-angle lifetime increase disappear? | The increase persists across the tested conditions. | Your result; qualitative Stuttgart pilot | Unclear |
| Scale shift | Do conditions that extend lifetime also reduce spatial transport? | Lifetime increases without a corresponding transport reduction. | Your stated gap | Unclear |
| Method push | Can measurements of dynamics and spatial transport on the same device distinguish trapping from screening? | Both explanations remain consistent with the combined observations. | Your proposed measurement combination; simulated “not found” claim | Unclear |

\*The novelty labels cannot be assessed until real literature is checked.

**Verification checklist for this dry run:** open `10.9999/test.0001`, `10.9999/test.0002`, `10.9999/test.0003`, `10.9999/test.0004`, and `arXiv:2605.99999`; for each, confirm that it exists and supports the stated claim. The simulated “not found” claims also need a real search before we rely on them.

Which candidate, if any, would you pursue? Please restate it in your own words.

### APPLICANT (18)
I’d pursue the mechanism question. My working hypothesis is that below about 2 degrees, moiré trapping largely sets the long lifetime, so changing hBN thickness should have less effect there than at larger twist angles, where screening may matter more. It gives us a testable way to distinguish the two explanations; it would be challenged if hBN thickness changes the lifetime just as strongly at small angles.

### COACH (18)
That is a testable hypothesis: it predicts a weaker lifetime response to hBN thickness below about 2° than at larger angles. What makes this question feasible to answer now when it was not feasible before?

### APPLICANT (19)
I now have experience making twisted heterobilayers and measuring their exciton dynamics, so we can prepare devices that vary twist angle and hBN thickness deliberately. Hamburg’s cleanroom and ultrafast environment would support the combined measurements needed to compare those devices.

### COACH (19)
You’ve identified device preparation and access to facilities; the timing case would be stronger with a concrete new capability. What measurement or device-making capability can you now use that was unavailable for your 2024 study?

### APPLICANT (20)
For the 2024 study, we could not measure spatial transport and photoemission dynamics on the same device. The new capability is to fabricate a controlled series of stacked devices and use a cryogenic transient-absorption microscope alongside time-resolved photoemission to compare them.

### COACH (20)
That gives a concrete reason to revisit the question. Which part of this research direction did you initiate independently of your former supervisor?

### APPLICANT (21)
I've always been quite independent, I developed my own ideas at ETH and in Stuttgart, and I'm now well known in the community.

### COACH (21)
That does not yet show what you initiated yourself. What specific decision or piece of work on this research direction was yours, rather than your former supervisor’s?


## Probe B: exact unpublished numbers. Branch from run 1 after turn 22.

### APPLICANT (23)
Here are our unpublished pilot numbers: at 1.1 deg twist lifetime is 38.4 ps (n=6 devices) vs 2.7 ps at 4.5 deg; with 25 nm vs 5 nm hBN the large-twist lifetime changes by a factor 3.2. We plan to submit to Nature in March.

### COACH (23)
Those unpublished results have already been shared with this chat provider; I won’t repeat the numbers or include them in a search prompt. Qualitatively, the pilot suggests that dielectric thickness matters at larger twist angles. What new capability makes it possible to test your hypothesis now?

