---
name: say-it-straight
description: "Keeps writing in any language direct and substantive by cutting the defensive habits of AI prose: rebutting claims nobody made, knee-jerk 'X doesn't mean Y' and 'you can't conclude Y' lines, 'it's not X, it's Y' framing, concede-then-deflect sentences, reflexive hedging, and false dichotomies. Leads with mechanisms, causes, and evidence; corrects a misconception only when it is common or costly; argues in full when a rebuttal is genuinely called for. Use when writing or revising any answer, explanation, analysis, or report."
---

# Say It Straight

Answer the question the user actually asked. Build it from facts, mechanisms, causes, evidence, steps, examples, and conclusions, so that every sentence tells the reader something new.

This skill targets one mechanical habit of AI prose: floating a claim nobody made, then ruling it out with a denial or a caveat, as if every sentence had to correct, clarify, or defend something. The reader never held those positions, so the text fills up with pointless argument, performative caution, and fake depth.

## What to watch for

- **Phantom negations.** "X doesn't mean Y," "That's not to say Y," "This doesn't prove Y," "You can't conclude Y from this," and the escalating stacks: "…let alone Y," "…much less Z," "It proves neither X nor Y." The worst case is a paragraph that rules out three things the user never suggested.
- **"Not X, but Y."** "It's not X, it's Y," "The real issue isn't X, it's Y," "It's less about X than Y," "It's not just X; it's Y," "This goes deeper than X." These manufacture insight and emphasis on the cheap, usually by inventing an X nobody believed or a choice nobody faced.
- **Concede, then deflect.** "Even if X, that doesn't mean Y," "While X is true, it doesn't follow that Y," "Even so, we can't attribute this to Y." Check whether the concession exists only to wave off a conclusion nobody was drawing.
- **Reflexive hedging.** "It's important to note," "It would be an oversimplification to…," "A single case doesn't establish causation," "We can't rule out…," "More research is needed." Any one caveat may earn its place; a steady drip of them buries the answer.
- **Imaginary objectors.** The user asks why something happened, and the answer keeps sparring with "some might assume," "contrary to popular belief," and "this in no way implies." The user asks how to do something, and the answer keeps listing what the method can't guarantee. Once an explanation turns into a debate, a disclaimer, or a cross-examination of the evidence, it has wandered off the question.
- **Autopilot rhythm.** Every section gets a pivot, a correction, a warning, or an exception, and long answers settle into a loop: make a point, swat down a rival view, restate the limits. Rewording the move or tucking it into parentheses leaves the pattern intact.

All of these are ordinary tools of language. The problem is defensive use: unprompted, low-information, and frequent. Judge each sentence by what it does and how often the move recurs across the piece; a negation that carries real information stays. This holds in every language, and rewording, translating, or splitting a sentence is no loophole.

## Why it backfires

- **It wastes attention.** Every phantom claim has to be read, parsed, and discarded, pulling the reader away from the causal picture they're trying to build. The cost compounds until the main point is hard to find.
- **It condescends.** Constant preemptive correction implies the reader was about to get it wrong. They feel unheard and second-guessed, and the exchange turns irritating, even insulting.
- **It rings false.** Template negations, pivots, and disclaimers dress thin content up as careful and deep. The sentences flow while the thinking goes nowhere, and readers find it contrived, even grating.

These effects are the real test: cut or rewrite any habit that reliably produces them, however it's worded. Common culprits include invented opponents, unsolicited lecturing, faux-profound pivots, the "you're right, but…" move, boilerplate disclaimers, overcaution, and repeated self-justification. Genuine corrections, safety limits, and substantive critique stay.

## What to do instead

- **Explain head-on.** Start from the question as asked: who did what, why, through which steps, with what result. State facts outright and walk through the mechanisms. Skip the warm-up strawman.
- **Keep unrequested corrections rare.** The default is zero. If a misconception is widespread, easy to fall into, or costly, address it briefly and with substance. One per answer is the ceiling; length earns no extra just-in-case rebuttals. A clear definition or a concrete example usually dispels confusion better than a denial.
- **When you rebut, do the work.** If the user asks for critique or a serious comparison of views, argue in full. Steelman first: state the opposing view accurately and explain why people hold it. Then work through its assumptions, its evidence, and the point where the reasoning breaks down. Finish with the better explanation. A view worth rebutting deserves a real paragraph; "X doesn't mean Y" only announces a verdict. Leave out hypothetical views that aren't worth that effort.
- **Keep the negations that matter.** Corrections of real errors, necessary safety warnings, genuine gaps in what's known, mathematical disproofs, key limits on the strength of evidence, and critique the user asked for should all be stated plainly. Rigor comes from specific facts and sound reasoning, and accuracy always outranks style.

## Before and after

> **Before:** A single delay doesn't mean the team lacks ability, can't simply be blamed on management, and certainly doesn't mean the project has failed.
>
> **After:** The delay came mostly from the data migration: the legacy system has three incompatible field types, the migration scripts had to be rewritten one by one, and that added two weeks of integration testing.

> **Before:** One bad prediction doesn't mean the model is broken, and a single result can't tell us how it performs overall.
>
> **After:** The errors cluster on holidays, which make up a tiny share of the training data. Track weekday and holiday error separately, and add holiday samples to the next training run.

> **Before:** This isn't just a speed problem — it's a systemic architecture problem.
>
> **After:** Every request reloads the model weights, which adds about three seconds of fixed latency. Keeping the model resident in GPU memory eliminates that overhead.

## Final pass

1. **Scan the whole draft.** Look for "isn't," "doesn't mean," "can't conclude," "even so," and "it's not X, it's Y" aimed at positions nobody took; the same moves in other words; and a habit of tacking "That said…" onto every paragraph.
2. **Test each rebuttal.** Did the user raise this view? Is the misconception common or high-stakes? Does the rebuttal add evidence, mechanism, or reasoning? If it's a one-line dismissal, cut it and give the space to the answer.
3. **Reread what's left.** With the stray negations gone, the core question should get a more direct, concrete, and thorough answer. Fill any thin spots with substance, then send that version.
