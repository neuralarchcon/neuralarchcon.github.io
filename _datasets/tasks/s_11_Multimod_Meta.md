---
layout: dataset
title: "Multimodal metacognition: battery of tasks"
modality:
  - behavior
keywords:
  - metacognition
  - multimodal
  - 2AFC
  - detection
  - discrimination
  - vision
  - auditory
  - somatosensory
  - tactile
  - pain
site:
  - Krakow
contact:
  - Katarzyna Hat
  - Renate Rutiku
email:
  - hat.kasia@gmail.com
  - renate.rutiku@uj.edu.pl
cc:
  - Michał Wierzchoń
  - Kristian Sandberg
cc_email:
  - michal.wierzchon@uj.edu.pl
  - kristian.sandberg@cfin.au.dk
summary: "Battery of tasks spanning four sensory domains: vision, audition, non-painful touch, and pain. In each modality, participants perform detection or discrimination judgments at individually calibrated difficulty levels and rate their confidence. The battery is designed to assess domain-general and domain-specific aspects of metacognitive ability."
participants: 261
---

{% include JB/setup %}

#### Detailed description

This battery was used to measure metacognitive sensitivity across sensory modalities using a shared experimental framework. All four tasks follow the same trial logic: a perceptual decision followed by a confidence rating on a 6-point scale (50-100%). Difficulty is individually calibrated via staircase procedures to equate performance across modalities and participants, and no feedback on accuracy is provided.

**General trial structure.** On each trial, participants make a perceptual decision (detection or discrimination, depending on the block and modality) under time pressure. Then there is a confidence rating. Confidence is reported through a visual interface in which a circle varies in size and color; its initial state is randomized at the start of each rating phase to decorrelate the number of button presses from the final confidence level. Both the perceptual decision and the confidence rating are time-restricted.

1. **Visual and auditory tasks.** Participants perform two-alternative forced-choice (2AFC) discrimination tasks. In the visual blocks, they discriminate properties of visual stimuli (e.g., orientation or contrast); in the auditory blocks, they discriminate properties of auditory stimuli (e.g., pitch or frequency). Difficulty is adjusted via staircase procedures to maintain comparable performance across the two modalities.

2. **Tactile task (non-painful electric pulses).** Participants receive non-painful electrical stimulation through electrodes placed on the skin. The task includes both detection blocks (pulse present vs. absent) and discrimination blocks (comparing intensity or temporal properties of pulses). Stimulus intensity is individually calibrated via staircase.

3. **Pain task (painful electric pulses).** This task follows the same logic as the tactile task, but uses stimulation intensities in the painful range. It likewise includes detection and discrimination blocks with staircase-calibrated intensity.

#### Graphical overview

![Multimodal metacognition visual 2AFC paradigm]({{ BASE_PATH }}/assets/images/datasets/s_11_1.png)
![Multimodal metacognition auditory 2AFC paradigm]({{ BASE_PATH }}/assets/images/datasets/s_11_2.png)
![Multimodal metacognition tactile stimulation paradigm]({{ BASE_PATH }}/assets/images/datasets/s_11_3.png)

#### Number of participants (raw)

| Modality              | N (Krakow) |
| --------------------- | ---------- |
| Visual                | 212        |
| Auditory              | 212        |
| Tactile (non-painful) | 212        |
| Pain (painful)        | 213        |

#### Conditions and number of trials

All four tasks use staircase-calibrated difficulty and a 6-point confidence rating after each trial.

| Modality              | Design                     | Approx. rows per participant |
| --------------------- | -------------------------- | ---------------------------- |
| Visual                | 2AFC discrimination        | 226–240                      |
| Auditory              | 2AFC discrimination        | 226–240                      |
| Tactile (non-painful) | Detection + discrimination | 225–240                      |
| Pain (painful)        | Detection + discrimination | 177–190                      |

#### Behavioural measures
* Objective choice (perceptual decision)
* Accuracy
* RT1 (objective choice)
* RT2 (confidence rating)
* Confidence (6-point scale)

#### Related publications

1. Morales, J., Lau, H., & Fleming, S. M. (2018). Domain-general and domain-specific patterns of activity supporting metacognition in human prefrontal cortex. Journal of Neuroscience, 38(14), 3534-3546.
2. Vaccaro, A., Fleming, S.M. (2018) Thinking about thinking: A coordinate-based meta-analysis of neuroimaging studies of metacognitive judgments. Brain and Neuroscience Advances, 2, 1-14.
3.  Zylberberg, A., Bartfeld, P., & Sigman, M. (2012). The construction of confidence in perceptual decision. Frontiers in Integrative Neuroscience, 6, 79.