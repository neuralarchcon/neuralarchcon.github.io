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
- `age`: Age at time of sampling
- `ID`: Subject ID
- `dataset`: Specifies sampling site (Krakow)

**Gender**
- `gender`: Participant's gender

**Student Status**
- `student`: Is the participant currently a student (Yes/No)
- `student_semester`: Current semester if student
- `student_time`: Full-time, part-time, or on leave status

**Employment**
- `job`: Employment/occupation status

**Relationship Status**
- `marital_status`: Marital/relationship/civil status

### Education and Socioeconomic Status

**Participant Education**
- Self-reported education level and years

**Parental/Guardian Education**
Detailed assessment of parental/caregiver educational background:
- `education_bg_parent_guardian_1`: Education level of parent/guardian 1
- `education_bg_parent_guardian_2`: Education level of parent/guardian 2
- `eduaction_bg_number_years_other_career_parent_guardian_1`: Number of years with other carers - parent/guardian 1
- `eduaction_bg_number_years_other_career_parent_guardian_2`: Number of years with other carers - parent/guardian 2

**Income**
- `income_PLN`: Income in Polish złoty (PLN)

## Physical Health and Measurements

### Anthropometric Measurements

**Body Measurements**
- `height_cm`: Height in centimeters
- `weight`: Weight in kilograms

### Self-Rated Health

**General Health**
- `health_self_rated`: Self-rated health on 0-10 scale
  - 0 = dead
  - 10 = best possible health

**Sensory Health**
- `health_vision_self_rated`: Vision with glasses/contacts
  - 0 = worst possible/blind
  - 10 = best possible vision
- `health_hearing_self_rated`: Hearing with aids if used
  - 0 = worst possible/deaf
  - 10 = best possible hearing

**Tinnitus**
- `tinnitus`: Presence of tinnitus/buzzing in ears (Yes/No)

## Detailed Handedness Assessment

**Krakow Unique Feature:** Extended handedness questionnaire assessing 15 different activities

### Structure

For each activity, participants indicate:
1. **Primary hand preference**: Which hand they prefer for the activity
2. **Secondary hand use**: Do they sometimes use the other hand?

### Activities Assessed

**1. Writing**
- `hand_pref_writing`: I prefer [hand] for writing
- `hand_pref_use_second_hand_writing`: Do you sometimes use second hand?

**2. Drawing**
- `hand_pref_drawing`: I prefer [hand] for drawing
- `hand_pref_use_second_hand_drawing`: Do you sometimes use second hand?

**3. Throwing**
- `hand_pref_throwing`: I prefer [hand] for throwing
- `hand_pref_use_second_hand_throwing`: Do you sometimes use second hand?

**4. Cutting with Scissors**
- `hand_pref_cutting_with_scissors`: I prefer [hand] for cutting with scissors
- `hand_pref_use_second_hand_cutting_with_scissors`: Do you sometimes use second hand?

**5. Brushing Teeth**
- `hand_pref_brushing_teeth`: I prefer [hand] for brushing teeth
- `hand_pref_use_second_hand_brushing_teeth`: Do you sometimes use second hand?

**6. Using a Knife (without a fork)**
- `hand_pref_using_a_knife_without_a_fork`: I prefer [hand] for using a knife
- `hand_pref_use_second_hand_using_a_knife_without_a_fork`: Do you sometimes use second hand?

**7. Using a Spoon**
- `hand_pref_using_a_spoon`: I prefer [hand] for using a spoon
- `hand_pref_use_second_hand_using_a_spoon`: Do you sometimes use second hand?

**8. Sweeping (upper hand on broom handle)**
- `hand_pref_sweeping_upper_hand_on_the_broom_handle`: I prefer [hand] for sweeping
- `hand_pref_use_second_hand_sweeping_upper_hand_on_the_broom_handle`: Do you sometimes use second hand?

**9. Lighting a Match**
- `hand_pref_lighting_a_match`: I prefer [hand] for lighting a match
- `hand_pref_use_second_hand_lighting_matches`: Do you sometimes use second hand?

**10. Opening a Box (holding the lid)**
- `hand_pref_opening_the_box_holding_the_lid`: I prefer [hand] for opening box
- `hand_pref_use_second_hand_opening_the_box_holding_the_lid`: Do you sometimes use second hand?

**11. Using a Computer Mouse**
- `hand_pref_using_a_computer_mouse`: I prefer [hand] for using mouse
- `hand_pref_use_second_hand_using_a_computer_mouse`: Do you sometimes use second hand?

**12. Twisting a Key in the Lock**
- `hand_pref_twisting_the_key_in_the_house`: I prefer [hand] for twisting key
  - Note: Variable name says "house" but refers to lock/castle
- `hand_pref_use_second_hand_twisting_the_key_in_the_house`: Do you sometimes use second hand?

**13. Using a Hammer**
- `hand_pref_using_a_hammer`: I prefer [hand] for using a hammer
- `hand_pref_use_second_hand_using_a_hammer`: Do you sometimes use second hand?

**14. Using a Brush or Comb**
- `hand_pref_using_a_brush_or_comb`: I prefer [hand] for using brush/comb
- `hand_pref_use_second_hand_using_a_brush_or_comb`: Do you sometimes use second hand?

**15. Lifting a Cup with a Drink**
- `hand_pref_lifting_a_cup_with_a_drink`: I prefer [hand] for lifting cup
- `hand_pref_use_second_hand_lifting_a_cup_with_a_drink`: Do you sometimes use second hand?

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
- `smoker_currently`: Are you a smoker?
- `smoker_smoked_last_24_hours`: Have you smoked in last 24 hours?
- `smoker_cigarettes_smoked_last_24_hours`: How many cigarettes in last 24 hours (0 if none)

**Smoking History**
- `smoker_age_first_cigarette`: Age when smoked first cigarette (0 if never smoked)
- `smoker_days_smoked_last_month`: How many days within last month have you smoked
- `smoker_cigarettes_per_day_last_month`: Typical cigarettes per day on days smoked in last month

### Alcohol Consumption

**Weekly Consumption**
- `weekly_alcohol_consumption`: How many units of alcohol do you usually consume in a week?
  - 1 unit = 250ml of 12° beer
  - 1 unit = 100ml of wine
  - 1 unit = 25ml of spirits
  - Enter 0 if no alcohol consumption

**Frequency**
- `weekly_alcohol_frequency`: How often do you drink alcohol?

### Physical Activity

**Exercise**
- `weekly_physical_activity`: Hours of moderate to vigorous physical activity per week

## Medical Screening

### Migraine Assessment

**Migraine Diagnosis**
- `suffer_from_migraines`: Do you suffer from migraines?
  - Same definition as Brno: recurrent headaches lasting 4-72 hours, typically unilateral, throbbing pain, impairs routine activities, associated with nausea or light/sound sensitivity

**Note:** Krakow does not collect the detailed migraine aura questions that Brno administers.

## Neuroimaging Variables

### Scanner Information

- `scanner_id`: ID used for MRI scanner
- Used to track and control for scanner-specific effects

## Data Quality Notes

**Data Completeness:**
- Krakow has comprehensive demographic data
- Unique detailed handedness assessment
- Parental education tracking
- Income data (site-specific)

## Related Measures

For psychometric questionnaires administered at Krakow (e.g., NEO-PI, VVIQ-2, MAIA-2, FPQ-3, GAD-7, SPQ-BR, PI-WSUR, ASQ-short, etc.), see the main questionnaires documentation in `_datasets/questionnaires/` and `_datasets/questionnaires_new/`.

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
