---
layout: dataset
title: Visual discrimination task with mouse-tracking and confidence judgements
modality:
  - behavior
keywords:
  - vision
  - mouse tracking
  - evidence accumulation
  - discrimination
  - 2AFC
  - metacognition
site:
  - Krakow
contact person: Nathan Faivre
summary: Observers used a computer mouse to respond to a two-alternative forced-choice visual discrimination task, followed by a confidence rating task. Kinematic analyses of mouse trajectories allow us to infer both decision times (i.e. when observers started to move the mouse to respond) and changes of mind (i.e. when patients modified their trajectory to respond). Decisions, decision times, changes of mind, and confidence ratings can be reproduced with a computational model of evidence accumulation, introduced by Faivre et al (2021) and extended by Goueytes et al (2025).
participants: 290
cc: Michal Wierzchoń, Renate Rutiku, Kristian Sandberg
---

{% include JB/setup %}

#### Detailed description

The task consisted of a random-dot kinematogram 2-AFC discrimination task followed by a confidence judgement. In the visual discrimination task, patients were asked to decide whether a cloud of dots circumscribed to a 108 px radius circle was moving rightward or leftward. Responses were given by moving a computer mouse from its initial position at the bottom centre of the screen to one of two targets presented in the top right and left corners of the screen (108 px radius), corresponding to right and left decisions. Participants were instructed to start moving only after reaching a decision, and were not given any particular instructions with regard to CoMs. Trials were self-initiated by clicking on a 90 × 19 px box situated at the bottom of the screen. This step was introduced to ensure that participants would bring back the mouse to a similar starting position at the beginning of every trial. They were instructed to inspect the stimulus for as long as necessary within a limit of 6 s. If they failed to answer within the 6 s timeframe, a buzzing sound was played and the trial was excluded from the analysis. No feedback was provided to the patients regarding accuracy after each trial. The second part of the task consisted in giving a confidence judgement on the accuracy of the decision, on a visual analogue scale ranging from 0 (sure of having provided an incorrect response) to 100 (sure of having provided a correct response). Participants were encouraged to use the continuous scale as accurately as possible. To minimise the confounding effect of visual-discrimination task difficulty on confidence judgements, motion coherence was titrated to reach 71% of correct responses for every participant using a 1-up/2-down adaptive staircase procedure preliminary to the experiment (80 trials without confidence judgements task). The staircase procedure was maintained throughout the main experiment to account for training or fatigue effects on task performance.
The model instantiates two anticorrelated accumulators, one for each possible decision outcome , and the confidence judgements were simulated by extending the evidence accumulation process after the initial decision. The free parameters were the rate at which sensory evidence is accumulated (drift rate), the boundary at which accumulated evidence leads to a decision (bound) and the proportion of response time that does not correspond to evidence accumulation (non-decision time).

#### Graphical overview

![Dotclouds motion discrimination with mouse tracking and diffusion model]({{ BASE_PATH }}/assets/images/datasets/s_08_1.png)

A Behavioural paradigm. Participants observed the random dot kinetogram and reported its motion direction using the mouse while it remained on screen. Confidence was rated on a continuous scale ranging from 0 to 100. B Schematic description of the race diffusion model used to fit data. A decision was defined when one of two accumulators coding for each possible motion direction crossed a threshold. Confidence was computed as a read-out of evidence accumulated up to 1 s after decision time (confidence read-out window, in blue).
#### Number of participants (raw)
Krakow: 290
#### Conditions and number of trials
Staircase calibration (80 trials), then main experiment in 5 blocks. Left/right motion direction 2AFC with mouse tracking, followed by confidence rating on each trial.
#### Behavioural Measures 
* Objective choice
* Accuracy
* Confidence (6-point scale)
* RT1 (objective choice)
* RT2 (confidence)
* Mouse movement tracking
#### Related publications

1. Faivre N, Roger M, Pereira M, de Gardelle V, Vergnaud JC, Passerieux C, Roux P. Confidence in visual motion discrimination is preserved in individuals with schizophrenia. J Psychiatry Neurosci. 2021 Jan 4;46(1):E65-E73. doi: 10.1503/jpn.200022. PMID: 33009905; PMCID: PMC7955841.

2. Goueytes, D., Stockart, F., Robin, A. et al. Evidence accumulation in the pre-supplementary motor area and insula drives confidence and changes of mind. Nat Commun 16, 6998 (2025). https://doi.org/10.1038/s41467-025-61744-8