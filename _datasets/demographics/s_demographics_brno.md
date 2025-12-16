---
layout: dataset
title: Demographic and Screening Measures - Brno
modality:
  - questionnaires
domain:
  - Demographics
paradigm:
  - demographic assessment
  - medical screening
  - substance use assessment
  - trauma assessment
site:
  - Brno
authors:
contact:
email:
ratings: false
summary: Demographic questionnaires and screening measures specific to the Brno site (2021 and 2023 cohorts). Includes comprehensive drug use questionnaire (DUQ), neurological questionnaire (NQ), maltreatment and abuse chronology (MACE), detailed health screening, and demographic variables.
participants:
citation:
doi:
---

{% include JB/setup %}

#### Overview

This document describes demographic and screening measures collected at the **Brno site** (including Brno_2021 and Brno_2023 cohorts). These measures provide essential background, medical screening, substance use history, and trauma assessment.

## Basic Demographics

### Core Variables

**Age and Identification**
- `age`: Age at time of sampling
- `ID`: Subject ID
- `dataset`: Specifies sampling site (Brno_2021 or Brno_2023)

**Gender**
- `gender`: Participant's gender

**Nationality** (Brno_2023)
- `nationality`: Participant nationality

**Student Status**
- `student`: Is the participant currently a student (Yes/No)
- `student_currently`: Current student status
- `student_semester`: Current semester if student
- `student_time`: Full-time, part-time, or on leave status

**Relationship Status**
- `marital_status`: Marital/relationship/civil status

### Education Background

**Parental Education** (Brno_2023)
- `education_bg_biological_parents`: Educational background of biological parents
- `education_bg_adoptive_parents`: Educational background of adoptive parents
- `education_bg_other_primary_care`: Educational background of other primary caregivers

## Physical Health and Measurements

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

**Tinnitus** (Brno_2023)
- `tinnitus`: Presence of tinnitus/buzzing in ears (Yes/No)

### Handedness

**Edinburgh Handedness Inventory** (Brno_2023)
- `hand_pref`: Preferred hand (general assessment)

### Sleep

**Sleep Duration**
- `average_sleep_dur`: How many hours a day do you sleep on average?
- `sleep_dur_last_night`: How many hours did you sleep today?

### Menstrual Cycle

**Cycle Status**
- `natural_menustral_cycle`: Do you have a natural menstrual cycle now?
  - Note: Natural cycle defined as any repeating cycle length
  - Excludes: diagnosed cyclic bleeding disorders, menopause, absence of menstruation, hormonal contraceptives

**Cycle Tracking**
- `day_of_menustral_cycle`: What day of your menstrual cycle are you on?
  - Calculated from first day of last period
  - Only applicable if participant knows this information

## Substance Use

### Smoking History

**Current Status** (Brno_2023)
- `smoker_currently`: Are you a smoker?
- `smoker_smoked_last_24_hours`: Have you smoked in last 24 hours?
- `smoker_cigarettes_smoked_last_24_hours`: How many cigarettes in last 24 hours

**Smoking History** (Brno_2023)
- `smoker_age_first_cigarette`: Age when smoked first cigarette (0 if never)
- `smoker_days_smoked_last_month`: Days smoked within last month
- `smoker_cigarettes_per_day_last_month`: Typical cigarettes per day when smoking

### Alcohol Consumption

**Weekly Consumption** (Brno_2023)
- `weekly_alcohol_consumption`: How many units of alcohol do you usually consume in a week?
  - 1 unit = 250ml of 12° beer
  - 1 unit = 100ml of wine
  - 1 unit = 25ml of spirits
  - Enter 0 if no alcohol consumption

### Physical Activity

**Exercise** (Brno_2023)
- `weekly_physical_activity`: Hours of moderate to vigorous physical activity per week

## Drug Use Questionnaire (DUQ)

**Sites:** Brno_2021, Brno_2023
**Purpose:** Comprehensive assessment of lifetime and recent substance use

### DUQ Structure

For **each substance category**, the DUQ assesses:
1. **Ever used** (yes/no)
2. **Lifetime usage** (how many times total)
3. **Used in last 12 months** (yes/no)
4. **Frequency in last 12 months** (how often)
5. **Frequency unit** (per day/week/month/year)
6. **Last time used** (date)

