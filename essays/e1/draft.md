### Possible AI Applications To Talk about:

* Robotic surgeries -> for
* Bail decisions -> against
* 

**Thesis**: Despite the convenience and increased throughput of deligating the responsability of bail sentencing to AI, this practice is overall harmful.

**Body Paragraph 1:**

* Previous data encodes racial and economic bias -> systems are not very interpretable making them difficult to audit and check for racial and economic bias

X → Y: The model produces racially/economically biased scores (because it's trained on biased criminal-justice data) → and because it's not interpretable/auditable, that bias can't be caught, corrected, or contested.

**Body Paragraph 2:**

**Concluding Paragraph**:

---

**Thesis**: AI bail scores are harmful.

**B1**: trained on biased arrest data→discriminatory scores→unjust detention (COMPAS).

**B2**: counter="more objective than biased judges"; rebut=opaque/proprietary, can't audit/contest→same bias, now unaccountable.

**Concl**: swaps questionable judge for unchallengeable algorithm.

---

▎ Thesis: AI bail risk-scores are harmful and should not decide pretrial detention.
▎ B1 (harm): Trained on historical arrest data that reflects biased policing → scores reproduce & amplify racial/economic bias → people jailed on discriminatory predictions dressed up as objective math (COMPAS).
▎ B2 (counter → rebut): Counter: we can audit and de-bias these models to make them fair. Rebut: they're opaque and often proprietary, so the bias can't be inspected or corrected; and unlike a biased judge, who can be questioned and appealed, a black-box score can't be challenged at all → not fixed, just unaccountable.
▎ Concl: Replaces a questionable judge with an unchallengeable algorithm — same bias, no recourse.

Courts use AI models as a blackbox. In State v. Loomis, a defendant was sentenced with a COMPAS score but couldn't challenge it, because the company never disclosed how the algorithm works. We may find a similar trend with complex models as they lack interpretability. Both of these point to the fact that these decisions cannot be properly audited and therefore we cannot blindly trust them.

---

Th: Using AI for making bail decisions is harmful

B1: Trained on historical arrest data that reflects biased policing. This may look like an objective methodology, however due to previous racial/economic bias, models are often harsher on certain groups rather than others. An explicit example of this occurring was when "Correctional Offender Management Profiling for Alternative Sanctions (COMPAS)" was used in practice but later discovered to perform harsher on racially and econocomic groups that are historically discriminated against.

B2ca: AI models can be corrected to account for bias.

B2r: But you cannot correct a bias you cannot see. Because these systems are opaque — COMPAS by trade secret, and newer neural-network models by their very design — the bias can't be audited, or fixed. So 'we can just correct it' assumes an access to the model that no one actually has.

C: Replacing a human judge with an unchallengeable algorithm

1:AI 4 bail decs->harm

2:Trained hist data -> biased
Looks obj but prev rac/econ bias
COMPAS used for b + s -> trgtd racially/econ prev marg groups

3:AI mods can b corctd acct for bias

4:Cnt corct bias u cnt see. Sys opaq (COMPAS by TS, NN mods cmplx) bias cant b audted/fxed

5:Rplac hum judg w unchlg alg

---

1:AI 4 bail decs->harm2:Trained hist data -> biasedLooks obj but prev rac/econ biasCOMPAS used for b + s -> trgtd racially/econ prev marg groups3:AI mods can b corctd acct for bias4:Cnt corct bias u cnt see. Sys opaq (COMPAS by TS, NN mods cmplx) bias cant b audted/fxed5:Rplac hum judg w unchlg alg

# Modifications to Essay 1

* Thesis sentence:

  * Harmful therefore should not be adopted -> inherit bias + opaque
* COMPAS

  * More detail about COMPAS
    * It is ris assessment tool that uses a survey to calculate a risk score.
  * More detail about the scandal + fact check it
    * Investigative journalists uncovered the bias
    * Black defendants who did not re-offend were nearly twice as likely to be misclassified as "high risk" compared to white defendants
    * The software was not altered to account for the bias.
  * Is it still being used today? -> it is still being actively used
  * Mention that this is an example of it being used, not the only possible way to use it
* More detail about NNs
* AI-generated fixes:

  * [HIGH] "biased towards marginalized groups" → "biased **against** marginalized groups" (B1, first sentence). "Towards" reads as favoring them — the opposite of your point.
  * [HIGH] State the rebuttal's punchline explicitly: **"you cannot correct a bias you cannot see."** Right now B2 shows opacity but never says why it defeats the "just fix it" counterargument — the fix requires inspecting the model, which opacity makes impossible.
  * [HIGH] Add the ethics framing to the conclusion: freedom is denied **before trial, while still presumed innocent** → this demands **due process / fairness** the algorithm cannot provide. (Strongest ethical punch, currently missing.)
  * [MEDIUM] Typos: "inherit bias" → "inher**ent**"; "those those" → "those"; "life changing" → "life-changing".
  * [MEDIUM] Keep your planned COMPAS additions — ProPublica "~twice as likely" stat, "investigative journalists uncovered it," "not altered afterward," "still actively used." The "still used" point proves opacity insulates bias from consequences.
  * [MEDIUM] Keep the "this is one example, not the only use" line — it answers the prompt's "specific application" framing.
  * [LOW] Add one nod to the article (prompt requires an application *from* it): a clause like "as Acemoglu warns, AI is already used for bail decisions." Currently the source is never mentioned.
  * [LOW] "racial profiling" → "racial bias/disparities" (profiling is a specific policing practice, not what the algorithm does).
  * [NOTE] If you only remember three: (1) "biased **against**", (2) say **"you can't fix a bias you can't see"**, (3) add **"presumed innocent / due process"** to the conclusion.

---

### Concise Notes to Remember:

**1. Top 3 (if nothing else):**

1. "biased **against**" (not "towards")
2. Rebuttal: **"you can't fix a bias you can't see"**
3. Conclusion: **"presumed innocent / due process"** -> bail jails people before trial, while presumed innocent. Human judge can explain and be appealed while an algorithm cannot.

**2. Thesis:** harmful → should NOT be adopted. Two reasons: inherent bias + opaque.

**3. COMPAS:**

- What: risk-assessment tool; survey → risk score.
- Scandal: investigative journalists (ProPublica) found Black defendants who did NOT reoffend were **~twice** as likely to be mislabeled "high risk."
- NOT FIXED AFTERWARDS: Still **actively used** today (→ opacity shields bias from consequences).
- It's **one example**, not the only possible use.

**4. Quick wins:** typos → "inher**ent**", "those" (not "those those"), "life-changing". "racial profiling" → "racial bias". Nod to article: "as Acemoglu warns, AI is already used for bail."

**5. Accuracy guardrails:** say "**nearly twice**" (no invented numbers).

~~**4. Rebuttal (opacity):** "just fix the bias" fails — **can't correct a bias you can't see.** COMPAS = trade secret; neural nets = opaque even to creators.~~

~~**4. Conclusion:** bail jails people **before trial, while presumed innocent** → demands **due process / fairness** a black box can't give. Human judge can explain & be appealed; algorithm can't~~.
