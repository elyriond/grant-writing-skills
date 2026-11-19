# E2E test: grant-proposal-coach, ERC StG, gpt-6-sol (coach and simulated applicant)

All research results in this transcript are SIMULATED TEST DATA (fake DOIs 10.0000/testN).

### APPLICANT (turn 1)
Hi, I'd like to prepare an ERC Starting Grant proposal.

### COACH (turn 1)
We’ll work through about 20–30 short questions over 30–45 minutes; say “later” to skip any question. Everything typed here reaches the provider of this chat. Share unpublished ideas and results only with training switched off or through an institutional account; otherwise describe them qualitatively, without numbers or the core trick.

When did you defend your PhD?

### APPLICANT (turn 2)
I defended my PhD in linguistics on 12 May 2020 at the University of Edinburgh.

### COACH (turn 2)
Your defence date falls within the window in the ERC Starting Grant 2027 documents, but that call has closed; rules for the next call are not yet published. Have you had any career breaks that could affect your eligibility window?

### APPLICANT (turn 3)
No career breaks or leave. I know we’ll need to check the ERC-2028-StG rules once they’re published.

### COACH (turn 3)
Yes. We’ll use the 2027 documents provisionally and check the 2028 rules when published. Which institution would host your project?

### APPLICANT (turn 4)
The University of Stuttgart would host it, through the Institute for Natural Language Processing. I’ve led a junior research group there since 2023.

### COACH (turn 4)
Leading a group is useful context for your track record. Do you have an important publication on which you are the main author, or one without your PhD supervisor as a coauthor?

### APPLICANT (turn 5)
Yes—a first-author TACL 2023 paper, without my PhD supervisor, showing that language models’ subject–verb agreement errors across 14 languages track word frequency rather than syntactic distance.

### COACH (turn 5)
That paper gives us a concrete example of independent work to examine later. Have you submitted an ERC proposal before, and if so, what was its result?

### APPLICANT (turn 6)
No, I haven’t applied to the ERC before.

### COACH (turn 6)
Which ERC evaluation panel do you expect to choose?

### APPLICANT (turn 7)
Probably SH4, with PE6 as a possible secondary panel, but I’m not certain yet.

### COACH (turn 7)
We can leave the panel choice provisional. Could you devote at least 50% of your working time to the project?

### APPLICANT (turn 8)
I expect so, but I’d need to confirm the workload arrangement with Stuttgart before committing to that figure.

### COACH (turn 8)
We’ll mark the time commitment [?] until Stuttgart confirms it. What specific scientific problem would your project tackle?

### APPLICANT (turn 9)
Basically LLMs don’t really understand language the way humans do, and I want to understand that better.

### COACH (turn 9)
“Understand language” is too broad to test. What specific language behaviour do current models fail to explain or reproduce?

### APPLICANT (turn 10)
The gap is that most claims about models learning grammar “like humans” come from English models trained on billions of words. We don’t know whether models trained on child-scale input—around 100 million words or fewer—learn grammatical structure in morphologically rich languages, or whether their apparent success comes from surface cues.

### COACH (turn 10)
That narrows the gap to child-scale training and morphologically rich languages. What is your central hypothesis about when models will rely on grammatical structure rather than surface cues?

### APPLICANT (turn 11)
Honestly, I have the topic but not a sharp hypothesis. Can you help me come up with some candidates?

### COACH (turn 11)
Yes. We can use idea mode to develop candidates for you to judge, rather than supply a hypothesis from the topic alone. Which two or three recent papers on child-scale language learning or morphology do you find most important?

### APPLICANT (turn 12)
A 2024 BabyLM challenge findings paper is important because it reports surprisingly good English grammar scores from small models. I’d also point to a 2025 paper arguing that English-only benchmarks overestimate structural generalisation. My TACL 2023 paper and a last-author ACL 2025 benchmark paper with my student give us a starting point; we also have an unpublished Slovenian pilot that I’d rather keep qualitative here.

