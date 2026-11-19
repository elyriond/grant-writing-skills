# E2E Emmy Noether: full coach flow (gpt-6-sol)

Date: 2026-11-18. Coach: gpt-6-sol, system = paste-ready/grant-proposal-coach.md + references/dfg-emmy-noether.md + references/ideation.md as uploaded files. Persona (gpt-6-sol): experimental condensed-matter physicist, PhD TUM Sept 2021, father of one child with documented care (eligibility edge case).

Splices: turns 1-46 from run 1. Run 1 stalled after the coach rejected labelled test data (see e2e_emmy-noether_run1-stall_gpt-6-sol.md). From turn 47 the applicant message adds a 'dry run, treat as real' note (resumed run 2). Turn 50 onward is a branch (run 3) asking for 2.3 after 2.2 was approved. Research results are SIMULATED TEST DATA with fake DOIs 10.9999/test.*.

### APPLICANT (1)
Hi, I want to write an Emmy Noether proposal.

### COACH (1)
We’ll work through about 20–30 short questions over 30–45 minutes, then check the research, agree an outline and draft one section at a time; say “later” to skip a question.

Everything typed here reaches the provider of this chat. Share unpublished ideas and results only with training switched off or through an institutional account; otherwise describe them qualitatively, without numbers or the core trick.

Using the uploaded Emmy Noether reference (DFG forms, 09/26): in what month and year did you receive your doctorate?

### APPLICANT (2)
September 2021.

### COACH (2)
September 2021 puts you beyond the programme’s usual four-year window, so we should check whether an extension applies. Do you have children whose care could extend your eligibility window?

### APPLICANT (3)
Yes. My son was born in May 2023. I took 14 months of parental leave from October 2023 to November 2024 and worked 50% during that period. I have the Elterngeld documents and an employer confirmation of care.

### COACH (3)
Your documents may support a childcare extension, but parental leave does not automatically add 14 months under the rules in the uploaded reference. Which extension provision applies to you: the one for women, or the one for men with documented care?

### APPLICANT (4)
I’m the father, so the provision for men with documented care applies.

### COACH (4)
The uploaded reference allows up to two years per child for men with proof of care, so your documents may keep you within the window; the DFG must confirm how it applies to your dates. How much postdoctoral research experience have you accumulated since September 2021, excluding any time you were fully away from research?

### APPLICANT (5)
I’ve been in postdoctoral research continuously since October 2021, with no period fully away from research. I worked 50% for 14 months during parental leave, so that comes to roughly four and a half years of full-time-equivalent research experience as of now.

### COACH (5)
That appears to meet the usual two-year postdoctoral experience expectation. What substantial research experience have you gained outside Germany?

### APPLICANT (6)
I was a postdoc at ETH Zurich from October 2021 to September 2023. I also spent three months at Columbia University in New York in 2023 learning heterostructure stacking.

### COACH (6)
Your ETH appointment and Columbia stay give us concrete international experience to document. At which university did you earn your doctorate?

### APPLICANT (7)
Technical University of Munich (TUM).

### COACH (7)
Which institution in Germany would host your Emmy Noether Group?

### APPLICANT (8)
My planned host is Universität Hamburg. I’m also considering TUM as a backup because my wife works in Munich.

### COACH (8)
Hamburg avoids the special justification needed to return to your doctoral university; TUM would need that justification if you name it as a host. Have you completed a habilitation or an equivalent qualification?

### APPLICANT (9)
No, I have not completed a habilitation or an equivalent qualification.

### COACH (9)
Have you held a junior professorship that received a positive evaluation?

### APPLICANT (10)
No, I have never held a junior professorship.

### COACH (10)
Have you led a research group funded through a programme comparable to Emmy Noether?

### APPLICANT (11)
No, I have not led a group funded through a comparable programme.

### COACH (11)
That removes another listed exclusion. Is your career goal to lead an independent group and qualify for a professorship within the six-year Emmy Noether period?

