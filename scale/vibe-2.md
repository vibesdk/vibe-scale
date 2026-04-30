# Vibe-Scale 2

[![Vibe-Scale 2: AI use balanced with understanding and testing](https://img.shields.io/badge/Vibe--Scale%202-Balanced%20AI%20use-2ca02c)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-2.md)

```markdown
[![Vibe-Scale 2: AI use balanced with understanding and testing](https://img.shields.io/badge/Vibe--Scale%202-Balanced%20AI%20use-2ca02c)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-2.md)
```

Vibe-Scale 2 projects strike a healthy balance: AI contribution is matched by proportionate human review and testing. There is a gap in one dimension — some code is spot-checked rather than read line-by-line, or test coverage is partial — but the gap is sized to the contribution, not running ahead of it.

If Vibe-Scale 1 is the gold standard, Vibe-Scale 2 is the everyday solid project. The team is using AI productively and keeping the loop closed, just without the rigor of full review *and* full testing on every change. Engineers picking up Vibe-Scale 2 code can work with it confidently; the trade-offs are intentional and in proportion.

This is where most healthy AI-assisted development sits in practice.

---

## Precise vectors

Each vector is one specific combination of [AI use (V), human understanding (U), and testing (T)](https://github.com/vibesdk/vibe-scale/blob/main/README.md#the-v-u-t-dimensions) that scores in the 1.5–2.0 range. Authors who want to publish their precise V-U-T can embed the matching badge.

### V1-U0-T2 (Score 1.5) — AI-assisted, no testing

![Vibe-Scale 1.5(V1|U0|T2): AI-assisted, fully reviewed](https://img.shields.io/badge/Vibe--Scale%201.5(V1%7CU0%7CT2)-AI--assisted%2C%20fully%20reviewed-2ca02c)

Limited AI use, full understanding, no testing.

AI contribution is small, every line is read and understood, and the project simply doesn't have a testing layer. The reviewed-but-untested combination is common for libraries with small surface areas, scripts, and exploratory tools where the human review carries the weight.

```markdown
[![Vibe-Scale 1.5(V1|U0|T2): AI-assisted, fully reviewed](https://img.shields.io/badge/Vibe--Scale%201.5(V1%7CU0%7CT2)-AI--assisted%2C%20fully%20reviewed-2ca02c)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-2.md#v1-u0-t2-score-15--ai-assisted-no-testing)
```

---

### V1-U1-T1 (Score 1.5) — AI-assisted with gaps

![Vibe-Scale 1.5(V1|U1|T1): AI-assisted with gaps](https://img.shields.io/badge/Vibe--Scale%201.5(V1%7CU1%7CT1)-AI--assisted%20with%20gaps-2ca02c)

Limited AI use, spot-checked understanding, partial testing.

AI's footprint is small, and review and testing are each partial. Neither dimension carries the project alone, but together they cover most of what AI produced — and AI produced little to begin with. A balanced shape for a typical iterative project.

```markdown
[![Vibe-Scale 1.5(V1|U1|T1): AI-assisted with gaps](https://img.shields.io/badge/Vibe--Scale%201.5(V1%7CU1%7CT1)-AI--assisted%20with%20gaps-2ca02c)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-2.md#v1-u1-t1-score-15--ai-assisted-with-gaps)
```

---

### V1-U1-T2 (Score 2.0) — AI-assisted with gaps

![Vibe-Scale 2.0(V1|U1|T2): AI-assisted with gaps](https://img.shields.io/badge/Vibe--Scale%202.0(V1%7CU1%7CT2)-AI--assisted%20with%20gaps-2ca02c)

Limited AI use, spot-checked understanding, no testing.

AI contribution is light, the author spot-checks output, and the project has no testing layer. The gaps are bigger than the other 2.0 shapes, but the small AI footprint keeps the overall surface they apply to small.

```markdown
[![Vibe-Scale 2.0(V1|U1|T2): AI-assisted with gaps](https://img.shields.io/badge/Vibe--Scale%202.0(V1%7CU1%7CT2)-AI--assisted%20with%20gaps-2ca02c)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-2.md#v1-u1-t2-score-20--ai-assisted-with-gaps)
```

---

### V2-U0-T1 (Score 2.0) — Significant AI, partial testing

![Vibe-Scale 2.0(V2|U0|T1): Significant AI, partial testing](https://img.shields.io/badge/Vibe--Scale%202.0(V2%7CU0%7CT1)-Significant%20AI%2C%20partial%20testing-2ca02c)

Significant AI generation, full understanding, partial testing.

AI generates whole functions or files and the human reads every line before it lands. Testing is partial — important paths are covered, edges may not be. Human review carries the project; tests fill in where they exist. A natural shape for AI-accelerated work where review keeps pace and testing catches up over time.

```markdown
[![Vibe-Scale 2.0(V2|U0|T1): Significant AI, partial testing](https://img.shields.io/badge/Vibe--Scale%202.0(V2%7CU0%7CT1)-Significant%20AI%2C%20partial%20testing-2ca02c)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-2.md#v2-u0-t1-score-20--significant-ai-partial-testing)
```

---

### V2-U1-T0 (Score 2.0) — Significant AI, spot-checked

![Vibe-Scale 2.0(V2|U1|T0): Significant AI, spot-checked](https://img.shields.io/badge/Vibe--Scale%202.0(V2%7CU1%7CT0)-Significant%20AI%2C%20spot--checked-2ca02c)

Significant AI generation, spot-checked understanding, complete testing.

AI does the heavy lifting on generation, the human spot-checks rather than reading line-by-line, and the test suite carries the weight of correctness. A common shape for agent-assisted projects with strong test discipline — where the harness is trusted to catch what review skims over.

```markdown
[![Vibe-Scale 2.0(V2|U1|T0): Significant AI, spot-checked](https://img.shields.io/badge/Vibe--Scale%202.0(V2%7CU1%7CT0)-Significant%20AI%2C%20spot--checked-2ca02c)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-2.md#v2-u1-t0-score-20--significant-ai-spot-checked)
```