### COACH (turn 12)
Your published work gives us a useful starting point; we can leave the Slovenian pilot qualitative. I can’t search the literature from here, so I don’t want to invent “open questions” or candidate hypotheses before checking the field. Please run this field-only prompt in a research tool:

> Map open questions and active debates from the last 2–3 years in computational language acquisition and cross-linguistic grammatical generalisation. Look for recent reviews, perspective papers, preprints, published disagreements, and the limitations and future-work sections of relevant studies. Report 5–10 findings. For each, give a DOI or URL, a one-sentence account of the open question, and what evidence supports it. Do not investigate a particular applicant’s project or unpublished work; write “not found” where evidence is unavailable.

Could you paste the findings and links here?

### APPLICANT (turn 13)
[SIMULATED TEST DATA — not real references] Here are the deep-research results: (1) Review 2025: open question whether small-data models’ grammatical success reflects structure or surface heuristics (doi:10.0000/test1). (2) Preprint 2026: models trained on child-directed speech fail on long-distance dependencies in Finnish (doi:10.0000/test2). (3) Paper 2024: agreement attraction in humans is stronger in languages with case syncretism (doi:10.0000/test3). (4) Perspective 2025: call for cross-linguistic developmental benchmarks (doi:10.0000/test4). (5) Study 2025: activation patching locates number agreement in specific attention heads in English models (doi:10.0000/test5).

### COACH (turn 13)
These are simulated references, so I won’t treat the five findings as established or cite their DOIs. For a real proposal, please open and verify each source before we use its claims. We can still generate **provisional candidates** from the gap you described and your reported TACL finding.

| Technique | Candidate for you to judge | What would refute it? | Builds on | Novelty risk |
|---|---|---|---|---|
| Boundary case | At child-scale input, apparent grammatical generalisation breaks down when frequency cues conflict with agreement rules in morphologically rich languages. | Models succeed on those conflict cases. | Your TACL finding; your stated gap | Unclear |
| Mechanism | Frequency cues explain apparent agreement success better than representations of syntactic relations do. | Tests that separate the two show syntax predicts success better. | Your TACL finding | Unclear |
| Scale shift | Increasing training input changes *which cues* models use, not merely their grammar scores. | Cue use stays stable as input grows. | Your child-scale question | Unclear |
| Inversion | Morphological richness helps small-data models learn grammatical relations, despite making surface patterns more varied. | Richer morphology consistently impedes learning under comparable conditions. | Your cross-linguistic question | Unclear |
| Contradiction | Strong benchmark scores and weak structural generalisation can coexist because benchmarks reward surface cues. | Benchmark success persists when those cues are controlled. | Your stated concern about English benchmarks | Unclear |
| Combination | The frequency effect in your earlier work predicts where child-scale models will fail across languages. | That effect does not predict their errors. | Your TACL finding; your proposed setting | Unclear |

Which candidate, if any, would you choose or combine—and how would you state the resulting hypothesis in your own words?

### APPLICANT (turn 14)
I’d combine the morphology and mechanism candidates: small models may make human-like agreement-attraction errors where case syncretism gives them ambiguous cues, rather than because they’ve built human-like syntactic structure. If models trained on languages without that ambiguity show the same pattern, the idea is in trouble. We’d need to verify the literature before claiming that’s novel.

### COACH (turn 14)
That is a testable hypothesis, developed in idea mode; we’ll check its novelty against verified literature. What makes this question answerable now when it was not a few years ago?

### APPLICANT (turn 15)
We can now train smaller models on child-scale input across several languages and test them with controlled psycholinguistic suites, rather than relying on English benchmark scores. Existing human reading-time and acceptability data give us a comparison, and activation patching lets us test whether the model’s behaviour reflects the mechanism we’re proposing.

### COACH (turn 15)
That explains why the comparison is now feasible, though we’ll need to specify what activation patching can establish. If your hypothesis holds, what claim about language models and human grammar would researchers need to revise?