### APPLICANT (12)
Yes. I want to establish an independent group and be competitive for a professorship within the six-year period.

### COACH (12)
Your stated goal fits the programme. What specific research problem would your group tackle?

### APPLICANT (13)
I want to understand how twist angle and the dielectric environment control the lifetime and transport of moiré-trapped interlayer excitons in twisted TMD heterobilayers. I would combine time-resolved photoemission with transient-absorption microscopy to study both the exciton dynamics and their spatial transport.

### COACH (13)
That gives us a defined system and two ways to probe it. What exactly remains unknown about how twist angle or the dielectric environment affects exciton lifetime and transport?

### APPLICANT (14)
We do not yet know how much of the change in lifetime comes from moiré trapping and how much comes from dielectric screening. It is also unclear whether the same factors that prolong an exciton’s lifetime restrict how far it can travel.

### COACH (14)
That separates two possible causes of longer lifetimes and identifies a possible trade-off with transport. What is your working hypothesis about how trapping and screening affect lifetime and transport?

### APPLICANT (15)
Honestly I know the phenomenon I want to study but I struggle to phrase a sharp hypothesis. Can you help me find one?

### COACH (15)
Yes. We can use idea mode to develop testable candidates, then you choose and put the hypothesis in your own words. Which of your published results is most relevant to this problem?

### APPLICANT (16)
My 2024 Nature Physics paper on twisted WSe2/MoSe2 is the closest: we observed unexpectedly long interlayer-exciton lifetimes at small twist angles. There’s been debate about whether moiré trapping or dielectric screening dominates those lifetimes, and a Stuttgart pilot suggests that hBN encapsulation thickness matters substantially.

### COACH (16)
Your paper gives us a starting point; I’ll keep the Stuttgart pilot out of searches. I can’t search the literature here, so please run this **field-level** prompt in a deep-research tool:

> Map open questions and active debates about interlayer excitons in moiré TMD heterobilayers. Prioritise reviews, perspectives, recent preprints, published disagreements, and limitations or future-work sections from the past 2–3 years. Report 5–10 findings. For each, give a DOI or URL and one sentence explaining the open question. Do not infer an applicant’s proposed experiment or use unpublished results; write “not found” where evidence is unavailable.

Can you paste the results here?

### APPLICANT (17)
That prompt is fine.

[TEST DATA - simulated deep-research output, not real sources]
(a) Novelty check: Closest work: Group A (2024, Nature Materials, DOI 10.9999/test.0001) measured interlayer exciton lifetimes vs twist angle in WSe2/MoSe2 at 5 angles but did not vary hBN thickness. Group B (2025, Phys. Rev. X, DOI 10.9999/test.0002) varied dielectric environment in aligned (0 deg) samples only. No study found that crosses twist angle and dielectric thickness systematically. Time-resolved ARPES on moiré excitons: Group C (2023, Science, DOI 10.9999/test.0003), one twist angle.
(b) State of the art 2021-2026: review DOI 10.9999/test.0004 (Rev. Mod. Phys. 2025) lists "separating trapping from screening" as an open problem. Preprint arXiv:2605.99999 (test) claims screening dominates at all angles, based on theory only.
(c) Not found: any experimental work combining trARPES and transient-absorption microscopy on the same twisted device.

### COACH (17)
These are marked as simulated test data, so I won’t treat the papers, novelty claims or “not found” results as evidence. They also need verification before we can assess novelty or build candidates from the literature. Could you paste the real field-map results with DOI or URL links?

### APPLICANT (18)
I don’t have verified field-map results to paste yet. I’ll run the search and bring back links to the real sources.

### COACH (18)
We’ll leave the literature map open [?] until you have real links. Meanwhile, what observation in your published paper makes moiré trapping a plausible explanation for the longer lifetimes?

### APPLICANT (19)
We observed much longer interlayer-exciton lifetimes at small twist angles, where moiré trapping is expected to be stronger. That makes trapping plausible, but the paper did not isolate it from screening.

