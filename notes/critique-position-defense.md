# Critique, Position & Defense: "Just a Glimpse"

*Deep critical analysis for IMWUT submission*
*Date: 2026-03-01*

---

## 1. POSITION: What This Paper Actually Contributes

### What Is Genuinely New

The paper's core novelty is **naming and formalizing a practice that exists but has never been theorized in HCI**. Temporal wearing — the idea that don/doff IS the interaction rather than overhead — is a real conceptual contribution. The specific moves that are new:

1. **The wearing duration taxonomy** (permanent / session / temporal) — surprisingly, nobody has proposed this. After 25+ years of ISWC, wearing duration has never been a primary design variable. This is the paper's strongest claim to novelty.

2. **The don/doff inversion** — reframing donning from "cost to minimize" to "the interaction itself." This is genuinely clever and has real design consequences (optimize for instant onset rather than sustained comfort).

3. **The glimpse cycle** — a cyclic process model (attract → approach → don → glimpse → doff → rest → return) that contrasts with linear don → use → doff. The rest and return phases are theoretically interesting.

4. **The design space** (body coupling × transition cost × social legibility) applied to temporal MR devices specifically.

### What Is Repackaging

- The **historical precedents** section (lorgnettes, stereoscopes, View-Masters) is cultural history, not HCI contribution. It's well-written color, but claiming "lorgnettes existed" as evidence of a paradigm shift is weak.
- The **social acceptability** argument is largely derivative of Koelle et al. (2020) [DOI: 10.1145/3313831.3376162] and Profita et al. (2013) [DOI: 10.1145/2493988.2494331], applied to a new context.
- Several **design principles** (Design for Discovery, Social Legibility) are established concepts from public display literature (Brignull & Rogers, 2003; Wouters et al., 2016 [DOI: 10.1145/2901790.2901796]) restated for temporal wearing.

### How It Advances the State of the Art

It fills a genuine gap in wearability theory. Gemperle et al. (1998) [DOI: 10.1109/ISWC.1998.729537] answered "where on the body?" Zeagler (2017) [DOI: 10.1145/3123021.3123042] answered "how?" This paper answers "for how long?" — and argues the answer matters for design. That's a real contribution.

### Audience

Primary: IMWUT/UbiComp community working on wearables, AR/MR, and public computing. Secondary: ISWC wearable design community. Tertiary: museum/exhibition technology designers.

### 5 Closest Prior Works

| Paper | Relationship | How We Differ |
|-------|-------------|---------------|
| **Khurana et al. (2019)** [DOI: 10.1145/3328921] Detachable Smartwatch, IMWUT | Closest methodological analog — mode-switching wearable | They explore device versatility (one device, multiple modes); we explore wearing duration as a paradigm across multiple devices |
| **Gemperle et al. (1998)** [DOI: 10.1109/ISWC.1998.729537] Design for Wearability, ISWC | Foundational spatial framework we extend temporally | They address WHERE/HOW; we add WHEN/HOW LONG |
| **Koelle et al. (2020)** [DOI: 10.1145/3313831.3376162] Social Acceptability of Smart Glasses, CHI | Social acceptability framework we draw on | They study continuous wear; we argue brief wear has a different acceptability profile |
| **Ashbrook & Starner (2010)** [DOI: 10.1145/1753326.1753653] Micro-interactions, CHI | Closest conceptual analog in time-bounded interaction | They study brief gestures on permanently worn devices; we study brief wearing of transiently donned devices |
| **Dhaka et al. (2024)** [DOI: 10.1109/ISMAR62088.2024.00134] AR UI Transitions, ISMAR | Closest technical analog in MR transitions | They study UI transition mechanics during sustained wear; we study device-level transitions (wearing itself) |

### Is "Temporal Wearing" a Real Paradigm Shift or Just a Catchy Label?

**Honest answer: it's somewhere in between.** The taxonomy is real — nobody has formalized this. The don/doff inversion is a genuine reframing with design consequences. But calling it a "paradigm" is overselling. It's more accurately a **design dimension** that has been overlooked. The paper would be stronger if it claimed less ("we identify an undertheorized design dimension") rather than more ("we propose a new paradigm").

