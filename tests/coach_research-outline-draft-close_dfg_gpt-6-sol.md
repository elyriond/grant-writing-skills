# Coach test: d_research

Model: gpt-6-sol  
System prompt: paste-ready core + references/dfg-sachbeihilfe.md. Checks: abstract research prompt, verification checklist, outline with page budget, draft with [?], closing checklist. The references in turn 2 are placeholders, not real papers.

## Turn 1: user

Programme: DFG Sachbeihilfe with Eigene Stelle (fit check done: doctorate March 2023, temporary university contract, first proposal, 3 years). We already did the interview in another chat; here is the summary, which I confirm as correct:

- Problem and gap: lab studies expose single soil species to pristine microplastic beads. It is unknown whether microplastic fibres shift energy flow between the fungal and the bacterial channel of soil food webs under field conditions.
- Central hypothesis (mine): polyester fibres loosen soil aggregates, which favours bacteria over fungi, so energy flow shifts towards the bacterial channel and fungal-feeding springtails and mites decline.
- What would prove me wrong: no change in the fungal-to-bacterial channel ratio at field-realistic fibre concentrations.
- Why me: PhD on stable-isotope tracing in soil food webs; two first-author papers without my supervisor.
- Core trick (UNPUBLISHED, confidential): I trace fibre-derived carbon into consumers by using polyester fibres made from a 13C-depleted polymer that my collaborator Dr. Okafor synthesises, combined with compound-specific isotope analysis of amino acids. Unpublished pilot data from my current lab in Göttingen show a 30% drop in the fungal channel.
- Objectives: O1 quantify the channel shift in field mesocosms; O2 identify the mechanism (aggregate structure vs. direct toxicity); O3 test recovery after fibre input stops.
- Methods: field mesocosms at the university's experimental field site, three fibre concentrations, isotope tracing, soil structure via X-ray CT.
- Risks: tracer signal too weak in the field -> fallback fatty-acid biomarkers.
- Resources: my own position, one doctoral researcher, isotope analyses.

Please go on to the research step.

## Turn 1: coach

I’m using the supplied DFG Sachbeihilfe reference, which cites DFG forms dated 09/26; current call documents would take precedence.

Here is a prompt for a deep-research tool. It leaves out your tracer design, pilot result, collaborator and location:

> **Novelty and literature check.** In soil ecology, has anyone tested whether polyester microplastic fibres alter the balance of energy flow through fungal and bacterial channels of soil food webs under field or field-mesocosm conditions? The proposed general approach is to compare fibre exposures in field mesocosms, measure soil structure, and assess food-web responses.
>
> Search work published in the **last five years**. Identify the closest studies, including work on soil aggregates, fungal and bacterial pathways, springtails and mites, and responses after fibre input stops. For each study, give the authors, year, DOI or stable URL, study setting, what was measured, and what the results actually show. Distinguish measured energy flow from indirect indicators of it.
>
> Assess whether the question has already been answered: **who did it, and how close was their design?** State whether each finding supports the proposed gap, narrows it, or closes it. Flag credible alternative explanations. Do not infer causation from correlations. Use only sources with a DOI or URL; write **“not found”** where you cannot verify a source or finding.

When the results return, we’ll check each reference against its DOI or URL before using it. **Does this prompt reveal too much of your unpublished work?**

## Turn 2: user

The prompt is fine. Here is what the deep-research tool returned (shortened; note for the test transcript: these are placeholder references, not real papers):

1. Study A (2022), DOI 10.0000/placeholder-a: lab microcosms, polyester fibres reduced water-stable aggregates; fungal biomass (PLFA) dropped; no fauna measured.
2. Study B (2024), DOI 10.0000/placeholder-b: field plots with polyethylene film fragments, nematode community shifted towards bacterial feeders; fibres not tested; no energy-flow measurement.
3. Study C (2023), DOI 10.0000/placeholder-c: review, states that food-web-level field studies with fibres are missing.
4. Energy-flux study with fibres in the field: not found.

Please summarise, and then give me the outline.

## Turn 2: coach

### Research check

These are **placeholder references, not verified papers**. They cannot support claims in the proposal. Provisionally, the reported findings map to your gap as follows:

| Item | Relation to the gap |
|---|---|
| Study A | **Narrows it:** reports effects of polyester fibres on aggregates and fungal biomass, but not field food-web energy flow. |
| Study B | **Narrows it:** reports a field shift in feeders, but tests film fragments rather than fibres and does not measure energy flow. |
| Study C | **Would support it** if its review and claim are verified. |
| Field energy-flux study with fibres | **Not found by this search.** That is not proof that none exists. |

Nothing in this *unverified* set shows that your question has already been answered. Before using any finding, open each DOI, confirm that the paper exists, and check that it says what the research tool claims. **Verification checklist:** Study A ☐; Study B ☐; Study C ☐. The placeholder DOIs must be replaced with real, checked sources or omitted.

### Proposed outline