### APPLICANT (turn 16)
We’d need to be more cautious about calling human-like errors evidence that a model has learned grammar in a human-like way. The same error pattern could arise from ambiguous morphological cues in its input; patching might help distinguish mechanisms, but it wouldn’t settle that on its own.

### COACH (turn 16)
That distinction gives the project a clear potential contribution without overstating what patching can show. What is the first objective you would need to achieve to test the hypothesis?

### APPLICANT (turn 17)
First, I’d build comparable child-scale training corpora across the six languages and measure how much case syncretism and agreement-cue ambiguity they contain. Without that baseline, differences in model errors would be hard to interpret.

### COACH (turn 17)
That baseline would help you interpret differences between languages. Which six languages would you use?

### APPLICANT (turn 18)
My provisional set is English, German, Finnish, Turkish, Basque, and Slovenian. I’d check corpus availability and whether the set gives us the contrasts in case syncretism we need before fixing it.

### COACH (turn 18)
We’ll keep the language set provisional until you’ve checked corpus availability and the contrasts it provides. What would the second objective test using the trained models?

### APPLICANT (turn 19)
I’d train matched 10–100M-word models and test whether agreement-attraction errors vary with cue ambiguity across the six languages, using controlled test suites. I’d compare the patterns with existing human data, while checking whether simpler frequency effects explain them.

### COACH (turn 19)
That objective separates cue ambiguity from frequency as a competing explanation. What would a third objective test about the mechanism behind the models’ errors?

### APPLICANT (turn 20)
I’d use probing and activation patching to test whether the errors depend on representations of agreement relations or on more local morphological cues. I’d treat that as evidence about the models’ mechanisms, not proof that they process grammar like humans.

### COACH (turn 20)
That keeps the mechanistic claim appropriately limited. What patching result would favour reliance on local morphological cues over agreement-relation representations?

### APPLICANT (turn 21)
If patching representations associated with a nearby noun’s ambiguous case or number cues changed the model’s agreement prediction, while patching representations of the subject–verb relation had little effect, that would favour the local-cue account. I’d want controls for position and frequency before interpreting it that way.

### COACH (turn 21)
That gives the mechanistic test a directional prediction, with controls still to specify. What is the biggest risk to interpreting the cross-language comparison?

### APPLICANT (turn 22)
The biggest risk is that child-directed corpora are too small for some languages, so differences between models could reflect data availability rather than morphology. I’d check corpus coverage first and, where needed, supplement with child-available text such as picture books and children’s subtitles.

### COACH (turn 22)
Supplementing corpora could help, but it may also change how comparable the languages are. If adequate child-scale input is unavailable for one of the six languages, what would you do?

### APPLICANT (turn 23)
I’d try supplementing with child-available text, while documenting the change and checking whether it affects the comparison. If that still isn’t adequate, I’d drop that language rather than force a misleading six-language result. I think we’ve covered enough — can you show me the summary?

### COACH (turn 23)
Here is the interview summary. **[?]** marks points still open; we can return to them after you check it.

### Problem and gap
Claims that language models learn grammar “like humans” often rest on English models trained on billions of words. It remains unclear whether models trained on child-scale input, around 100 million words or fewer, learn grammatical structure in morphologically rich languages or succeed by using surface cues.

### Central idea and hypothesis
Small models may make human-like agreement-attraction errors where case syncretism makes morphological cues ambiguous, without building human-like syntactic structure. Similar errors in languages without that ambiguity would challenge the hypothesis. **This hypothesis was developed in idea mode.** Its novelty remains [?] until the literature is verified.

If the project works, human-like error patterns would become weaker evidence, on their own, for human-like grammatical learning. Mechanistic tests could help distinguish explanations, but would not settle the comparison with human processing.

