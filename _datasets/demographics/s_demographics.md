---
layout: dataset
title: Demographic and Screening Measures
modality:
  - questionnaires
keywords:
site:
  - Krakow
  - Aarhus
  - Brno
contact:
summary: Merged demographic questionnaires and screening measures across all three sites (Krakow, Aarhus, Brno). Organized by domain with common and site-specific measures clearly marked.
participants:
---

{% include JB/setup %}

#### Overview

Demographic and screening measures collected across the three project sites, organized by domain. Sections ordered from broadest site coverage to most site-specific.

**Convention:** ✓ = collected at both Brno cohorts. ✓\* = Brno 2023 only. Kra = Krakow, Aar = Aarhus.

---

## Core Demographics

| Measure                          | Scale / Unit | Kra | Aar | Brno | Notes                                     |
| -------------------------------- | ------------ | --- | --- | ---- | ----------------------------------------- |
| Age                              | years        | ✓   | ✓   | ✓    |                                           |
| Date of birth                    | date         | —   | ✓   | —    |                                           |
| Gender                           | categorical  | ✓   | ✓   | ✓    |                                           |
| Nationality                      | categorical  | —   | —   | ✓*   | Brno 2021 has `language` instead          |
| Student status                   | Yes / No     | ✓   | ✓   | ✓    |                                           |
| Current semester                 | number       | ✓   | ✓   | ✓*   | If student                                |
| Student level                    | categorical  | —   | —   | ✓*   |                                           |
| Study subject                    | free text    | —   | ✓   | —    | e.g., Psychology, Medicine                |
| Full-time / part-time / on leave | categorical  | ✓   | ✓   | ✓*   |                                           |
| Employment status                | categorical  | ✓   | ✓   | ✓*   | Aar: some students reported PT/unemployed |
| Relationship status              | categorical  | ✓   | ✓   | ✓*   |                                           |

## Self-Rated Health

| Measure | Scale / Unit | Kra | Aar | Brno | Notes |
|---------|-------------|-----|-----|------|-------|
| General health | 0–10 (0 = dead, 10 = best) | ✓ | ✓ | ✓* | |
| Vision (with correction) | 0–10 (0 = blind, 10 = best) | ✓ | ✓ | ✓* | |
| Hearing (with aids) | 0–10 (0 = deaf, 10 = best) | ✓ | ✓ | ✓* | |
| Tinnitus | Yes / No | ✓ | — | ✓* | |

## Handedness

| Measure | Scale / Unit | Kra | Aar | Brno | Notes |
|---------|-------------|-----|-----|------|-------|
| Edinburgh Handedness Inventory | categorical | — | ✓ | ✓ | General preferred-hand assessment |
| Extended 15-activity questionnaire | laterality index (30 vars) | ✓ | — | — | See details below |

**Krakow 15-activity handedness:** For each activity, participants report (1) preferred hand and (2) whether they sometimes use the other hand. Activities: writing, drawing, throwing, cutting with scissors, brushing teeth, using a knife (no fork), using a spoon, sweeping (upper hand), lighting a match, opening a box (lid hand), computer mouse, twisting a key, using a hammer, brush/comb, lifting a cup. Scoring yields laterality index classifying: consistent right/left-handers, mixed-handers, ambidextrous.

## Smoking

| Measure | Scale / Unit | Kra | Aar | Brno | Notes |
|---------|-------------|-----|-----|------|-------|
| Current smoker | Yes / No | ✓ | ✓ | ✓* | |
| Smoked in last 24 hours | Yes / No | ✓ | ✓ | ✓* | |
| Cigarettes in last 24 hours | count (0 if none) | ✓ | ✓ | ✓* | |
| Age of first cigarette | years (0 = never) | ✓ | ✓ | ✓* | |
| Days smoked in last month | days | ✓ | ✓ | ✓* | |
| Typical cigarettes/day on smoking days | count | ✓ | ✓ | ✓* | |

## Education & Socioeconomic

| Measure | Scale / Unit | Kra | Aar | Brno | Notes                             |
| ---------------------------------- | -------------- | --- | --- | ---- | --------------------------------- |
| Income | local currency | ✓ | ✓ | ✓* | Kra: PLN, Aar: DKK, Brno: CZK     |
| Parent/guardian 1 education | categorical | ✓ | — | — | Krakow asks per numbered guardian |
| Parent/guardian 2 education | categorical | ✓ | — | — |                                   |
| Years with other carers — parent 1 | years | ✓ | — | — |                                   |
| Years with other carers — parent 2 | years | ✓ | — | — |                                   |
| Biological parents education | categorical | — | — | ✓* |                                   |
| Adoptive parents education | categorical | — | — | ✓* |                                   |
| Other caregivers education | categorical | — | — | ✓* |                                   |

