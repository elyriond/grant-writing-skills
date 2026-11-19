# E2E test: erc-stg-reviewer, gpt-6-sol

Input: coach draft + interview summary from tests/e2e_erc_coach_gpt-6-sol.md (simulated persona; references are fake test DOIs).

### USER
Please review my draft Part I section (scientific question and objectives) for an ERC Starting Grant (next call, likely panel SH4). It is a first submission. Below is the section, then my interview notes for context (PhD May 2020; junior group leader at Stuttgart).

---
# DRAFT SECTION
### Part I — Scientific question and objectives  
*Draft for the approved 1.5-page working budget*

Human-like agreement errors do not, by themselves, show that a language model has learned grammar in a human-like way. Similar errors could arise when a model relies on ambiguous morphological cues rather than a representation of the subject–verb relation. This distinction matters for claims about models trained on developmentally plausible amounts of input: strong grammar scores from large English models do not establish what smaller models learn across languages with different morphological systems. The closest published work and the precise novelty of this question remain to be verified [?].

This project asks whether **case syncretism shapes agreement-attraction errors in models trained on child-scale input**. Its working hypothesis is that small models may produce human-like error patterns where ambiguous case cues favour a nearby noun, even when those patterns do not depend on a human-like syntactic representation. If models trained on languages without comparable ambiguity show the same pattern, the hypothesis is in trouble. Frequency provides a further rival explanation: my earlier work found that agreement errors across 14 languages tracked word frequency rather than syntactic distance. The project will test whether cue ambiguity explains errors once frequency is taken into account.

**Objective 1: establish the input comparison.** I will assemble comparable child-scale training corpora and measure the case syncretism and agreement-cue ambiguity they contain. The provisional language set is English, German, Finnish, Turkish, Basque and Slovenian [?]. The set will be fixed only after checking corpus availability and whether it supplies the contrasts needed to test the question.

**Objective 2: test the behavioural prediction.** I will train matched models on 10–100 million words and use controlled tests to examine whether agreement-attraction errors vary with cue ambiguity across languages. I will compare the resulting patterns with available human reading-time and acceptability evidence, while testing whether frequency accounts for the model errors more simply. The suitability of the human datasets for these comparisons remains to be established [?].

**Objective 3: distinguish mechanisms within the models.** Probing and activation patching will test whether agreement predictions depend more on representations of agreement relations or on local morphological cues. A result favouring the local-cue account would be a change in prediction when representations associated with a nearby noun’s ambiguous case or number cues are patched, with little corresponding effect from patching representations associated with the subject–verb relation. These tests can provide evidence about model mechanisms; they cannot establish that models and humans process grammar in the same way.

Together, the objectives test when an apparently human-like error is informative about grammatical structure and when it is compatible with a simpler cue-based account. The project’s contribution will depend on separating those accounts, not on treating resemblance between model and human errors as an explanation in itself.

**Open points:** [?] verified closest studies and novelty; [?] final languages and corpus availability; [?] suitability of human comparison data.



---
# INTERVIEW SUMMARY (context)
Here is the interview summary. **[?]** marks points still open; we can return to them after you check it.

### Problem and gap
Claims that language models learn grammar “like humans” often rest on English models trained on billions of words. It remains unclear whether models trained on child-scale input, around 100 million words or fewer, learn grammatical structure in morphologically rich languages or succeed by using surface cues.

### Central idea and hypothesis
Small models may make human-like agreement-attraction errors where case syncretism makes morphological cues ambiguous, without building human-like syntactic structure. Similar errors in languages without that ambiguity would challenge the hypothesis. **This hypothesis was developed in idea mode.** Its novelty remains [?] until the literature is verified.

If the project works, human-like error patterns would become weaker evidence, on their own, for human-like grammatical learning. Mechanistic tests could help distinguish explanations, but would not settle the comparison with human processing.

### Why now
Smaller models can be trained on child-scale input across languages and tested with controlled psycholinguistic suites. Existing human reading-time and acceptability data offer a comparison; activation patching offers a way to test proposed model mechanisms.

