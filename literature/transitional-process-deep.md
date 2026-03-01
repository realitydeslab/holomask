# Transitional Interaction as Process: Cyclic & Transitional Models

*Deep literature review for "Just a Glimpse" — IMWUT submission*
*Focus: Cyclic interaction, calm technology, transitional interfaces, micro-mobility, intermittent interaction*

---

## 1. The Glimpse Cycle as a Process Model

The core argument: temporal wearing interaction is not a single event but a **cyclic process**:

```
attract → approach → don → glimpse → doff → rest → [return →] attract → ...
```

This contrasts with dominant interaction models that assume either:
- **Single-session** use (pick up, use, put down, done)
- **Continuous** use (wear all day)

The glimpse cycle is neither. It is **intermittent, voluntary, and repeating** — more like breathing than like opening an application.

---

## 2. Calm Technology & Attention Transitions

### Weiser & Brown (1996) [DOI: 10.1007/978-1-4612-0685-9_6] — The Coming Age of Calm Technology

The foundational text for understanding attention transitions in computing. Core concept:

- Information moves between **center** and **periphery** of attention
- Good technology allows this movement to be fluid and user-initiated
- **"Calm technology engages both the center and the periphery of our attention, and in fact moves back and forth between the two."**

> Weiser, M., & Brown, J. S. (1996). The Coming Age of Calm Technology. In *Beyond Calculation* (pp. 75–85). Copernicus/Springer.

**Mapping to temporal wearing**: The device at rest (on a table) is at the periphery. When donned for a glimpse, it moves to the center. When doffed, it returns to periphery. This is a *physical instantiation* of Weiser & Brown's attention transition — not just information moving between center/periphery, but the entire computing apparatus physically transitioning.

### Bakker et al. (2015) [DOI: 10.1007/s00779-014-0775-2] — Peripheral Interaction

Extended calm technology into a design framework for **peripheral interaction** — interactions that do not require focused attention. Key contributions:

- Taxonomy of interaction along the **attention spectrum** (peripheral → focal)
- Design patterns for artifacts that support fluid transitions between attention levels
- Evaluation methodology for peripheral interaction (ecological, longitudinal)

> Bakker, S., van den Hoven, E., & Eggen, B. (2015). Evaluating Peripheral Interaction Design. *Human–Computer Interaction*, 30(6), 473–506.

> Bakker, S., van den Hoven, E., & Eggen, B. (2015). Design for Peripheral Interaction. Eindhoven University of Technology (PhD thesis).

**Key insight**: Bakker argues that the *transition itself* between peripheral and focal attention is a design concern. Temporal wearing makes this transition physical and deliberate — donning = shifting to focal; doffing = returning to peripheral.

### Hausen et al. (2012) [DOI: 10.1145/2148131.2148191] — StayInTouch

Explored peripheral awareness displays that move between ambient and focal modalities. Demonstrated that physical form factors affect the ease of attention transition.

> Hausen, D., Boring, S., Lueling, C., Rodestock, S., & Butz, A. (2012). StayInTouch: An Ambient Awareness System for Remote Couples. *Proc. NordiCHI 2012*, 516–519. ACM.

---

## 3. Cyclic Interaction Models

### Interaction as Cycle (vs. Funnel or Pipeline)

Most HCI interaction models are **sequential** or **funnel-shaped**:
- Norman's (1986) [DOI: 10.1007/978-1-4612-4600-8] **seven stages of action** (gulf of execution → gulf of evaluation) is a single cycle, but typically modeled for one task completion
- Müller et al.'s **audience funnel** (passing by → follow-up) is linear
- Forlizzi & Battarbee's (2004) [DOI: 10.1145/1013115.1013152] **experience framework** distinguishes experience, an experience, and co-experience — but doesn't model return

The glimpse cycle is unique in that **return is an expected, designed-for phase**. The closest existing models:

### Benford et al. (2009) [DOI: 10.1145/1518701.1518812] — Trajectories Through Mixed Reality

Proposed **trajectories** as a framework for designing mixed reality experiences. Key concepts:

- **Canonical trajectory**: The designed path through an experience
- **Participant trajectory**: The actual path taken
- **Transitions**: Moments of crossing boundaries (physical, temporal, interface)
- **Interleaving**: How mixed reality experiences interleave with the rest of life

> Benford, S., Giannachi, G., Koleva, B., & Rodden, T. (2009). From Interaction to Trajectories: Designing Coherent Journeys Through User Experiences. *Proc. CHI 2009*, 709–718. ACM.