### Why now
Smaller models can be trained on child-scale input across languages and tested with controlled psycholinguistic suites. Existing human reading-time and acceptability data offer a comparison; activation patching offers a way to test proposed model mechanisms.

### Why you
You lead a junior research group at Stuttgart. Your first-author TACL 2023 paper, without your PhD supervisor, found that agreement errors across 14 languages tracked word frequency rather than syntactic distance. You also identified a last-author ACL 2025 benchmark paper with your student. The significance of that output and your distinct contribution to it remain [?]. The Slovenian pilot stays qualitative here.

### Objectives
1. Build comparable child-scale training corpora and measure case syncretism and agreement-cue ambiguity.
2. Test whether agreement-attraction errors vary with cue ambiguity, comparing model patterns with human data and testing frequency as a rival explanation.
3. Use probing and activation patching to test whether errors depend more on agreement-relation representations or local morphological cues.

### Methods and work packages
The provisional languages are English, German, Finnish, Turkish, Basque and Slovenian [?]. You would train matched models on 10–100 million words and use controlled cross-linguistic test suites. For the mechanism test, a result favouring local cues would be a change in agreement predictions after patching nearby ambiguous case or number cues, with little effect from patching subject–verb-relation representations. Position and frequency controls still need specifying [?].

### Risks and fallbacks
Uneven availability of child-directed input could make a corpus difference look like a morphological effect. You would assess coverage first, document any supplement from child-available text, test its effect on comparability, and drop a language if adequate input remains unavailable.

### Host, team, timeline and resources
The proposed host is the University of Stuttgart’s Institute for Natural Language Processing. Team roles, work-package timing, computing needs and costs are [?]. Your ability to commit at least 50% of working time awaits confirmation from Stuttgart [?].

### ERC fit and open checks
You defended your PhD on 12 May 2020, reported no extensions and have not applied to the ERC before. SH4 is your provisional panel, with PE6 a possible secondary panel [?]. We are using the **ERC Starting Grant 2027 Work Programme and Information for Applicants** provisionally: that call closed on 14 October 2026, and the 2028 rules are not yet published. The five research findings you pasted were labelled simulated test data, so none is a verified source or supports a novelty claim.

What would you correct in this summary before we move to the literature check?

### APPLICANT (turn 24)
One fix: the ACL 2025 paper is last-author with my student, not first-author. Otherwise it’s fine—let’s move to the literature check.

### COACH (turn 24)
Confirmed: the ACL 2025 paper is **last-author with your student**. The summary now stands approved.

For the literature check, this prompt keeps the project at conference-talk level and leaves out the specific cue you plan to test:

> Investigate computational models of grammatical agreement trained on developmentally plausible amounts of language input. The question is whether human-like error patterns across languages indicate structural generalisation or can arise from simpler cues. The general approach compares controlled model tests across languages with published human evidence and examines model representations.
>
> **Novelty check:** Has this question or a closely related cross-linguistic, small-data study already been done? For each close study, identify who did it, what they tested, and how close it is. Say plainly if the proposed direction appears already done.
>
> **State of the art:** Summarise relevant work from the last five years, including disagreements and limitations. Distinguish published findings from preprints and authors’ interpretations from results.
>
> Give a DOI or working URL for every source and claim. Write **“not found”** where you cannot find evidence; do not invent citations.

The five items labelled simulated test data are not evidence. When you bring back real results, we’ll map each close study to the proposed gap and put every source on a checklist for you to open and verify. **Does this prompt reveal too much of your idea to send to a research tool?**

### APPLICANT (turn 25)
[SIMULATED TEST DATA — not real references] Results: (a) Novelty: closest work is a 2025 study comparing attraction in English and German small models (doi:10.0000/test6) — it does not vary syncretism systematically; nothing found on syncretism as cause across 6 languages. (b) State of the art: BabyLM 2023–2025 findings (doi:10.0000/test7); cross-linguistic agreement benchmarks (doi:10.0000/test8); interpretability of agreement circuits (doi:10.0000/test5). (c) Not found: developmentally plausible corpora for Basque. The prompt doesn’t reveal too much, but these are simulated results, not sources we can use.