Using the supplied DFG Sachbeihilfe reference (forms dated 09/26), the project description allows **25 pages: at most 17 for sections 1–3 and 8 from section 4 onwards**. The allocations below are a planning split, not DFG rules.

| Template section | Pages | Your material and what remains open |
|---|---:|---|
| **1. Starting point: state of the art and preliminary work** | 5 | Gap; your isotope-tracing experience and independent papers; pilot result, with its provenance made clear. **[?]** Verified literature, pilot methods and uncertainty, precise account of your contribution. |
| **2.1 Anticipated total duration** | 0.5 | Three years. |
| **2.2 Objectives** | 1.5 | O1 channel shift; O2 aggregate structure versus direct toxicity; O3 recovery. **[?]** A distinct working hypothesis and decisive outcome for each objective. |
| **2.3 Work programme, methods and schedule** | 6 | Field mesocosms, three concentrations, isotope tracing, X-ray CT; weak-signal risk and biomarker fallback. **[?]** Concentrations and controls, sampling and analysis plan, how O2 separates mechanisms, recovery design, work-package schedule, and each researcher’s tasks. |
| **2.4 Handling of research data** | 1 | **[?]** Data types, storage, documentation and access arrangements. |
| **2.5 Relevance of sex, gender and/or diversity** | 1 | **[?]** Whether and how these dimensions matter to the *research content*. |
| **3. Project- and subject-related publications** | 2 | Your two first-author papers and only verified works cited in sections 1–2. **[?]** Full, checked citations. |
| **4. Supplementary information** | 3 | First-time proposal; temporary university employment; field-site environment. **[?]** Ethics and other applicable declarations, project group, partners, recent collaborators, equipment and other submissions. |
| **5. Requested modules/funds** | 5 | Own position, doctoral researcher, isotope analyses. **[?]** Itemised costs and justification tied to work-package tasks; Eigene Stelle employer statement. |

**Total: 17 + 8 = 25 pages.** The reference also lists German and English summaries and a CV (form 53.200) as required materials; they are not allocated pages in this project-description split.

Do you approve this outline, or what should change before we draft section 1?

## Turn 3: user

Approved. Please draft section 2.2 Objectives now, in English.

## Turn 3: coach

## 2.2 Objectives

The project will test whether polyester microplastic fibres shift energy flow from the fungal to the bacterial channel of soil food webs under field conditions. My working hypothesis is that fibres loosen soil aggregates, favouring bacteria over fungi and reducing fungal-feeding springtails and mites. A finding of no change in the fungal-to-bacterial channel ratio at field-realistic fibre concentrations would contradict the predicted shift.

**Objective 1** is to quantify the fungal-to-bacterial channel ratio across three fibre concentrations in field mesocosms, alongside responses of fungal-feeding springtails and mites.

**Objective 2** is to determine whether changes in aggregate structure, rather than direct toxicity, account for any shift in the channel ratio. The working hypothesis and the comparison that will distinguish these mechanisms remain **[?]**.

**Objective 3** is to test whether the channel ratio recovers after fibre input stops. The predicted course of recovery and the criterion for calling it recovery remain **[?]**.

**Open points:** O2’s working hypothesis and distinguishing comparison; O3’s working hypothesis and recovery criterion; the three concentrations and their basis for being field-realistic.

If you share one or two samples of your own writing, I can adjust the style to match. What would distinguish an effect of aggregate structure from direct toxicity in your O2 design?

## Turn 4: user

Good. Assume for the test that all other sections are drafted the same way. What do I have to do before I submit?

## Turn 4: coach

Before submission, work through this checklist:

- **Resolve every `[?]`.** In section 2.2, this includes O2’s distinguishing test, O3’s recovery criterion, and the basis for calling the concentrations field-realistic. Check the other sections the same way. You must be able to defend every claim and choice.
- **Verify every reference.** Open each DOI or URL and confirm that the source exists and supports the precise claim. The placeholder Studies A–C cannot be cited.
- **Check the work programme against the request.** Make sure the schedule, each person’s tasks, isotope analyses and other requested costs follow from the proposed work. Confirm data handling and the required statement on sex, gender and/or diversity in the research content.
- **Check length in the official template.** The project description is limited to **25 pages**, with **at most 17 pages for sections 1–3** and **8 pages from section 4 onwards**. I cannot reliably count pages in your final formatted document; check the exported submission file.
- **Complete the accompanying materials.** The supplied reference lists summaries in German and English and a CV on form 53.200 (maximum four pages). For **Eigene Stelle**, obtain the employer statement (41.027). Check the current DFG forms for any changes before submission.
- **Disclose generative-AI use.** The supplied reference requires disclosure of the model, purpose and extent when AI drafted text. For example: “I used ChatGPT [insert exact model, if known] to help structure the proposal and draft and edit sections from my own research inputs. I reviewed and revised the text and am responsible for its scientific content.” Confirm the appropriate placement with the DFG; the reference prescribes no section.

Finally, seek a critical read of the complete draft using **`dfg-sachbeihilfe-reviewer`**, ideally in a fresh chat.
