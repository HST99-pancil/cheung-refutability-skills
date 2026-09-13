---
name: three-step-logic
description: Quick logic check for an idea that is still forming. Turns a hunch, hypothesis or half-written thesis into a three-step hypothetical syllogism (if A then C, plus a second line, plus what follows), shows which of the four inference moves it is making, and writes the one sentence that would kill it. Use whenever the user is brainstorming, formulating a hypothesis, sketching a column or paper idea, asks "does this logic hold", "is this a valid inference", "what follows from this", or writes an "if... then..." or "because" sentence they are not yet sure of, in English or Chinese. Lighter than refutability-audit, so use this first and escalate to refutability-audit when the idea is ready for a full test.
---

# Three-Step Logic (三步邏輯)

## What this is for

Ideas arrive as a hunch with a "because" in it. Before building on one, put it through the simplest structure that exposes whether it can be tested at all: a hypothetical syllogism. Line one is the conditional. Line two is the case you have in hand. Line three is what follows, and only two of the four possible second lines let anything follow. This is the logical core of Steven Cheung's (張五常) method in 《經濟解釋》: a theory is useful only if it yields a "if 甲 then 乙" whose failure you could observe.

Keep the whole thing short. This skill is for shaping an idea in a minute, not auditing it. When the idea survives and the user wants the full treatment (observability table, constraint conditions, five disqualifiers, priced rescue), hand off to `refutability-audit`.

## The three steps

### Step 1. Write the conditional

Restate the idea as one line: **If A, then C.** A is the antecedent, the thing that changes. C is the consequent, what should follow.

Two requirements, both from Cheung. A must be a change in something observable (a price, a rule, a cost, an entry cutoff), because a factor that did not change cannot explain a change. C must be something you could see or count, because 看不到則驗不着, what cannot be seen cannot be tested. If either side is a feeling, a motive or an attitude, write the observable stand-in next to it and use that instead.

### Step 2. Add the second line and read off the third

The user has one of four second premises. Only two of them license a conclusion.

| Second line | Third line | Status | What it is |
|---|---|---|---|
| A is the case | C should follow | Valid | The prediction. Go and look for C. |
| C is absent | A is not the case, or the idea is wrong | Valid | The test. This is the only line that refutes. |
| C is present | Nothing follows about A | Invalid | Confirmation is not proof. Other causes produce C. |
| A is absent | Nothing follows about C | Invalid | Denying the antecedent. Attacking the assumption says nothing about the prediction. |

Say which row the idea, or the objection to it, is sitting in. Most half-formed ideas sit in row three: "C happened, so my A must be behind it." Most objections sit in row four: "your A is unrealistic, so your C will not happen." Cheung's reply to row four: idiots build petrol stations at random, only the roadside ones survive, and the survivors match the maximising prediction though none of them maximised.

### Step 3. Write the kill sentence

One sentence: **"If I see A with C absent, in [where, when], the idea is dead."** Concrete enough that two people would agree whether it happened. Add one line on where to look. If no kill sentence can be written, the idea is not yet an idea about the world; say which side, A or C, needs an observable before it can be one.

## Output

A card of at most 120 words, in the user's language:

```
If A, then C:   <one line, observables on both sides>
Your line two:  <which row of the grid, and whether it is valid>
Kill sentence:  <If I see A with C absent, in ..., the idea is dead.>
Where to look:  <one line>
Status:         Ready to test / Needs an observable for A or C / Needs a real change in A
```

If the idea is ready and the user is writing, offer the full audit in one line. Do not run it unasked.

## Calibration

- Do not improve the idea beyond what the user said. Restate it in their words, then check it.
- One conditional per card. If the user's sentence contains two "because" clauses, split it and do two cards.
- A ready-to-test idea is not a true idea. Status "ready to test" means the kill sentence can be written, nothing more.
- Reply in the user's language. Chinese terms to keep: 前件 (antecedent) 後件 (consequent) 局限條件 (the constraint that changes) 否決前事的謬誤 (denying the antecedent) 看不到則驗不着 (what cannot be seen cannot be tested).