**Critical connection**: Benford et al. explicitly discuss how experiences are not contained within single sessions but extend across time, with planned transitions between engagement and disengagement. The glimpse cycle is a *micro-trajectory* — a repeating loop within a larger experiential trajectory.

### Ciolfi & Bannon (2007) [DOI: 10.1080/15710880701524559] — Designing for Visitor Engagement

Studied how museum visitors return to and revisit interactive installations within a single visit. Found that:

- Return visits to the same exhibit are common (not exceptional)
- Each return brings different expectations and attention
- The physical availability of the artifact (always there, waiting) enables casual re-engagement

> Ciolfi, L., & Bannon, L. J. (2007). Designing Hybrid Places: Merging Interaction Design, Ubiquitous Computing and Geographies of the Museum Space. *CoDesign*, 3(3), 159–180.

### Lehn et al. (2001) [DOI: 10.1525/si.2001.24.2.189] — Revisiting Exhibits

Ethnographic study of how museum visitors revisit exhibits, often bringing companions back to see something they found interesting. This **social return** pattern maps directly to temporal wearing: one person glimpses, doffs, tells a companion, who then dons the device.

> vom Lehn, D., Heath, C., & Hindmarsh, J. (2001). Exhibiting Interaction: Conduct and Collaboration in Museums and Galleries. *Symbolic Interaction*, 24(2), 189–216.

---

## 4. Transitional Interfaces

### Hubenschmid et al. (2022, 2023) — Cross-Device & Cross-Reality Transitions

Studied how users transition between devices (phone → tablet → AR → VR) and how to design for continuity across these transitions. Key findings:

- Transitions should preserve **spatial context** — objects should appear in consistent locations
- **Gradual transitions** are preferred over abrupt switches
- Users develop **mental models** of where information "lives" across devices

> Hubenschmid, S., Wieland, J., Fink, D., Batch, A., Zagermann, J., Elmqvist, N., & Reiterer, H. (2022). ReLive: Bridging In-Situ and Ex-Situ Visual Analytics for Analyzing Mixed Reality User Studies. *Proc. CHI 2022*, Article 250. ACM. [DOI: 10.1145/3491102.3517550]

> Schmidt, L., & Yigitbas, E. (2024). Development and Usability Evaluation of Transitional Cross-Reality Interfaces. *Proc. ACM on Human-Computer Interaction (EICS)*, 8(263), 31. [DOI: 10.1145/3664637]

**For temporal wearing**: The don/doff transition IS a cross-reality transition — from unmediated reality to mixed reality and back. But unlike Hubenschmid's device-switching, temporal wearing's transition is **embodied** (putting something on your head) rather than digital (switching apps).

### Ens et al. (2015) [DOI: 10.1145/2556288.2557058] — Candid Interaction

Introduced techniques for **revealing** hidden mobile/wearable computing activities to bystanders. Explored a design space where:

- Wearable device use is made **transparent** to others
- Social awareness of device use affects interaction norms
- Seven prototypes demonstrated different revelation strategies

> Ens, B., Grossman, T., Anderson, F., Matejka, J., & Fitzmaurice, G. (2015). Candid Interaction: Revealing Hidden Mobile and Wearable Computing Activities. *Proc. UIST 2015*, 467–476. ACM. [DOI: 10.1145/2807442.2807449]

**Relevance**: Temporal wearing inherently makes device use visible (you can see someone donning/doffing). The question is what to reveal about the *content* of the glimpse to bystanders.

### Marquardt & Greenberg (2015) [DOI: 10.1007/978-3-031-02208-1] — Proxemic Interactions

Framework for using spatial relationships (distance, orientation, identity, movement) as input for interactive systems. Based on Hall's (1966) proxemics:

- **Intimate** (< 0.45m): Device worn on body
- **Personal** (0.45–1.2m): Device held or on nearby surface
- **Social** (1.2–3.6m): Device visible but not accessible
- **Public** (> 3.6m): Device part of environment

> Marquardt, N., & Greenberg, S. (2015). *Proxemic Interactions: From Theory to Practice*. Morgan & Claypool.

> Marquardt, N., Diaz-Marino, R., Boring, S., & Greenberg, S. (2011). The Proximity Toolkit: Prototyping Proxemic Interactions in Ubiquitous Computing Ecologies. *Proc. UIST 2011*, 315–326. ACM. [DOI: 10.1145/2047196.2047238]

**Mapping**: The glimpse cycle traverses proxemic zones — the device starts at social distance (on display), moves to personal distance (picked up), then intimate distance (worn on face), then reverses. This is a **proxemic trajectory** through the glimpse cycle.

