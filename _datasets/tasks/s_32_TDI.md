---
layout: dataset
title: Sniffin' Sticks olfactory test
modality:
  - behavior
keywords:
  - Somatosensory
  - Detection
  - Threshold Perception
  - Discrimination
site:
  - Aarhus
contact:
  - Per Quist
email:
  - per.q@biomed.au.dk
cc:
  - Kristian Sandberg
cc_email:
  - kristian.sandberg@cfin.au.dk
summary: Assessment of orthonasal olfactory function using the Sniffin' Sticks battery, a clinically validated set of pen-like odor-dispensing devices. The full test comprises three subtests — threshold, discrimination and identification — whose scores combine into a composite TDI score.
participants: 208
---

{% include JB/setup %}

#### Detailed description

The Sniffin' Sticks battery (Burghart Messtechnik, Germany) measures the sense of smell using pen-like devices, each filled with an odorant and presented to the participant under the cap. Testing is conducted in a well-ventilated room free of competing odors and distraction, with the components administered in a fixed order: threshold first, then discrimination, then identification. The three subtests yield a composite score, the TDI, which is the sum of the threshold (T), discrimination (D) and identification (I) sub-scores. Each sub-score ranges up to 16 points, so the maximum composite is 48; a TDI below the normative cut-off indicates olfactory dysfunction.

**Threshold (T).** Olfactory sensitivity is measured with the odorant n-butanol, prepared in sixteen successive dilution steps (each half the concentration of the previous). On each trial the participant is presented with a triplet of pens, one containing the diluted odorant and two odorless blanks, and must indicate which pen smells (a three-alternative forced-choice procedure). A single-staircase method is used: two consecutive correct identifications at a given concentration reverse the staircase downward to a weaker dilution, while a single error reverses it upward to a stronger one. The procedure continues until a set number of reversals (turning points) is reached, and the threshold score is taken as the mean of the last turning points. Higher scores indicate the ability to detect weaker concentrations.

**Discrimination (D).** The ability to tell odors apart is assessed with sixteen triplets of pens. In each triplet two pens contain the same odorant and one differs; the participant, again under forced choice, indicates the pen that smells different. The score is the number of triplets answered correctly, from 0 to 16.

**Identification (I).** The ability to name odors is assessed with sixteen common odorants presented one at a time. For each, the participant selects the matching label from a list of four descriptors (multiple forced-choice). The score is the number of odors correctly identified, from 0 to 16.

#### Graphical overview

![Sniffin' Sticks olfactory test (TDI) — graphical overview]({{ BASE_PATH }}/assets/images/datasets/s_32_1.png)

#### Number of participants (raw)

The dataset file holds one row per participant, keyed by SONA ID. Total participants: 208.

#### Conditions and number of trials

* Threshold: repeated three-alternative forced-choice triplets under a single-staircase procedure across sixteen n-butanol dilution steps; threshold derived from the mean of the final turning points (recorded as four reversal values plus the derived score).
* Discrimination: sixteen forced-choice triplet trials; one point per correct trial (recorded as the total and as sixteen item-level correct/incorrect indicators).
* Identification: standard procedure uses sixteen multiple-forced-choice trials.

#### Behavioural Measures

* Threshold score (mean of final staircase turning points)
* Four threshold reversal values
* Total discrimination score (0 to 16)
* Total identification score (0 to 16)
* Sixteen item-level discrimination outcomes (correct / incorrect)
* Sixteen item-level identification outcomes (correct / incorrect)

#### Related publications

1. Hummel, T., Sekinger, B., Wolf, S. R., Pauli, E., & Kobal, G. (1997). "Sniffin' Sticks": olfactory performance assessed by the combined testing of odour identification, odor discrimination and olfactory threshold. Chemical Senses, 22(1), 39–52.
2. Oleszkiewicz, A., Schriever, V. A., Croy, I., Hähner, A., & Hummel, T. (2019). Updated Sniffin' Sticks normative data based on an extended sample of 9139 subjects. European Archives of Oto-Rhino-Laryngology, 276(3), 719–728.
3. Fjaeldstad, A. W., Tchemerinsky Konieczny, D., Fernandes, H., Gaini, L. M., Vejlø, M., & Sandberg, K. (2022). The relationship between individual significance of olfaction and measured olfactory function. Current Research in Behavioral Sciences, 3, 100076.
