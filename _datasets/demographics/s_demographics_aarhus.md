---
layout: dataset
title: Demographic and Screening Measures - Aarhus
modality:
  - questionnaires
domain:
  - Demographics
paradigm:
  - demographic assessment
  - olfactory assessment
site:
  - Aarhus
authors:
contact:
email:
ratings: false
summary: Demographic questionnaires and screening measures specific to the Aarhus site. Includes standard demographics, anthropometric measurements, smoking history, handedness, olfactory perception testing, and neuroimaging-derived variables (FLICA components).
participants:
citation:
doi:
---

{% include JB/setup %}

#### Overview

This document describes demographic and screening measures collected at the **Aarhus site**. These measures provide essential background information and control variables for analyses.

## Basic Demographics

### Core Variables

**Age and Identification**
- `age`: Age at time of sampling
- `DoB`: Date of Birth
- `ID`: Subject ID (previously `sona_id`)
- `dataset`: Specifies sampling site (Aarhus)

**Gender**
- `gender`: Participant's gender

**Student Status**
- `student`: Is the participant currently a student (Yes/No)
- `student_semester`: Current semester if student
- `student_subject`: Study subject if student (e.g., Psychology, Medicine)
- `student_time`: Full-time, part-time, or on leave status

**Employment**
- `job`: Employment/occupation status
- Note: Some students may have filled part-time or unemployed, so totals may not match

**Relationship Status**
- `marital_status`: Marital/relationship/civil status

## Physical Health and Measurements

### Anthropometric Measurements

**Body Measurements**
- `bmi`: Body Mass Index
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

### Handedness

**Edinburgh Handedness Inventory**
- `hand_pref`: Preferred hand (general assessment)

## Substance Use

### Smoking History

**Current Status**
- `smoker_currently`: Are you a smoker? (Yes/No)
- `smoker_smoked_last_24_hours`: Have you smoked in last 24 hours?
- `smoker_cigarettes_smoked_last_24_hours`: How many cigarettes in last 24 hours (0 if none)

**Smoking History**
- `smoker_age_first_cigarette`: Age when smoked first cigarette (0 if never smoked)
- `smoker_days_smoked_last_month`: How many days within last month have you smoked
- `smoker_cigarettes_per_day_last_month`: Typical cigarettes per day on days smoked in last month

## Olfactory Perception

**Sniffin' Sticks Test** (from Daniel Tchermerinski's study)

Objective olfactory function assessment using standardized testing:

**Component Scores:**
- `Identification`: Olfactory identification score (ability to identify odors)
- `Threshold`: Olfactory threshold (sensitivity to detect odors)
- `Discrimination`: Olfactory discrimination (ability to differentiate odors)

**Composite Score:**
- `TDI`: Combined Threshold-Discrimination-Identification score
  - Total olfactory function index
  - Sum of all three component scores

**Clinical Interpretation:**
- TDI > 30: Normosmia (normal smell function)
- TDI 16-30: Hyposmia (reduced smell function)
- TDI < 16: Anosmia (absence of smell function)

## Site-Specific Notes

**Aarhus Unique Features:**
- Olfactory testing (Sniffin' Sticks)
- FLICA neuroimaging components
- Social Brain study variables
- Detailed employment status tracking

**Contact:** For questions about Aarhus-specific data, contact the site PI or data manager.