## Anthropometrics

| Measure | Scale / Unit | Kra | Aar | Brno | Notes |
|---------|-------------|-----|-----|------|-------|
| Height | cm | ✓ | ✓ | — | |
| Weight | kg | ✓ | ✓ | — | |

## Alcohol & Lifestyle

| Measure | Scale / Unit | Kra | Aar | Brno | Notes |
|---------|-------------|-----|-----|------|-------|
| Alcohol — units per week | units | ✓ | — | ✓* | 1 unit = 250 ml 12° beer = 100 ml wine = 25 ml spirits |
| Alcohol — frequency | categorical | ✓ | — | — | |
| Physical activity | hours/week | ✓ | — | ✓* | Moderate-to-vigorous |

## Medical Screening — Migraine

| Measure | Scale / Unit | Kra | Aar | Brno | Notes |
|---------|-------------|-----|-----|------|-------|
| Migraine diagnosis | Yes / No | ✓ | — | ✓ | Recurrent headaches 4–72 h, unilateral, throbbing, impairs activity, nausea / light-sound sensitivity |
| Migraine with aura (last 10 years) | Yes / No | — | — | ✓ | Unilateral visual changes, tingling, movement/speech disturbance |
| Migraine frequency | categorical | — | — | ✓ | |

Brno has at-home and on-site versions of all migraine items. Brno 2023 has both; Brno 2021 and Krakow have at-home only. Use at-home answers for cross-site comparison.

## Sleep & Cycle (Brno Only)

| Measure | Scale / Unit | Notes |
|---------|-------------|-------|
| Average sleep per day | hours | |
| Sleep today | hours | |
| Natural menstrual cycle status | Yes / No | Excludes hormonal contraceptives, menopause, diagnosed cyclic bleeding disorders |
| Current cycle day | day count | From first day of last period; only if known |

## Neurological Questionnaire — NQ (Brno Only)

Medical history screening for exclusion criteria and covariate control.

| Measure | Scale / Unit | Notes |
|---------|-------------|-------|
| Neurological condition (current/past) | Yes / No + specify | |
| Psychiatric condition (current/past) | Yes / No + specify | |
| Other chronic condition (current/past) | Yes / No + specify | |
| Surgery under general anesthesia | Yes / No + count | |
| Serious head injury with unconsciousness | Yes / No | |
| Learning disability diagnosis | Yes / No + specify | ✓* only; dyslexia, dysgraphia, dyscalculia |

## Drug Use Questionnaire — DUQ (Brno Only)

Comprehensive lifetime and recent substance use assessment.

**Structure:** For each substance, 6 items are assessed: ever used (Yes/No), lifetime usage (count), used in last 12 months (Yes/No), frequency in last 12 months (count), frequency unit (day/week/month/year), last time used (date).

| Substance | Examples |
|-----------|----------|
| Alcohol | |
| Caffeine | |
| Nicotine | |
| Cannabis | |
| Stimulants | Cocaine, amphetamines, methamphetamine |
| Opiates | Heroin, prescription opioids |
| Benzodiazepines | Valium, Xanax, sleeping pills |
| Hallucinogens / psychedelics | LSD, psilocybin, mescaline, DMT |

## Maltreatment and Abuse Chronology of Exposure — MACE (Brno Only)

Retrospective childhood adversity assessment. Each category scored as ever experienced (Yes/No).

| Category | Description |
|----------|-------------|
| 1. Parental physical maltreatment | Physical abuse by parents |
| 2. Parental verbal abuse | Verbal abuse by parents |
| 3. Parental non-verbal emotional abuse | Non-verbal emotional abuse by parents |
| 4. Emotional neglect | |
| 5. Physical neglect | |
| 6. Sexual abuse | |
| 7. Witnessing intimate partner violence | Domestic violence |
| 8. Witnessing sibling abuse | |
| 9. Peer verbal abuse | Bullying |
| 10. Peer physical abuse | |

**Composite scores:** Total sum (0–10), multiplicity score (number of categories endorsed), intrafamilial maltreatment score (excludes peer abuse).

Note: Highly sensitive data requiring appropriate confidentiality protections. Retrospective self-report subject to recall bias.

## Olfactory Testing (Aarhus Only)

Sniffin' Sticks test — objective olfactory function assessment.

| Measure | Scale / Unit | Notes |
|---------|-------------|-------|
| Olfactory identification | score | Ability to identify odors |
| Olfactory threshold | score | Sensitivity to detect odors |
| Olfactory discrimination | score | Ability to differentiate odors |
| Combined TDI score | score (sum of above) | > 30 normosmia, 16–30 hyposmia, < 16 anosmia |