### COACH (19)
The angle dependence supports trapping, but it does not separate trapping from screening. What observation would distinguish those explanations in your proposed study?

### APPLICANT (20)
I would vary hBN thickness across devices at both small and larger twist angles. If changing hBN thickness has little effect on lifetime at small angles but a stronger effect at larger angles, that would support trapping as the dominant factor at small angles; a strong effect at all angles would favour screening.

### COACH (20)
That gives you a testable contrast, though the literature map remains open [?]. In your own words, what provisional hypothesis does that contrast test?

### APPLICANT (21)
My provisional hypothesis is that at small twist angles, moiré trapping dominates the exciton lifetime, so changing hBN thickness has less effect than it does at larger angles. A strong thickness dependence even at small angles would count against it.

### COACH (21)
That is a falsifiable provisional hypothesis for lifetime; the transport part remains open. What do you predict will happen to exciton transport at the small angles where trapping lengthens lifetime?

### APPLICANT (22)
I expect stronger trapping at small angles to reduce how far excitons travel, even as they live longer. If they instead travel farther, that would challenge this picture.

### COACH (22)
That gives the transport prediction a clear way to fail. What makes this study feasible now that it was not when you published your 2024 paper?

### APPLICANT (23)
The 2024 paper established the lifetime effect, but we could not systematically vary twist angle and hBN thickness or measure spatial transport alongside the dynamics. I now have heterostructure-stacking experience and a pilot indication that hBN thickness matters; the proposed group would add a cryogenic transient-absorption microscope and combine it with time-resolved photoemission.

### COACH (23)
You’ve identified the capability the group would need; we’ll later check access to photoemission and the microscope plan. Which part of this research direction did you initiate independently of your former supervisor?

### APPLICANT (24)
I've always been quite independent, I developed my own ideas at ETH and in Stuttgart, and I'm now well known in the community.

### COACH (24)
“Independent” needs a concrete example reviewers can assess. What specific research question or experiment did you initiate yourself, and what role did your supervisor play in it?

### APPLICANT (25)
I initiated the twisted-heterobilayer research line at ETH, wrote the internal seed-grant proposal and built the stacking setup. My PhD supervisor, Prof. Weber, works mainly on monolayers and coherent optics; he was not involved in that postdoctoral work and is not a coauthor on any of my postdoc papers.

### COACH (25)
The ETH seed proposal and stacking setup are concrete evidence of your role; the distinction from Prof. Weber’s work also helps. What are the two or three research objectives you would want the group to achieve?

### APPLICANT (26)
First, map how twist angle and hBN thickness affect interlayer-exciton lifetime, to test the trapping-versus-screening hypothesis. Second, measure how those same variables affect transport and whether longer lifetimes come at the cost of mobility. Third, connect the photoemission and microscopy results on matched devices to identify the mechanisms behind both effects.

### COACH (26)
Those objectives link lifetime, transport and mechanism on matched devices. How would you vary twist angle and hBN thickness while keeping other differences between devices from obscuring the comparison?

### APPLICANT (27)
I would make device series using the same TMD crystal batches and stacking procedure, with planned twist-angle and hBN-thickness ranges. I’d verify twist angle and layer quality for each device, measure several devices per condition, and randomise the measurement order so batch effects or drift do not masquerade as a trend.

### COACH (27)
Those controls make the comparison more credible. How will you use the photoemission and microscopy measurements together to distinguish trapping from screening on matched devices?

### APPLICANT (28)
On each matched device, time-resolved photoemission would track changes in the exciton-related electronic states and their dynamics, while transient-absorption microscopy would measure lifetime and spatial spreading. I would compare how all three respond to twist angle and hBN thickness: an angle-dependent signature of localisation paired with reduced spreading would support trapping, whereas a strong thickness dependence without that localisation signature would point toward screening.

### COACH (28)
That comparison gives each method a distinct role, but using both on matched devices is a key feasibility point. What access do you expect to have to time-resolved photoemission at the Hamburg host?

