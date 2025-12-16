---
layout: dataset
title: AQ / ASQ – Autism-Spectrum Quotient
modality:
  - questionnaires
domain:
  - Social cognition
  - Other
paradigm:
  - Autism
site:
  - Krakow
  - Brno
authors:
contact:
email:
ratings: false
summary: A self-report questionnaire measuring autistic traits in adults with average or above-average intelligence. Available in both short (28-item) and full (50-item) versions. Krakow administers the AQ-Short (28 items), while Brno_2023 administers the full AQ (50 items). Not a diagnostic instrument but assesses the distribution of autism-related characteristics across the population.
participants:
citation: Baron-Cohen, S., Wheelwright, S., Skinner, R., Martin, J., & Clubley, E. (2001). The Autism-Spectrum Quotient (AQ) - Evidence from Asperger Syndrome/High-Functioning Autism, males and females, scientists and mathematicians. Journal of Autism and Developmental Disorders, 31(1), 5-17.
doi: 10.1023/A:1005653411471
---

{% include JB/setup %}

#### Detailed description

The Autism-Spectrum Quotient (AQ) is a self-administered questionnaire designed to measure the degree to which adults with average or above-average intelligence possess traits associated with the autism spectrum. The AQ was developed at the Cambridge Autism Research Centre to provide a brief, quantitative assessment of autistic traits in the general population and clinical samples.

**Important Note**: The AQ is a screening tool for research purposes and measures autistic traits dimensionally. It is **not a diagnostic instrument** for autism spectrum disorder.

**Theoretical Basis**: The AQ is based on the understanding that autistic traits exist on a continuum in the general population, with clinical autism representing the extreme end of this distribution.

## Versions Used in This Study

### AQ-Short (28 items) - **Krakow**

The abbreviated version comprises 28 items selected from the full 50-item scale.

**Subscales in Short Version** (as reported in po_short.ods):
- `sum_asq_imagination_short`: Imagination subscale
- `sum_asq_num_pat_short`: Numerical Pattern Recognition subscale
- `sum_asq_routine_short`: Routine subscale
- `sum_asq_soc_behav_short`: Social Behavior subscale
- `sum_asq_soc_skills_short`: Social Skills subscale
- `sum_asq_switching_short`: Switching/Cognitive Flexibility subscale
- `sum_asq_short`: Total AQ-Short score

**Higher-Order Factor Structure** (Hoekstra et al., 2011):
1. **Social behavioral difficulties**: Captures social interaction and communication challenges
2. **Fascination for numbers/patterns**: Reflects attention to detail and systematic thinking

### AQ-Full (50 items) - **Brno_2023**

The full version contains 50 items assessing five dimensions with 10 items each.

**Subscales in Full Version** (as reported in po_short.ods):
- `sum_asq_imagination_full`: Imagination - Full (10 items)
- `sum_asq_attention_to_detail_full`: Attention to Detail - Full (10 items)
- `sum_asq_communication_full`: Communication - Full (10 items)
- `sum_asq_soc_skills_full`: Social Skills - Full (10 items)
- `sum_asq_switching_full`: Switching/Cognitive Flexibility - Full (10 items)
- `sum_asq_full`: Total AQ-Full score

## Five Subscales (Full Version Structure)

1. **Social Skills**: Difficulties with social interaction and understanding social cues
   - Items: 10 (full version)
   - Example: "I prefer to do things with others rather than on my own" (reverse-scored)

2. **Attention Switching / Cognitive Flexibility**: Difficulty changing attentional focus
   - Items: 10 (full version)
   - Example: "I frequently get so strongly absorbed in one thing that I lose sight of other things"

3. **Attention to Detail**: Strong focus on details and patterns
   - Items: 10 (full version)
   - Example: "I tend to notice details that others do not"

4. **Communication**: Difficulties in verbal and non-verbal communication
   - Items: 10 (full version)
   - Example: "I frequently find that I don't know how to keep a conversation going"

5. **Imagination**: Preference for routine and difficulty with imagination/creativity
   - Items: 10 (full version)
   - Example: "I find it difficult to imagine what it would be like to be someone else"

## Scoring

**Response Format**: 4-point Likert scale
- Definitely agree
- Slightly agree
- Slightly disagree
- Definitely disagree

