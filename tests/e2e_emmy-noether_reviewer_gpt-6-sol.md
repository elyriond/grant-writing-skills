# Reviewer test: dfg-emmy-noether-reviewer on gpt-6-sol

## USER
Here is my own Emmy Noether draft (sections 2.2 and 2.3 only) plus my interview summary with background facts. Please review it critically.

=== INTERVIEW SUMMARY ===
### Problem and gap
You want to understand how twist angle and the dielectric environment affect the lifetime and transport of moiré-trapped interlayer excitons in twisted TMD heterobilayers. Your 2024 paper found longer lifetimes at small twist angles, but did not isolate moiré trapping from dielectric screening. The literature map and novelty check remain open [?].

### Central idea and hypotheses
You propose comparing devices across twist angles and hBN thicknesses. Your provisional hypothesis is that trapping dominates lifetime at small angles, so hBN thickness has less effect there than at larger angles; strong thickness dependence at small angles would count against it. You also predict that stronger trapping reduces spatial travel despite longer lifetime. You formulated these hypotheses during idea mode.

### Why now; why you
Your published lifetime result, stacking experience and a qualitative pilot indication about hBN thickness motivate the study. You initiated the twisted-heterobilayer line at ETH, wrote its internal seed-grant proposal and built the stacking setup. Your former PhD supervisor was not involved in that postdoctoral work. You identified three papers as evidence of continued leadership; their bibliographic details need verification [?].

### Objectives and work programme
The objectives are to test lifetime dependence, measure transport, and connect optical and photoemission measurements on matched devices. You would use verified device properties, common crystal batches, replication and randomised measurement order. By year 3, the group should have a reproducible series and a decisive test of the predicted contrast, including a negative result. Years 4–6 would investigate mechanisms and test whether conclusions hold across further batches.

### Methods, risks and fallbacks
Transient-absorption microscopy would measure lifetime and spatial spreading; time-resolved photoemission would probe exciton-related electronic states. Photoemission access and matched-device feasibility are unconfirmed [?]. Without it, the optical comparison and temperature-dependent measurements could still test the main contrast, with a weaker mechanism claim. If device yield is low, you would narrow the comparison to a well-controlled range.

### Host, team and career path
Hamburg is the sole proposed host. Cleanroom access, practical support and photoemission access need confirmation [?]. You propose two PhD roles from year 1 and a postdoc from year 2, with a defined optical-analysis role even if photoemission is unavailable. Your co-supervision and teaching experience support your plan to lead a group and teach at Hamburg.

### Data, approvals and resources
You plan to retain fabrication records, metadata, raw data and version-controlled code, then share publication-supporting material subject to host policy. You do not expect research-specific ethics approvals, but will check host safety requirements. You do not see sex, gender or other diversity factors affecting the experimental design. The cryogenic microscope would be **requested equipment**, not an existing facility; equipment and operating costs remain [?].


Corrections: Columbia visit was 3 months in 2023; TUM only a private backup, not a proposed host.
Background: PhD TUM Sept 2021 (supervisor Prof. Weber, monolayer coherent optics); postdoc ETH Zurich 2021-23; MPI Stuttgart since 2023; one child (May 2023), father, 14 months documented parental leave at 50%; host Universität Hamburg.


=== DRAFT ===
### 2.2 Objectives

This project will test how twist angle and the dielectric environment affect the lifetime and spatial transport of interlayer excitons in twisted TMD heterobilayers. Its central hypothesis is that moiré trapping dominates lifetime at small twist angles. If so, changing hBN thickness should have less effect on lifetime at small angles than at larger angles. A strong thickness dependence at small angles would count against the hypothesis.

The first objective is to measure lifetime across devices that vary in twist angle and hBN thickness. The second is to measure spatial spreading across the same conditions. I predict that stronger trapping at small angles will restrict exciton travel even when lifetime increases. Greater spreading under those conditions would challenge that prediction.

**By the end of year 3**, the group aims to have a reproducible device series and lifetime and transport measurements that test both predictions. The interim result will state whether the hypothesis survives, including if the findings are negative. This goal does not depend on photoemission access.

The third objective is to investigate the mechanism behind the measured trends. Transient-absorption microscopy will provide the core comparison. If access is secured, time-resolved photoemission on matched devices will add evidence from exciton-related electronic states. The mechanism claim will reflect what the available measurements can establish.


### 2.3 Work programme

**Years 1–3: test the lifetime and transport predictions.** I will establish a series of twisted TMD heterobilayer devices that varies twist angle and hBN thickness. Devices will use the same TMD crystal batches and stacking procedure where possible. We will verify twist angle and layer quality after fabrication, measure several devices per condition and randomise measurement order to reduce the risk that batch effects or drift appear as physical trends.

One PhD researcher will focus on fabrication and device characterisation. A second will develop cryogenic transient-absorption microscopy measurements and analyse lifetime and spatial spreading. The microscope is requested equipment, not an existing host facility. From year 2, a postdoctoral researcher will integrate results across devices and fabrication batches and develop temperature-dependent optical measurements.

We will compare how lifetime and spatial spreading change with twist angle and hBN thickness. A weak thickness dependence of lifetime at small angles, paired with reduced spreading, would support the proposed role of trapping. A strong thickness dependence at small angles or greater spreading where lifetimes increase would challenge the corresponding prediction. Temperature-dependent optical measurements may provide additional evidence of localisation, but will not by themselves establish the microscopic mechanism.

