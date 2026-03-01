# Related Works Positioning
*Against 10–12 closest papers in UbiComp/ISWC communities*

---

## Positioning Map

Our paper sits at the intersection of:
- **Wearable form factor design** (ISWC lineage)
- **Mobile/handheld AR** (UbiComp/IMWUT lineage)  
- **Public/exhibition computing** (UbiComp/Pervasive lineage)
- **Transient/micro-interaction** (UbiComp lineage)

---

## 12 Closest Related Papers with Positioning

### 1. Dhaka, Katsuragawa, & Hasan (2024) — AR UI Transitions [ISMAR]
**Their contribution:** Design space for transitioning AR interfaces across surfaces (mid-air, on-body, physical).  
**Our differentiation:** They focus on efficiency of UI transition mechanics; we focus on the *scenario* (transient social encounters) and *form factor* (non-HMD). They assume sustained MR use; we design for brief episodes. We also cover stationary and neck-worn form factors they don't address.

---

### 2. Khurana, Goel, & Lyons (2019) — Detachable Smartwatch [IMWUT]
**Their contribution:** Smartwatch that morphs between wrist-worn and handheld for micro vs. extended interactions.  
**Our differentiation:** They focus on a single device type morphing between modes; we address three distinct form factor categories for MR (not general computing). The MR layer adds: spatial overlay, registration, and the unique social dynamics of "seeing through" a device.

---

### 3. Gemperle et al. (1998) [DOI: 10.1109/ISWC.1998.729537] — Design for Wearability [ISWC]
**Their contribution:** Foundational body placement and wearability design principles.  
**Our differentiation:** Their principles apply to general wearables; we apply and extend them specifically to mixed reality devices in transient social contexts. We add: MR-specific factors (display occlusion, camera ethics, spatial registration) and transient-specific factors (rapid don/doff, cold start).

---

### 4. Profita et al. (2013) [DOI: 10.1145/2493988.2494331] — On-Body Technology in Public [ISWC]
**Their contribution:** Social acceptability of touching wrist-worn devices in public.  
**Our differentiation:** They study interaction with existing wrist wearables (smartwatches). We study *first encounter* social acceptability of novel non-HMD MR form factors in exhibition contexts — different device types, different interaction modes, different social settings.

---

### 5. Hoang et al. (2016) — AR on Smart Glasses [IMWUT/UbiComp]
**Their contribution:** Comparative study of smartglasses vs. smartphone AR in naturalistic settings.  
**Our differentiation:** They compare two existing form factors (smartglasses ≈ HMD, smartphone = handheld). We propose a richer design space including a novel third category (neck-worn) and specifically target transient rather than sustained AR use — a context they don't address.

---

### 6. Mistry & Maes (2009) [DOI: 10.1145/1667146.1667160] — SixthSense [SIGGRAPH Asia]
**Their contribution:** Neck-worn projector+camera enabling gestural AR on any surface.  
**Our differentiation:** SixthSense proves technical feasibility of neck-worn MR. Our work asks: *how should neck-worn MR be designed for transient social encounters?* We provide design principles, prototype variants, and empirical insights that move beyond the technical demo.

---

### 7. vom Lehn, Heath, & Hindmarsh (2001) [DOI: 10.1525/si.2001.24.2.189] — Museum Exhibition Interaction [Symbolic Interaction]
**Their contribution:** Ethnographic study of how museum visitors engage with exhibits — inherently brief and social.  
**Our differentiation:** They study behavior with existing physical exhibits. We design MR interfaces specifically to fit the naturalistic patterns they document — treating their ethnographic findings as design requirements.

---

### 8. Müller et al. (2009) — Display Blindness [Pervasive]
**Their contribution:** Documents how people stop noticing public digital displays over time.  
**Our differentiation:** Display blindness results from passive, persistent displays. Our transient interactive MR interfaces are activated by user intent — avoiding display blindness by design. Our work implicitly provides a solution to the problem they document.

---

### 9. Billinghurst, Grasset, & Looser (2005) — Designing AR Interfaces [SIGGRAPH]
**Their contribution:** Design guidelines for AR across display types.  
**Our differentiation:** Their guidelines are display-agnostic and context-agnostic. We specialize to the transient social context and derive form-factor-specific principles not addressed in general AR interface design.

---

### 10. Raskar et al. (1998) — Spatial Augmented Reality [SIGGRAPH]
**Their contribution:** Projection-based AR for immersive room-scale experiences.  
**Our differentiation:** They pursue sustained, high-fidelity spatial AR. Our stationary prototype uses projection-based AR specifically for brief, incidental encounter — optimizing for accessibility and low barrier to entry over immersion.

---

### 11. Lyons et al. (2012) — Facet Wrist-Worn System [UIST]
**Their contribution:** Multi-facet wrist display showing different information at different angles.  
**Our differentiation:** Facet is always-worn, always-on display for personal information. Our neck-worn and handheld MR interfaces are explicitly transient (activated for encounters) and aimed at enhancing a shared physical environment rather than personal information display.

---

### 12. Sahami Shirazi et al. (2014) — Mobile Notifications [CHI]
**Their contribution:** Large-scale study showing most mobile interactions are extremely brief.  
**Our differentiation:** They document the phenomenon (most interactions are transient). We provide the design response: if interactions are brief, MR interfaces must be specifically designed for that brevity — not adapted from sustained-use HMD paradigms.

---

## Summary Positioning Statement

Our work is unique in combining three elements no prior paper addresses together:
1. **Non-HMD form factors** (vs. most MR research focused on HMDs)
2. **Transient scenario specificity** (vs. prior non-HMD work assuming sustained use)
3. **Designer-grounded design principles** (vs. technical feasibility demonstrations)

The paper fills a clear gap: between the established wearable design literature (ISWC) and the emerging transitional AR literature (ISMAR/UbiComp), specifically in the underexplored quadrant of *brief, socially-embedded MR encounters*.