The risk of "paradigm" language: reviewers will hold it to a higher standard. A paradigm implies that existing frameworks are *wrong* or *incomplete in a fundamental way*. The paper's actual claim is narrower: existing frameworks are incomplete because they don't foreground duration.

### IMWUT-Grade Contribution?

**Conditionally yes**, IF:
- The empirical data is real and substantive (currently all PLACEHOLDERs)
- N is reasonable (20+ interviewed, 50+ logged interactions minimum)
- The deployment is at least 3-5 days
- Statistical claims are backed by actual numbers

The conceptual contribution alone (taxonomy + design space + design principles) is borderline for IMWUT — it would be more natural at DIS or ISWC. What makes it IMWUT-grade is the combination of concept + prototypes + field deployment + empirical findings. The four-contribution structure (C1-C4) is well-suited to IMWUT if each contribution has substance.

**Risk**: If the empirical component is thin, this becomes a design exploration paper that belongs at ISWC Notes & Briefs, not IMWUT.

---

## 2. CRITIQUES (Ranked Most → Least Significant)

### Critique 1: The Empirical Component Is All Placeholders

**The attack:** "The entire results section is placeholders. I cannot evaluate a paper where every quantitative claim is [PLACEHOLDER]. Are there actual prototypes? Was a deployment actually conducted? This reads like a well-structured thought experiment, not a research paper."

**Severity:** CRITICAL

**Defense:** This is an early draft; the deployment is planned. The methodological design is sound and detailed.

**Action:** FILL IN THE DATA. This is non-negotiable for IMWUT. Every [PLACEHOLDER] must become a real number. If the deployment hasn't happened yet, it must happen before May 1. If it can't, submit to ISWC Notes & Briefs instead.

---

### Critique 2: Conceptual Novelty — Is This Genuinely New?

**The attack:** "The authors claim temporal wearing is a 'paradigm shift,' but picking up binoculars and putting them down is not a paradigm — it's just... using binoculars. The taxonomy (permanent/session/temporal) is reasonable but simplistic. The boundaries are fuzzy: when does a 30-second VR demo become 'temporal' vs. 'session'? Is a 2-minute museum AR experience temporal or session? The paper acknowledges the historical precedents (lorgnettes, View-Masters) but then claims novelty — if this has been practiced for centuries, what exactly is new?"

**Severity:** Critical

**Defense:**
- The novelty is not the practice but the **formalization**. Gravity existed before Newton named it. Temporal wearing has been practiced but never theorized — no duration taxonomy, no design space, no design principles.
- The taxonomy boundaries ARE fuzzy, but this is true of all taxonomies (is a tablet a phone or a laptop?). The key insight is that seconds-scale wearing has qualitatively different design requirements than minutes-scale.
- The don/doff inversion (overhead → interaction) is a genuine design reframing with concrete consequences.

**Action:**
- Tone down "paradigm shift" language. Use "design dimension" or "undertheorized category."
- Add a clear boundary discussion: temporal wearing is characterized not just by duration (<15s) but by the three properties (brief, donning-as-interaction, cyclicity). A 30-second VR demo is session wear because donning is overhead, not interaction.
- Strengthen the "so what" of the historical argument: lorgnettes existed, but nobody derived *HCI design principles* from them.

---

### Critique 3: No Session-Wear Baseline

**The attack:** "The paper compares three temporal wearing form factors to each other but never compares temporal wearing to session wearing. Without a session-wear condition (e.g., a conventional HMD showing the same content for 2-5 minutes), how can you claim temporal wearing is 'qualitatively distinct'? You've only shown that different temporal wearing devices differ from each other."

**Severity:** Critical

**Defense:**
- This is an RtD paper, not a controlled experiment. The goal is to explore the design space, not to prove superiority over session wear.
- Social comfort comparisons to session wear come from participants' self-reported prior experiences with VR/AR HMDs (interview Theme 2).
- Adding a session-wear baseline would change the study design fundamentally and isn't necessary for the contribution claimed.