### COACH (turn 25)
Agreed: these are simulated results, so they cannot support a novelty or state-of-the-art claim.

| Simulated finding | If verified, effect on the proposed gap |
|---|---|
| English–German small-model study (`test6`) | Narrows the gap; its tests and treatment of syncretism would need checking. |
| BabyLM findings (`test7`), agreement benchmarks (`test8`), circuit study (`test5`) | Provide possible context; their relevance depends on what they actually report. |
| No Basque corpus found | Flags a feasibility check, not proof that no suitable corpus exists. |

The proposed six-language syncretism question therefore remains **novelty [?]**. The verification checklist is `test1`–`test8` (with `test5` appearing twice): none has been opened or verified, and none should enter the proposal as a citation.

Can you bring back real sources with working DOI or URL links, including the closest studies, so we can finish the literature check before outlining?

### APPLICANT (turn 26)
I don’t have verified sources to paste right now, and I don’t want to substitute those simulated DOIs. I’ll check the closest studies and bring back working links; could we outline provisionally with novelty marked as open?

### COACH (turn 26)
Yes. We can outline **provisionally**, with novelty [?] and no simulated citations. I’m using the *ERC Starting Grant 2027 Work Programme and Information for Applicants* as the template reference; we’ll check the 2028 documents when available. The splits below are working budgets, not ERC-required allocations within each section.

| Section | Working budget | Your material | Still needed |
|---|---:|---|---|
| **B1 cover page: abstract** | Half page, not counted | Question, hypothesis, three objectives, potential change to the field | Verified novelty claim [?]; concise overall strategy |
| **B1 Part I: state of knowledge** | 1.25 of 5 pages | Concern about English, large-data evidence; your TACL finding | Verified sources and precise gap [?] |
| **B1 Part I: question and objectives** | 1.5 of 5 pages | Syncretism/local-cue hypothesis; what would challenge it; three objectives | Scope and language choice [?] |
| **B1 Part I: overall strategy** | 2.25 of 5 pages | Corpora, matched training, controlled tests, human comparison, mechanism tests | Convincing cross-language comparison and controls [?]. This part must stand alone, without B2-level feasibility detail. |
| **B1 CV and Track Record** | 4 pages total | Group leadership; first-author TACL 2023; **last-author ACL 2025 with your student** | Your role and the field contribution of each selected output [?]; other outputs and peer recognition [?] |
| **B2 Part II: methodology** | 4 of 7 pages | Corpus measures, model tests, frequency rival explanation, probing and patching prediction | Corpus availability; matched-training design; position/frequency controls; human-data suitability [?] |
| **B2 Part II: work plan** | 1.5 of 7 pages | Sequence from corpus baseline to behavioural and mechanism tests | Milestones, team roles and timing [?] |
| **B2 Part II: risks and mitigation** | 1.5 of 7 pages | Uneven corpora; documented supplementation or dropping a language | Other consequential risks and decision points [?]. This part should add detail, not repeat Part I. |
| **Part A: Resources and Time Commitment** | Budget table; text **up to 8,000 characters** | Stuttgart host; junior-group context | Confirmed time commitment of at least 50% [?]; personnel, computing, costs and justification [?] |

The 5-page B1 Part I and 7-page B2 Part II allocations each sum to their respective limits; references are excluded from those limits. We would not draft a claim that the six-language question is new until the closest real studies are checked.

Do you approve this provisional outline?

### APPLICANT (turn 27)
Looks good. Please draft the Part I section on the scientific question and objectives.

### COACH (turn 27)
### Part I — Scientific question and objectives  
*Draft for the approved 1.5-page working budget*

