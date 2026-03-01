# Temporal Wearing: A Literature Review

*Master document for positioning "Temporal Wearing" as a novel interaction paradigm for ISWC 2026*

## 1. Introduction

This review synthesizes literature across seven thematic areas to establish **temporal wearing** — the concept that the act of donning, using, and doffing a wearable device constitutes the interaction itself, measured in seconds rather than minutes or hours — as a distinct and underexplored interaction paradigm in wearable computing.

The review supports the reframing of "Just a Glimpse: Designing Seamless Transitional Interfaces for Transient Mixed Reality Use" for ISWC 2026, positioning six non-head-mounted MR prototypes (handheld, neck-hung, stationary) as exemplars of temporal wearing in exhibition, museum, and classroom contexts.

---

## 2. Wearing Duration Taxonomies

**See:** [wearing-duration-taxonomies.md](wearing-duration-taxonomies.md)

The wearable computing field has implicitly operated with a binary: devices are either *worn* or *not worn*. Duration taxonomies are surprisingly rare. Gemperle et al. (1998) [DOI: 10.1109/ISWC.1998.729537] defined wearability as "the interaction between the human body and the wearable object" but focused on spatial (body placement) rather than temporal dimensions. Zeagler (2017) [DOI: 10.1145/3123021.3123042] extended this with body maps for wearable placement, again primarily spatial.

**Key gap:** No existing taxonomy explicitly categorizes wearables by *intended wearing duration* as a primary design variable. The closest work includes:

- **Khurana et al. (2019) [DOI: 10.1145/3328913]** — "Detachable smartwatch" (IMWUT) explores mode-switching between attached and detached states, implicitly acknowledging temporal variation in wearing
- **Starner (2001) [DOI: 10.1109/40.946681]** — "The challenges of wearable computing" distinguishes always-available vs. task-specific wearables but doesn't formalize duration
- **Knight et al. (2006) [DOI: 10.1109/ISWC.2002.1167220]** — Comfort assessment framework mentions donning/doffing but as usability concern, not interaction paradigm

**Our proposed taxonomy:**

| Category | Duration | Examples | Relationship to body |
|----------|----------|----------|---------------------|
| Permanent wear | Hours–days | Smartwatch, smart glasses | Integrated, forgotten |
| Session wear | Minutes–hours | VR headset, AR HMD | Committed, immersive |
| **Temporal wear** | **Seconds** | **Peek devices, handheld viewers** | **Transitional, the wearing IS the interaction** |

---

## 3. Transition and Liminal Interaction

**See:** [transition-interactions.md](transition-interactions.md)

Temporal wearing is fundamentally about *transition* — the liminal moment between not-wearing and wearing, between unaugmented and augmented perception. Several research threads inform this:

- **Glanceable AR** (Lu et al., 2020, 2021) — Explores rapid activation of AR information in head-worn displays. "Glanceable" implies seconds-long attention, but assumes permanently worn hardware. Temporal wearing extends this: the *device itself* is glanceable.
- **Micro-interactions** (Ashbrook, 2010) — Interactions of 4 seconds or less with mobile/wearable devices. Directly relevant timeframe, but focused on input gestures on permanently worn devices, not on donning/doffing as interaction.
- **Cross-device transitions** (Hubenschmid et al., 2025) — "Hybrid User Interfaces" survey covers cross-device interaction in MR but focuses on simultaneous multi-device use, not transitional wearing.
- **Transitional interfaces** (Dhaka et al., 2024) — AR UI transitions at ISMAR; closest technical analog but addresses software transitions within a worn device, not the physical transition of wearing.

**Key insight:** Existing work on transitions focuses on *software state transitions within worn devices*. Temporal wearing reframes the *physical act of wearing* as the transition itself.

---

## 4. Social Acceptability of Brief Wearable Use

**See:** [social-acceptability-temporal.md](social-acceptability-temporal.md)

A critical advantage of temporal wearing is reduced social stigma compared to permanent HMD use:

- **Koelle et al. (2020) [DOI: 10.1145/3313831.3376162]** — "Social Acceptability in HCI: A Survey of Methods, Measures, and Design Strategies" (CHI 2020). Comprehensive survey establishing that social acceptability depends on context, duration, and visibility of device use.
- **Koelle et al. (2017) [DOI: 10.1145/2785830.2785842]** — "All about Acceptability? Identifying Factors for the Adoption of Data Glasses" (ISWC 2017). Shows that even familiarization doesn't fully overcome negative attitudes toward always-worn data glasses.
- **Profita et al. (2013) [DOI: 10.1145/2493988.2494331]** — "Don't Mind Me Touching My Wrist" (ISWC 2013). On-body interaction in public; body location affects perceived social acceptability.
- **Profita et al. (2016) [DOI: 10.1145/2904092.2904101]** — "The AT Effect" (CHI 2016). Disability context affects perceived acceptability of HMD use.

**Key argument for temporal wearing:** If social acceptability is inversely related to wearing duration and visibility, then temporal wearing (seconds-long, purpose-clear, socially readable) may represent an optimal point on the acceptability curve.

---

## 5. Body-Device Coupling Temporality

**See:** [wearing-duration-taxonomies.md](wearing-duration-taxonomies.md) (Section 3)

Gemperle et al. (1998) [DOI: 10.1109/ISWC.1998.729537] established 13 design guidelines for wearability at ISWC, organized around body placement. Through a temporal lens:

- **Placement affects transition speed:** Wrist (fast don/doff) vs. head (slow, socially conspicuous) vs. neck-hung (instant raise-to-eyes)
- **Zeagler (2017) [DOI: 10.1145/3123021.3123042]** — "Where to Wear It" (ISWC 2017). Body maps for wearable placement considering functional, technical, and social factors.
- **Park et al. (2019) [DOI: 10.1080/00140139.2019.1652351]** — Acceptable form factors vary by body area; weight and contact area thresholds differ by placement.

**Novel contribution:** Reframing Gemperle's spatial framework with a temporal axis reveals that *different body placements enable different temporal modalities of wearing*.

---

## 6. Exhibition, Museum, and Public Deployments

**See:** [exhibition-deployments.md](exhibition-deployments.md)

Real-world instances of temporal wearing already exist in exhibition and museum contexts but have not been theorized as such:

- **vom Lehn et al. (2001) [DOI: 10.1525/si.2001.24.2.189]** — Social nature of museum encounters; visitors' interactions are brief, shared, and performative
- **Li et al. (2024) [DOI: 10.1177/21582440241303507]** — Visitors' Acceptance of Wearable AR Technology in Museums (SAGE Open)
- **Museum AR guides** — Various deployments represent de facto temporal wearing
- **Pop-up VR experiences** — Exhibition VR stations where visitors briefly don a headset

---

## 7. Calm Technology and Peripheral Interaction

**See:** [theoretical-foundations.md](theoretical-foundations.md)

- **Weiser & Brown (1996) [DOI: 10.1007/978-1-4612-0685-9_6]** — Calm technology shifts information between center and periphery. Temporal wearing shifts the *device itself*.
- **Bakker et al. (2015) [DOI: 10.1007/s00779-014-0775-2]** — Peripheral interaction framework. Temporal wearing creates a deliberate shift from peripheral to focal attention through physical device engagement.

---

## 8. Related HCI Concepts

- **Micro-mobility** (Luff & Heath, 1998) — Small-scale repositioning of artifacts. Temporal wearing extends this to body-device transitions.
- **Situated action** (Suchman, 1987/2007) — Temporal wearing is inherently situated: wearing responds to contextual triggers.
- **Appropriation** (Dourish, 2003; Dix, 2007) — Low-commitment temporal wearing may facilitate appropriation.
- **Candid Interaction** (Ens et al., 2015) — Visibility/hiddenness of wearable computing activities.

---

## 9. Gap Analysis

**The core gap:** No existing work explicitly theorizes wearing duration as a primary design dimension or identifies interactions where *the wearing act itself constitutes the interaction*.

**What "temporal wearing" contributes:**

