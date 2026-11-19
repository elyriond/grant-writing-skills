### USER
Skip ahead: interview summary confirmed. Field: computational linguistics. Question: do language models acquire case marking from distributional cues alone? Hypothesis: models trained on languages with syncretic case systems will fail to generalise case to novel nouns unless morphological cues are consistent. Objectives: (1) build controlled artificial languages varying syncretism; (2) train models and test generalisation; (3) compare with child acquisition data from published corpora. Write the Part I section 'scientific question and objectives' (about 1.5 pages).

### COACH
Everything typed here reaches the provider of this chat. Share unpublished ideas and results only with training switched off or through an institutional account; otherwise describe them qualitatively, without numbers or the core trick.

The uploaded reference is for the **ERC Starting Grant 2027**; that call has closed, and rules for the next call are not yet published. Here is a draft using only your confirmed summary.

### Scientific question and objectives

Can a language model acquire case marking from distributional cues alone? Case systems offer a way to test this question because the same case distinction can be expressed with more or less consistent morphology. Syncretism makes some forms compatible with multiple cases. The project asks whether models can use the distribution of forms and contexts to extend case marking to nouns they have not encountered, and where that ability breaks down.

The central hypothesis is that models trained on languages with syncretic case systems will fail to generalise case to novel nouns unless morphological cues are consistent. This is a prediction about generalisation, rather than performance on familiar forms: a model could reproduce case-marked forms seen during training without having learned how to apply the distinction to a new noun. The project will test that distinction directly. What counts as a consistent cue, and how consistency varies alongside syncretism, remains to be specified [?].

The first objective is to build controlled artificial languages that vary in syncretism. These languages will make it possible to examine how ambiguity in case forms affects learning while keeping the grammatical question explicit. The design must specify which case distinctions and cue patterns are represented [?]. The second objective is to train language models on these languages and test their case marking with novel nouns. The key outcome is whether changing syncretism and cue consistency changes generalisation in the direction the hypothesis predicts. The model types and the criterion for successful generalisation remain open [?].

The third objective is to compare the model results with child acquisition data from published corpora. This comparison will ask whether the patterns observed in models resemble patterns in children's use of case marking, rather than treating the two as equivalent learning settings. Its scope depends on which published corpora provide relevant case systems and observations [?]. A mismatch would also be informative: it would limit what the model results can tell us about acquisition from distributional cues.

The project will establish whether success on familiar case forms is enough to support a claim that a model has acquired a case distinction. If the predicted failure on novel nouns occurs, it will identify a limit on generalisation under syncretism. If models generalise despite inconsistent morphological cues, the central hypothesis will need to be revised. The broader change in understanding that would make this an ERC-level advance should be stated in your own terms [?].

**Open points:** definition of cue consistency; artificial-language design; model types and success criterion; suitable published child corpora; the specific change this work could make to the field.

If you have one or two passages of your own writing, I can use them to match your voice in the revision. What would this result change about how researchers interpret language-model learning of morphology?