### Grubert et al. (2018) [DOI: 10.1109/TVCG.2016.2543720] — Text Entry in Immersive Head-Mounted Display-Based VR

While focused on text entry, documented the transition costs of donning/doffing HMDs and the concept of **"break-out" interaction** — tasks that require temporarily leaving VR.

> Grubert, J., Witzani, L., Ofek, E., Pahud, M., Kranz, M., & Kristensson, P. O. (2018). Text Entry in Immersive Head-Mounted Display-Based Virtual Reality Using Standard Keyboards. *Proc. VR 2018*, 159–166. IEEE.

---

## 5. Micro-Mobility

### Luff & Heath (1998) [DOI: 10.1145/289444.289505] — Mobility in Collaboration

Foundational paper on **micro-mobility** — the fine-grained, moment-to-moment repositioning of artifacts (documents, devices) during collaborative work. Key concepts:

- Objects are not just "used" but constantly **repositioned** relative to participants
- Repositioning serves communicative functions (showing, sharing, orienting toward/away)
- The **physical manipulation of an artifact IS part of the interaction**, not just a precondition

> Luff, P., & Heath, C. (1998). Mobility in Collaboration. *Proc. CSCW 1998*, 305–314. ACM.

**Critical insight for temporal wearing**: The device is a **micro-mobile artifact**. When someone picks it up, shows it to a companion, holds it out for them to try, passes it — these are all micro-mobility actions that are integral to the interaction, not incidental. The glimpse cycle's social dimension is fundamentally about the micro-mobility of the device.

### Luff et al. (2003) [DOI: 10.1207/s15327051hci1812_3] — Fractured Ecologies

Extended micro-mobility to examine how mobile technologies create **fractures** in social interaction — moments where device use pulls a participant out of the shared social space.

> Luff, P., Heath, C., Kuzuoka, H., Hindmarsh, J., Yamazaki, K., & Oyama, S. (2003). Fractured Ecologies: Creating Environments for Collaboration. *Human–Computer Interaction*, 18(1–2), 51–84.

**For temporal wearing**: Donning creates a deliberate fracture (entering MR); doffing repairs it (returning to shared reality). The brevity of the glimpse means the fracture is short — a **micro-fracture** — which may be more socially acceptable than sustained HMD use.

### Koelle et al. (2022) [DOI: 10.18573/book3.l] — Donning and Doffing

Recent work examining how the physical acts of putting on and taking off wearable devices carry social meaning. The donning/doffing moment is a **transition ritual** that signals intent.

> Relevant to the concept but need to verify specific publication. [UNVERIFIED]

---

## 6. Intermittent Interaction & Resumption

### Iqbal & Horvitz (2007) [DOI: 10.1145/1240624.1240730] — Disruption and Recovery of Computing Tasks

Studied how people recover from interruptions during computer work. Key findings:

- **Resumption lag**: Time to return to a task after interruption increases with task complexity
- People develop **placekeeping strategies** to facilitate return
- The structure of the interrupted task affects recovery ease

> Iqbal, S. T., & Horvitz, E. (2007). Disruption and Recovery of Computing Tasks: Field Study, Analysis, and Directions. *Proc. CHI 2007*, 677–686. ACM.

### Pejovic & Musolesi (2014) [DOI: 10.1145/2632048.2632062] — InterruptMe

Studied interruptibility in mobile computing. Found that:

- Context (physical activity, location, time) predicts interruptibility
- **Transitions between activities** are natural interruption points
- People prefer interruptions at **breakpoints** — moments between tasks

> Pejovic, V., & Musolesi, M. (2014). InterruptMe: Designing Intelligent Prompting Mechanisms for Pervasive Applications. *Proc. UbiComp 2014*, 897–908. ACM.

**For temporal wearing**: The doff moment IS a natural breakpoint. The glimpse cycle inherently provides breakpoints (don/doff) that structure when the user is available for social interaction vs. immersed in MR.

### Intermittent Computing (Lucia et al., 2017)

In embedded systems, **intermittent computing** refers to computation that proceeds through cycles of power-on, compute, power-off. The system must maintain state across power cycles.

> Lucia, B., Balaji, V., Colin, A., Maeng, K., & Ruppel, E. (2017). Intermittent Computing: Challenges and Opportunities. *SNAPL 2017*, Article 8. [DOI: 10.4230/LIPIcs.SNAPL.2017.8]

