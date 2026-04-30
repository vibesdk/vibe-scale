# Vibe-Scale 3

[![Vibe-Scale 3: Significant AI use with understanding or testing gaps](https://img.shields.io/badge/Vibe--Scale%203-Significant%20AI%20with%20gaps-ffe066)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-3.md)

```markdown
[![Vibe-Scale 3: Significant AI use with understanding or testing gaps](https://img.shields.io/badge/Vibe--Scale%203-Significant%20AI%20with%20gaps-ffe066)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-3.md)
```

Vibe-Scale 3 is where users should be more selective about how reliant they are on a project and what role it plays in their work. AI generates significant portions of the code, and one of the two safety nets — review or testing — has thinned out. The remaining net is doing more than its share, and any failure it misses has nothing else to catch it.

A reader of a Vibe-Scale 3 project should look closely at where the gaps lie. The team has accepted that one dimension of verification will not catch everything; a careful reader needs to know which dimension and how that affects the parts of the code they care about. Appropriate for internal tools, prototypes, and non-critical paths; risky for production systems where review and testing normally guard against overlapping classes of failure.

Score 3 is reasonable when iteration speed matters more than the rigor a Vibe-Scale 1 or 2 project would demand, but it is no longer a comfortable target for code that has to be trusted by people who didn't write it.

---

## Precise vectors

Each vector is one specific combination of [AI use (V), human understanding (U), and testing (T)](https://github.com/vibesdk/vibe-scale/blob/main/README.md#the-v-u-t-dimensions) that scores 3.0. Authors who want to publish their precise V-U-T can embed the matching badge.

### V2-U0-T2 (Score 3.0) — Significant AI, no testing

![Vibe-Scale 3.0(V2|U0|T2): Significant AI, no testing](https://img.shields.io/badge/Vibe--Scale%203.0(V2%7CU0%7CT2)-Significant%20AI%2C%20no%20testing-ffe066)

Significant AI generation, full understanding, no testing.

AI writes a lot, humans read every line that lands, but the project has no automated or manual test layer. Code review is the only safety net. What reviewers miss has nothing else to catch it, and behavior changes will not be flagged by a regression check. Common in early-stage projects where iteration speed has outpaced the test harness.

```markdown
[![Vibe-Scale 3.0(V2|U0|T2): Significant AI, no testing](https://img.shields.io/badge/Vibe--Scale%203.0(V2%7CU0%7CT2)-Significant%20AI%2C%20no%20testing-ffe066)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-3.md#v2-u0-t2-score-30--significant-ai-no-testing)
```

---

### V2-U1-T1 (Score 3.0) — Significant AI with gaps

![Vibe-Scale 3.0(V2|U1|T1): Significant AI with gaps](https://img.shields.io/badge/Vibe--Scale%203.0(V2%7CU1%7CT1)-Significant%20AI%20with%20gaps-ffe066)

Significant AI generation, spot-checked understanding, partial testing.

The compromised shape: AI does the heavy lifting, humans spot-check rather than read deeply, and tests cover only part of what the project does. Neither safety net is at full strength, and the gaps in each can overlap on the same piece of code.

```markdown
[![Vibe-Scale 3.0(V2|U1|T1): Significant AI with gaps](https://img.shields.io/badge/Vibe--Scale%203.0(V2%7CU1%7CT1)-Significant%20AI%20with%20gaps-ffe066)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-3.md#v2-u1-t1-score-30--significant-ai-with-gaps)
```

---

### V2-U2-T0 (Score 3.0) — Vibed code, tested

![Vibe-Scale 3.0(V2|U2|T0): Vibed code, tested](https://img.shields.io/badge/Vibe--Scale%203.0(V2%7CU2%7CT0)-Vibed%20code%2C%20tested-ffe066)

Significant AI generation, no human review, complete testing.

The vibe-and-verify shape: the agent writes, the human doesn't read the implementation, but a strong suite of automated and manual tests validates behavior. Trust rests entirely on the test suite. What isn't tested isn't checked at all, and code quality questions (clarity, security, maintainability) that tests don't surface go unexamined.

```markdown
[![Vibe-Scale 3.0(V2|U2|T0): Vibed code, tested](https://img.shields.io/badge/Vibe--Scale%203.0(V2%7CU2%7CT0)-Vibed%20code%2C%20tested-ffe066)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-3.md#v2-u2-t0-score-30--vibed-code-tested)
```