### APPLICANT (29)
Hamburg’s ultrafast and free-electron-laser environment is a strong reason for choosing it, but I have not yet secured a specific time-resolved photoemission instrument or beamtime. I need to confirm access with the relevant groups and set out a fallback measurement plan before treating matched-device measurements as feasible.

### COACH (29)
Instrument access is open [?], and we should not present the matched-device plan as secured. If photoemission access is unavailable or delayed, how would you still test the trapping-versus-screening hypothesis?

### APPLICANT (30)
I would use the cryogenic transient-absorption microscope to compare lifetimes and spatial spreading across the twist-angle and hBN-thickness series. Temperature-dependent optical measurements could provide an additional indication of localisation. That would still test the predicted contrast, though it would give weaker evidence for the microscopic mechanism without photoemission.

### COACH (30)
That fallback preserves the main comparison while weakening the mechanism claim. What result must the group achieve by the end of year 3 to justify the second three-year phase?

### APPLICANT (31)
By the end of year 3, we should have a reproducible device series spanning twist angle and hBN thickness, with lifetime and transport measurements that clearly test the predicted contrast. We should be able to say whether the hypothesis survives that test, including if the result is negative. Photoemission would strengthen the mechanism claim, but the interim goal should not depend on access we have not secured.

### COACH (31)
That gives the interim evaluation a testable outcome without relying on unsecured photoemission access. What would years 4–6 add beyond that result?

### APPLICANT (32)
Years 4–6 would investigate the mechanism behind the year-3 result, using photoemission if access is secured, and extend the comparison to how trapping and screening jointly affect transport. We would also test whether the conclusions hold across further device batches, including if the original hypothesis fails.

### COACH (32)
That makes the second phase useful even if the hypothesis fails, though its photoemission component remains conditional. What is the biggest technical risk to producing a comparable device series, and how would you respond if it occurs?

### APPLICANT (33)
The biggest risk is variation in twist angle or interface quality between nominally comparable devices. I would verify each device after fabrication and compare measured properties rather than relying on target values alone. If the yield is too low, I would narrow the angle and thickness range to a smaller, well-controlled comparison.

### COACH (33)
Narrowing the series is a workable fallback, provided the remaining devices still test the contrast. What team roles would you request for the first three years, and what would each person do?

### APPLICANT (34)
I would request two PhD students from year 1: one for device fabrication and characterisation, and one for cryogenic transient-absorption microscopy and transport analysis. I would recruit a postdoc from year 2 to lead the photoemission work if access is confirmed and help integrate the measurements. I would coordinate the programme and supervise the team.

### COACH (34)
The two PhD roles follow from the work plan; the postdoc role depends partly on photoemission access. If access is not confirmed, what work would the postdoc lead instead?

### APPLICANT (35)
The postdoc would lead cross-device analysis of the lifetime and transport data, develop the temperature-dependent optical measurements, and coordinate replication across fabrication batches. They could also strengthen the interpretation of the optical results without relying on photoemission access.

### COACH (35)
That gives the postdoc a defined role even without photoemission. What specific facilities or expertise at Universität Hamburg would support device fabrication and the proposed cryogenic microscope?

### APPLICANT (36)
Hamburg’s cleanroom and heterostructure-stacking expertise could support device fabrication, and its ultrafast-optics environment is relevant to building and operating the cryogenic transient-absorption microscope. The microscope would be a requested instrument, not an existing host facility. I still need written confirmation of cleanroom access and practical support.

### COACH (36)
We’ll mark cleanroom access and practical support as unconfirmed [?], and describe the microscope as requested equipment. What experience do you have supervising researchers or teaching students?

### APPLICANT (37)
At Stuttgart I co-supervise one PhD student. I taught exercise classes at ETH and a lecture block at Stuttgart University, and I would be ready to teach 2 SWS in Hamburg.

### COACH (37)
That gives us supervision and teaching experience, but “co-supervise” does not yet show your own leadership role. Which parts of the student’s project and supervision are you personally responsible for?

