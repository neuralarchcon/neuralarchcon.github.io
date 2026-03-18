---
layout: dataset
title: Eye tracking with two-tone images
modality:
  - behavior
keywords:
  - Vision
site:
  - Krakow
contact:
  - Marek A. Pedziwiatr
  - Christoph Teufel
email:
  - marek.pedziwiatr@uj.edu.pl
  - TeufelC@cardiff.ac.uk
cc:
  - Michał Wierzchoń
  - Renate Rutiku
cc_email:
  - michal.wierzchon@uj.edu.pl
  - renate.rutiku@uj.edu.pl
summary: Participants have viewed black-and-white two-tone images with their eye movements being recorded. The images were derived from photographs of natural scenes (“templates”). Each two-tone image appears as meaningless patches on initial viewing. Once the observer has acquired relevant prior object knowledge by viewing the corresponding template, however, processes of perceptual organization in the visual system bind the patches of the two-tone image into a coherent percept of an object.
participants: ~300
---

{% include JB/setup %}

#### Detailed description:

This task investigates how acquiring object knowledge changes the way observers sample visual information with their eyes, following the paradigm of Pedziwiatr, Von dem Hagen & Teufel (2023).

**Stimuli.** 30 pairs of images were used, each consisting of a two-tone image and its grayscale template. The depicted objects were predominantly animals (25 images), with the remainder showing humans (3) or both (2). Images subtended 21.9° × 14.6° of visual angle and were presented centrally against a mid-gray background. Eye movements were recorded using an EyeLink 1000+ eye-tracker at 500 Hz. The experiment comprised 10 blocks, each containing three image pairs and proceeding through four phases in fixed order.

**Before condition.** Three two-tone images are presented for 3 s each, preceded by a 1 s fixation dot. Observers look freely at the images without being told to search for objects. After each image, they rate how meaningful the two-tone appeared on a visual analog scale, followed by a 500 ms blank.

**Template condition.** The corresponding grayscale template images are displayed for 3 s each (also preceded by a fixation dot) while eye movements are recorded. This provides the observer with the object knowledge needed to disambiguate the two-tones.

**Blending phase.** Six cycles of dynamic blending between each two-tone and its template ensure that observers have acquired sufficient knowledge to perceive the object in the two-tone.
After condition. Identical to the Before condition, except the three two-tone images are presented in a newly randomized order. Any differences in eye-movement patterns and meaningfulness ratings between Before and After index the effect of knowledge-driven perceptual reorganization.

#### Graphical overview

![Eye tracking two-tone image disambiguation paradigm]({{ BASE_PATH }}/assets/images/datasets/s_23_1.png)

#### Number of participants (raw)

Krakow: ~300

#### Conditions and number of trials

10 blocks × 3 image pairs = 30 unique two-tone/template pairs. Each two-tone is viewed twice (Before and After disambiguation). Each template is viewed once. Meaningfulness ratings collected on every two-tone viewing.

#### Behavioural measures
* Eye movements (fixation positions, durations, saccades; 500 Hz)
* Meaningfulness ratings (VAS)

#### Related publications

1. Pedziwiatr, M. A., Von dem Hagen, E., & Teufel, C. (2023). Knowledge-driven perceptual organization reshapes information sampling via eye movements. Journal of Experimental Psychology: Human Perception and Performance, 49(3), 408. [https://doi.org/10.1037/xhp0001080](https://doi.org/10.1037/xhp0001080)