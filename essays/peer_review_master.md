# Peer Review Master Notes (Essays 1–4)

Compiled from the peer-review PDFs in each `essays/eN/peer_reviews/`. Rubric = 4 criteria, each 0–5:
**S** = Well Structured · **C** = Makes its Case · **U** = Understanding of subject · **E** = Clear English.
This file is my quick-reference so I don't re-parse the PDFs.

**IMPORTANT — grading model:** the essay grade *is* a weighted average of these peer-review scores. The numbers below are not advisory; they directly determine the grade. So every recurring-weakness fix in this file translates straight into points, and the goal when drafting is explicitly to maximize what peers will score, not just to satisfy a hypothetical TA. (Per CLAUDE.md a TA can override on appeal, but in practice peer scores drive the grade.)

---

## SCORE SUMMARY

| Essay | Topic / Framework | S | C | U | E |
|---|---|---|---|---|---|
| E1 pr1 | AI bail (COMPAS), harmful | 4 | 5 | 4 | 5 |
| E1 pr2 | " | 5 | 5 | 4 | 5 |
| E1 pr3 | " | 5 | 5 | 5 | 5 |
| E1 pr4 | " | 5 | 4 | 5 | 5 |
| E2 pr1 | Ethical egoism, "not most natural" | 4 | 4 | 4 | 5 |
| E2 pr2 | " | 4 | 5 | 4 | 5 |
| E2 pr3 | " | 4 | 4 | 4 | 4 |
| E3 pr1 | Rule util, grade-hack unjustifiable | 5 | 5 | 5 | 4 |
| E3 pr2 | " | 4 | 4 | 4 | 4 |
| E3 pr3 | " | 5 | 4 | 5 | 4 |
| E4 pr1 | Rule util, Apple complies | 5 | 4 | 5 | 5 |
| E4 pr2 | " | 5 | 5 | 4 | 5 |
| E4 pr3 | " | 4 | 4 | 3.25 | 4 |

Rough averages: **E1 ≈ 4.75/4.75/4.5/5** (best) · **E2 ≈ 4/4.3/4/4.7** · **E3 ≈ 4.7/4.3/4.7/4** · **E4 ≈ 4.7/4.3/4.1/4.7**.
Weakest single criterion overall = **U (Understanding)** on the two rule-util essays, and **C (Makes its case)** broadly.

---

## RECURRING PATTERNS (most actionable — read this before writing the next essay)

### Consistent STRENGTHS (keep doing)
- **Clear, explicit thesis** + standard format (intro → thesis → arg → counterarg → rebuttal → conclusion). Never dinged for missing thesis or format.
- **Concrete named evidence / analogies** consistently praised: COMPAS, Warneken & Tomasello (2006), Akerlof "Market for Lemons," Quinn's Nachi worm, Google 2010, Lithuanian audit. Reviewers reward a specific case study over abstract claims.
- **Always includes a counterargument** and attempts a rebuttal — this alone reliably earns the 4th point on C.
- **English is a reliable strength** (mostly 5s early; slipped to 4 when run-ons/awkward phrasing crept in).

### Recurring WEAKNESSES (fix these — each cost real points)

1. **Evidence asserted, not developed / unpacked.** The single most repeated criticism.
   - E1: "additional examples beyond COMPAS would strengthen"; black-box consequences under-explored.
   - E3: "collateral impact" not explained; the *fallout* of universal grade-alteration not detailed enough to "broaden understanding."
   - E4: claims about Chinese alternatives / Lithuanian audit "asserted rather than fully developed."
   - **Fix:** after each piece of evidence, add 1–2 sentences explaining the mechanism / why it matters. Don't drop a name and move on.

2. **Argument vs. counterargument-vs-rebuttal roles get muddled.**
   - E2: the "self-destructive behavior" point was framed as the *rebuttal* but is really its own *second argument* → broke the logical flow; and the rebuttal "doesn't actually address the counterargument, it argues a separate point."
   - E4: two body paragraphs judged "a bit similar" (both = "Apple's refusal won't matter") → cost a structure point.
   - **Fix:** make each argument attack from a genuinely different angle (no double-counting), and make the rebuttal *directly answer the counterargument's claim*, not a neighboring point.

3. **Rule-utilitarian slip into ACT-utilitarian reasoning.** (Directly relevant — flagged in my own e4 audit and confirmed by peers.)
   - E4 pr2: "you slip to act utilitarian discussion… under rule utilitarianism it might be more appropriate to generalize to all phone providers."
   - E4 pr3 (U=3.25): "instead of using rule utilitarianism to argue compliance is ethical, the essay leans on the *situation* to argue the bad consequence is inescapable, therefore not unethical."
   - E3 by contrast was *praised* for keeping it rule-level (universal adoption, Nachi worm).
   - **Fix:** when using rule utilitarianism, reason about the *general practice/rule adopted by everyone*, not this one actor's single act. Say "the practice of…" explicitly.