**Action:**
- Explicitly frame this as a limitation and justify: "We compare within the temporal wearing design space rather than against session wear because our research questions concern the internal structure of temporal wearing, not its superiority."
- Consider adding a brief HMD condition if feasible — even a Meta Quest showing the same content for comparison. This would dramatically strengthen the paper.
- If no baseline, strengthen the interview data comparing temporal wearing to participants' prior HMD experiences.

---

### Critique 4: Generalizability — Exhibition-Only Context

**The attack:** "All findings come from a single exhibition venue. Exhibition visitors are primed for novel experiences, socially comfortable with unfamiliar objects, and have no productivity goals. Would temporal wearing 'work' in a workplace, a home, a classroom, or a commute? The paper's design principles may only apply to exhibition/museum contexts."

**Severity:** Significant

**Defense:**
- Exhibition contexts are *representative* of the most common real-world MR deployment context (museums, trade shows, demos account for the vast majority of public MR encounters).
- The discussion section explicitly addresses beyond-MR applications (IoT, health monitoring, accessibility).
- Single-deployment studies are common and accepted in IMWUT (Khurana et al. 2019 evaluated in lab + brief user study).

**Action:**
- Be honest in limitations: "Our findings are drawn from exhibition contexts where novelty and exploration are normative. Future work should examine temporal wearing in instrumental contexts."
- If possible, add even a brief secondary deployment (classroom, retail) to demonstrate generalizability.

---

### Critique 5: The Glimpse Cycle — Descriptive, Not Predictive

**The attack:** "The 7-phase glimpse cycle (attract → approach → don → glimpse → doff → rest → return) describes what you observed but doesn't predict anything. Any cyclical human-device interaction could be decomposed this way. What testable predictions does the model make? When does rest become abandonment? What determines whether return occurs? Without predictive power, this is just a descriptive vocabulary."

**Severity:** Significant

**Defense:**
- Descriptive process models are valuable contributions in HCI — Brignull & Rogers' engagement zones are descriptive, not predictive, and are widely cited.
- The model DOES generate design-relevant predictions: e.g., lower transition cost → more cycles (tested via RQ1); content that varies → more returns (tested via orbiting behavior).
- The value is in naming phases that designers can target — "design for the attract phase" is actionable guidance.

**Action:**
- Make the design implications of each phase more explicit.
- Connect each phase to a specific design principle.
- Add a sentence acknowledging that the model is descriptive-generative (it generates design possibilities) rather than predictive-explanatory.

---

### Critique 6: Prototypes Are Too Heterogeneous to Compare

**The attack:** "The six prototypes differ in form factor, display technology, optical design, weight, and presumably content rendering. When you find differences in re-engagement frequency, how do you attribute them to 'body coupling' vs. the specific hardware characteristics of each prototype? You've confounded form factor with implementation."

**Severity:** Significant

**Defense:**
- All deployed prototypes show the same content, controlling for content effects.
- The paper explicitly frames this as RtD, not a controlled experiment. The goal is design exploration, not causal attribution.
- Confounds are inherent in form factor comparisons — a handheld device is different from a stationary one in MANY ways.

**Action:**
- Acknowledge this explicitly as a limitation.
- Be careful with causal language — say "prototypes with lower transition costs TENDED TO show more re-engagement" not "lower transition cost CAUSED more re-engagement."
- Emphasize that the prototypes are exemplars of design space positions, not controlled conditions.

---

### Critique 7: Relationship to Micro-Interactions (Ashbrook)

**The attack:** "How is temporal wearing different from micro-interactions [Ashbrook & Starner, 2010, DOI: 10.1145/1753326.1753653]? Both involve brief interactions lasting seconds. The distinction you draw — 'micro-interactions are brief gestures on permanent devices; temporal wearing is brief wearing of transient devices' — feels like splitting hairs. A glance at a smartwatch IS a form of temporal wearing of the eyes toward the wrist."

**Severity:** Significant