### Why you
You lead a junior research group at Stuttgart. Your first-author TACL 2023 paper, without your PhD supervisor, found that agreement errors across 14 languages tracked word frequency rather than syntactic distance. Last-author ACL 2025 benchmark paper with your student. The significance of that output and your distinct contribution to it remain [?]. The Slovenian pilot stays qualitative here.

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



### REVIEWER
**This is a review of one Part I subsection, not the full five-page Part I or your CV.** I am using ERC-2027 guidance, which may be outdated for the next call. On that basis, Step 1 judges the ambition and scientific persuasiveness of the project from Part B1; a reviewer will not have your interview notes to fill gaps in this section.

### Fatal weaknesses and repair priorities

1. **The claimed gap is still unverified.** “The closest published work and the precise novelty of this question remain to be verified [?]” is an honest drafting note, but it cannot survive submission. A specialist’s first question will be whether child-scale multilingual agreement work has already tested this contrast, or whether syncretism is a new label for a known cue-conflict result. **Repair:** establish the closest studies and state exactly what each leaves unresolved. Until then, you cannot confidently claim frontier-level novelty.

2. **The hypothesis does not yet isolate case syncretism.** “If models trained on languages without comparable ambiguity show the same pattern, the hypothesis is in trouble” makes *language* the contrast, although languages also differ in agreement systems, frequencies, word order and training data. A six-language correlation would be hard to interpret. **Repair:** state the decisive *within- and across-language* comparison: what changes between otherwise matched attraction items when the intervening noun’s case cue is ambiguous versus unambiguous, and what observation would favour frequency instead? Explain how that comparison works for languages with substantially different case systems. This is the central scientific design question, not a Part II detail.

3. **The proposed mechanism test promises a cleaner distinction than it can deliver.** “Representations associated with the subject–verb relation” and “representations associated with a nearby noun’s ambiguous case or number cues” are not yet identifiable intervention targets. A syntactic model can also use local morphology; a patching effect on the nearby noun would not establish the *absence* of a syntactic representation. **Repair:** define what contrasting predictions the two accounts make under controlled interventions, and which result would remain ambiguous. Keep the sensible limit you already state: model interventions cannot establish how humans process grammar.

4. **The human comparison is carrying significance without a specified role.** You promise comparison with “available human reading-time and acceptability evidence” while conceding its suitability is unknown. Are human data a target pattern to explain, a test of the syncretism prediction, or context for interpreting model errors? Those are different claims. **Repair:** choose one primary role and say what comparison is interpretable across tasks and languages. Otherwise the human-learning motivation may look attached to a model benchmark rather than tested by the project.

5. **The objectives describe activities more clearly than a breakthrough.** Objective 1 “establish[es] the input comparison”; Objective 2 trains and tests models; Objective 3 applies tools. The strongest idea—*when resemblance in errors is evidence for grammatical structure*—arrives at the end. **Repair:** put the discriminating question and its possible answers in the first half-page, then make each objective close a specific inferential gap. Remove the “[?]” markers and “Open points” from the submitted version.

### How it is likely to read

A neighbouring-field panel member can follow the opening and will appreciate that you do **not** equate similar errors with similar processing. But they may finish unsure why case syncretism, specifically, is the decisive variable rather than one candidate among several correlated cues. A specialist will press hardest on the claimed novelty and whether your design can separate morphology, frequency and language-level differences.

Your interview notes contain useful material that this subsection cannot rely on: the 14-language frequency finding gives a concrete reason to take the rival explanation seriously, and the corpus fallback addresses a real risk. In the full Part I, make the former part of the scientific argument. The latter can be brief here and developed in Part II.

### What already works

- The opening states an identifiable inferential error rather than claiming that another model benchmark is needed.
- Frequency is a genuine competing explanation, not a token control.
- The final paragraph appropriately limits what model–human resemblance and mechanistic tests can establish.

**Hardest unanswered question:** What observation would distinguish a case-syncretism-driven attraction effect from a frequency-driven effect **without treating differences between languages as evidence for either one**?

**Verdict:** This subsection helps by posing a clear, sceptical question; it currently hurts by leaving the novelty unverified and the decisive comparison unspecified. I would not predict a Step 1 outcome from this subsection alone.