4. **Contested premises asserted as fact / conclusions stronger than evidence.**
   - E2: "most natural" claim under-supported (never said how instincts are measured/ranked); altruism examples don't *prove* selflessness; final paragraph over-reached to a sweeping "universal ethical framework" claim without developing it.
   - E4 pr3: the core "comply-and-stay OR refuse-and-exit" binary was called an *opinion presented as fact* — reviewer raised a real third option (Apple refuses, isn't expelled, consumers choose). This is the false-binary / load-bearing-assumption risk. Also questioned whether "bad outcome is inescapable" even establishes "ethical."
   - **Fix:** back or explicitly hedge any load-bearing premise; acknowledge and dismiss alternative options rather than assuming the binary; don't let the conclusion outrun the evidence.

5. **Minor English: run-on sentences, missing commas, awkward phrasing** (the usual cause of E dropping 5→4).
   - E3: run-ons (esp. the long Quinn/Nachi sentence), missing commas.
   - E4: "would not only lack a tangible benefit," "supplies no benefits" flagged as awkward.
   - E2 typos: "receive an award or benefit" (→ reward), "a one learned by others."
   - **Fix:** on the edit pass, hunt run-ons and split them; read for awkward phrasings.

---

## PER-ESSAY DETAIL

### E1 — AI in bail decisions is HARMFUL (COMPAS)
- **Thesis:** Using AI to inform bail decisions is overall harmful (bias + opaqueness).
- **Structure:** Arg = AI trained on historically biased data (COMPAS mislabeled Black defendants ~2× as "high-risk"). CA = bias can be adjusted. Rebuttal = opaqueness/trade-secret + neural-net black box → can't audit/correct. Conclusion adds an explainability point.
- **Scores:** 4/5/4/5 · 5/5/4/5 · 5/5/5/5 · 5/4/5/5 (strongest essay overall).
- **Praise:** compelling, statistic + case study, strong CA handling, clear English, insightful on model inference/bias.
- **Dings:** conclusion introduced an argument not fully fleshed out (pr1); black-box consequences could be explored more outside the CA (pr2); more examples beyond COMPAS (pr4).

### E2 — Ethical egoism: NOT most natural to act in self-interest
- **Thesis:** Acting in self-interest is a natural instinct but not the *most* natural, due to instinctive altruism + self-destructive behavior.
- **Structure:** Arg1 = altruism (Warneken & Tomasello 2006, 18-mo-olds help unprompted; parental sacrifice). CA = instincts are disguised selfishness. Rebuttal/Arg2 = self-destructive behavior (procrastination) disproves universal self-maximizing.
- **Scores:** 4/4/4/5 · 4/5/4/5 · 4/4/4/4 (weakest structure band; never got a 5 on S).
- **Dings (most instructive essay for weaknesses):**
  - Self-destructive point mislabeled as rebuttal — should be its own argument (pr1).
  - Rebuttal doesn't actually answer the CA (pr1).
  - Doesn't distinguish *self-interest* vs *seemingly-selfish action*; the baby example may not be devoid of self-interest (pr1, pr3). Suggested reframe: needing others to meet emotional needs is itself evidence egoism is unnatural.
  - "Most natural" unmeasurable / never ranked instincts (pr3). Final paragraph over-reached to "universal ethical framework" undeveloped (pr3).
  - Typos (pr3).

### E3 — Rule utilitarianism: exploiting grade-hack is UNJUSTIFIABLE
- **Thesis:** Under rule util, a student altering their own grades via a security flaw is morally unjustifiable.
- **Structure:** Arg = permitting grade alteration destroys the grading signal (Akerlof "Market for Lemons" → grades become unreliable, hurts employers + deserving students). CA = only unfairly-graded students self-correct → more accurate. Rebuttal = rule util needs *universal* adoption (Quinn's Nachi worm) → no auditing → abuse → grade inflation → net negative.
- **Scores:** 5/5/5/4 · 4/4/4/4 · 5/4/5/4 (E consistently 4 — the run-on problem).
- **Praise:** Akerlof + Nachi analogies loved; strong, correct rule-util application (rule-level, not act-level — the thing E4 got dinged for).
- **Dings:** "collateral impact" under-explained; fallout of universal alteration not detailed (pr2). Run-on sentences / missing commas (pr1, pr2, pr3).

### E4 — Rule utilitarianism: Apple SHOULD comply (the essay I workshopped)
- **Thesis:** Under rule util, ethical for Apple to comply & remove apps to keep operating.
- **Structure (as submitted):** Arg1 = refusing benefits no one (apps already firewall-blocked; GFW IP-blocks VPN datacenters). Arg2 = refusing → China bans App Store → users forced to insecure Chinese phones (2021 Lithuanian audit). CA = comply normalizes censorship. Rebuttal = fails Quinn's "workable" test (no industry coordination); Google 2010 → Baidu filled gap.
- **Scores:** 5/4/5/5 · 5/5/4/5 · 4/4/3.25/4 (pr3 harsh, and validated my pre-submission audit).
- **Key dings (all things my audit predicted):**
  - **Act-vs-rule slip** (pr2, pr3) — didn't generalize to "all phone providers"/the practice.
  - **False binary** (pr3) — "comply-stay vs refuse-exit" asserted as fact; reviewer named a third path (Apple refuses, not expelled, consumers choose). The bounded-rule/partial-compliance pre-empt from my final outline was NOT in the submitted version.
  - **Arg1 & Arg2 overlap** (pr3) — both read as "refusal won't matter."
  - Evidence asserted not developed (pr1). Awkward phrasing (pr3).
  - NOTE: submitted version lacked the Setup paragraph (RU-as-practice definition, supply-chain justification, bounded rule, "partial compliance isn't a third rule") that the final workshop outline had — exactly the omissions the harsh reviewer punished.

---

## TOP 3 TAKEAWAYS FOR FUTURE ESSAYS
1. **Develop the evidence** — never drop a case study/stat without 1–2 sentences of mechanism. (Hit on every essay.)
2. **If using rule utilitarianism, stay at the RULE/practice level** — generalize to "everyone/all actors," never argue the single actor's act. (Cost E4 its worst score.)
3. **Don't assert a contested premise (esp. a binary) as fact** — name and dismiss alternatives, or hedge. Keep the conclusion within what the evidence shows.