**Defense:** The distinction is real and has concrete design consequences:
- Micro-interactions: device is already on body → optimize gesture → device stays on body
- Temporal wearing: device is NOT on body → optimize don/doff → device leaves body
- The design requirements are fundamentally different: micro-interactions optimize gesture efficiency; temporal wearing optimizes transition (don/doff) efficiency.
- A smartwatch glance doesn't involve donning/doffing — the watch is already worn.

**Action:**
- Sharpen the distinction in the design space section. Create a comparison table: micro-interaction vs. temporal wearing on key dimensions.
- Explicitly address the "splitting hairs" objection with concrete examples of how the two paradigms lead to different design decisions.

---

### Critique 8: The Don/Doff Inversion — Reframing or Real?

**The attack:** "You claim temporal wearing 'inverts' the don/doff relationship from overhead to interaction. But this isn't an inversion — it's just a context where overhead is short. A fast don/doff is still overhead; calling it 'the interaction itself' is rhetorical sleight of hand. The user picks up a viewer to see content, not for the pleasure of picking it up."

**Severity:** Significant

**Defense:**
- The inversion is real: in session wear, designers try to MINIMIZE don/doff time to maximize use time. In temporal wear, don/doff time IS use time — they're inseparable. The physical act of raising the device is when augmented content appears.
- Analogy: turning a doorknob is overhead for entering a room. But turning a combination lock IS the interaction with the lock. Same physical gesture, different relationship to purpose.
- The emergent behaviors (double-take, hand-off) show that users treat the don/doff gesture as meaningful, not as overhead.

**Action:**
- Strengthen the inversion argument with concrete examples from the deployment. Quote participants who describe the PHYSICAL ACT of donning as part of the experience.
- Use the interview theme "Wearing Without Commitment" to support this — participants distinguished between "being a device wearer" and "using a device momentarily."

---

### Critique 9: Sample Size and Statistical Power

**The attack:** "For an IMWUT paper, the sample sizes are concerning. N=[PLACEHOLDER] for exit interviews, N=[PLACEHOLDER] for surveys. Non-parametric tests on three conditions with small N per condition have limited statistical power. Can you really claim significant effects of form factor?"

**Severity:** Significant (depends on actual N)

**Defense:**
- Naturalistic deployment studies in IMWUT routinely have smaller interview samples (15-25) paired with larger interaction log datasets (50-200+).
- The paper uses mixed methods — quantitative interaction logs are supplemented by qualitative interview data. The qualitative findings don't require large N.

**Action:**
- Maximize interaction log N through longer deployment or higher-traffic venue.
- Aim for: N≥80 unique visitors with logged interactions, N≥20 interviewed, N≥30 surveyed.
- If N is small, downplay statistical claims and foreground qualitative findings.

---

### Critique 10: Historical Precedents — "So What?"

**The attack:** "Section 3.6 documents that lorgnettes, opera glasses, and View-Masters existed. This is interesting cultural history but it's not an HCI contribution. 'Optical instruments have been temporal for centuries' doesn't tell us anything new about designing MR systems. What specific design lessons do these precedents yield that weren't already obvious?"

**Severity:** Minor

**Defense:**
- The historical section serves a legitimation function: temporal wearing isn't a novel invention but a *recovery* of a proven pattern that wearable computing forgot.
- Design lessons: instant-on (no boot sequence), social legibility (familiar gesture vocabulary), graceful doff (lowering is natural), cyclicity (raise-peek-lower-repeat).

**Action:**
- Shorten the historical section. Keep 2-3 examples max (lorgnette, coin-op viewfinder, View-Master).
- Extract explicit design lessons from each precedent. Connect each historical device to a specific design principle.
- Move detailed history to supplementary material.

---

### Critique 11: Novelty Effect

**The attack:** "This is a first-encounter study. All your findings — the double-takes, the orbiting, the pleasure of brevity — could be novelty effects. Would people still do double-takes on their 10th visit? Would the 'pleasure of brevity' persist, or would they get bored? You have no longitudinal data."

**Severity:** Minor

