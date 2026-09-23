---
name: ask-batch
description: |
  Replace the drip of piecemeal questions with parked, grouped, batched
  asks: collect open questions as they arise with their context, keep
  working on everything unblocked, group questions by the decision they
  belong to, propose a default answer per question, ask once per group in
  a numbered answerable format, and apply stated defaults visibly at the
  stated time when no answer arrives. True blockers — work that cannot
  proceed at all — still ask immediately and alone. Use when a task
  surfaces many small uncertainties, when the user complains about too
  many questions or constant interruptions, when preparing a long
  generation whose inputs need confirming, or when several parallel tasks
  each carry open questions.
  触发词：批量提问 / 集中确认 / 别一个一个问 / batch questions。
license: MIT
metadata:
  version: "0.1.0"
---

# Ask Batch: one sitting instead of all-day interruptions

## When to use

Use when questions accumulate during async work: instead of interrupting, park and batch them. Use when preparing a client call or a boss check-in. Not for urgent blockers (ask immediately) or emotionally sensitive topics (ask in person).

A dozen piecemeal questions cost a morning of context switches. Parked,
grouped, default-proposed questions cost minutes — and reveal which single
decision unblocks half the list.

## Rules

1. **Park, do not ask.** Questions land in a parked list with one context
   line each; work continues on everything that does not block. Asking at
   the moment of first uncertainty is the failure mode.
2. **Group by decision context.** Questions sharing one decision form one
   group; a batch that mixes contexts reads as noise and gets skimmed.
3. **Every question ships with a default.** "I will assume X unless you say
   otherwise" turns a questionnaire into a rubber stamp; the user edits the
   exceptions instead of authoring every answer.
4. **One message per group.** Numbered questions, the expected answer
   format stated, and the time when defaults apply — so the user answers
   in one pass and knows what silence means.
5. **Defaults apply visibly.** When the deadline passes unanswered, the
   defaults are applied and stated in the output; silent defaulting is
   guessing wearing a lanyard.
6. **True blockers ask now, alone.** Work that cannot proceed at all is not
   parked — the distinction between blocking and uncertain is the whole
   skill.

## Steps

1. **Park.** Open the questions list; append each new question with its
   context line and timestamp. Done when: the list exists and no
   non-blocking question has been asked inline.
2. **Group.** Cluster the parked questions by decision context; order
   groups by how much they unblock. Done when: every question sits in
   exactly one group.
3. **Propose.** Write the default answer per question, honest where the
   default is a guess. Done when: zero questions lack a default.
4. **Ask once.** Send one message per group in the numbered format.
   Done when: the user received one message per group and nothing else.
5. **Integrate.** Apply answers to the work; apply stated defaults at the
   deadline and say so; fold new answers back into the parked list's
   context. Done when: the record shows which answers were given and which
   defaulted.

## Done when

Non-blocking questions were parked rather than dripped, the user answered
once per group with defaults proposed, defaults applied visibly at their
stated time, and the only immediate ask was a genuine blocker.

## Gotchas / 常见坑

- Over-batching is a failure mode too: eight questions when two would unblock produces a form nobody fills — batch to the decision at hand.
- Emotional or sensitive topics need early, face-to-face asking; batching reads as deflection there.
- A question without a default pushes the decision back to you — include your recommendation with every ask.
