---
layout: dataset
title: Backward masked face emotion discrimination with awareness rating
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
summary: Threshold-level backward-masked face emotion discrimination task. Participants identify the emotional expression (2AFC - Emotional vs Neutral) of briefly presented face images from the NimStim database, followed by subjective visibility ratings using the Perceptual Awareness Scale (PAS). Stimulus contrast is individually calibrated via staircase to achieve 70% accuracy.
participants: 98
---

{% include JB/setup %}

#### Detailed description

* Stimuli were face images from the NimStim database (Tottenham et al., 2009). 16 Caucasian models (8 female, 8 male) were selected, with two pictures per model: one neutral and one fearful expression, yielding 32 images total. Fearful faces had open mouths; neutral faces had closed mouths.

* Photos were cropped in an oval shape (without hair) to keep location of significant face elements (eyes, nose, mouth) constant between photographs. Stimuli were converted to grayscale and normalized for luminance and contrast using the SHINE toolbox (lumMatch function; Willenbockel et al., 2010).

* Backward masks were created by manually cutting and relocating rectangular pieces from face images of 16 other models (not used as stimuli), all with neutral expressions. Mask visual features were equated with face images using SHINE.

* A uniform gray background was maintained. Each trial started with a central fixation cross (8 × 8 pixels). Between 2000 and 3000 ms from trial onset, a face image (4° × 5° visual angle) was presented centrally for 33 ms, with onset randomized within each trial. Stimulus contrast was individually adjusted via staircase procedure.

* Immediately after face offset, a backward mask (same size as face, opacity 0.4) was presented centrally for 66 ms. A gray background was presented for an additional 1200 ms after mask offset.

* Participants performed:
  1. **Emotion identification task** (2AFC): Indicate whether the face expression was "Emotional" or "Neutral" (button assignment counterbalanced across participants)
  2. **Subjective awareness rating**: Rate visibility using the Perceptual Awareness Scale (PAS; 1-4): 'no experience', 'a brief glimpse', 'an almost clear experience', 'a clear experience'

* Participants performed training (16 trials), staircase calibration (64 trials), and the main procedure (384 trials divided into 12 blocks of 32 trials). The entire session lasted approximately 2 hours.

* EEG was recorded using a 64-channel BioSemi ActiveTwo system at 2048 Hz sampling rate. Behavioral responses were collected via Cedrus Button Box (RB-840).

#### Behavioural Measures

* Emotion identification accuracy (2AFC)
* PAS ratings (1-4)
* Response times

#### Related publications

1. Zębrowski, A., Ciupińska, K., Orłowska, W., Łępa, L., Koculak, M., Wierzchoń, M., & Bola, M. (in preparation). Spontaneous changes in the pre-stimulus alpha power predict both objective and subjective aspects of perception - evidence from 5 paradigms and 471 experimental sessions.

2. Tottenham, N., Tanaka, J. W., Leon, A. C., McCarry, T., Nurse, M., Hare, T. A., ... & Nelson, C. (2009). The NimStim set of facial expressions: Judgments from untrained research participants. Psychiatry Research, 168(3), 242-249.
