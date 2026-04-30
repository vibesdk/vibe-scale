# Vibe-Scale 4

[![Vibe-Scale 4: Significant AI use with compound gaps](https://img.shields.io/badge/Vibe--Scale%204-Significant%20AI%2C%20compound%20gaps-ff7f0e)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-4.md)

```markdown
[![Vibe-Scale 4: Significant AI use with compound gaps](https://img.shields.io/badge/Vibe--Scale%204-Significant%20AI%2C%20compound%20gaps-ff7f0e)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-4.md)
```

Vibe-Scale 4 projects have significant AI contribution with compound gaps — both review and testing are limited. Neither safety net is carrying the project; the gaps in each can overlap on the same code, and what the model got wrong may go undetected entirely. Trust rests largely on the model's own output.

Users should be selective about relying on Vibe-Scale 4 projects and should not use them in roles where undetected failures carry real consequences. This is not a project to trust blindly — it is a project to treat as a starting point, a prototype, or a tool where failure is recoverable.

---

## Precise vectors

Each vector is one specific combination of [AI use (V), human understanding (U), and testing (T)](https://github.com/vibesdk/vibe-scale/blob/main/README.md#the-v-u-t-dimensions) that scores 4.0. Authors who want to publish their precise V-U-T can embed the matching badge.

### V2-U1-T2 (Score 4.0) — Significant AI, test gaps

![Vibe-Scale 4.0(V2|U1|T2): Significant AI, test gaps](https://img.shields.io/badge/Vibe--Scale%204.0(V2%7CU1%7CT2)-Significant%20AI%2C%20test%20gaps-ff7f0e)

Significant AI generation, spot-checked understanding, no testing.

AI generates most of the code, humans skim rather than read deeply, and there is no automated or manual test layer. The spot-check is the only human touchpoint on what the model produced, and it is incomplete. Behavior that looks plausible on a quick scan but is subtly wrong has nothing to surface it.

```markdown
[![Vibe-Scale 4.0(V2|U1|T2): Significant AI, test gaps](https://img.shields.io/badge/Vibe--Scale%204.0(V2%7CU1%7CT2)-Significant%20AI%2C%20test%20gaps-ff7f0e)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-4.md#v2-u1-t2-score-40--significant-ai-test-gaps)
```

---

### V2-U2-T1 (Score 4.0) — Vibed code with gaps

![Vibe-Scale 4.0(V2|U2|T1): Vibed code with gaps](https://img.shields.io/badge/Vibe--Scale%204.0(V2%7CU2%7CT1)-Vibed%20code%20with%20gaps-ff7f0e)

Significant AI generation, no human review, partial testing.

The agent writes, the human does not read the implementation, and only some behavior is tested. What isn't covered by tests is entirely unverified — no review and no test has touched it. The partial test suite provides some confidence in the paths it covers and none elsewhere.

```markdown
[![Vibe-Scale 4.0(V2|U2|T1): Vibed code with gaps](https://img.shields.io/badge/Vibe--Scale%204.0(V2%7CU2%7CT1)-Vibed%20code%20with%20gaps-ff7f0e)](https://github.com/vibesdk/vibe-scale/blob/main/scale/vibe-4.md#v2-u2-t1-score-40--vibed-code-with-gaps)
```
