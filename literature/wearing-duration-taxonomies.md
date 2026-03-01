# Wearing Duration Taxonomies

*How has the wearable computing field categorized wearing time?*

## 1. The Absence of Explicit Duration Taxonomies

Remarkably, the wearable computing literature lacks an explicit taxonomy organized by *intended wearing duration*. Existing frameworks prioritize:

- **Body placement** (where on the body)
- **Form factor** (rigid vs. flexible, size, weight)
- **Functionality** (sensing, display, actuation)
- **Integration level** (standalone vs. tethered)

Duration appears only implicitly, usually as a usability variable rather than a design dimension.

## 2. Existing Frameworks and Their Temporal Gaps

### 2.1 Gemperle et al. (1998) [DOI: 10.1109/ISWC.1998.729537] — Design for Wearability
**Venue:** ISWC '98 | **Citation count:** ~800+

The foundational ISWC paper on wearability. Defines wearability as "the interaction between the human body and the wearable object" and proposes 13 design guidelines:

1. Placement (body location)
2. Form language (organic vs. geometric)
3. Human movement (joint proximity)
4. Proxemics (personal space)
5. Sizing (body variation)
6. Attachment (how it stays on)
7. Containment (enclosing components)
8. Weight (distribution)
9. Accessibility (reaching controls)
10. Sensory interaction (visibility, tactility)
11. Thermal (heat management)
12. Aesthetics (appearance)
13. Long-term use (durability, hygiene)

**Temporal gap:** Guideline 13 ("long-term use") assumes extended wearing. No guideline addresses *brief* or *transitional* wearing. The framework implicitly assumes permanent or session-length wear.

### 2.2 Zeagler (2017) [DOI: 10.1145/3123021.3123042] — Where to Wear It
**Venue:** ISWC '17

Body maps for wearable placement organized by:
- Functional considerations (reach, visibility)
- Technical considerations (sensor proximity, power)
- Social considerations (visibility, intrusiveness)

**Temporal gap:** Social considerations touch on duration ("staring at a wrist-worn device is more acceptable than staring at a head-mounted device") but don't formalize wearing duration as a variable.

### 2.3 Starner (2001) [DOI: 10.1109/40.946681] — The Challenges of Wearable Computing
**Venue:** IEEE Micro

Distinguishes:
- **Always-available** devices (assumed to be worn continuously)
- **Task-specific** devices (used for particular activities)

This comes closest to a temporal distinction, but task-specific still implies session-length wearing (minutes to hours), not seconds.

### 2.4 Knight et al. (2006) [DOI: 10.1109/ISWC.2002.1167220] — Comfort Assessment of Wearable Computers
**Venue:** ISWC '06

Proposes a comfort rating scale including "ease of donning and doffing." This acknowledges don/doff as a usability factor but treats it as *friction to be minimized* rather than a design opportunity.

### 2.5 Khurana et al. (2019) [DOI: 10.1145/3328913] — Detachable Smartwatch
**Venue:** IMWUT/UbiComp

Explores a smartwatch that can be detached from the wrist strap and used as a handheld device. The key insight: the same device can operate in different *wearing modes* (attached vs. detached). This is the closest precedent to temporal wearing as a design concept, though it focuses on device versatility rather than wearing duration as an interaction paradigm.

### 2.6 Park et al. (2019) [DOI: 10.1080/00140139.2019.1652351] — Comfort and User Acceptance
**Venue:** Ergonomics

Identifies acceptable ranges of physical attributes (weight, volume, contact area) by body location. Implicitly, comfort thresholds assume extended wear. For temporal wearing, these thresholds may be relaxed: users tolerate more weight/bulk for seconds than for hours.

### 2.7 Sorysz et al. (2025) [DOI: 10.1109/ISMAR-Adjunct68609.2025.00160] — Beyond the Pocket
**Venue:** arXiv (ISWC-oriented)

Large-scale international study on user preferences for bodily placements of commercial wearables. Focuses on where users *want* to wear devices, not on duration, but provides relevant data on body-placement preferences that interact with temporal wearing patterns.

## 3. Body Placement Through a Temporal Lens

Reframing Gemperle's body placement framework with temporal wearing in mind:

| Body Location | Don/Doff Speed | Temporal Wearing Suitability | Examples |
|--------------|----------------|------------------------------|----------|
| **Hand/handheld** | Instant (grab) | ★★★★★ | Phone, handheld viewer, lorgnette |
| **Neck-hung** | Near-instant (raise to eyes) | ★★★★★ | Neck-hung binoculars, our prototypes |
| **Wrist** | Fast (strap, ~5s) | ★★★ | Watch-style devices |
| **Chest/torso** | Moderate (~10s) | ★★ | Chest-mounted cameras |
| **Head** | Slow (~15-30s) | ★ | VR headset, AR glasses |
| **Full body** | Very slow (minutes) | ☆ | Motion capture suit, exoskeleton |

**Key insight:** Body locations with fastest don/doff times are most compatible with temporal wearing. This explains why our prototypes cluster around handheld, neck-hung, and stationary (zero don/doff) form factors.

## 4. Our Proposed Taxonomy

| Category | Duration | Don/Doff Relationship | Design Priority | Examples |
|----------|----------|-----------------------|----------------|----------|
| **Permanent wear** | Hours–days | Don once, forget | Comfort, aesthetics, battery life | Smartwatch, smart ring, smart glasses |
| **Session wear** | Minutes–hours | Don/doff as bookends | Immersion, sustained comfort, content depth | VR headset, AR HMD, sports tracker |
| **Temporal wear** | Seconds | **Don/doff IS the interaction** | Instant-on, information density, social legibility | Peek viewer, lorgnette, handheld AR, viewfinder |

### What Makes Temporal Wearing Distinct

1. **Donning/doffing is not overhead** — it's the productive interaction itself
2. **Comfort constraints are relaxed** — brief discomfort is tolerable
3. **Social legibility is enhanced** — brief, purposeful acts are easier for bystanders to interpret
4. **Design must maximize information per second** — no time for tutorials, onboarding, or adjustment
5. **Context triggers wearing** — wearing is *occasioned* (situated) rather than habitual

## 5. References

- Gemperle, F., et al. (1998). Design for Wearability. *ISWC '98*.
- Zeagler, C. (2017). Where to Wear It. *ISWC '17*.
- Starner, T. (2001). The Challenges of Wearable Computing. *IEEE Micro*, 21(4).
- Knight, J. F., et al. (2006). The comfort assessment of wearable computers. *ISWC '06*.
- Khurana, R., et al. (2019). Detachable Smartwatch. *IMWUT*.
- Park, H., et al. (2019). Designing wearable computing devices for improved comfort. *Ergonomics*, 62(11).
- Sorysz, J., et al. (2025). Beyond the Pocket. *arXiv*.
