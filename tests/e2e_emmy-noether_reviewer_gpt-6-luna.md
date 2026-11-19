# Reviewer test: dfg-emmy-noether-reviewer on gpt-6-luna

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
## Scope and assumptions

I’m reviewing this as **sections 2.2–2.3 only**, not as a complete Emmy Noether proposal. The field, timeline, PhD institution, former supervisor and proposed host are supplied; I assume the missing scientific details may appear elsewhere, but they cannot be assessed here. I have not been provided the DFG forms; my knowledge refers to the 09/26 versions and may be outdated.

## Main weaknesses, ranked

### 1. The design does not yet show that angle and dielectric effects can be separated
You say the study will “vary twist angle and hBN thickness,” but give no angle/thickness ranges, condition matrix, device numbers, or analysis plan. “Same TMD crystal batches … where possible” is not a design: it leaves open whether angle and thickness will be confounded with batch, fabrication quality, or other device differences. Randomising measurement order helps with measurement drift; it does not resolve confounding in device fabrication.

**Why reviewers will care:** The central claim is an interaction—whether hBN thickness has less effect at small angles. If the conditions are unbalanced or the variables covary, the central hypothesis may not be testable, even with many measurements.

**Repair:** Specify a balanced, feasible angle × thickness design; define how many independently fabricated devices per condition you expect; state which device properties will be measured and controlled; and give the analysis that tests the interaction. Explain what result would count as evidence for or against it, including uncertainty and device-to-device variability.

### 2. “Spatial spreading” is not yet a clear measure of transport
The prediction that trapping will “restrict exciton travel even when lifetime increases” is plausible as a hypothesis, but the draft does not define the transport observable. Raw spread or travel distance can increase simply because excitons live longer. Without separating lifetime from mobility or diffusion, the predicted relationship may be hard to interpret.

**Why reviewers will care:** The transport result is one of the project’s two main tests, yet the proposal does not say what quantity is measured or how it distinguishes slower transport from longer survival.

**Repair:** Define the observable and analysis—for example, how spatial broadening will be measured over time and how lifetime, initial excitation profile, and instrument response enter the interpretation. State whether the prediction concerns a diffusion coefficient, a lifetime-normalised distance, or another quantity. Do not call it “transport” without specifying what the experiment actually identifies.

### 3. The mechanism objective rests on access and matching that remain unverified
“Time-resolved photoemission on matched devices” is presented as the route to mechanism, but the summary says both access and matched-device feasibility are unconfirmed. The fallback keeps the main comparison alive, which is good, but leaves a substantial part of years 4–6 conditional. The proposed interpretation—an angle-dependent localisation signature plus reduced spreading supports trapping, while strong thickness dependence without that signature favours screening—is also too simple as written. Mixed or ambiguous outcomes are likely possible.

**Why reviewers will care:** The proposal promises a mechanism study without establishing that its key method and sample protocol are practicable. Nor is it clear that the proposed observations distinguish the two mechanisms rather than merely correlate with them.

**Repair:** Establish access, technical feasibility and the meaning of “matched devices” before submission, with a concrete protocol and supporting evidence or a collaborator’s confirmed commitment. Specify what photoemission measures, its relevant resolution and sample requirements, and how those results discriminate among mechanisms. Predefine how mixed results will be interpreted. Give the optical fallback a specific, mechanistically informative question of its own—not only “replication” and “temperature-dependent measurements.”

### 4. The year-3 milestone sounds decisive but has no decision criteria
“Reproducible device series” and measurements that “test both predictions” are not operational milestones. There are no stated thresholds for device yield, reproducibility, data completeness or a result that would make the group change course.

**Why reviewers will care:** The 3+3 structure depends on a credible interim evaluation. At present, the year-3 language promises a “decisive test” without showing what makes the test decisive.

**Repair:** Set measurable year-3 deliverables: the condition coverage, minimum usable replication, quality criteria, analysis completed, and the specific comparison that determines whether years 4–6 pursue a trapping, screening, or mixed-mechanism account. Avoid promising a definitive mechanism if the first three years only establish trends.

### 5. The programme and requested resources are not yet connected tightly enough
The staffing is sketched, but the year-by-year sequence is thin. The requested cryogenic microscope is a dependency, yet its cost and operating needs are unresolved in the background. The postdoc’s role from year 2 is described broadly, while years 4–6 depend partly on access that is not secured.

**Why reviewers will care:** Reviewers need to see that the staff, equipment and milestones follow from a feasible work programme. This excerpt does not yet make that case, and the budget cannot be judged from it.

**Repair:** Give a concise schedule with dependencies, hand-offs and milestones. Justify the microscope and its operating costs against the measurements and staffing plan; state what happens if procurement or installation is delayed. Show that the optical core remains deliverable without photoemission, not merely that there is substitute work for the postdoc.

## What is working

- The hypotheses are explicit and falsifiable. In particular, “A strong thickness dependence at small angles would count against the hypothesis” is stronger than a generic promise to explore trends.
- You protect the core test from the uncertain photoemission component: the year-3 comparison does not depend on it.
- You acknowledge device variation and a negative result rather than presenting only a success scenario.

Keep these features, but make the tests and fallback more operational.

## What is missing from these sections

- Preliminary evidence is not shown here. The 2024 lifetime result and qualitative hBN pilot need to be cited and described with enough detail to show what they establish—and what they do not. The summary says the novelty check and three leadership papers still need verification; those are substantive gaps, not polishing tasks.
- No angle or thickness ranges, condition matrix, replication plan, quantitative analysis, or decision rules are given.
- The temperature-dependent fallback has no range, prediction, or explanation of how it separates the proposed mechanisms.
- The sections do not establish the applicant’s independence or readiness to lead. Your background—that you initiated the line at ETH, wrote the seed-grant proposal and built the stacking setup without your former supervisor’s involvement—could make a strong independence case, but it needs to be evidenced elsewhere in the proposal. Team leadership, supervision and teaching plans also need to appear somewhere in the application.
- Hamburg is the only proposed host, but the summary says cleanroom, practical and photoemission access need confirmation. The host’s specific contribution and the reason it is the right environment need to be made concrete elsewhere.
- Check formal eligibility urgently. With a PhD in September 2021, the time since doctorate is a material issue for a submission now; do not assume that the documented parental leave resolves it automatically. Confirm the applicable extension calculation with the DFG. The Columbia visit should be reported accurately as three months in 2023, and the international-experience appendix must make the overall case.
- If text generated by this AI interaction is used in the proposal, disclose the model, purpose and extent of use as required; ordinary grammar, style and translation assistance are exempt.

## How a reviewer is likely to read this

A specialist may find the question interesting and appreciate the explicit falsification logic, but will ask whether the proposed device comparison can identify the angle-by-dielectric interaction and whether the transport measurement separates mobility from lifetime. A broader review board member may see a promising independent line, based on the background you supplied, but these sections alone do not yet demonstrate a tightly designed six-year programme or make the requested resources assessable.

## Short verdict

**This part currently helps on hypothesis clarity and risk candour, but hurts on experimental identifiability and feasibility detail.** The core project could be persuasive; in this draft, reviewers cannot yet tell whether the central contrast will be cleanly testable, and the mechanism phase relies on access that is not secured.
