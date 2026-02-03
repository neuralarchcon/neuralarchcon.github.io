---
layout: dataset
title: High-Density EEG Resting State
modality:
  - neurobiomarkers
keywords:
  - EEG
  - States of consciousness
site:
  - Krakow
contact:
  - Michał Koculak
  - Michał Wierzchoń
participants: ~300
summary: High-density EEG recordings from various resting state conditions including standard paradigms (eyes open/closed) and naturalistic conditions (listening to music, watching videos). The database comprises over 1000 individual sessions (3-4 sessions per participant) collected on a BioSemi system with 64 active Ag/AgCl scalp electrodes.
---

{% include JB/setup %}

#### Detailed description:

**Paradigms**

The dataset consists of:
- **Standard resting-state paradigm**: Periods of opened or closed eyes with no external stimulation
- **Naturalistic conditions** simulating more out-of-laboratory environments (Koculak & Wierzchoń, 2022):
  - Listening to music
  - Watching footage from a CCTV camera
  - Video recorded during a walk through a city
  - Short fiction videos

After each resting session, an ARSQ2 questionnaire was filled by the participants (Diaz et al., 2014).

**Acquisition Parameters**

EEG data was recorded on a **BioSemi system** with:
- 64 active Ag/AgCl scalp electrodes
- Following the 10-10 placement system
- 2048 Hz sampling rate
- 412 Hz lowpass hardware filter

**Additional Recordings**

Peripheral electrodes recorded:
- Eye movements
- Signal from the mastoids
- Proxy ECG signal from the left forearm

**Electrode Localization**

For most of the recorded sessions, the digitalization of the actual positions of electrodes was acquired. This, in tandem with the structural image, significantly improves the precision of signal localization algorithms.

#### Preprocessing

The team has performed preprocessing on 1050 recordings including:
- Down-sampling
- Filtering
- Bad channel removal
- Re-referencing
- Artifact rejection and correction (ICA)
- Interpolation of channels

#### Data Organization

Data is organised in compliance with the BIDS standardized format (Pernet et al., 2019).

#### Potential Analyses

Multiple analyses supporting the MRI analyses interpretation could be proposed here, including:
- Time-frequency analysis
- Information theory measures
- Connectivity measures
- Power spectral analysis
- Event-related potentials
- Source localization

#### Related publications