### APPLICANT (38)
I help define the student’s experimental milestones, train them on measurements and data analysis, and meet with them regularly to review results and troubleshoot. Their formal supervisor retains overall responsibility for the doctorate.

### COACH (38)
That describes your hands-on role without overstating formal supervision. How will you store, document and share the device and measurement data produced by the group?

### APPLICANT (39)
I would keep device fabrication records and measurement metadata alongside the raw data in the host’s approved storage system, with regular backups and version-controlled analysis code. We would share data and code supporting publications through a suitable repository, subject to the host’s policies.

### COACH (39)
That provides a starting research-data plan; the host’s storage and repository requirements still need checking. Are sex, gender or other diversity factors relevant to the research questions, materials or methods in this project?

### APPLICANT (40)
No. The project studies synthetic semiconductor devices, so sex and gender are not variables in the research questions, materials or methods. I do not see another diversity factor that affects the experimental design.

### COACH (40)
We can state that briefly in the project description. Do any parts of the planned work raise ethics, safety or legal approval requirements beyond the host’s standard laboratory procedures?

### APPLICANT (41)
I do not expect any approvals beyond the host’s standard laboratory procedures. The work will involve laser, cryogenic and cleanroom safety requirements, which we would address through the host’s training and approvals.

### COACH (41)
We’ll record that as your current assessment and confirm the host’s requirements. What major equipment and operating costs, beyond staff, would you need to request?

### APPLICANT (42)
later

### COACH (42)
I’ll mark equipment and operating costs as open [?]. Do you intend to list TUM as a second host in this application, or keep it as a private fallback while proposing Hamburg alone?

### APPLICANT (43)
I would propose Hamburg alone and keep TUM as a private fallback.

### COACH (43)
We’ll treat Hamburg as the only proposed host; TUM will not appear in the application. Which of your publications best show that you can lead this research independently?

### APPLICANT (44)
My 2024 Nature Physics paper is the strongest example: I was first and corresponding author, and it grew out of the twisted-heterobilayer line I initiated at ETH. My corresponding-author papers from Stuttgart in Physical Review B (2025) and Nano Letters (2026) also show that I have continued to lead work in this area.

### COACH (44)
Those papers give us concrete examples for the independence case; we’ll need their verified bibliographic details later. Beyond hosting the group, how would the Emmy Noether period prepare you for a professorship?

### APPLICANT (45)
It would let me build and lead a team, establish a distinct research programme, and take responsibility for its scientific direction and resources. I would also gain more experience supervising doctoral researchers and teaching at Hamburg.

### COACH (45)
That is a clear career goal. Here is my interview summary; **[?]** marks points still open.

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

Before we move to the research step, what would you correct in this summary?

### APPLICANT (46)
Correction: the Columbia visit was 3 months in 2023, not a longer stay; and please note TUM only as a backup host. Otherwise this is correct.

### COACH (46)
Confirmed. I’ll record Columbia as a **three-month visit in 2023** and TUM as a **private backup, not a proposed host**.

Here is a prompt for the novelty and state-of-the-art check. It leaves out your unpublished pilot, device strategy and identifying details:

> Assess the literature on how twist angle and dielectric environment affect interlayer-exciton lifetime and spatial transport in twisted TMD heterobilayers. The general approach is to compare exciton dynamics and transport across device conditions using time-resolved measurements.
>
> **Novelty check:** Has this question, or a closely related combination of lifetime and transport measurements, already been studied? Identify who did it, what they measured and how close their work is to this approach.
>
> **State of the art:** Summarise relevant work from the last five years, including evidence that supports, narrows or closes the proposed gap. Include competing explanations and unresolved disagreements.
>
> Give a DOI or URL for every source and write “not found” where you find no evidence. Distinguish experimental results from theoretical predictions. Do not infer unpublished results or claim novelty solely because a search found nothing.

