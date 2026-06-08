---
layout: dataset
title: Flicker Fusion Task
modality:
  - behavior
keywords:
  - Vision
  - Discrimination
  - Threshold Perception
site:
  - Aarhus
contact:
cc:
  - Kristian Sandberg
cc_email:
  - kristian.sandberg@cfin.au.dk
summary: Perceptual discrimination task requiring detection of one versus two flashes presented in rapid succession. The task measures temporal resolution of perception by varying the inter-flash interval (IFI) between two stimulus presentations.
participants:
---

{% include JB/setup %}

#### Detailed description

Participants completed a two-flash discrimination task assessing temporal resolution of visual perception — specifically, the minimal temporal interval required to perceive consecutive stimuli as distinct. The task measured each participant's critical flicker fusion threshold, defined as the shortest inter-flash interval at which two flashes are perceived as separate rather than fused into a single event.

Stimuli consisted of two light grey circular disks (RGB [175,175,175]) presented in rapid succession on a darker grey background (RGB [127.5,127.5,127.5]). Each disk had a diameter of 0.75 degrees of visual angle. On each trial, the inter-flash interval (IFI) between the first and second flash was varied pseudorandomly using the method of constant stimuli. The IFI ranged from 1 frame (approximately 7 ms at a 144 Hz refresh rate) to 10 frames (70 ms) in steps of 1 frame, resulting in 10 distinct levels. In 50% of trials (two-flash condition), the IFI was blank, meaning the screen displayed only the background during the interval. In the other 50% of trials (single-flash condition), the grey disk remained continuously on screen during the IFI, effectively creating a single prolonged flash. This design allowed measurement of both temporal resolution (minimum detectable gap) and response bias.

Each trial proceeded as follows: blank screen (600 ms), fixation cross (400 ms), first flash (1 second), variable inter-flash interval (7–70 ms), second flash (1 second), followed by a response window. Participants were instructed to maintain fixation on the central cross and performed a two-alternative forced-choice (2-AFC) task, indicating via keypress whether they perceived one flash or two flashes.

#### Graphical overview

![Flicker Fusion Task — graphical overview]({{ BASE_PATH }}/assets/images/datasets/s_36_1.jpg)

#### Number of participants (raw)

TBA!

#### Conditions and number of trials

* Inter-flash interval (IFI): 10 levels (1 to 10 frames; 7 to 70 ms at 144 Hz)
* Trial types: 50% single-flash, 50% two-flash
* Practice trials: 10 trials
* Formal trials: 150 trials (1 block)

#### Behavioural Measures

* **Perceptual discrimination (2-AFC):** Participants indicated via keypress whether they perceived one flash or two flashes.
* **Critical flicker fusion threshold:** The shortest IFI at which participants reliably perceived two flashes (e.g., 75% two-flash reports threshold derived from psychometric function fitting).
* **Response bias:** Tendency to report two flashes versus one flash, assessed separately for two-flash and single-flash trials.

#### Related publications

Standard Flicker Fusion Paradigm.
