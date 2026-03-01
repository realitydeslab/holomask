# Positioning "Temporal Wearing" for ISWC 2026

*Gap analysis, novelty argument, and suggested framing*

## 1. The Core Argument

**Temporal wearing** is a novel interaction paradigm where the act of donning, using, and doffing a wearable device constitutes the interaction itself, measured in seconds rather than minutes or hours.

This fills a gap in wearable computing's conceptual landscape:

- **Permanent wear** (smartwatch, glasses) — extensively studied
- **Session wear** (VR headset) — extensively studied
- **Temporal wear** ← **unstudied as a category**

## 2. Why This Is Novel (Gap Analysis)

### 2.1 No Existing Duration Taxonomy
Despite 25+ years of ISWC, no paper has proposed a taxonomy where wearing duration is a *primary design variable*. Gemperle (1998) [DOI: 10.1109/ISWC.1998.729537] and Zeagler (2017) [DOI: 10.1145/3123021.3123042] address *where* to wear; Starner (2001) [DOI: 10.1109/40.946681] distinguishes always-available vs. task-specific; nobody has formalized *how long* as a design dimension.

### 2.2 Donning/Doffing as Overhead vs. Interaction
Every existing framework treats donning and doffing as *friction* — time wasted before/after productive use. Temporal wearing inverts this: don/doff IS the productive use. This is a genuine paradigm shift.

### 2.3 The Practice Exists, the Theory Doesn't
Museum AR, exhibition VR, peek devices, viewfinders, opera glasses — temporal wearing has been practiced for centuries (lorgnettes!) and decades (museum audio/video guides). But no one has named the pattern or derived design principles from it.

### 2.4 Social Acceptability Sweet Spot
The social acceptability literature (Koelle, Profita, etc.) identifies duration and purpose legibility as key factors. Temporal wearing optimizes both. This connection has not been made.

## 3. Suggested Framing for ISWC

### 3.1 Title Options
- "Temporal Wearing: When Donning Is the Interaction"
- "Seconds, Not Sessions: Designing for Temporal Wearing in Mixed Reality"
- "Just a Glimpse: Temporal Wearing as an Interaction Paradigm for Transient Mixed Reality"
- "Beyond Permanent and Session Wear: Temporal Wearing in Exhibition Contexts"

### 3.2 Abstract Structure
1. Wearable computing assumes extended wearing (permanent or session)
2. We identify a third category: *temporal wearing* — where wearing IS the interaction, lasting seconds
3. We present 6 non-HMD MR prototypes designed for temporal wearing in exhibitions/museums
4. We derive design principles for temporal wearing from iterative prototyping and expert evaluation
5. Temporal wearing opens new design space for wearable computing beyond traditional duration assumptions

### 3.3 Contribution Statement
- **Conceptual contribution:** The concept of "temporal wearing" and a three-part taxonomy of wearing duration (permanent, session, temporal)
- **Empirical contribution:** 6 prototypes instantiating temporal wearing across form factors (handheld, neck-hung, stationary)
- **Design contribution:** Design principles for temporal wearing devices derived from iterative prototyping in exhibition contexts

### 3.4 ISWC-Specific Positioning
ISWC values:
- **Novel form factors** ✓ (non-HMD MR devices)
- **Wearability considerations** ✓ (temporal wearing reframes Gemperle's framework)
- **Real-world deployment** ✓ (exhibition/museum contexts)
- **Design insights** ✓ (principles for temporal wearing)

This paper extends ISWC's own foundational work (Gemperle, Zeagler, Profita) with a missing dimension (temporality).

## 4. Potential Reviewers' Questions & Responses

### Q: "Isn't this just a handheld device? Not really a wearable?"
**A:** The taxonomy includes devices that are *worn temporarily* — neck-hung, raised to eyes, held against the body. The key is that body-device coupling, however brief, creates a wearing relationship. A lorgnette is a wearable; a viewfinder is a wearable. Temporal wearing expands what counts as "wearing."

### Q: "How is this different from micro-interactions?"
**A:** Micro-interactions (Ashbrook, 2010) describe brief input gestures on permanently worn/carried devices. Temporal wearing describes the entire device encounter (don + use + doff) as a brief interaction. The device itself is the medium of the interaction, not just the gesture.

### Q: "Is a 3-part taxonomy (permanent/session/temporal) the right granularity?"
**A:** It's a starting point. The key insight is that temporal wearing represents a *qualitatively different* design challenge, not just a shorter version of session wearing. Different design principles apply (instant-on, social legibility, etc.).

### Q: "Where's the quantitative evaluation?"
**A:** For ISWC Notes/Briefs, the conceptual contribution (temporal wearing as a category) + prototypes as design exemplars is sufficient. Future work can quantify transition times, social acceptability scores, and information uptake in temporal vs. session wearing.

## 5. Papers to Cite Prominently

### Must-cite (establish the gap):
1. Gemperle et al. (1998) [DOI: 10.1109/ISWC.1998.729537] — Design for Wearability [ISWC] — foundational, lacks temporal dimension
2. Zeagler (2017) [DOI: 10.1145/3123021.3123042] — Where to Wear It [ISWC] — body maps, lacks temporal dimension
3. Koelle et al. (2020) [DOI: 10.1145/3313831.3376162] — Social Acceptability Survey [CHI] — framework, lacks duration variable
4. Weiser & Brown (1996) [DOI: 10.1007/978-1-4612-0685-9_6] — Calm Technology — theoretical ancestor

### Should-cite (build the argument):
5. Profita et al. (2013) [DOI: 10.1145/2493988.2494331] — On-body interaction [ISWC] — social acceptability baseline
6. Bakker et al. (2015) [DOI: 10.1007/s00779-014-0775-2] — Peripheral Interaction — attention framework
7. Ashbrook (2010) — Micro-interactions — temporal reference point
8. Luff & Heath (1998) [DOI: 10.1145/289444.289505] — Micro-mobility — physical manipulation framework
9. vom Lehn et al. (2001) [DOI: 10.1525/si.2001.24.2.189] — Museum interaction — deployment context
10. Khurana et al. (2019) [DOI: 10.1145/3328913] — Detachable Smartwatch — closest prior work on wearing modality shifts

### Nice-to-cite (breadth):
11. Suchman (1987/2007) — Situated Action
12. Dourish (2003) [DOI: 10.1023/A:1026149119426] — Appropriation
13. Li et al. (2024) [DOI: 10.1177/21582440241303507] — Museum AR acceptance
14. Ens et al. (2015) [DOI: 10.1145/2556288.2557058] — Candid Interaction

## 6. Risk Assessment

### Strengths
- Novel concept that fills a genuine gap
- Strong empirical material (6 prototypes, real deployments)
- Extends ISWC's own canonical work
- Practically relevant (exhibition/museum/education)

### Risks
- "Temporal wearing" as a term may feel too niche → counter: it names a widespread but untheorized practice
- Six prototypes may feel design-heavy for ISWC → counter: ISWC Notes accepts design-focused work
- Line between handheld device and wearable is blurry → counter: define wearing as any body-device coupling, however brief
- Reviewers may want quantitative data → counter: frame as conceptual + design contribution; quantitative evaluation is future work