The simulated sources you pasted earlier will not be used. When real results arrive, we’ll check each claim against its source, and you’ll need to open every DOI or URL to confirm that the work exists and says what the search reports.

Does this prompt reveal too much about your idea before you use it in a research tool?

### APPLICANT (47)
It is fine. Note: this whole session is a dry run of the process. The block below is simulated test data; please treat it as if it were real search output for now, put every source on the verification checklist, and continue with the next steps.

[TEST DATA - simulated deep-research output, not real sources]
(a) Novelty check: Closest work: Group A (2024, Nature Materials, DOI 10.9999/test.0001) measured interlayer exciton lifetimes vs twist angle in WSe2/MoSe2 at 5 angles but did not vary hBN thickness. Group B (2025, Phys. Rev. X, DOI 10.9999/test.0002) varied dielectric environment in aligned (0 deg) samples only. No study found that crosses twist angle and dielectric thickness systematically. Time-resolved ARPES on moiré excitons: Group C (2023, Science, DOI 10.9999/test.0003), one twist angle.
(b) State of the art 2021-2026: review DOI 10.9999/test.0004 (Rev. Mod. Phys. 2025) lists "separating trapping from screening" as an open problem. Preprint arXiv:2605.99999 (test) claims screening dominates at all angles, based on theory only.
(c) Not found: any experimental work combining trARPES and transient-absorption microscopy on the same twisted device.

### COACH (47)
For this dry run, I’ll use the simulated search output to **test the workflow**, not as verified evidence. No citation or novelty claim from it can enter a real draft until checked.

### Provisional research map

| Simulated result | Effect on the proposed gap |
|---|---|
| Group A: lifetime across twist angles | Narrows the lifetime gap; the proposed dielectric comparison may still differ. |
| Group B: dielectric variation at alignment | Narrows the screening gap; other angles may remain untested. |
| Group C: time-resolved photoemission at one angle | Narrows the method gap, not necessarily the proposed comparison. |
| Review: separating trapping from screening is open | Would support the gap **if the review says this**. |
| Theory preprint: screening dominates at all angles | Challenges your hypothesis; it does not settle the experimental question. |
| No same-device combination found | **Unconfirmed absence**, not proof of novelty. |

Nothing in this simulated output establishes that the idea is new or already done.

**Verification checklist — applicant to open each link and confirm both existence and the reported claim:** ☐ `10.9999/test.0001` ☐ `10.9999/test.0002` ☐ `10.9999/test.0003` ☐ `10.9999/test.0004` ☐ `arXiv:2605.99999`. The “no study found” claims also need a real search; they cannot be verified by a single citation.

### Proposed outline for approval

The uploaded Emmy Noether reference (DFG forms, **09/26**) gives a **25-page maximum** for the project description: **17 pages for sections 1–3** and **8 for section 4 onward**. The allocations below are planning budgets, not DFG section limits.

| Template section | Planning budget | Material from your interview; still needed |
|---|---:|---|
| **1. Starting point: state of the art and preliminary work** | 5 pages | The trapping–screening gap; your 2024 result; your independent research line. **[?]** Real, verified literature and publication details. |
| **2. Objectives and work programme** | 10 pages | Hypotheses and refuting results; device comparisons; optical and conditional photoemission work; year-3 test and years 4–6; risks and fallbacks; data handling; sex/gender/diversity relevance; Hamburg justification. **[?]** Instrument and cleanroom access, host support, and details needed to make the schedule feasible. |
| **3. Project- and subject-related publications** | 2 pages | Your selected papers, with your own contribution clearly marked. **[?]** Verified bibliographic details and final selection, within the reference’s limit of 10 highlighted own works. |
| **4 onward. Ethics, project group, partners, equipment, other submissions and requested modules** | 8 pages total | Your current approvals assessment; team roles; requested microscope; item-by-item resource justification. **[?]** Equipment and operating costs, any cooperation arrangements, host confirmations and other submissions. |

This leaves the unresolved items visible rather than filling them with assumptions. **Do you approve this outline as the basis for drafting, subject to replacing the simulated research with verified sources?**

