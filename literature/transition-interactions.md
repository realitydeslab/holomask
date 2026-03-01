# Transition and Liminal Interactions

*Micro-interactions, glanceable displays, peek interactions, and transitional paradigms*

## 1. Overview

Temporal wearing positions the physical act of wearing as a *transition* — a liminal moment between unaugmented and augmented perception. This document reviews related interaction paradigms that involve brief, transitional encounters with technology.

## 2. Glanceable Interactions

### 2.1 Glanceable AR (Lu et al., 2020, 2021)
**Venue:** IEEE VR '20 [DOI: 10.1109/vr46266.2020.00113] / SUI '21 [DOI: 10.1145/3485279.3485286]

Feiyu Lu and colleagues proposed "Glanceable AR" as an interaction paradigm for AR head-worn displays where information is accessed through quick glances. Two key techniques:

- **Head-glance:** Virtual content fixed to user's body, accessed by head rotation
- **Gaze-summon:** Content summoned to central vision on demand

**Relevance to temporal wearing:** Glanceable AR shares the same *temporal intention* (seconds-long information access) but assumes a permanently worn device. Temporal wearing extends the glanceable concept to the *device itself* — the device is donned and doffed as a glance-equivalent action.

**Gap:** Glanceable AR addresses information management on always-worn devices; temporal wearing addresses device management for brief use.

### 2.2 Glanceable Feedback for Activity Trackers (Gouveia et al., 2016)
**Venue:** UbiComp '16 [DOI: 10.1145/2971648.2971754]

Explores design space of glanceable feedback on wearable activity trackers. Identifies that effective glanceable displays must convey information in <2 seconds of visual attention.

**Relevance:** Establishes the temporal constraint (~2 seconds) that temporal wearing must also meet. If the device is worn for only seconds, the display must communicate within the first second.

### 2.3 Smartwatch Glanceable Visualizations (IEEE, 2023)
**Venue:** IEEE VIS

Studies of part-to-whole visualizations on smartwatch faces designed for rapid comprehension. Demonstrates that effective glanceable displays use preattentive visual features.

## 3. Micro-Interactions

### 3.1 Ashbrook (2010) — Enabling Mobile Micro-interactions
**Venue:** PhD Thesis, Georgia Institute of Technology [URL: https://smartech.gatech.edu/handle/1853/36311]

Defines micro-interactions as device interactions lasting **4 seconds or less**. The key characteristics:
- Brief enough to perform while engaged in another primary task
- Low cognitive overhead
- Often reflexive/habitual

**Relevance:** Temporal wearing operates in the same duration range but reframes the *entire device encounter* (don + use + doff) as a micro-interaction, not just the input gesture.

### 3.2 Peek Interactions
The concept of "peeking" at information appears across several domains:
- **Phone peek** — Quick glance at phone screen without full engagement
- **Smartwatch peek** — Raise-to-wake gesture reveals time/notification
- **AR peek** — Our temporal wearing prototypes enable "peeking" into an augmented layer

**Gap:** Peeking has been studied for permanently carried/worn devices but not for devices that are *donned specifically to peek*.

## 4. Cross-Device Transitions

### 4.1 Hybrid User Interfaces (Hubenschmid et al., 2025)
**Venue:** arXiv [DOI: 10.48550/arXiv.2509.05491]

Comprehensive survey of cross-device interaction in MR. Identifies complementary use of 2D devices and MR environments. Key taxonomy dimensions:
- Device roles (primary, secondary, peripheral)
- Transition types (sequential, parallel, complementary)

**Relevance:** Temporal wearing represents a specific type of transition: from no-device to device to no-device, where the transition itself is the interaction. This is not covered in the HUI taxonomy.

### 4.2 Cross-Device Shortcuts (Beyeler, Cheng, & Holz, 2023)
**Venue:** ICMI '23 [DOI: 10.1145/3577190.3614145]

Seamless attention-guided content transfer between apps and devices via deep links. Focuses on reducing friction in cross-device transitions.

**Relevance:** Shares the goal of seamless transitions but addresses software/content transitions, not physical device transitions.

### 4.3 Transitional Interfaces in AR (Dhaka et al., 2024)
**Venue:** ISMAR '24 [DOI: 10.1109/ismar62088.2024.00134]

AR UI transitions — how AR interfaces transition between states. Closest technical analog to temporal wearing's transition concept, but operates at the software level within a worn device.

## 5. Candid Interaction (Ens et al., 2015)
**Venue:** UIST '15 [DOI: 10.1145/2807442.2807449]

"Candid Interaction: Revealing Hidden Mobile and Wearable Computing Activities." Addresses the tension between private device use and public visibility. Proposes techniques for making device activities visible or hidden as appropriate.

**Relevance to temporal wearing:** Temporal wearing is inherently "candid" — the brief, purposeful act of donning a device is publicly visible and socially readable. This contrasts with continuous wearable use, which can feel surveillance-like.

## 6. Key Insight

Existing transition/micro-interaction literature focuses on:
1. **Information transitions** within always-worn/always-carried devices
2. **Content transitions** between devices
3. **UI state transitions** within a single device

**Temporal wearing introduces a new transition type:** The *physical device transition* — the act of bringing a device to the body and removing it — as the primary interaction event.

## 7. References

- Lu, F., et al. (2020). Glanceable AR: Evaluating Information Access Methods for Head-Worn Augmented Reality. *IEEE VR '20*. [DOI: 10.1109/vr46266.2020.00113]
- Lu, F., et al. (2021). Exploration of Techniques for Rapid Activation of Glanceable Information in Head-Worn AR. *SUI '21*. [DOI: 10.1145/3485279.3485286]
- Gouveia, R., et al. (2016). Exploring the design space of glanceable feedback for physical activity trackers. *UbiComp '16*. [DOI: 10.1145/2971648.2971754]
- Ashbrook, D. (2010). Enabling Mobile Micro-interactions. *PhD Thesis, Georgia Tech*. [URL: https://smartech.gatech.edu/handle/1853/36311]
- Hubenschmid, S., et al. (2025). Hybrid User Interfaces. *arXiv:2509.05491*. [DOI: 10.48550/arXiv.2509.05491]
- Beyeler, M., Cheng, Y. F., & Holz, C. (2023). Cross-Device Shortcuts: Seamless Attention-guided Content Transfer via Opportunistic Deep Links between Apps and Devices. *ICMI '23*. [DOI: 10.1145/3577190.3614145]
- Dhaka, R., et al. (2024). Exploring Augmented Reality User Interface Transitions Across Mid-Air, On-Body and Physical Surfaces. *ISMAR '24*. [DOI: 10.1109/ismar62088.2024.00134]
- Ens, B., et al. (2015). Candid Interaction: Revealing Hidden Mobile and Wearable Computing Activities. *UIST '15*. [DOI: 10.1145/2807442.2807449]
