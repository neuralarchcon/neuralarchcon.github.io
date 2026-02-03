---
layout: dataset
title: Backward masked scene perception with awareness rating
modality:
  - behavior
  - neurobiomarkers
keywords:
  - EEG
  - Vision
site:
  - Krakow
contact:
  - Michał Bola
summary: Threshold-level backward-masked scene perception task with two subtasks. Participants classify either the background (natural vs man-made) or the foreground object (animal vs furniture) of briefly presented scene images, followed by subjective visibility ratings using the Perceptual Awareness Scale (PAS). Scenes can be congruent or incongruent (e.g., animal in man-made setting). Display times vary (8, 16, 32 ms) without individual calibration.
participants: 96
---

{% include JB/setup %}

#### Detailed description

* Stimuli were 320 scene images originally developed by Rémy et al. (2013) and previously used by Furtak et al. (2022). Each image depicted either a natural (outdoor) or man-made (indoor) background, with a single foreground object (animal or furniture).

* Scene congruency was manipulated:
  - **Congruent scenes**: animal in natural background OR furniture in man-made background
  - **Incongruent scenes**: animal in man-made background OR furniture in natural background

* Stimuli were fully counterbalanced: each object appeared in both congruent and incongruent backgrounds, and each background appeared with both congruent and incongruent objects.

* All images were converted to grayscale with luminance (128.2 ALU) and contrast (55.4 ALU) equated using the SHINE toolbox (histMatch function). Ten backward masks were created from 280 gray rectangles (7 shades), equated to luminance 126.2 and contrast 49.1 ALU.

* A uniform gray background was maintained. Each trial started with a central fixation cross (8 × 8 pixels). Between 2000 and 3000 ms from trial onset, a scene image (13.8° × 9.2° visual angle) was presented centrally for 8, 16, or 32 ms (fixed display times, no individual staircase), with onset randomized.

* Immediately after scene offset, a backward mask was presented for 66 ms, followed by a blank screen for 1200 ms.

* The experiment consisted of two tasks in separate blocks (order counterbalanced across participants):
  1. **Background classification task** (2AFC): Classify whether the scene background was natural or man-made
  2. **Object classification task** (2AFC): Classify whether the foreground object was natural (animal) or man-made (furniture)

* After each classification, participants provided:
  - **Subjective awareness rating**: Rate visibility of the task-relevant scene element (object or background) using the Perceptual Awareness Scale (PAS; 1-4): 'no experience', 'a brief glimpse', 'an almost clear experience', 'a clear experience'

* Design: 2 (task: background, object) × 2 (congruency: congruent, incongruent) × 3 (display time: 8, 16, 32 ms), with 300 trials per task (100 per display time), 600 trials total.

* Participants performed training (16 trials at 100 ms display) and the main procedure (600 trials divided into 10 blocks of 30 trials). The entire session lasted approximately 2 hours.

* EEG was recorded using a 64-channel BioSemi ActiveTwo system at 2048 Hz sampling rate. Behavioral responses were collected via Cedrus Button Box (RB-840).

#### Behavioural Measures

* Background classification accuracy (2AFC)
* Object classification accuracy (2AFC)
* PAS ratings (1-4)
* Response times
* Congruency effects

#### Related publications

1. Zębrowski, A., Ciupińska, K., Orłowska, W., Łępa, L., Koculak, M., Wierzchoń, M., & Bola, M. (in preparation). Spontaneous changes in the pre-stimulus alpha power predict both objective and subjective aspects of perception - evidence from 5 paradigms and 471 experimental sessions.

2. Furtak, M., Mudrik, L., & Bola, M. (2022). The forest, the trees, or both? Hierarchy and interactions between gist and object processing during perception of real-world scenes. Cognition, 221, 104983.

3. Rémy, F., Saint-Aubert, L., Bacon-Macé, N., Vayssière, N., Barbeau, E., & Fabre-Thorpe, M. (2013). Object recognition in congruent and incongruent natural scenes: A life-span study. Vision Research, 91, 36-44.
