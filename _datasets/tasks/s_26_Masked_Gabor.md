---
layout: dataset
title: Backward masked Gabor orientation discrimination with awareness rating
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
summary: Threshold-level backward-masked Gabor patch orientation discrimination task. Participants identify the orientation (4AFC) of centrally presented Gabor patches followed by a Gaussian noise mask, then rate subjective visibility using the Perceptual Awareness Scale (PAS). Stimulus contrast is individually calibrated via staircase to achieve 70% accuracy.
participants: 160
---

{% include JB/setup %}

#### Detailed description

* Target stimuli were Gabor patches with a size of 128 × 128 pixels (3.3° × 3.3° visual angle), spatial frequency of 1.5 cycles/degree, and phase of 1. The contrast was individually determined for each participant through a "1 up, 2 down" staircase procedure, aimed at achieving 70% accuracy.

* A uniform gray background was maintained during the procedure. Each trial started with a central presentation of a white fixation cross (8 × 8 pixels). Between 2000 and 3000 ms from trial onset, a target Gabor patch was presented centrally for 33 ms, with onset chosen randomly within each trial.

* In each trial, the Gabor patch was presented in one of four possible orientations: horizontal (90°), vertical (0°), tilted right (45°), or tilted left (-45° rotation from vertical angle).

* Immediately after the Gabor offset, a backward mask was presented centrally for 66 ms. The mask (256 × 256 pixels) was generated from Gaussian noise in each trial by PsychoPy. A gray background was presented for an additional 1200 ms after mask offset.

* Participants performed:
  1. **Orientation identification task** (4AFC): Indicate the orientation of the presented Gabor patch
  2. **Subjective awareness rating**: Rate visibility using the Perceptual Awareness Scale (PAS; 1-4): 'no experience', 'a brief glimpse', 'an almost clear experience', 'a clear experience'

* Participants performed training (16 trials), staircase calibration (70 trials), and the main procedure (400 trials divided into 25 blocks of 16 trials). The entire session lasted approximately 2 hours.

* EEG was recorded using a 64-channel BioSemi ActiveTwo system at 2048 Hz sampling rate. Behavioral responses were collected via Cedrus Button Box (RB-840).

#### Behavioural Measures

* Orientation identification accuracy (4AFC)
* PAS ratings (1-4)
* Response times

#### Related publications

1. Zębrowski, A., Ciupińska, K., Orłowska, W., Łępa, L., Koculak, M., Wierzchoń, M., & Bola, M. (in preparation). Spontaneous changes in the pre-stimulus alpha power predict both objective and subjective aspects of perception - evidence from 5 paradigms and 471 experimental sessions.
