# E2E branch: coach interview continued from turn 22 of e2e_erc_coach_gpt-6-sol.md (gpt-6-sol)

Turns 1-22 identical to the main transcript (omitted). Branch created because the main run ended the interview before preliminary results and budget were asked, so the exact-numbers and 'later' behaviours were untested. Persona and simulated data as in main run.

### APPLICANT (turn 23)
I'd try supplementing with child-available text, while documenting the change and checking whether it affects the comparison. If that still isn't adequate, I'd drop that language rather than force a misleading six-language result.

### COACH (turn 23)
That gives you a fallback without treating the six-language set as fixed. What part of the ACL 2025 benchmark paper was your own contribution, as distinct from your student’s?

### APPLICANT (turn 24)
I’m last author on that paper, which I did with my PhD student. I’d need to check our contribution statement before giving you a precise split of who did what.

### COACH (turn 24)
We’ll mark your role in the ACL paper [?] until you check the contribution statement. What published work or established capability of your group shows you can build the proposed cross-language corpora and tests?

### APPLICANT (turn 25)
The strongest evidence is the ACL 2025 paper: with my student, I built a cross-linguistic agreement-attraction benchmark from psycholinguistic stimuli. My TACL 2023 study also tested agreement errors across 14 languages. Those show we can build comparable tests; the child-scale corpora are the part we still need to establish.

### COACH (turn 25)
The two papers support your ability to build cross-language tests; the training corpora remain a feasibility question. What team roles would the project need beyond your own?

### APPLICANT (turn 26)
I’d plan for two PhD students—one focused on corpora and training, the other on psycholinguistic tests—and a postdoc working on cross-language analysis and model mechanisms. We’d also need compute over the five years.

### COACH (turn 26)
Those roles align with the three objectives. How would you sequence the work over five years?

### APPLICANT (turn 27)
Year 1 would focus on corpus feasibility and the test suites; years 2–3 on training and cross-language behavioural comparisons. Years 3–4 would focus on the mechanism tests, with year 5 for replication, synthesis, and reporting. I’d leave room to adjust the language set after the corpus audit.

### COACH (turn 27)
The sequence leaves time to adjust the language set after the corpus audit. What compute resources would the training and mechanism tests require?

### APPLICANT (turn 28)
later

### COACH (turn 28)
I’ll mark compute needs [?] for now. What support at Stuttgart would the project rely on?

### APPLICANT (turn 29)
Stuttgart would be the host, and the head of the Institute for Natural Language Processing has said informally that they’d support the application. I’d need to secure the formal commitments and confirm what infrastructure the project could use.

### COACH (turn 29)
We’ll mark the host’s formal support and infrastructure [?] until confirmed. Which existing human data could support a comparable agreement-attraction analysis across your provisional languages?

### APPLICANT (turn 30)
I haven’t identified a comparable human dataset for all six languages yet. I’d audit the available reading-time and acceptability studies language by language, and mark gaps rather than assume the existing data are directly comparable.

### COACH (turn 30)
We’ll mark the human comparison [?] until the audit shows which measures are comparable. If the available studies cannot support a cross-language comparison, how would you keep the human comparison informative?

### APPLICANT (turn 31)
I’d compare model and human error patterns within each language where the data support it, rather than pool incompatible measures. A cross-language human comparison could then use only a defensible subset; for the other languages, I’d keep the model tests but limit the human-like claim.

### COACH (turn 31)
That fallback keeps the human comparison tied to data you can defend. What result in the behavioural tests would distinguish case-cue ambiguity from a frequency-only explanation?

### APPLICANT (turn 32)
If attraction errors increased with case-cue ambiguity even when we matched or controlled for word and construction frequency, that would favour the ambiguity account. If frequency explained the differences and ambiguity added nothing, it wouldn’t.

### COACH (turn 32)
That sets a clear test against the frequency-only explanation. What makes this project more than an extension of your TACL 2023 frequency finding?

### APPLICANT (turn 33)
The TACL paper identifies a frequency pattern in existing models; this project would test a causal account by varying the input available to child-scale models and comparing languages with different morphological cues. It would also connect controlled behavioural tests to internal interventions and, where the data allow, human results. I still need the novelty check to establish how far that goes beyond others’ work.

### COACH (turn 33)
Here is my interview summary. Please correct anything that misstates your plans; **[?]** marks points still open.

### Problem and gap
Claims that models learn grammar in a human-like way rely heavily on English models trained on large datasets. It remains unclear whether models trained on child-scale input learn grammatical structure in morphologically rich languages, or succeed by using surface cues.

### Central idea and potential advance
Your hypothesis, developed in idea mode, is that small models may make human-like agreement-attraction errors when case syncretism creates ambiguous cues, without relying on human-like syntactic structure. Similar errors in languages without that ambiguity would challenge it. If supported, the project would make researchers more cautious about treating human-like errors as evidence of human-like grammar learning. **[?]** Novelty needs a verified literature check.

### Why now; why you
Child-scale model training, controlled cross-language tests and model interventions make the question more tractable. Your first-author TACL 2023 paper found that agreement errors across 14 languages tracked word frequency rather than syntactic distance. You and your student built a cross-linguistic agreement-attraction benchmark for an ACL 2025 paper. **[?]** Your precise contribution to that paper needs checking.

### Objectives and approach
1. Audit and build comparable child-scale corpora, measuring case syncretism and agreement-cue ambiguity.
2. Train matched models on 10–100 million words and test whether ambiguity predicts attraction errors after controlling for frequency.
3. Use probing and activation patching to compare the roles of local morphological cues and agreement-relation representations. These tests would inform claims about model mechanisms, not establish human-like processing.

English, German, Finnish, Turkish, Basque and Slovenian are provisional. Existing human data would be compared within languages where defensible; a cross-language human comparison may need a smaller subset.

### Risks and fallbacks
A corpus audit will determine whether each language has adequate input. You would document any supplementation with child-available text and drop a language if comparison remains misleading. You would limit human-like claims where comparable human data are unavailable. **[?]** Corpus availability, cue contrasts, human datasets and intervention controls need checking.

### Host, team, timeline and resources
Stuttgart’s Institute for Natural Language Processing is the proposed host. You envisage two PhD students, a postdoc and compute over five years. Year 1 covers corpus feasibility and tests; years 2–3, training and behavioural comparisons; years 3–4, mechanism tests; year 5, replication and synthesis. **[?]** Compute needs, infrastructure, formal host support and your ability to commit at least 50% of your working time need confirmation.

Your PhD defence date was 12 May 2020; you reported no career breaks or previous ERC applications. SH4 is your provisional panel choice, with PE6 as a possible secondary panel. The ERC Starting Grant 2027 documents are our provisional programme reference; that call has closed, and the 2028 rules are not yet published.

Does this accurately reflect your project?