Human-like agreement errors do not, by themselves, show that a language model has learned grammar in a human-like way. Similar errors could arise when a model relies on ambiguous morphological cues rather than a representation of the subject–verb relation. This distinction matters for claims about models trained on developmentally plausible amounts of input: strong grammar scores from large English models do not establish what smaller models learn across languages with different morphological systems. The closest published work and the precise novelty of this question remain to be verified [?].

This project asks whether **case syncretism shapes agreement-attraction errors in models trained on child-scale input**. Its working hypothesis is that small models may produce human-like error patterns where ambiguous case cues favour a nearby noun, even when those patterns do not depend on a human-like syntactic representation. If models trained on languages without comparable ambiguity show the same pattern, the hypothesis is in trouble. Frequency provides a further rival explanation: my earlier work found that agreement errors across 14 languages tracked word frequency rather than syntactic distance. The project will test whether cue ambiguity explains errors once frequency is taken into account.

**Objective 1: establish the input comparison.** I will assemble comparable child-scale training corpora and measure the case syncretism and agreement-cue ambiguity they contain. The provisional language set is English, German, Finnish, Turkish, Basque and Slovenian [?]. The set will be fixed only after checking corpus availability and whether it supplies the contrasts needed to test the question.

**Objective 2: test the behavioural prediction.** I will train matched models on 10–100 million words and use controlled tests to examine whether agreement-attraction errors vary with cue ambiguity across languages. I will compare the resulting patterns with available human reading-time and acceptability evidence, while testing whether frequency accounts for the model errors more simply. The suitability of the human datasets for these comparisons remains to be established [?].

**Objective 3: distinguish mechanisms within the models.** Probing and activation patching will test whether agreement predictions depend more on representations of agreement relations or on local morphological cues. A result favouring the local-cue account would be a change in prediction when representations associated with a nearby noun’s ambiguous case or number cues are patched, with little corresponding effect from patching representations associated with the subject–verb relation. These tests can provide evidence about model mechanisms; they cannot establish that models and humans process grammar in the same way.

Together, the objectives test when an apparently human-like error is informative about grammatical structure and when it is compatible with a simpler cue-based account. The project’s contribution will depend on separating those accounts, not on treating resemblance between model and human errors as an explanation in itself.

**Open points:** [?] verified closest studies and novelty; [?] final languages and corpus availability; [?] suitability of human comparison data.

If you share one or two passages you wrote yourself, I can analyse their style once and adjust later sections to sound more like you. What would you change in this section?

### APPLICANT (turn 28)
Thanks, that’s good enough for now. No style analysis needed, just keep it plain. What’s left before I submit?

### COACH (turn 28)
You have a draft of **one Part I section**, not a submission-ready proposal. Before submitting:

- **Check the next call’s documents.** The ERC Starting Grant 2027 call closed on 14 October 2026; 2028 rules are not yet published. Recheck eligibility, template, limits and requirements against that call.
- **Verify the science.** Open the closest real studies and confirm what each says. Resolve novelty [?], the language and corpus choices [?], and the suitability of the human comparison data [?]. Do not use the simulated DOIs.
- **Finish the application.** Draft the rest of B1 Part I and its abstract; the CV and Track Record, including your own role in the **last-author ACL 2025 paper**; B2 methodology, work plan and risks; and Part A resources and time commitment. Confirm the team, costs, milestones and your at-least-50% time commitment with Stuttgart.
- **Obtain host support.** The 2027 reference requires a binding host support letter. Check the next call’s documents for the full attachment list.
- **Check limits in the official template.** The 2027 limits are B1 Part I **5 pages**, CV and Track Record **4 pages**, B2 Part II **7 pages**, and Part A resources text **8,000 characters**. I cannot reliably check page counts from chat text. Resolve every [?] before submission.
- **Check AI rules for the actual call.** The 2027 ERC guidance did not require AI disclosure. You remain responsible for the content and must be able to defend every sentence.

Once the full draft exists, I recommend a critical review with **`erc-stg-reviewer`**, ideally in a fresh chat.

