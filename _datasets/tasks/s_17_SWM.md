---
layout: dataset
title: Shape of visual field capacity
modality:
  - behavior
keywords:
  - Vision
  - Memory
  - Awareness
  - PAS
site:
  - Krakow
contact:
  - Simon del Pin
  - Renate Rutiku
email:
  - renate.rutiku@uj.edu.pl
cc:
  - Michał Wierzchoń
  - Kristian Sandberg
cc_email:
  - michal.wierzchon@uj.edu.pl
  - kristian.sandberg@cfin.au.dk
summary: Working memory task measuring variability of recognition capacity across the visual field. 8 objects are presented in a circular array, one location is retro-cued. Participants judge whether the centrally presented probe matches cued object. The eccentricity of each location is independently adjusted with QUEST staircase to equate individual performance.
participants: 292
---

{% include JB/setup %}

#### Detailed description

This task estimates the spatial profile of visual working memory capacity across eight locations in the visual field, building on the paradigm of Del Pin et al. (2020).

**Stimuli.** A set of 200 object images (approximately 60% man-made, 40% natural) was drawn from the Snodgrass & Vanderwart–like repository, selected for ease of naming in Polish. Each image was displayed inside a black-outlined square (3.3° × 3.3°) arranged in a circular array of eight positions at 0°, 45°, 90°, 135°, 180°, 225°, 270°, and 315° of polar angle.

**Trial structure.** Each trial begins with a fixation cross (1 s), followed by the eight-object array for 1 s. After a 100 ms blank (empty frames remain on screen), a red line cue points to one of the eight locations for 500 ms. Following a 1400 ms retention interval, a single probe object appears centrally and participants judge whether it is identical to the cued item (right arrow) or a different object (left arrow).

**Adaptive eccentricity.** Each of the 8 locations has its own independent QUEST staircase controlling the distance of that location from fixation. All locations start at 6.8° eccentricity, and the staircase targets approximately 63% correct (above a 50% guess rate). Correct responses push the stimulus further from fixation; incorrect responses bring it closer. Over 256 trials, this converges on the eccentricity at which each location reaches threshold performance — locations where a participant performs better end up farther from fixation.

**Training.** A short practice block precedes the main experiment, with objects displayed at fixed starting eccentricity and no staircase adjustment.

#### Graphical overview

![Visual field working memory retro-cue paradigm]({{ BASE_PATH }}/assets/images/datasets/s_17_1.png)

#### Number of participants (raw)

Krakow: 292

#### Conditions and number of trials

256 trials total (8 locations × 32 repetitions)

#### Behavioural Measures 
* Objective choice
* Accuracy (recognition)
* Per-location QUEST eccentricity estimates
* RT

#### Related publications

1. Papiernik-Kłodzińska, J., Del Pin, S. H., Wierzchoń, M., Carrasco, M., & Rutiku, R. (2025). Visual field inhomogeneities shape visual working memory. bioRxiv. doi: 10.1101/2025.05.13.653695
2. Del Pin, S. H., Skóra, Z., Sandberg, K., Overgaard, M., & Wierzchoń, M. (2020). Comparing theories of consciousness: Object position, not probe modality, reliably influences experience and accuracy in object recognition tasks. Consciousness and Cognition, 84, 102990.