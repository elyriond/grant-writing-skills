# E2E test: erc-stg-reviewer, gpt-6-luna

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
**Scope and assumptions.** I’m reviewing only this scientific-question/objectives section, not the full Part I, CV or Part II. You’ve supplied enough context to assess the argument; the main literature and design details remain unverified. I don’t have the ERC Work Programme or Information for Applicants, so my procedural knowledge refers to the ERC-2027 call and may be outdated for the next call.

## Fatal or near-fatal weaknesses

1. **The central premise and novelty are still unverified.**  
   You write: “*The closest published work and the precise novelty of this question remain to be verified [?]*” and later say the “*provisional language set*” and human datasets are still unsettled. That is honest in a working draft, but it leaves a reviewer unable to tell whether this is a frontier question, an extension of established work, or an idea already tested. For an ERC Step 1 reader, the gap and the advance have to be clear in Part I—not deferred to later checks.

   **Repair:** Establish the closest competing studies and state precisely what they do *not* test. Then name the proposed advance in one sentence: what will be learned that existing cross-linguistic, developmental-input or agreement-attraction studies could not establish? Don’t claim novelty until that comparison is verified.

2. **“Case syncretism” is not yet connected convincingly to the predicted agreement error.**  
   The hypothesis says ambiguous case cues may favour a nearby noun, but it is unclear how case syncretism leads to a particular number-attraction error. Case ambiguity and number ambiguity are different, yet Objective 3 shifts to “*ambiguous case or number cues*.” That risks making the explanatory variable expand to cover whatever cue happens to matter.

   **Repair:** Specify the causal chain and the relevant construction: which case forms are syncretic, what grammatical-role ambiguity they create, how that changes the model’s subject estimate, and why that should increase a defined agreement error. Keep case and number ambiguity distinct unless you have a principled reason to combine them.

3. **The cross-language comparison risks treating six unlike languages as six comparable data points.**  
   English, German, Finnish, Turkish, Basque and Slovenian differ in much more than case syncretism: their agreement systems, word order, morphology, available constructions and child-directed corpora may differ. A language-level association across this small set would not isolate case syncretism. “*If models trained on languages without comparable ambiguity show the same pattern, the hypothesis is in trouble*” is not yet a strong falsification test, because other language-specific or training differences could explain that result.

   **Repair:** Make the key test a controlled, within-language contrast where possible, with language-level comparisons as supporting evidence. State what is matched across languages and what variation provides the test. Define in advance what result would count against the hypothesis, rather than relying on a broad contrast between languages.

4. **The behavioural outcome and human comparison are underspecified.**  
   “*Agreement-attraction errors*” and “*human-like error patterns*” could refer to different tasks and measures. You propose controlled model tests, human reading times and acceptability evidence, but those are not interchangeable outcomes. The draft itself acknowledges that dataset suitability is unresolved.

   **Repair:** Name the primary model outcome and the human measure that can validly be compared with it. If there is no direct measure match, say that the human data provide a qualitative or secondary comparison—not a direct test of human-like processing. Also specify the construction and error contrast in enough detail for a neighbouring-field reviewer to understand what is being measured.

5. **Objective 3 promises more mechanistic inference than the stated methods warrant.**  
   “*Probing and activation patching will test whether agreement predictions depend more on representations of agreement relations or on local morphological cues*” overstates what these methods establish without a concrete intervention design. Probing can reveal decodable information without showing that a model uses it; patching effects can reflect position, lexical content or other correlated information. “*Little corresponding effect*” also needs a defined comparator.

   **Repair:** Frame this as testing a specific causal contrast in model predictions, not identifying a model’s full grammatical representation. Briefly state the intervention logic and the key controls. Keep the final sentence’s important limit—“*they cannot establish that models and humans process grammar in the same way*”—but make the preceding claim equally precise.

## Other weaknesses a panel is likely to notice

- **Objective 1 reads like project setup, not a scientific objective.** “*Assemble comparable child-scale training corpora*” is necessary work, but the objective should make clear what scientific uncertainty the corpus analysis resolves.
- **“Child-scale” needs careful definition.** Equal word counts across languages do not necessarily imply comparable developmental input. The interview notes already acknowledge uneven corpus availability; that threat should be reflected in the core design, not left only to a later risk section.
- **The relationship to your prior result needs sharpening.** You cite your finding that errors tracked frequency rather than syntactic distance, then say this project tests ambiguity “*once frequency is taken into account*.” A reviewer may see this as a follow-on analysis of your existing result unless you explain what new conceptual or empirical test it enables.
- **The language set is doing too much work while still provisional.** Don’t retain six languages for appearance of breadth if the available corpora or matched constructions cannot support the test. A smaller, defensible set is stronger than a broad but non-comparable one.
- **The draft contains visible drafting notes.** All three “[?]” markers and the “Open points” list must disappear from a submitted version. More importantly, the underlying uncertainties need to be resolved; deleting the markers alone won’t fix the argument.

## How a neighbouring-field reviewer may read it

The opening is accessible and the project’s caution about interpreting human-like errors is sensible. But the reviewer may reach the end without knowing whether the project tests a **case-syncretism effect**, a **general cue-based account**, or a **cross-linguistic model–human comparison**. Those are related, but they are not yet one tightly specified test. The section also does not yet tell them why this particular comparison will change the field’s understanding, rather than add another set of multilingual model results.

## Repair priorities

1. Verify the novelty claim and identify the closest work that leaves this question open.
2. Define the causal link from case syncretism to the specific agreement-attraction outcome; separate case from number ambiguity.
3. Build the test around controlled contrasts and make the cross-language comparison secondary unless comparability is demonstrable.
4. Specify the primary outcome and the limits of the human-data comparison.
5. Narrow the activation-patching claim to an operational, controlled test.
6. Recast the objectives so each states a scientific question and an informative possible result—not only a task.

## Short verdict

**The core idea is potentially interesting, but this section is not yet ready to carry a Step 1 case for funding.** Its strongest feature is the disciplined refusal to equate model–human error resemblance with shared processing. Its main weakness is that the proposed causal variable, cross-language design and evidence for mechanism are not yet specified tightly enough to show that the project can distinguish the rival explanations. I would not assign an A/B/C outcome from this excerpt alone; as written, the unresolved novelty and design questions would make the section more likely to hurt than help.
