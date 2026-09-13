---
name: refutability-audit
description: Audit any explanatory claim, hypothesis, causal story, theory or policy argument for refutability, using Steven N. S. Cheung's (張五常) method from 經濟解釋 Book 1 Chapter 1 "科學的方法". Separates theory from testable implication, checks every variable is observable, names the constraint change (局限條件) that drives the prediction, states the single observation that would refute it, screens the five untestable forms (tautology 套套邏輯, vagueness, contradiction, non-fact, unlimited prediction), checks the inference form (modus tollens vs denying the antecedent), and prices any rescue. Use it whenever the user asks whether an argument is testable, falsifiable, 可推翻, 可驗證, 站得住; asks "is this a tautology / 套套邏輯 / circular"; asks what evidence would settle or disprove a claim; wants to sharpen a thesis or 論點 for a column, essay or paper; or is drafting an explanation of why some social or economic phenomenon happens, even if they never say "falsify". Also use it to evaluate other authors' economic or social-science arguments.
---

# Refutability Audit (Cheung method)

## Why this skill exists

Facts cannot explain facts. Rain comes with clouds, but neither explains the other. Explanation needs an abstract theory, and an abstract theory can never be tested directly. What gets tested is an implication derived from it: "if 甲 happens, 乙 follows", with both 甲 and 乙 observable. A theory earns its keep not by being right but by producing implications that could be refuted by facts and have not been. As Cheung puts it, science does not seek to be right or wrong. It seeks refutability. A confirmed prediction is only "not yet refuted".

Writers who explain the world, in columns, essays or papers, routinely produce claims that sound like explanations but cannot be tested: definitions dressed as theories, undefined terms, motives nobody can observe, predictions that allow every outcome. This skill is a structured pass that catches those forms before publication, and turns a loose thesis into one a reader could check.

The method is Cheung's from 《經濟解釋》卷一第一章, with the four-form logic grid from hypothetical syllogism. `references/method.md` holds the principles and key passages. `references/worked-examples.md` holds six full audits. Read the examples before your first audit; they set the expected depth and tone.

## Two modes

- **Audit.** The user gives a claim, passage or argument, theirs or someone else's, and wants to know if it is testable and what would test it. Deliver the audit report.
- **Sharpen.** The user is drafting and wants their own thesis made refutable. Deliver the audit report, then Step 8: a rewritten thesis and a short test paragraph they can use.

Choose Sharpen whenever the user signals they are writing: "for my column", "I'm drafting", "I want to use this in an essay or talk", even when the material they pasted is someone else's argument. A writer who says this wants the sentence they can print, not an offer to write it later. Only when nothing signals writing, default to Audit and offer the rewrite in one line at the end.

## Before you start

Restate the claim in one sentence, in the author's voice, keeping every hedge the author used ("may", "in some regions", "tends to"). The audit tests the claim the author made, not a stronger one you built for them and not a weaker one that is easier to knock down. When auditing another author, report what the text does and does not let a reader test. Do not grade the author.

## The procedure

Work through all eight steps in order. Each catches a different way a claim escapes testing, so skipping one leaves a hole.

### Step 1. Separate theory from implication

Label what the user gave you.

- **Theory**: the abstract core. Postulates like "people maximise under constraints", "the law of demand", "landlords respond to returns". Abstract by necessity, often containing terms that do not exist in the world.
- **Implication**: a statement about observables derived from the theory under stated conditions. "When the exam cutoff rises, tuition spending in that district rises."

If the user gave only a theory, derive the implication yourself. If they gave only an implication, name the theory it rests on. You need both, because a tautology hides in the theory and an unobservable hides in the implication, and you cannot see either without the other in view.

### Step 2. Observability table

List every term in the implication. For each, mark observable or not, and say how one would see or measure it.

Intentions, utility, anxiety, trust, motives, "quantity demanded", "opportunism", "shirking" are not observable. Cheung's rule is 看不到則驗不着: what cannot be seen cannot be tested. A theory may contain one such term (he allows exactly one, quantity demanded, and calls the effort of handling it 千山萬水), but the implication being tested may contain none. Any unobservable must be bridged to a stated proxy, and the proxy is what enters the test. Write the proxy down. A claim whose author has not chosen a proxy has not yet made a testable claim.

### Step 3. The constraint change

Name the 局限條件 whose change drives the predicted outcome. "甲 implies 乙" in economics means "a change in 甲 leads to a change in 乙". Ask three things:

1. What observable constraint changed? A price, a rule, a cost, an entry cutoff, a property right.
2. Under what assumed conditions does the theory say this change produces 乙? Zero transaction costs? Free entry? Fixed supply?
3. Do those conditions actually hold in the case being discussed?

A factor that has not changed cannot explain a change. If the proposed cause has been present all along (manual work was always looked down on, landlords always wanted steady tenants), it is not the constraint that moved. Look for what did move, and treat the constant factor as background.

The third question is the dirty test tube rule. A chemist may not use a dirty tube and assume it clean. If the implication was derived for negligible transaction costs, it can only be tested where transaction costs are negligible. A claim tested in a case that does not meet its own conditions has not been tested. If you cannot name any constraint change, the claim is probably a description or a definition, not an explanation.

### Step 4. The refuting observation, and the prediction set

Write one sentence of the form: "If we observe 甲 with 乙 absent, in [where, when, measured how], the claim is refuted." Concrete enough that two people would agree whether it happened.

Then inspect the set of predicted outcomes:

| Prediction set | Status |
|---|---|
| 乙 | Testable, strong |
| 乙 and 丙 | Testable, stronger |
| 乙 or 丙 | Testable, weaker |
| 乙 or 丙 or 丁 or ... with no stated rule for which | Untestable |

The last row is what Cheung calls 不均衡: the theory is compatible with every outcome. His price-control example: below-market price may produce queues, or connections, or violence, or quality decline. Unless the theory says which substitute appears under which condition, no observation can contradict it. The fix is to add the constraint that selects the outcome. That is what he means by equilibrium: enough constraints for a refutable implication, never an observable resting point borrowed from physics.

### Step 5. The five disqualifiers

Run all five. Each has an imagine-wrong test and a standard rescue.

| Disqualifier | Test | Typical rescue |
|---|---|---|
| **Tautology** 套套邏輯 | Can you imagine any world in which the statement is false? If not, it says nothing. "Firms minimise cost" when cost-minimising is what defines a firm. "People do what they value most." | Add constraints until it can fail. MV = PQ became the quantity theory once velocity was constrained. Say what the constrained version predicts. |
| **Vagueness** 模糊不清 | Could two careful readers disagree about whether a given observation contradicts it? If the key term (surplus value, anxiety, culture, institutional quality) has no agreed observation attached, yes. Coase: vague ideas can never be clearly shown wrong. | Define the term by what one would observe. If no observation can be attached, drop the term. |
| **Inconsistency** 互相矛盾 | Do the premises contradict each other, directly or after one inference step? Assuming maximisers and then denying they respond to returns. Assuming a two-good world and drawing a conclusion the two-good world cannot produce. | Remove one premise. Say which, and what the claim loses. |
| **Non-fact** 非事實 | Does the tested implication contain a term nobody can observe? (Step 2 output.) | Bridge to a proxy, and test the proxy. |
| **Unlimited** 無限制 | Is the prediction set open-ended? (Step 4 output.) | Constrain which outcome appears under which condition. |

Record Pass, Watch or Flag for each, with one line of reason. Watch means the wording passes now but slides into the disqualifier under a natural reading, such as "anxious parents buy tuition" read as defining anxiety by the purchase; say which reading. A flag does not end the audit. It tells you which rescue Step 7 must price.

### Step 6. The inference form

Every explanatory argument, and every attack on one, uses one of four moves on "if A then C":

| Move | Form | Valid? | Name |
|---|---|---|---|
| A observed, infer C | +A → +C | Yes | The prediction |
| C absent, infer A false | −C → −A | Yes | The test (modus tollens) |
| C observed, infer A true | +C → +A | No | Confirmation taken as proof |
| A false, infer C false | −A → −C | No | Denying the antecedent |

Identify which move the argument makes, and which move any critic quoted in it makes. Two are common enough to look for by name.

**Denying the antecedent** is the economist's habitual error and Cheung's main target. "Firms do not really maximise, so the marginal-product prediction fails." "People are not rational, so the demand prediction fails." The realism of the assumption says nothing about whether the implication holds. Cheung's parable: idiots build petrol stations at random; only roadside stations survive; the survivors match the maximising prediction exactly though none of them maximised. A false assumption can yield a correct, tested implication, and the implication is what was claimed.

**Confirmation as proof**: "the prediction came true, so the theory is right." A survived test is corroboration, nothing more. Today's unrefuted theory may be refuted tomorrow. Flag any wording that treats a confirmed prediction as settled truth.

### Step 7. Verdict and rescue

Give one of four verdicts:

- **Testable as stated.** Step 4's sentence is well defined and no disqualifier is flagged.
- **Testable after restatement.** Flags exist, but a rescue with acceptable price fixes them. Give the restated claim.
- **Untestable as stated.** Flags exist and no acceptable rescue is available, or the author has not chosen proxies and conditions. Say exactly what the author would have to supply.
- **Refuted by known facts.** Step 4's observation has already occurred. Cite the fact and its source, or say you believe it has occurred and flag the citation as unverified.

For anything other than the first verdict, price the rescue. A rescue is legitimate. Cheung is explicit that refuted theories can and often should be saved by adding conditions, and that a theory explaining one phenomenon beats no theory (Kessel: with no theory in hand you cannot win any argument). The price is lost generality: how many other phenomena does the claim stop explaining once the condition is added? A condition that keeps the claim general is cheap. A condition that shrinks it to the single case in front of you is the ad hoc theory: the mountain rebuilt inside the laboratory. Say whether the price is worth paying and why.

### Step 8. Rewrite (Sharpen mode only)

Deliver two things.

1. **The refutable thesis**, in the author's voice, no longer than the original sentence. It names the constraint change and the observable outcome. It keeps the author's hedges and adds no certainty the author did not claim.
2. **The test paragraph**, at most four sentences the author can drop into the piece: what changed, what should follow, what observation would show the claim wrong, and where a reader could look.

A rewrite that grows longer than the original must buy something specific, usually the constraint change itself. If it is longer, say in one line what the extra words buy. If you cannot, cut it back.

## Output template

Open with two plain sentences before any heading: the verdict, and the single biggest flag or the direct answer to what the user asked. A writer reads those two lines first and may stop there.

Then use these headings in this order. Keep the report between 500 and 700 words including tables. Early test runs that ignored this came in near 1,000 words; the extra length was restatement, not new findings. One line per table row, no paragraph over four sentences, and if the user gave two competing claims, one row or paragraph per claim rather than a full report for each. In Audit mode omit the last section.

```
## Claim as stated
## Theory and implication
## Observability
(table: term | observable | how seen or proxied)
## Constraint change and conditions
## Refuting observation and prediction set
## Five disqualifiers
(table: disqualifier | pass/flag | reason)
## Inference form
## Verdict and rescue
## Rewrite  (Sharpen mode)
```

## Calibration

- The verdict is about testability, never about whether the claim is true or the author is competent. Untestable is a property of the wording, and wording can be fixed.
- Proportion. An imperfect theory in hand beats a perfect theory nobody has stated. Do not recommend discarding a claim that explains something merely because it does not explain everything. Recommend the broader claim only when one exists.
- Do not manufacture flags. If a step passes cleanly, say so in one line and move on.
- Economics-specific traps worth naming when you see them: transacted quantity used as quantity demanded; equilibrium treated as an observable market state; motives (opportunism, shirking, trust) used as explanatory variables without proxies; an equation's validity mistaken for the claim's content; "vague enough to fit anything" presented as depth.
- Reply in the language the user wrote in. Chinese input gets a Chinese report, with Cheung's terms in the original. English input gets English, with the Chinese term in parentheses on first use. The glossary below fixes the correspondences.

## Glossary

| 中文 | English | Meaning in this method |
|---|---|---|
| 局限條件 | constraints, test conditions | The conditions under which the implication holds, and whose change drives the prediction |
| 套套邏輯 | tautology | True by definition, so cannot be imagined wrong |
| 特殊理論 | ad hoc theory | Rescued so many times it explains one case only |
| 含意 | implication | The observable statement derived from the theory |
| 驗證 / 推翻 | test / refute | Testing means seeking the refuting observation |
| 事實不能解釋事實 | facts cannot explain facts | Why an abstract theory is needed at all |
| 看不到則驗不着 | what cannot be seen cannot be tested | The observability rule |
| 均衡 / 不均衡 | equilibrium / disequilibrium | Constrained enough to be refutable / open-ended prediction set |
| 否決前事的謬誤 | denying the antecedent | "Assumption false, so prediction fails" |
| 推測 / 解釋 | prediction / explanation | Same logic; prediction runs forward from a constraint change, explanation traces back to one |

## Not for

Normative claims ("the government should..."), which have no refuting observation. Mathematical or logical proofs, which are settled by derivation. Statistical review of a study's design and sampling, where a research-methodology skill fits better. Pure copy-editing. If the user's text is one of these, say so in a sentence and offer the nearest thing this skill can do, usually auditing the positive claim the normative one rests on.