**Defense:**
- Acknowledged in limitations.
- The 80+ year persistence of View-Masters and coin-op viewfinders suggests temporal wearing itself is NOT a novelty effect, even if specific devices may lose appeal.
- The deployment captures first encounters, which are the most relevant for exhibition contexts (most museum visitors visit once).

**Action:**
- Strengthen the limitations discussion.
- Note that exhibition contexts are DESIGNED for first encounters — novelty is a feature, not a bug.

---

## 3. STRONGEST ARGUMENTS

### Argument 1: The Taxonomy Fills a Real, Documented Gap

The most compelling argument is that **nobody has proposed wearing duration as a primary design variable** despite 25+ years of wearable computing. This is verifiable — you can search the ISWC, IMWUT, and CHI proceedings. Gemperle addressed WHERE. Zeagler addressed HOW. Nobody addressed FOR HOW LONG. The gap is real, documented, and the taxonomy is a clean, useful contribution.

**Best supporting evidence:** The literature review in wearing-duration-taxonomies.md systematically demonstrates that every major wearability framework (Gemperle, Zeagler, Starner, Knight) treats duration as incidental.

### Argument 2: Emergent Social Behaviors Are Genuinely Novel

The **hand-off, narrator, and shared glimpsing** patterns are the paper's most distinctive empirical findings. If these are robust in the data, they demonstrate something no other MR study has shown: that single-device, single-user MR hardware can produce **socially shared experiences** through temporal wearing's brevity and legibility. This is a direct counterargument to the assumption that shared MR requires multi-device or multi-user systems.

**Best supporting evidence:** The narrator pattern — one person wears, describes aloud, companion participates without ever donning — is genuinely striking. It shows temporal wearing enables MR experiences to be social *because* they're brief, not *despite* it.

### Argument 3: The Don/Doff Inversion Has Real Design Consequences

The reframing from "donning as overhead" to "donning as interaction" is not just rhetorical — it leads to concretely different design decisions. When donning is overhead, you optimize for comfort, strap systems, calibration. When donning IS the interaction, you optimize for instant onset, information density per second, and graceful exit. This reframing changes what designers build. The design principles (P1-P6) flow directly from this inversion.

**What would make a reviewer say "this changes how I think about wearables":** The realization that we've been designing ALL wearables for sustained use — even the ones people actually use for seconds. The mismatch data (trade show demos average 3-5 minutes but use devices designed for hours) is the "aha moment."

---

## 4. WEAKEST POINTS

### Weakness 1: No Empirical Data Yet

**Can it be fixed before May 1?** Yes, IF the prototypes are built and a venue is available. A 3-5 day deployment is feasible in 2 months. This is the highest priority.

### Weakness 2: No Session-Wear Baseline

**Can it be fixed?** Partially. Adding a brief HMD condition (e.g., same content on a Meta Quest for comparison) is feasible. Even informal data (5-10 users trying both temporal and session conditions) would strengthen the paper significantly. If not possible, the paper must explicitly justify this absence.

### Weakness 3: Single Context (Exhibition Only)

**Can it be fixed?** Probably not before May 1 for a full second deployment, but a brief informal pilot in a different context (classroom, library, retail) with 5-10 users would help. This is a structural limitation to acknowledge honestly.

### What the paper should explicitly acknowledge as limitations:
1. Single deployment context (exhibition)
2. No session-wear comparison condition
3. First-encounter data only (no longitudinal evidence)
4. Content confounds (single content piece limits generalizability of content-related findings)
5. Limited demographic data (naturalistic recruitment)
6. No head-mounted temporal wearing prototype tested

---

## 5. REVIEWER SIMULATION

### Reviewer 1: Wearable Systems Person (ISWC Background)

**Overall Score: 3.0 / 5 (Borderline)**

**Summary:** This paper proposes "temporal wearing" as a new design paradigm for MR devices worn for seconds rather than minutes, introduces a wearing duration taxonomy and design space, and reports a field deployment of three prototypes. The concept is interesting and the prototypes span a reasonable range of form factors. However, the technical contribution is limited — the prototypes are not described in sufficient detail, and the design space, while neat, is fairly straightforward (body coupling × transition cost is intuitive, not surprising).

