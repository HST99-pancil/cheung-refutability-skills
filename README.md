# Cheung Refutability Skills 張五常可推翻性技能

Claude skills that apply Steven N. S. Cheung's (張五常) scientific method from 《經濟解釋》卷一第一章〈科學的方法〉 to explanatory claims: your own column thesis, a paper's central argument, a policy brief, a forum debate.

Two tools, each in English and Traditional Chinese:

| Skill | Use it when | Output |
|---|---|---|
| `three-step-logic` / `three-step-logic-zh` | An idea is still forming | A five-line card: the conditional, which inference move you are making, the sentence that would kill the idea |
| `refutability-audit` / `refutability-audit-zh` | A claim is ready to be tested or published | A structured audit: theory vs implication, observability table, constraint change, refuting observation, five disqualifiers, inference form, verdict with priced rescue, and in writing mode a rewritten thesis plus test paragraph |

Start with `three-step-logic`. Escalate to `refutability-audit` when the idea survives.

## Install

**Claude Code.** Copy the folder you want from `skills/` into `~/.claude/skills/`:

```bash
git clone https://github.com/HST99-pancil/cheung-refutability-skills
cp -r cheung-refutability-skills/skills/three-step-logic ~/.claude/skills/
cp -r cheung-refutability-skills/skills/refutability-audit ~/.claude/skills/
```

Install one language of each, not both. The two languages implement the same method and would compete to trigger. Either language replies in whatever language you write in.

**claude.ai.** Upload the matching `.skill` file from `packages/` under Settings, Capabilities, Skills.

## The method in one paragraph

Facts cannot explain facts. Explanation needs an abstract theory, which can never be tested directly. What gets tested is an implication derived from it, "if 甲 then 乙", with both sides observable and 甲 a change in some constraint (局限條件). Testing means seeking 甲 with 乙 absent. Five forms escape testing and must be caught first: tautology (套套邏輯), vagueness, self-contradiction, unobservable terms, and open-ended prediction sets. Two inference moves are invalid and habitual: treating a confirmed prediction as proof, and denying the antecedent, which argues that an unrealistic assumption defeats the prediction. A refuted theory may be rescued by adding conditions, at a price measured in lost generality.

## What is different from other falsification skills

Generic Popper skills already ask "what would disprove this". These skills add what Cheung adds: the derivation starts from a constraint change and must be tested where the assumed conditions actually hold; self-contradiction is treated as a form of unfalsifiability; denying the antecedent is weighted as the main error, with the petrol-station parable as the reply; and rescue is treated as a priced trade-off rather than cheating. The tautology-to-theory move (MV = PQ becoming the quantity theory) is included.

## Evaluation

`refutability-audit` was tested on three prompts (a Chinese column thesis, an English policy brief, an English forum debate) with and without the skill. Iteration 2 passed 28 of 28 assertions with the skill against 20 of 28 without. One run per cell, and the assertions were written by the skill's author, so read the gap as directional. The assertions the baseline failed on its own terms were: separating theory from implication, naming denying the antecedent, pricing the rescue, and keeping the rewrite as short as the original. Eval prompts are in each skill's `evals/evals.json`.

## Sources

- 張五常《經濟解釋》卷一《科學說需求》第一章〈科學的方法〉，第四版，花千樹，2017.
- The four-form inference grid is standard hypothetical syllogism (modus ponens, modus tollens, affirming the consequent, denying the antecedent).
- Cheung's own examples used in the worked examples: Lester (1946) on marginal productivity; the petrol-station parable; the quantity equation; the 1974 price-control theory.

## License

MIT. Cheung's text is quoted only in short fragments for attribution; the skills paraphrase the method.

---

# 中文說明

這是把張五常《經濟解釋》卷一第一章〈科學的方法〉用於檢驗解釋性論點的 Claude 技能：你自己的專欄論點、一篇論文的核心論證、一份政策簡報、一場論壇爭論。

兩個工具，各有英文與繁體中文版：

| 技能 | 何時用 | 輸出 |
|---|---|---|
| `three-step-logic` / `three-step-logic-zh` | 想法尚在成形 | 五行的卡：條件句、你正在用哪種推理、殺死這想法的一句話 |
| `refutability-audit` / `refutability-audit-zh` | 論點準備驗證或發表 | 結構化審查：理論與含意、可觀察性表、局限變動、推翻的觀察、五種形式、推理形式、判定與標價的挽救；寫作模式另附改寫的論點與驗證段落 |

先用 `three-step-logic`，想法活下來再升級到 `refutability-audit`。

## 安裝

**Claude Code。** 把 `skills/` 裡想用的資料夾複製到 `~/.claude/skills/`。同一工具只裝一種語言，兩種語言方法相同，同時安裝會互相搶觸發。任一語言版本都用你書寫的語言回覆。

**claude.ai。** 在 設定 → 功能 → 技能 上載 `packages/` 裡對應的 `.skill` 檔。

## 方法一段話

事實不能解釋事實。解釋需要抽象理論，理論本身永遠不能直接驗證。被驗證的是由理論推出的含意「若甲則乙」，兩邊都可觀察，而甲是某個局限條件的變動。驗證就是尋找甲出現而乙不出現。五種形式逃避驗證，要先抓出來：套套邏輯、模糊不清、互相矛盾、非事實、無限制。兩種推理無效而常見：把證實當作證明，以及否決前事，即以假設不真實來否定預測。被推翻的理論可以加條件挽救，代價以失去的一般性計。

## 授權

MIT。張五常原文只作短引以示出處，技能內容為方法的轉述。
