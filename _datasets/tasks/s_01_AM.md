---
layout: dataset
title: Associative memory task
modality:
  - behavior
keywords:
  - Vision
  - Memory
  - Multisite
site:
  - Aarhus
  - Krakow
  - Brno
contact:
  - Jovana Bjekic
email:
  - ""
cc:
  - Michał Wierzchoń
  - Kristian Sandberg
cc_email:
  - michal.wierzchon@uj.edu.pl
  - kristian.sandberg@cfin.au.dk
summary: Scene-item (landscape photographs and objects) paired associative memory task with confidence rating after recognition of old or new pairs. Additionally, there is a repeated encoding of the pairs, followed by recognition of single scenes and a cued recall.
participants:
---

{% include JB/setup %}

#### Detailed description

In the first block, participants are shown 48 picture pairs, consisting of a scene (desert, river, road, or golf court) and an item (common object, animal, or plant). The pairs are presented sequentially, each displayed for 2.5 seconds. Participants are instructed to try to memorize the scene-item pairs. They are then presented with 96 scene-item pairs (48 old pairs + 48 new pairs but consisting of known pictures) and have to indicate, via pressing certain keys, if they recognize the pair as old or if they believe it to be new. Following each response, participants have to rate their confidence on the previous decision on a scale from 1 to 6 (1: 50% = guessing, 2: 60%, 3: 70%, 4: 80%, 5: 90%, 6: 100%).

In the second block (happening immediately after the first one) participants are shown the old 48 scene-item pairs again and are instructed to try to memorize them. Then they are presented with 96 single scenes (48 old scenes + 48 new scenes) and have to indicate, via key press, if they recognize the particular scene or if they think it is a new scene. If a scene is recognized as old, an optional text field appears, allowing participants to recall and type the associated item.

#### Graphical overview

![Associative memory paradigm overview]({{ BASE_PATH }}/assets/images/datasets/s_01_1.png)

![Detailed associative memory paradigm with timeline]({{ BASE_PATH }}/assets/images/datasets/s_01_2.png)

#### Number of participants (raw)

Krakow: 295

#### Conditions and number of trials

Total of 192 rows per participant, including:
* Block 1 — encoding + recognition: 48 scene-item pairs encoded, then 96 recognition trials (48 old + 48 new pairs) and confidence ratings.
* Block 2 — re-encoding + scene recognition + cued recall: 48 pairs re-encoded, then 96 scene recognition trials (48 old + 48 new scenes) with optional cued recall of items.

#### Behavioural measures

* Objective choices:
* Recognition accuracy (old/new)
* Cued recall accuracy
* Confidence (6-point scale)
* RT1 + RT2 (obj. choices)
* RT3 (confidence)


#### Related publications

1. Bjekić, J., Vulić, K., Živanović, M., Vujičić, J., Ljubisavljević, M., & Filipović, S. R. (2019). The immediate and delayed effects of single tDCS session over posterior parietal cortex on face-word associative memory. Behavioural brain research, 366, 88-95.