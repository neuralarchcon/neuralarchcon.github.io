---
layout: dataset
title: PI-WSUR – Padua Inventory-Washington State University Revision
modality:
  - questionnaires
domain:
  - Mental health
  - Other
paradigm:
  - OCD
site:
  - Krakow
authors:
contact:
email:
ratings: false
summary: A 39-item self-report questionnaire measuring obsessive-compulsive symptoms across five dimensions administered at Krakow. Uses a 5-point distress rating scale. The PI-WSUR provides improved distinction between obsessions, compulsions, and worry compared to the original Padua Inventory.
participants:
citation: Burns, G. L., Keortge, S. G., Formea, G. M., & Sternberger, L. G. (1996). Revision of the Padua Inventory of obsessive compulsive disorder symptoms - Distinctions between worry, obsessions, and compulsions. Behaviour Research and Therapy, 34(2), 163-173.
doi: 10.1016/0005-7967(95)00035-6
---

{% include JB/setup %}

#### Detailed description

The Padua Inventory-Washington State University Revision (PI-WSUR) is a self-report measure designed to assess the presence and severity of obsessive-compulsive disorder (OCD) symptoms. This revision of the original Padua Inventory (Sanavio, 1988) was developed to address psychometric limitations and provide clearer differentiation between OCD symptoms and general worry.

**Site**: This measure is administered at **Krakow** only.

The PI-WSUR improved upon the original 60-item Padua Inventory by:
- Reducing to 39 items (more efficient administration)
- Removing items that conflated OCD symptoms with generalized worry
- Enhancing specificity for obsessions and compulsions
- Providing better discriminant validity
- Identifying distinct content dimensions of OCD

**Response Format**: Respondents rate the degree of disturbance caused by each symptom on a 5-point scale:
- 0 = Not at all
- 1 = A little
- 2 = Quite a bit
- 3 = A lot
- 4 = Very much

## Five Subscales

The PI-WSUR assesses five content dimensions relevant to OCD:

### 1. Obsessional Thoughts of Harm to Self/Others
**Variable**: `piwsur_thoughts_harm`
**Items**: 7 items

- Intrusive, unwanted thoughts about causing harm
- Fear of accidentally hurting oneself or others
- Disturbing mental images of harm
- Example: "I am upset by the idea that I might cause an accident"

### 2. Obsessional Impulses to Harm Self/Others
**Variable**: `piwsur_impulses_harm`
**Items**: 9 items

- Urges or impulses to cause harm (without acting on them)
- Fear of losing control and acting on harmful impulses
- Aggressive obsessions
- Example: "When I see a sharp object, I worry that I might hurt someone"

### 3. Contamination Obsessions and Washing Compulsions
**Variable**: `piwsur_contamination_washing`
**Items**: 10 items

- Fear of contamination or germs
- Excessive concern about cleanliness
- Compulsive washing or cleaning behaviors
- Example: "I wash my hands more often or longer than necessary"

### 4. Checking Compulsions
**Variable**: `piwsur_checking_compulsions`
**Items**: 10 items

- Repetitive checking behaviors
- Doubting and need for reassurance
- Verification of locks, appliances, work, etc.
- Example: "I check and recheck gas and water taps and light switches after turning them off"

### 5. Dressing/Grooming Compulsions
**Variable**: `piwsur_dressing_grooming`
**Items**: 3 items

- Excessive concern with symmetry or exactness in dressing/grooming
- Need for things to feel "just right"
- Ritualistic dressing or grooming behaviors
- Example: "I spend a lot of time every day checking things over and over again"

## Scoring

**Subscale Scores**: Sum items within each of the five dimensions

**Total Score** (`sum_piwsur`): Sum across all 39 items
- Range: 0-156
- Higher scores indicate greater severity and frequency of OCD symptoms

**Interpretation**:
- The PI-WSUR can identify specific symptom profiles
- Useful for both clinical screening and research on subclinical OCD symptoms
- No universally established clinical cutoffs, but higher scores suggest more severe OCD symptoms

**Clinical Utility**: While the PI-WSUR is not a diagnostic instrument, it can:
- Screen for potential OCD in clinical and research settings
- Track symptom severity over time
- Identify predominant symptom dimensions
- Assess treatment outcomes
- Characterize OCD symptom profiles

## Psychometric Properties

The PI-WSUR demonstrates:
- **Excellent internal consistency**: α = .929 for total score (95% CI [.922, .936])
- **Good subscale reliability**: α ranging from .792 to .900
- **Test-retest reliability**: r = .767 for total score (95% CI [.700, .820])
- **Subscale stability**: r ranging from .540 to .790
- **Five-factor structure**: Confirmed through factor analysis
- **Convergent validity**: Correlates with other OCD measures (e.g., Y-BOCS, Maudsley Obsessional-Compulsive Inventory)
- **Discriminant validity**: Better separation from general worry and anxiety than original Padua Inventory

## Comparison to Original Padua Inventory

**Improvements in PI-WSUR**:
- Reduced from 60 to 39 items (more efficient)
- Removed 21 items that conflated worry with OCD symptoms
- Clearer five-factor structure
- Better psychometric properties
- Enhanced clinical and research utility
- Improved specificity for OCD symptoms

**Original Padua Inventory** (Sanavio, 1988):
- 60 items with less clear factor structure
- Mixed OCD symptoms with general worry
- Less discriminant validity

## Research Applications

The PI-WSUR is used in:
- Clinical trials of OCD treatments (tracking symptom change)
- Epidemiological studies of OCD prevalence
- Research on OCD subtypes and symptom dimensions
- Studies of subclinical obsessive-compulsive symptoms in general population
- Cross-cultural OCD research (validated in multiple languages)
- Neuroimaging studies relating brain structure/function to OCD symptoms
- Genetic and family studies of OCD

## Cross-Cultural Validations

The PI-WSUR has been validated in multiple languages including:
- Persian
- Dutch
- Spanish
- Turkish
- German
- And others

Demonstrates cross-cultural applicability and consistent factor structure across diverse populations.

## Important Caveats

- The PI-WSUR is a **self-report measure** subject to response biases
- **Not a diagnostic tool**; clinical assessment required for OCD diagnosis
- Assesses symptom severity and dimensions but does not establish clinical diagnosis
- Should be used in conjunction with clinical interview and other assessment methods
- High scores indicate presence of OCD symptoms but do not confirm OCD diagnosis

## Related publications

**Original PI-WSUR Development:**
Burns, G. L., Keortge, S. G., Formea, G. M., & Sternberger, L. G. (1996). Revision of the Padua Inventory of obsessive compulsive disorder symptoms: Distinctions between worry, obsessions, and compulsions. Behaviour Research and Therapy, 34(2), 163-173. https://doi.org/10.1016/0005-7967(95)00035-6

**Reliability Meta-Analysis:**
Rubio-Aparicio, M., Núñez-Núñez, R. M., Sánchez-Meca, J., López-Pina, J. A., Marín-Martínez, F., & López-López, J. A. (2020). The Padua Inventory-Washington State University Revision of obsessions and compulsions: A reliability generalization meta-analysis. Journal of Personality Assessment, 102(1), 113-123.

**Original Padua Inventory:**
Sanavio, E. (1988). Obsessions and compulsions: The Padua Inventory. Behaviour Research and Therapy, 26(2), 169-177.

**Manual:**
Burns, G. L. (1995). Padua Inventory-Washington State University Revision. Pullman, WA: Author.