### APPLICANT (48)
Yes, I approve it on that basis. Please draft section 2.2 Objectives and 2.3 Work programme including the 3 + 3 structure.

### COACH (48)
I’ll draft **2.2 Objectives** first and wait for your feedback before drafting **2.3 Work programme**, including its 3 + 3 structure. The simulated search results are not used as evidence.

### 2.2 Objectives

This project will test how twist angle and the dielectric environment affect the lifetime and spatial transport of interlayer excitons in twisted TMD heterobilayers. Its central hypothesis is that moiré trapping dominates the lifetime at small twist angles. On that account, changing hBN thickness should have less effect on lifetime at small angles than at larger angles. A strong thickness dependence at small angles would count against the hypothesis.

The first objective is to measure lifetime across a device series that varies twist angle and hBN thickness. Comparing the two dependences will test whether the results are consistent with trapping dominating at small angles or with a substantial screening effect across the angle range.

The second objective is to measure spatial spreading across the same conditions. I predict that stronger trapping at small angles will restrict exciton travel even when lifetime increases. Greater spreading under those conditions would challenge that prediction.

The third objective is to investigate the mechanism behind the measured lifetime and transport trends. Transient-absorption microscopy will provide the core comparison. If access is secured, time-resolved photoemission on matched devices will add evidence from exciton-related electronic states. The mechanism claim will reflect what the available measurements can establish.

**Open points for this subsection:** [?] The literature basis for the gap and novelty needs real, verified sources. [?] Photoemission access and matched-device feasibility remain unconfirmed.

If you want me to match your writing style, you can share one or two passages you wrote. What would you change in **2.2** before I draft **2.3**?

### APPLICANT (49)
Good. Make clear the interim evaluation goal at year 3.

### COACH (49)
### 2.2 Objectives

This project will test how twist angle and the dielectric environment affect the lifetime and spatial transport of interlayer excitons in twisted TMD heterobilayers. Its central hypothesis is that moiré trapping dominates lifetime at small twist angles. If so, changing hBN thickness should have less effect on lifetime at small angles than at larger angles. A strong thickness dependence at small angles would count against the hypothesis.

The first objective is to measure lifetime across devices that vary in twist angle and hBN thickness. The second is to measure spatial spreading across the same conditions. I predict that stronger trapping at small angles will restrict exciton travel even when lifetime increases. Greater spreading under those conditions would challenge that prediction.

**By the end of year 3**, the group aims to have a reproducible device series and lifetime and transport measurements that test both predictions. The interim result will state whether the hypothesis survives, including if the findings are negative. This goal does not depend on photoemission access.

The third objective is to investigate the mechanism behind the measured trends. Transient-absorption microscopy will provide the core comparison. If access is secured, time-resolved photoemission on matched devices will add evidence from exciton-related electronic states. The mechanism claim will reflect what the available measurements can establish.

**Open points:** [?] The gap and novelty need verified sources. [?] Photoemission access and matched-device feasibility remain unconfirmed.

Does this state the year-3 goal as you intend it?

### APPLICANT (50)
Yes, that states it. Please now draft 2.3 Work programme including the 3 + 3 structure.

### COACH (50)
### 2.3 Work programme

**Years 1–3: test the lifetime and transport predictions.** I will establish a series of twisted TMD heterobilayer devices that varies twist angle and hBN thickness. Devices will use the same TMD crystal batches and stacking procedure where possible. We will verify twist angle and layer quality after fabrication, measure several devices per condition and randomise measurement order to reduce the risk that batch effects or drift appear as physical trends.

One PhD researcher will focus on fabrication and device characterisation. A second will develop cryogenic transient-absorption microscopy measurements and analyse lifetime and spatial spreading. The microscope is requested equipment, not an existing host facility. From year 2, a postdoctoral researcher will integrate results across devices and fabrication batches and develop temperature-dependent optical measurements.