**Strengths:**
1. The wearing duration taxonomy fills a genuine gap — I've been working in wearables for 15 years and nobody has formalized this dimension.
2. The prototypes span three distinct form factors with controlled content, enabling meaningful comparison.
3. The transition cost measurements and efficiency ratio are useful metrics that the community could adopt.

**Weaknesses:**
1. Prototype technical details are insufficient. What displays? What tracking? What optics? At ISWC I'd want enough detail to reproduce these devices. The [PLACEHOLDER]s in the prototype table are concerning.
2. The design space (body coupling × transition cost × social legibility) is reasonable but not deep. Social legibility as a third dimension is hard to operationalize — how do you measure it? The three-component decomposition (action, purpose, duration legibility) is proposed but never validated.
3. No head-mounted temporal wearing prototype. For ISWC, this is a notable gap — the community cares about head-mounted devices, and the paper should at least discuss whether flip-up visors or masks could achieve temporal wearing.

**Questions for Authors:**
- What specific display and tracking technologies do the prototypes use?
- How is social legibility measured beyond subjective survey items?
- Have you considered a flip-up visor or mask form factor for head-mounted temporal wearing?

**Recommendation:** Revise and resubmit. Strengthen technical details and address the head-mounted gap.

---

### Reviewer 2: HCI Theory Person (CHI/DIS Background)

**Overall Score: 3.5 / 5 (Weak Accept)**

**Summary:** This paper makes a conceptual contribution by naming and formalizing "temporal wearing" as a distinct interaction paradigm. The three-part taxonomy, the don/doff inversion framing, and the glimpse cycle model are all interesting theoretical contributions. The historical grounding in optical instruments is charming. However, I have concerns about the strength of the novelty claim and the relationship to existing concepts (micro-interactions, calm technology, peripheral interaction).

**Strengths:**
1. The don/doff inversion is a genuine reframing with concrete design consequences. Moving donning from "overhead" to "interaction" is an elegant conceptual move that changes what designers optimize for.
2. The glimpse cycle model is useful — the "rest" and "return" phases are undertheorized in existing transition models, and naming them opens design space.
3. The emergent behaviors (double-take, hand-off, narrator, orbit) are lovely observational findings that give the concept empirical flesh.

**Weaknesses:**
1. The relationship to micro-interactions (Ashbrook & Starner, 2010 [DOI: 10.1145/1753326.1753653]) needs much sharper articulation. The current distinction — "micro-interactions are on permanent devices; temporal wearing is on transient devices" — doesn't feel deep enough. A smartwatch glance and a lorgnette peek are more similar than they are different.
2. "Paradigm" is too strong a claim. This is an undertheorized *dimension* of wearability, not a Kuhnian paradigm shift. The inflation of the claim will invite deflation by reviewers.
3. The historical precedents section, while enjoyable, risks undermining the novelty claim. If this has been practiced for 250+ years, the theoretical contribution needs to be positioned carefully — "we formalize an existing practice" rather than "we propose something new."

**Questions for Authors:**
- Can you articulate a deeper distinction between micro-interactions and temporal wearing beyond the permanent/transient device axis?
- Would you consider "temporal wearing as a design dimension" rather than "temporal wearing as a paradigm"?
- How does the glimpse cycle relate to Kolb's experiential learning cycle or other cyclic process models in HCI?

**Recommendation:** Accept with minor revision if the authors sharpen the micro-interaction distinction and moderate the novelty claim.

---

### Reviewer 3: UbiComp Empiricist (IMWUT Background)

**Overall Score: 2.5 / 5 (Reject)**

**Summary:** This paper introduces the concept of "temporal wearing" for MR and reports a field deployment with three prototype form factors. While the concept is interesting, I cannot recommend acceptance because the empirical component is not at the standard expected of IMWUT. The results section consists entirely of placeholders. The methodology is well-designed but unexecuted. I would welcome a resubmission when the study has been completed.