**Metaphorical connection**: Temporal wearing is "intermittent experiencing" — the user's experience proceeds through cycles of engagement and disengagement, and the system must maintain coherence across these cycles. What does the user see when they re-don the device?

### Dix (2002) — Beyond Intention

Discussed how much of human interaction with technology is **not intentional** in the traditional sense but emerges from situated action. Relevant to the "rest" and "return" phases — the decision to re-don may not be a deliberate plan but an emergent response to social/environmental cues.

> Dix, A. (2002). Beyond Intention — Pushing Boundaries with Incidental Interaction. *Proc. Building Bridges: Interdisciplinary Context-Sensitive Computing*. [URL: https://alandix.com/academic/papers/beyond-intention-2002/]

---

## 7. Somatic & Embodied Transitions

### Höök (2018) — Designing with the Body

Argued that interaction design must account for the **felt experience** of the body. The don/doff transition is not just functional but somatic — the felt sensation of placing something on your face, the weight, the visual shift.

> Höök, K. (2018). *Designing with the Body: Somaesthetic Interaction Design*. MIT Press. [DOI: 10.7551/mitpress/11481.001.0001]

### Schiphorst (2009) [DOI: 10.1145/1520340.1520345] — Soft(n)

Explored how body awareness and somatic practices inform interaction design. The physicality of temporal wearing — holding, lifting, placing on face, removing — engages proprioception and tactile awareness in ways that screen-based interaction does not.

> Schiphorst, T. (2009). Soft(n): Toward a Somaesthetics of Touch. *Proc. CHI 2009 Extended Abstracts*, 2427–2438. ACM.

---

## 8. Synthesis: The Glimpse Cycle in Context

### Positioning Against Existing Models

| Model | Structure | Return? | Physical? | Temporal Wearing Advance |
|-------|-----------|---------|-----------|-------------------------|
| Norman's Action Cycle | Single loop | Same task | No | Glimpse cycle spans physical don/doff |
| Audience Funnel (Müller) | Linear funnel | No | No | Cyclic, with designed return |
| Trajectories (Benford) | Linear with branches | Possible | Yes | Micro-trajectories with repeating loops |
| Calm Tech (Weiser) | Center ↔ periphery | Continuous | No | Physical instantiation of attention shift |
| Peripheral Interaction (Bakker) | Attention spectrum | Fluid | Partially | Full-body transition (don/doff) |
| Proxemics (Marquardt) | Distance zones | Possible | Yes | Device traverses ALL zones in one cycle |
| Micro-mobility (Luff & Heath) | Artifact repositioning | N/A | Yes | Device IS the repositioned artifact |

### What the Glimpse Cycle Adds

1. **Physicality of transition**: Unlike digital attention shifts, temporal wearing involves a whole-body physical act (donning/doffing). This makes the transition **deliberate, visible, and socially meaningful**.

2. **Designed return**: The cycle explicitly includes rest and return phases. The interaction is designed to be left and returned to, not to capture sustained attention.

3. **Social micro-mobility**: The device moves between people, not just between attention states. Passing the device IS part of the interaction design.

4. **Intermittent coherence**: Like intermittent computing, the system must maintain experiential coherence across cycles of engagement and disengagement.

5. **Somatic punctuation**: The physical sensations of donning and doffing create **felt boundaries** between engagement states — a somatic rhythm that digital interfaces lack.

---

## References (Consolidated)

- Bakker, S., van den Hoven, E., & Eggen, B. (2015). Evaluating Peripheral Interaction Design. *Human–Computer Interaction*, 30(6), 473–506. [DOI: 10.1007/s00779-014-0775-2]
- Benford, S., Giannachi, G., Koleva, B., & Rodden, T. (2009). From Interaction to Trajectories. *Proc. CHI 2009*, 709–718. [DOI: 10.1145/1518701.1518812]
- Bitgood, S. (2010). An Attention-Value Model of Museum Visitors. *CAISE*. [DOI: 10.4324/9781315433455]
- Brignull, H., & Rogers, Y. (2003). Enticing People to Interact with Large Public Displays. *Proc. INTERACT 2003*, 17–24. [URL: http://www.idc.ul.ie/library/paperdb/papers/IDCpaper_brignull.pdf]
- Ciolfi, L., & Bannon, L. J. (2007). Designing Hybrid Places. *CoDesign*, 3(3), 159–180. [DOI: 10.1080/15710880701524559]
- Dix, A. (2002). Beyond Intention. *Proc. Building Bridges*. [URL: https://alandix.com/academic/papers/beyond-intention-2002/]
- Ens, B., Grossman, T., Anderson, F., Matejka, J., & Fitzmaurice, G. (2015). Candid Interaction. *Proc. UIST 2015*, 467–476. [DOI: 10.1145/2807442.2807449]
- Grubert, J., et al. (2018). Text Entry in Immersive HMD-Based VR. *Proc. VR 2018*, 159–166. [DOI: 10.1109/TVCG.2016.2543720]
- Höök, K. (2018). *Designing with the Body*. MIT Press. [DOI: 10.7551/mitpress/11481.001.0001]
- Hornecker, E., & Buur, J. (2006). Getting a Grip on Tangible Interaction. *Proc. CHI 2006*, 437–446. [DOI: 10.1145/1124772.1124838]
- Hubenschmid, S., et al. (2022). ReLive: Bridging In-Situ and Ex-Situ Visual Analytics. *Proc. CHI 2022*, Article 250. [DOI: 10.1145/3491102.3517550]
- Iqbal, S. T., & Horvitz, E. (2007). Disruption and Recovery of Computing Tasks. *Proc. CHI 2007*, 677–686. [DOI: 10.1145/1240624.1240730]
- Koelle, M., Ananthanarayan, S., & Boll, S. (2020). Social Acceptability in HCI. *Proc. CHI 2020*, Article 318. [DOI: 10.1145/3313831.3376162]
- Lucia, B., et al. (2017). Intermittent Computing. *SNAPL 2017*, Article 8. [DOI: 10.4230/LIPIcs.SNAPL.2017.8]
- Luff, P., & Heath, C. (1998). Mobility in Collaboration. *Proc. CSCW 1998*, 305–314. [DOI: 10.1145/289444.289505]
- Luff, P., et al. (2003). Fractured Ecologies. *Human–Computer Interaction*, 18(1–2), 51–84. [DOI: 10.1207/s15327051hci1812_3]
- Marquardt, N., & Greenberg, S. (2015). *Proxemic Interactions*. Morgan & Claypool. [DOI: 10.1007/978-3-031-02208-1]
- Michelis, D., & Müller, J. (2011). The Audience Funnel. *IJHCI*, 27(6), 562–579. [DOI: 10.1080/10447318.2011.555299]
- Müller, J., et al. (2009). Display Blindness. *Proc. Pervasive 2009*, 1–8. [DOI: 10.1007/978-3-642-01516-8_1]
- Müller, J., et al. (2010). Requirements and Design Space for Interactive Public Displays. *Proc. ACM MM 2010*, 1285–1294. [DOI: 10.1145/1873951.1874203]
- Norman, D. A. (2013). *The Design of Everyday Things* (Revised). Basic Books. [DOI: 10.15358/9783800648108]
- Pejovic, V., & Musolesi, M. (2014). InterruptMe. *Proc. UbiComp 2014*, 897–908. [DOI: 10.1145/2632048.2632062]
- Reeves, S., Benford, S., O'Malley, C., & Fraser, M. (2005). Designing the Spectator Experience. *Proc. CHI 2005*, 741–750. [DOI: 10.1145/1054972.1055074]
- Rico, J., & Brewster, S. (2010). Usable Gestures for Mobile Interfaces. *Proc. CHI 2010*, 887–896. [DOI: 10.1145/1753326.1753458]
- Sandifer, C. (2003). Technological Novelty and Open-Endedness. *JRST*, 40(2), 121–137. [DOI: 10.1002/tea.10068]
- Schiphorst, T. (2009). Soft(n): Toward a Somaesthetics of Touch. *Proc. CHI EA 2009*, 2427–2438. [DOI: 10.1145/1520340.1520345]
- Schmidt, L., & Yigitbas, E. (2024). Transitional Cross-Reality Interfaces. *Proc. ACM HCI (EICS)*, 8(263). [DOI: 10.1145/3664637]
- Serrell, B. (1997). Paying Attention. *Curator*, 40(2), 108–125. [DOI: 10.1111/j.2151-6952.1997.tb01292.x]
- vom Lehn, D., Heath, C., & Hindmarsh, J. (2001). Exhibiting Interaction. *Symbolic Interaction*, 24(2), 189–216. [DOI: 10.1525/si.2001.24.2.189]
- Weiser, M., & Brown, J. S. (1996). The Coming Age of Calm Technology. In *Beyond Calculation*, 75–85. [DOI: 10.1007/978-1-4612-0685-9_6]
- Wouters, N., et al. (2016). Uncovering the Honeypot Effect. *Proc. DIS 2016*, 5–16. [DOI: 10.1145/2901790.2901796]
