---
layout: dataset
title: Demographic and Screening Measures - Krakow
modality:
  - questionnaires
keywords:
  - Demographics
site:
  - Krakow
contact:
summary: Demographic questionnaires and screening measures specific to the Krakow site. Includes standard demographics, detailed handedness assessment (15 activities), parental education, anthropometric measurements, smoking history, alcohol consumption, and migraine screening.
participants:
---

{% include JB/setup %}

#### Overview

This document describes demographic and screening measures collected at the **Krakow site**. These measures provide essential background information and include a uniquely detailed handedness assessment.

## Basic Demographics

### Core Variables

**Age and Identification**
- Age at time of sampling
- Subject ID
- Specifies sampling site (Krakow)

**Gender**
- Participant's gender

**Student Status**
- Is the participant currently a student (Yes/No)
- Current semester if student
- Full-time, part-time, or on leave status

**Employment**
- Employment/occupation status

**Relationship Status**
- Marital/relationship/civil status

### Education and Socioeconomic Status

**Participant Education**
- Self-reported education level and years

**Parental/Guardian Education**
Detailed assessment of parental/caregiver educational background:
- Education level of parent/guardian 1
- Education level of parent/guardian 2
- Number of years with other carers - parent/guardian 1
- Number of years with other carers - parent/guardian 2

**Income**
- Income in Polish złoty (PLN)

## Physical Health and Measurements

### Anthropometric Measurements

**Body Measurements**
- Height in centimeters
- Weight in kilograms

### Self-Rated Health

**General Health**
- Self-rated health on 0-10 scale
  - 0 = dead
  - 10 = best possible health

**Sensory Health**
- Vision with glasses/contacts
  - 0 = worst possible/blind
  - 10 = best possible vision
- Hearing with aids if used
  - 0 = worst possible/deaf
  - 10 = best possible hearing

**Tinnitus**
- Presence of tinnitus/buzzing in ears (Yes/No)

## Detailed Handedness Assessment

**Krakow Unique Feature:** Extended handedness questionnaire assessing 15 different activities

### Structure

For each activity, participants indicate:
1. **Primary hand preference**: Which hand they prefer for the activity
2. **Secondary hand use**: Do they sometimes use the other hand?

### Activities Assessed

**1. Writing**
- I prefer [hand] for writing
- Do you sometimes use second hand?

**2. Drawing**
- I prefer [hand] for drawing
- Do you sometimes use second hand?

**3. Throwing**
- I prefer [hand] for throwing
- Do you sometimes use second hand?

**4. Cutting with Scissors**
- I prefer [hand] for cutting with scissors
- Do you sometimes use second hand?

**5. Brushing Teeth**
- I prefer [hand] for brushing teeth
- Do you sometimes use second hand?

**6. Using a Knife (without a fork)**
- I prefer [hand] for using a knife
- Do you sometimes use second hand?

**7. Using a Spoon**
- I prefer [hand] for using a spoon
- Do you sometimes use second hand?

**8. Sweeping (upper hand on broom handle)**
- I prefer [hand] for sweeping
- Do you sometimes use second hand?

**9. Lighting a Match**
- I prefer [hand] for lighting a match
- Do you sometimes use second hand?

**10. Opening a Box (holding the lid)**
- I prefer [hand] for opening box
- Do you sometimes use second hand?

**11. Using a Computer Mouse**
- I prefer [hand] for using mouse
- Do you sometimes use second hand?

**12. Twisting a Key in the Lock**
- I prefer [hand] for twisting key
- Do you sometimes use second hand?

**13. Using a Hammer**
- I prefer [hand] for using a hammer
- Do you sometimes use second hand?

**14. Using a Brush or Comb**
- I prefer [hand] for using brush/comb
- Do you sometimes use second hand?

**15. Lifting a Cup with a Drink**
- I prefer [hand] for lifting cup
- Do you sometimes use second hand?

### Handedness Scoring

**Laterality Index Calculation:**
Can be computed using various formulas, e.g.:
- Number of right-hand activities / total activities
- Weighted score accounting for "always" vs. "sometimes" responses

**Classification:**
- Consistent right-handers: Right hand for all/most activities
- Consistent left-handers: Left hand for all/most activities
- Mixed-handers: Variable hand preference across activities
- Ambidextrous: Frequent use of both hands

**Research Applications:**
- More fine-grained assessment than single-item handedness
- Can identify degree of lateralization
- Useful for brain lateralization studies
- Detects inconsistent handedness patterns

## Substance Use

### Smoking History

**Current Status**
- Are you a smoker?
- Have you smoked in last 24 hours?
- How many cigarettes in last 24 hours (0 if none)

**Smoking History**
- Age when smoked first cigarette (0 if never smoked)
- How many days within last month have you smoked
- Typical cigarettes per day on days smoked in last month

### Alcohol Consumption

**Weekly Consumption**
- How many units of alcohol do you usually consume in a week?
  - 1 unit = 250ml of 12° beer
  - 1 unit = 100ml of wine
  - 1 unit = 25ml of spirits
  - Enter 0 if no alcohol consumption

**Frequency**
- How often do you drink alcohol?

### Physical Activity

**Exercise**
- Hours of moderate to vigorous physical activity per week

## Medical Screening

### Migraine Assessment

**Migraine Diagnosis**
- Do you suffer from migraines?
  - Same definition as Brno: recurrent headaches lasting 4-72 hours, typically unilateral, throbbing pain, impairs routine activities, associated with nausea or light/sound sensitivity

**Note:** Krakow does not collect the detailed migraine aura questions that Brno administers.

## Neuroimaging Variables

### Scanner Information

- ID used for MRI scanner
- Used to track and control for scanner-specific effects

## Data Quality Notes

**Data Completeness:**
- Krakow has comprehensive demographic data
- Unique detailed handedness assessment
- Parental education tracking
- Income data (site-specific)

## Related Measures

For psychometric questionnaires administered at Krakow (e.g., NEO-PI, VVIQ-2, MAIA-2, FPQ-3, GAD-7, SPQ-BR, PI-WSUR, ASQ-short, etc.), see the main questionnaires documentation in _datasets/questionnaires/ and _datasets/questionnaires_new/.

## Site-Specific Notes

**Krakow Unique Features:**
- Most detailed handedness assessment (15 activities × 2 questions each = 30 variables)
- Parental/guardian education with alternative care tracking
- Income in PLN
- Comprehensive lifestyle factors (smoking, alcohol, physical activity)

**Contact:** For questions about Krakow-specific data, contact the site PI or data manager.

## Comparison with Other Sites

| Feature | Aarhus | Brno | Krakow |
|---------|--------|------|--------|
| Handedness detail | Basic (1 item) | Basic (1 item) | Extensive (15 activities) |
| Substance use | Smoking only | Comprehensive DUQ | Smoking + alcohol |
| Medical screening | Basic | Extensive NQ | Migraine only |
| Trauma assessment | No | MACE | No |
| Olfactory testing | Yes (Sniffin' Sticks) | No | No |
| Parental education | No | Yes (2023) | Yes (detailed) |
| Income | No | No | Yes (PLN) |