### Substance Categories Assessed

**1. Alcohol** (`duq_alcohol_*`)
- `duq_alcohol_ever_used`
- `duq_alcohol_lifetime_usage`
- `duq_alcohol_used_used_used_last__months`
- `duq_alcohol_how_often_in_used_used_used_last__months`
- `duq_alcohol_frequency_last__months_per`
- `duq_alcohol_last_time_used_date`

**2. Caffeine** (`duq_caffino_*`)
Note: Variable names use "CaffeiNo" spelling
- Same structure as alcohol

**3. Nicotine** (`duq_nicotinono_*`)
Note: Variable names use "NicotiNo" spelling
- Same structure as alcohol

**4. Cannabis** (`duq_cannabis_*`)
- Same structure as alcohol

**5. Stimulants** (`duq_stimulants_*`)
Examples: cocaine, amphetamines, methamphetamine
- Same structure as alcohol

**6. Opiates** (`duq_opiates_*`)
Examples: heroin, prescription opioids
- Same structure as alcohol

**7. Benzodiazepines** (`duq_benzodiazepinos_*`)
Note: Variable names use "BenzodiazepiNos" spelling
Examples: Valium, Xanax, sleeping pills
- Same structure as alcohol

**8. Hallucinogens/Psychedelics** (`duq_hallucinogens_psychedelics_*`)
Examples: LSD, psilocybin, mescaline, DMT
- Same structure as alcohol

### DUQ Applications

**Research Uses:**
- Control for substance use in brain imaging studies
- Examine relationships between substance use and cognition
- Screen participants for exclusion criteria
- Characterize substance use patterns in study sample

**Important Notes:**
- Self-report measure (subject to response bias)
- Covers broad range of legal and illegal substances
- Assesses both lifetime and recent use
- Provides quantitative frequency estimates

## Neurological Questionnaire (NQ)

**Sites:** Brno_2021, Brno_2023
**Purpose:** Medical history screening for neurological, psychiatric, and health conditions

### Medical Conditions

**Neurological Conditions**
- `ever_treated_neurological`: Are you being (or have you been) treated for any neurological condition?
- `ever_treated_neurological_specified`: If yes, please specify the condition

**Psychiatric Conditions**
- `ever_treated_psychiatric`: Are you being (or have you been) treated for any psychiatric condition?
- `ever_treated_psychiatric_specified`: If yes, please specify the condition

**Other Chronic Conditions**
- `ever_treated_other_chronic`: Are you being (or have you been) treated for other chronic condition?
- `ever_treated_other_chronic_specified`: If yes, please specify the condition

### Surgical and Injury History

**Surgery Under General Anesthesia**
- `ever_had_surgery_general_anesthesia`: Have you ever undergone surgery under general anaesthesia (with sedation)?
- `ever_had_surgery_general_anesthesia_times`: If yes, how many times?

**Head Injury**
- `ever_serious_head_injury_unconsciousness`: Have you had a serious head injury with unconsciousness in the past?

### Migraine Assessment

**Migraine Diagnosis**
- `suffer_from_migraines`: Do you suffer from migraines?
  - Description provided: "Migraine is a recurrent headache that manifests itself as attacks lasting 4-72 hours. Typically, these pains occur on only one side of the head. The pain is throbbing, mild or severe in intensity, impairs the ability to perform routine physical activity, and is associated with nausea or sensitivity to light and sound."
  - Alternate phrasing: Have you had a migraine attack in the last 10 years?

**Migraine with Aura**
- `ever_migraine_aura_last_10_years`: Have you had a migraine attack with aura in the last 10 years?
  - Description: "Migraine auras are recurrent attacks lasting several minutes. Typical of these attacks are unilateral changes in visual perception, a unilateral tingling sensation, and disturbances in movement or speech. These symptoms develop gradually, are usually followed by headache, and are associated with migraine symptoms."

**Migraine Frequency**
- `migraine_attack_frequency`: If you suffer from migraine, how frequent are the attacks?

### Learning Disabilities (Brno_2023)

