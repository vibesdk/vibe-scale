# Vibe-Scale 1

[![Vibe-Scale 1: AI-assisted with full understanding](https://img.shields.io/badge/Vibe--Scale%201-AI--assisted%2C%20full%20review-1f77b4)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-1.md)

```markdown
[![Vibe-Scale 1: AI-assisted with full understanding](https://img.shields.io/badge/Vibe--Scale%201-AI--assisted%2C%20full%20review-1f77b4)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-1.md)
```

Vibe-Scale 1 is the gold standard for AI-assisted projects: AI contributes meaningfully but humans stay firmly in the loop. AI may produce autocomplete, snippets, answers to questions, or whole functions, but every line that lands in the repository has been read and understood by a human before commit, and behavior is validated by a strong suite of automated and manual tests.

A reader picking up code from a Vibe-Scale 1 project can trust that any line could be defended by a human author. Code review catches the model's mistakes, and tests catch the gaps between what the model wrote and what was actually wanted. The leverage AI provides is real, but the responsibility for what ships still sits with the team.

Score 1 is the recommended target for production code where AI assistance is welcome but accountability rests with humans.

---

## Precise vectors

Each vector is one specific combination of [AI use (V), human understanding (U), and testing (T)](https://github.com/vibesdk/vibe-scale/blob/main/README.md#the-v-u-t-dimensions) that scores in the 0.5–1.0 range. Authors who want to publish their precise V-U-T can embed the matching badge.

### V1-U0-T0 (Score 0.5) — AI-assisted, fully reviewed

![Vibe-Scale 0.5(V1|U0|T0): AI-assisted, fully reviewed](https://img.shields.io/badge/Vibe--Scale%200.5(V1%7CU0%7CT0)-AI--assisted%2C%20fully%20reviewed-3558a0)

Limited AI use, full understanding, complete testing.

AI tools assist the human author — autocomplete, snippet generation, the occasional small function — but the human is doing the bulk of the design and writing. Every line is reviewed and understood. Coverage is strong across both automated and manual testing.

This is how a careful engineer typically uses an AI editor: the AI accelerates typing without taking over judgment.

```markdown
[![Vibe-Scale 0.5(V1|U0|T0): AI-assisted, fully reviewed](https://img.shields.io/badge/Vibe--Scale%200.5(V1%7CU0%7CT0)-AI--assisted%2C%20fully%20reviewed-3558a0)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-1.md#v1-u0-t0-score-05--ai-assisted-fully-reviewed)
```

---

### V1-U0-T1 (Score 1.0) — AI-assisted, partial testing

![Vibe-Scale 1.0(V1|U0|T1): AI-assisted, partial testing](https://img.shields.io/badge/Vibe--Scale%201.0(V1%7CU0%7CT1)-AI--assisted%2C%20partial%20testing-1f77b4)

Limited AI use, full understanding, partial testing.

Same hands-on review as 0.5, but the project has gaps in test coverage — perhaps integration tests are thin, or some flows are only manually exercised. Reviewers still understand every line, so the risk lives in undetected behavior rather than in unreviewed code.

```markdown
[![Vibe-Scale 1.0(V1|U0|T1): AI-assisted, partial testing](https://img.shields.io/badge/Vibe--Scale%201.0(V1%7CU0%7CT1)-AI--assisted%2C%20partial%20testing-1f77b4)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-1.md#v1-u0-t1-score-10--ai-assisted-partial-testing)
```

---

### V1-U1-T0 (Score 1.0) — AI-assisted, spot-checked

![Vibe-Scale 1.0(V1|U1|T0): AI-assisted, spot-checked](https://img.shields.io/badge/Vibe--Scale%201.0(V1%7CU1%7CT0)-AI--assisted%2C%20spot--checked-1f77b4)

Limited AI use, spot-checked understanding, complete testing.

AI's contribution is small, but rather than read every suggestion line-by-line the author spot-checks output and trusts the rest. Strong test coverage compensates: even where review is partial, behavior is verified end-to-end.

```markdown
[![Vibe-Scale 1.0(V1|U1|T0): AI-assisted, spot-checked](https://img.shields.io/badge/Vibe--Scale%201.0(V1%7CU1%7CT0)-AI--assisted%2C%20spot--checked-1f77b4)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-1.md#v1-u1-t0-score-10--ai-assisted-spot-checked)
```

---

### V2-U0-T0 (Score 1.0) — Significant AI, fully reviewed

![Vibe-Scale 1.0(V2|U0|T0): Significant AI, fully reviewed](https://img.shields.io/badge/Vibe--Scale%201.0(V2%7CU0%7CT0)-Significant%20AI%2C%20fully%20reviewed-1f77b4)

Significant AI generation, full understanding, complete testing.

The most AI-heavy shape that still scores 1: AI generates whole functions or files, but every line is read and understood before commit, and the project is fully tested. The model produces a lot, but humans take responsibility for all of it.

This is the high-leverage end of responsible AI use. Heavy generation with no compromise on review or testing.

```markdown
[![Vibe-Scale 1.0(V2|U0|T0): Significant AI, fully reviewed](https://img.shields.io/badge/Vibe--Scale%201.0(V2%7CU0%7CT0)-Significant%20AI%2C%20fully%20reviewed-1f77b4)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-1.md#v2-u0-t0-score-10--significant-ai-fully-reviewed)
```