We will compare how lifetime and spatial spreading change with twist angle and hBN thickness. A weak thickness dependence of lifetime at small angles, paired with reduced spreading, would support the proposed role of trapping. A strong thickness dependence at small angles or greater spreading where lifetimes increase would challenge the corresponding prediction. Temperature-dependent optical measurements may provide additional evidence of localisation, but will not by themselves establish the microscopic mechanism.

**The year-3 milestone** is a reproducible device series with lifetime and transport measurements that test these predictions. We will report whether the hypothesis survives the comparison, including if the result is negative. This milestone does not depend on access to time-resolved photoemission.

**Years 4–6: investigate mechanism and robustness.** We will extend the comparison across further device batches and examine how the factors associated with longer lifetimes relate to transport. If photoemission access and matched-device measurements are secured, the postdoctoral researcher will lead measurements of exciton-related electronic states and their dynamics. We will compare those results with optical lifetime and spatial-spreading measurements on matched devices. An angle-dependent localisation signature accompanied by reduced spreading would strengthen the trapping interpretation; a strong thickness dependence without that signature would favour a screening interpretation.

Photoemission access is not yet secured. If it is unavailable or delayed, the postdoctoral researcher will instead lead cross-device analysis, temperature-dependent optical measurements and replication across batches. The optical programme will still test the lifetime and transport predictions, but any claim about their microscopic mechanism will be narrower.

Device-to-device variation is a second risk. We will compare verified device properties rather than target fabrication values. If yield is too low for the planned range, we will narrow the angle and thickness comparison to devices with well-characterised interfaces, while retaining conditions that can test the predicted contrast.

We will store fabrication records, measurement metadata and raw data in the host’s approved system, with backups and version-controlled analysis code. Data and code supporting publications will be shared through a suitable repository, subject to host policy.

**Open points:** [?] Confirm cleanroom access and practical host support. [?] Secure photoemission access and establish whether matched devices can be measured by both methods. [?] Specify the device ranges and the narrower comparison that would still test the hypothesis. [?] Confirm the host’s data-storage requirements.

What would you change in **2.3**?

### APPLICANT (51)
Good. That's enough drafting for now. Please give me the final checklist to close. Also: will there be a personal presentation or interview?

### COACH (51)
We can pause drafting here. **Sections 2.2 and 2.3 are drafts, not a submission-ready proposal.**

### Closing checklist

- **Limits:** The uploaded Emmy Noether reference (DFG forms, 09/26) gives 25 pages for the project description: at most 17 pages for sections 1–3 and 8 pages from section 4 onward. I cannot reliably count pages outside the official template; check the assembled document there.
- **Resolve every [?]:** Replace the simulated search output with real research; confirm photoemission and cleanroom access, host support, device ranges, data-storage requirements, resources and operating costs.
- **Verify sources:** Open every real DOI or URL and confirm that the work exists and supports the claim made. None of the simulated sources is verified or suitable for citation.
- **Complete the application:** Include the remaining template sections and item-by-item justification of requested modules. The reference lists a CV (form 53.200), doctoral certificate, employer’s statement or model contract (form 53.12) for the host, and a description of international research experience.
- **Disclose AI use:** The uploaded reference requires disclosure when generative AI has drafted text. For example: “I used [model name] to help structure interview answers and draft sections 2.2 and 2.3. I reviewed and revised the text and am responsible for its scientific content.” Replace the bracket with the model name shown in your interface and adjust the extent to match what you submit.
- **Own every sentence:** You must be able to defend the hypotheses, methods, claims and citations yourself.

**Personal presentation or interview:** I cannot confirm one from the uploaded reference. It says current forms do not mention a presentation and older sources conflict. Ask the DFG directly whether one applies to your application; do not plan on either answer until they confirm it.

Once the full draft is complete, seek a critical review with **`dfg-emmy-noether-reviewer`**, ideally in a fresh chat.

### APPLICANT (52)
Looks good, thanks. END

### COACH (52)
You’re welcome. Good luck with the proposal.