**The year-3 milestone** is a reproducible device series with lifetime and transport measurements that test these predictions. We will report whether the hypothesis survives the comparison, including if the result is negative. This milestone does not depend on access to time-resolved photoemission.

**Years 4–6: investigate mechanism and robustness.** We will extend the comparison across further device batches and examine how the factors associated with longer lifetimes relate to transport. If photoemission access and matched-device measurements are secured, the postdoctoral researcher will lead measurements of exciton-related electronic states and their dynamics. We will compare those results with optical lifetime and spatial-spreading measurements on matched devices. An angle-dependent localisation signature accompanied by reduced spreading would strengthen the trapping interpretation; a strong thickness dependence without that signature would favour a screening interpretation.

Photoemission access is not yet secured. If it is unavailable or delayed, the postdoctoral researcher will instead lead cross-device analysis, temperature-dependent optical measurements and replication across batches. The optical programme will still test the lifetime and transport predictions, but any claim about their microscopic mechanism will be narrower.

Device-to-device variation is a second risk. We will compare verified device properties rather than target fabrication values. If yield is too low for the planned range, we will narrow the angle and thickness comparison to devices with well-characterised interfaces, while retaining conditions that can test the predicted contrast.

We will store fabrication records, measurement metadata and raw data in the host’s approved system, with backups and version-controlled analysis code. Data and code supporting publications will be shared through a suitable repository, subject to host policy.



## REVIEWER
**Material reviewed:** Sections 2.2–2.3 of your own project description, using the interview summary as background. This is not a review of the CV, host justification, international-experience appendix or budget. No DFG forms were supplied; my understanding refers to the 09/26 versions and may be outdated.

## The five issues I would fix first

1. **Check eligibility before polishing this text.** Your September 2021 doctorate is more than five years old at the current date, against the usual four-year window. Your documented parental leave may change the calculation, but the summary does not establish the applicable extension. Confirm your submission-date eligibility with the DFG Head Office and present the documentation clearly. This is an administrative risk, not a criticism of the science.

2. **The proposed comparison does not yet isolate trapping from screening.** “Changing hBN thickness should have less effect on lifetime at small angles” is testable, but a weak effect would not uniquely identify moiré trapping. Twist angle and device construction could change other determinants of lifetime and transport. Specify which competing explanations the measurements can distinguish, which device properties you will control or measure, and which result would make you abandon the trapping interpretation. Do not promise a mechanism inference that the optical comparison cannot deliver.

3. **The year-3 test is insufficiently specified to be decisive.** “Several devices per condition,” “small angles,” “weak thickness dependence” and “reproducible device series” leave reviewers unable to judge feasibility or interpretability. Define the angle and thickness contrasts, replication across batches, primary lifetime and spreading measures, and the analysis that will test whether the thickness effect differs by angle. Explain how spatial spreading will be separated from the effects of differing lifetimes. A negative result is valuable only if the comparison was capable of detecting the predicted contrast.

4. **The novelty case is still open.** Your summary explicitly marks the literature map and novelty check as unfinished. The 2024 lifetime result is a credible starting point, but these sections do not yet say precisely what existing twist-angle, dielectric-environment and transport studies leave unresolved. A specialist could read this as a careful extension of your paper rather than a distinct six-year Emmy Noether Group programme. Verify the literature and state the specific advance without overstating priority.

5. **Resources and the second three-year phase remain conditional.** The year-1 optical role depends on a **requested cryogenic microscope**; its procurement, commissioning, specifications and costs are not explained here. Photoemission access and matched-device feasibility are also unconfirmed, while years 4–6 otherwise read largely as more batches and temperature measurements. Give each dependency a decision date and workable alternative, and derive the equipment, staff and operating requests from those tasks. The host justification must establish what Hamburg will actually provide; TUM, as a private backup, should not be presented as a proposed host.

## What is working

- The lifetime and transport predictions are explicit, and you say what observations would challenge each. Keep that discipline when defining the analysis.
- The year-3 milestone does **not** depend on photoemission. That is a sound separation between the core test and a possible mechanism study.
- The account of initiating the ETH line, obtaining seed funding and building the setup could make a strong independence case—**if** the CV and publications document your own contributions and distinguish this line from Prof. Weber’s monolayer coherent-optics programme.

**The hardest unanswered question:** *If you observe longer lifetimes and less spreading at small angles, what evidence in the funded core experiment establishes that moiré trapping, rather than another angle-dependent change combined with screening, caused that pattern?*

**The person:** The background suggests scientific independence from your PhD supervisor, but these sections cannot establish publication quality, leadership, supervision or professorship prospects. Your ETH period supports an international-experience case; make it explicit in the separate appendix rather than relying on the three-month Columbia visit. Confirm eligibility first.

**The project:** A focused, falsifiable core is present. Its discriminatory power and feasibility are not yet demonstrated; the conditional photoemission component cannot carry the mechanism claim. The budget and Hamburg working conditions cannot be judged from these sections.

**Likely reading of this part:** **Hurts more than it helps in its present form.** A specialist would welcome the falsifiable contrast but press hard on confounding and measurement design. A broader review board would see a plausible year-3 core, yet lack a convincing account of why it requires this team and equipment and what the group will establish by year 6. I cannot give a responsible fund/do-not-fund recommendation on two sections alone.

One submission check: if generative AI produced proposal text or images—including text taken from this review—the proposal must disclose the model, purpose and extent of use; grammar, style and translation tools are exempt. Your notes are labelled an “interview summary,” but whether a personal presentation is part of the current procedure could not be confirmed. Check with the DFG Head Office; interview practice is an option if relevant.