1. **A missing cell in the taxonomy** — fills the gap between permanent and session wearing
2. **Reframing donning/doffing** — from overhead to productive use (paradigm inversion)
3. **Design implications** — instant-on, high information density, social legibility, rapid body-device coupling
4. **Bridge between wearable computing and interaction design** — connects body-device relationships to attention, transition, and social context

---

## 10. References (Consolidated)

### Wearability & Body Placement
- Gemperle, F., Kasabach, C., Stivoric, J., Bauer, M., & Martin, R. (1998). Design for Wearability. *ISWC '98*.
- Zeagler, C. (2017). Where to Wear It. *ISWC '17*.
- Park, H., Pei, J., Shi, M., Xu, Q., & Fan, J. (2019). Designing wearable computing devices for improved comfort and user acceptance. *Ergonomics*, 62(11), 1474-1484.
- Knight, J. F., Baber, C., Schwirtz, A., & Bristow, H. W. (2006). The comfort assessment of wearable computers. *ISWC '06*.

### Social Acceptability
- Koelle, M., Ananthanarayan, S., & Boll, S. (2020). Social Acceptability in HCI. *CHI '20*.
- Koelle, M., El Ali, A., Cobus, V., Heuten, W., & Boll, S. (2017). All about Acceptability? *ISWC '17*.
- Koelle, M., Wallbaum, T., Heuten, W., & Boll, S. C. (2019). Evaluating a Wearable Camera's Social Acceptability In-the-Wild. *CHI EA '19*.
- Profita, H., et al. (2013). Don't Mind Me Touching My Wrist. *ISWC '13*.
- Profita, H., et al. (2016). The AT Effect. *CHI '16*.
- Goodman, S., et al. (2019). Social Tensions with Head-Mounted Displays for Accessibility.
- Kelly, N. & Gilbert, S. B. (2018). The Wearer, the Device, and Its Use. *HFES*.

### Glanceable & Micro-Interactions
- Lu, F., et al. (2020). Glanceable AR. *Virginia Tech*.
- Lu, F., et al. (2021). Rapid Activation of Glanceable Information in AR. *SUI '21*.
- Ashbrook, D. (2010). Enabling Mobile Micro-interactions. *PhD Thesis, Georgia Tech*.

### Transitions & Cross-Device
- Dhaka, R., et al. (2024). AR UI Transitions. *ISMAR '24*.
- Hubenschmid, S., et al. (2025). Hybrid User Interfaces. *arXiv:2509.05491*.
- Khurana, R., et al. (2019). Detachable Smartwatch. *IMWUT*.

### Calm Technology & Peripheral Interaction
- Weiser, M. & Brown, J. S. (1996). The Coming Age of Calm Technology. *Xerox PARC*.
- Bakker, S., van den Hoven, E., & Eggen, B. (2015). Peripheral Interaction. *PUC*, 19(1), 239-254.
- Bakker, S., Hausen, D., & Selker, T. (2016). *Peripheral Interaction*. Springer.

### Situated Action, Micro-mobility, Appropriation
- Suchman, L. (1987/2007). *Human-Machine Reconfigurations*. Cambridge University Press.
- Luff, P. & Heath, C. (1998). Mobility in Collaboration. *CSCW '98*.
- Heath, C., Knoblauch, H., & Luff, P. (2000). Technology and social interaction. *BJS*, 51(2).
- Ens, B., et al. (2015). Candid Interaction. *UIST '15*.
- Dourish, P. (2003). The Appropriation of Interactive Technologies. *CSCW*, 12(4).

### Museum & Exhibition
- vom Lehn, D., Heath, C., & Hindmarsh, J. (2001). Exhibiting Interaction. *Symbolic Interaction*, 24(2).
- Li, J., et al. (2024). Visitors' Acceptance of Wearable AR Technology in Museums. *SAGE Open*, 14(4).
- Mistry, P. & Maes, P. (2009). SixthSense. *SIGGRAPH '09*.

### General Wearable Computing
- Starner, T. (2001). The Challenges of Wearable Computing. *IEEE Micro*, 21(4).
- Oliver, H. (2021). Obstacles to Wearable Computing. *Cambridge TR UCAM-CL-TR-966*.