**Diagnosis**
- `ever_diagnosed_learning_disability`: Have you been diagnosed with a learning disability?
  - Examples: dyslexia, dysgraphia, dyscalculia
- `ever_diagnosed_learning_disability_specific`: Which specific learning disability?

### NQ Applications

**Screening Functions:**
- Identify exclusion criteria for neuroimaging studies
- Control for medical conditions in analyses
- Assess comorbidities
- Document relevant medical history

**Important:**
- Self-report measure
- May require verification from medical records
- Used in conjunction with other screening procedures

## Maltreatment and Abuse Chronology of Exposure (MACE)

**Sites:** Brno_2021, Brno_2023
**Domain:** Emotion regulation / Trauma history
**Purpose:** Comprehensive assessment of childhood maltreatment and adverse experiences

### MACE Overview

The MACE is one of the most comprehensive retrospective assessments of childhood maltreatment, covering multiple types of adversity across childhood and adolescence.

### MACE Categories

**1. Parental Physical Maltreatment**
- `mace_pphysm_ever`: Ever experienced parental physical abuse

**2. Parental Verbal Abuse**
- `mace_pva_ever`: Ever experienced parental verbal abuse

**3. Parental/Non-Verbal Emotional Abuse**
- `mace_nvea_ever`: Ever experienced non-verbal emotional abuse from parents

**4. Emotional Neglect**
- `mace_en_ever`: Ever experienced emotional neglect

**5. Physical Neglect**
- `mace_pn_ever`: Ever experienced physical neglect

**6. Sexual Abuse**
- `mace_sexab_ever`: Ever experienced sexual abuse

**7. Witnessing Intimate Partner Violence**
- `mace_ipv_ever`: Ever witnessed intimate partner violence (domestic violence)

**8. Witnessing Sibling Abuse**
- `mace_wsiba_ever`: Ever witnessed sibling being abused

**9. Peer Verbal Abuse**
- `mace_peerva_ever`: Ever experienced peer verbal abuse (bullying)

**10. Peer Physical Abuse**
- `mace_peerphys_ever`: Ever experienced peer physical abuse

### MACE Composite Scores

**Summary Variables:**
- `mace_sum_ever`: Total sum of all maltreatment types experienced
  - Range: 0-10 (number of different types endorsed)

- `mace_mult_ever`: Multiplicity score
  - Number of different maltreatment categories experienced
  - Higher scores indicate exposure to multiple types

- `mace_intrafamalial`: Intrafamilial maltreatment score
  - Subset of maltreatment occurring within family context
  - Excludes peer abuse

### MACE Applications

**Research Uses:**
- Study effects of early life adversity on brain development
- Examine relationships between childhood trauma and mental health
- Investigate emotion regulation difficulties
- Control for adverse childhood experiences in analyses

**Clinical Relevance:**
- Early adversity linked to numerous outcomes:
  - Brain structure and function
  - Emotion regulation difficulties
  - Mental health disorders
  - Physical health problems
  - Stress response systems

**Ethical Considerations:**
- MACE data is highly sensitive
- Requires appropriate confidentiality protections
- Retrospective self-report (subject to recall bias)
- May trigger distress in participants
- Should be handled with care and respect

## Neuroimaging Variables

### FLICA Components (Brno_2023)

**Variable:** `licacomp_*`

FLICA components calculated by Mariana Pereira (also collected at Aarhus). See Aarhus demographics file for details.

## Data Quality Notes

**Data Completeness:**
- Brno sites have comprehensive substance use and medical screening data
- MACE data only available at Brno sites
- Some measures differ between Brno_2021 and Brno_2023 cohorts

## Related Measures

For psychometric questionnaires administered at Brno (e.g., ASI, CAPS, CHi-II, VDS, VS, STAI), see the main questionnaires documentation in `_datasets/questionnaires/` and `_datasets/questionnaires_new/`.

## Site-Specific Notes

**Brno Unique Features:**
- Comprehensive Drug Use Questionnaire (DUQ)
- Detailed Neurological Questionnaire (NQ)
- MACE trauma assessment
- Menstrual cycle tracking
- Detailed migraine assessment

**Contact:** For questions about Brno-specific data, contact the site PI or data manager.