**Strengths:**
1. The study design is sound — naturalistic deployment, mixed methods (interaction logs + video coding + interviews + surveys), counterbalanced positioning. This is how field deployments should be designed.
2. The research questions are clear and addressable with the proposed methods.
3. The coding scheme (adapted from Brignull & Rogers for temporal wearing) is appropriate.

**Weaknesses:**
1. **No data.** Every quantitative result is [PLACEHOLDER]. I cannot evaluate findings that don't exist. This alone is grounds for rejection.
2. The analysis plan mentions Kruskal-Wallis tests and Spearman correlations, but with three conditions and likely small N per condition, statistical power is a serious concern. The paper should plan for Bayesian analysis or report effect sizes rather than relying on p-values.
3. The exit interview sample (N=[PLACEHOLDER]) is described as "purposive sampling" but the criteria are vague. What constitutes variation in "observed interaction patterns"? How do you identify "multi-cycle visitors" before interviewing them?

**Questions for Authors:**
- When will the deployment take place? Has it already occurred?
- What is the expected N for interaction logs? For interviews?
- Have you considered a Bayesian approach given the likely small sample sizes?

**Recommendation:** Reject. Resubmit when data is collected. The conceptual contribution alone does not meet IMWUT standards; paired with real empirical findings, this could be a strong paper.

---

## 6. STRATEGIC RECOMMENDATIONS

### Top 5 Changes Before Submission

1. **COLLECT THE DATA.** This is existential. No IMWUT paper survives all-placeholder results. Deploy for minimum 5 days at a high-traffic venue. Aim for N≥80 logged interactions, N≥20 interviews, N≥30 surveys.

2. **Add a session-wear comparison.** Even informal — 10 users trying the same content on a Meta Quest — would preempt the most damaging critique. Report it as supplementary comparison data, not a controlled condition.

3. **Moderate the novelty claim.** Replace "paradigm shift" with "undertheorized design dimension." Replace "inversion" with "reframing." The substance is the same; the rhetoric is more defensible.

4. **Sharpen the micro-interaction distinction.** Add a comparison table. Make the design consequences concrete: micro-interaction → optimize gesture on worn device; temporal wearing → optimize don/doff of undonned device. Different input (gesture vs. body coupling), different output (command vs. perception), different time structure (gesture within session vs. don/doff IS session).

5. **Cut historical precedents to 1 page.** Keep lorgnette (social legibility), coin-op viewfinder (stationary), View-Master (cyclicity). Move the rest to supplementary material. Connect each precedent to a specific design principle — don't just list them.

### What to Emphasize

- The **taxonomy** — it's clean, novel, and useful.
- The **emergent social behaviors** (hand-off, narrator, shared glimpsing) — these are the unique empirical findings no other paper has.
- The **design principles** — actionable, specific, grounded in both design process and empirical observation.
- The **mismatch** between how MR is actually used in public (seconds) and how devices are designed (hours) — this is the motivating tension.

### What to Downplay

- The historical precedents (interesting but not IMWUT-grade contribution).
- The "paradigm shift" language (invites attacks).
- The transition cost equation (T = T_onset + T_offset is trivially obvious; don't formalize the obvious).
- The "beyond MR" applications section (speculative; keep it brief).

### Framing Advice for the Rebuttal

If reviewers attack novelty: "We do not claim temporal wearing is new — we claim it is *untheorized*. The practice is centuries old; the design framework is new. Newton didn't invent gravity; he formalized it."

If reviewers attack the taxonomy boundaries: "All taxonomies have fuzzy boundaries. The value is in identifying the *ends* of the spectrum, not in drawing precise lines. A 3-second peek and a 3-hour VR session require fundamentally different design — the taxonomy names this difference."

If reviewers attack generalizability: "Exhibition contexts represent the most common real-world MR deployment context. We agree that temporal wearing in instrumental contexts deserves study — this is why we frame it as a design *space* rather than a single design solution."

If reviewers want more data: "We agree that larger-scale and longitudinal studies would strengthen the findings. We offer the conceptual framework and initial empirical grounding; the community can build on both."

---

*This document is a working critique for internal use. Its purpose is to identify every weakness before reviewers do, enabling targeted revision.*