**Scoring Methods**:

1. **Binary Scoring** (dichotomized):
   - Agreement with autistic-trait items = 1 point
   - Agreement with non-autistic-trait items = 0 points
   - Score ranges: 0-50 (full) or 0-28 (short)

2. **Continuous Scoring** (4-point):
   - Items are reverse-scored where "agree" indicates autistic traits (24 out of 50 items in full scale)
   - Item scores are summed
   - Used in some research contexts for greater variability

**Interpretation (Binary Scoring, Full Version)**:
- 0-25: Low autistic traits (typical range)
- 26-31: Borderline; some autistic traits
- 32-50: High autistic traits; clinical range
- **Cutoff for potential autism**: ≥32 (80% sensitivity, 74% specificity in original validation)

**Interpretation (4-point Scoring)**:
- The study suggests that a cut-off of >65 (on the full scale) may be useful for identifying clinically relevant levels of autistic traits

**Data Quality**: If more than 10% of items are missing (>3 in the AQ-Short, >5 in the AQ-Full), the questionnaire is considered unreliable and data should be discarded.

## Psychometric Properties

The AQ demonstrates:
- **Internal consistency**: α typically .63-.77 for subscales, .71-.91 for total score
- **Test-retest reliability**: Good stability over time
- **Discriminant validity**: Ability to discriminate between clinical autism and general population
- **Continuous distribution**: Scores distribute continuously in general population (supporting dimensional view)
- **Cross-cultural validity**: Validated in numerous languages and cultures

**AQ-Short Specific** (Hoekstra et al., 2011):
- Maintains good psychometric properties with reduced length
- Strong correlation with full AQ (r > .95)
- More efficient for large-scale studies

## Research Applications

The AQ is widely used in:
- Research on individual differences in autistic traits
- Studies of social cognition and theory of mind
- Genetic and neuroimaging research on autism
- Screening in clinical and research settings
- Investigation of the "broader autism phenotype"
- Studies of cognitive, neural, genetic, and hormonal correlates of autistic traits

## Site-Specific Implementation

| Site | Version | Items | Subscales |
|------|---------|-------|-----------|
| **Krakow** | AQ-Short | 28 | 6 subscales (short versions) |
| **Brno_2023** | AQ-Full | 50 | 5 subscales (10 items each) |

**Note**: The short version was designed to capture the same construct as the full version while reducing participant burden. Both versions are valid for measuring autistic traits.

## Important Caveats

- The AQ is a **self-report measure** subject to response biases
- **Not a diagnostic tool**; clinical assessment required for diagnosis
- Some items may be culturally specific
- Scores should be interpreted in context of other information
- High scores indicate presence of autistic traits but do not confirm autism diagnosis

## Related publications

**Original AQ Development:**
Baron-Cohen, S., Wheelwright, S., Skinner, R., Martin, J., & Clubley, E. (2001). The Autism-Spectrum Quotient (AQ): Evidence from Asperger Syndrome/High-Functioning Autism, males and females, scientists and mathematicians. Journal of Autism and Developmental Disorders, 31(1), 5-17. https://doi.org/10.1023/A:1005653411471

**AQ-Short Development:**
Hoekstra, R. A., Vinkhuyzen, A. A., Wheelwright, S., Bartels, M., Boomsma, D. I., Baron-Cohen, S., Posthuma, D., & van der Sluis, S. (2011). The construction and validation of an abridged version of the autism-spectrum quotient (AQ-Short). Journal of Autism and Developmental Disorders, 41(5), 589-596. https://doi.org/10.1007/s10803-010-1073-0

**Psychometric Validation:**
Hoekstra, R. A., Bartels, M., Cath, D. C., & Boomsma, D. I. (2008). Factor structure, reliability and criterion validity of the Autism-Spectrum Quotient (AQ): A study in Dutch population and patient groups. Journal of Autism and Developmental Disorders, 38(8), 1555-1566.

Lundqvist, L. O., & Lindner, H. (2017). Is the Autism-Spectrum Quotient a valid measure of traits associated with the autism spectrum? A Rasch validation in adults with and without autism spectrum disorders. Journal of Autism and Developmental Disorders, 47(7), 2080-2091.
