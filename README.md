# The Mindfulness Paradox: Do secular mindfulness programs bring spiritual and non-spiritual individuals closer?

This repository contains the anonymized dataset associated with the manuscript:

**The Mindfulness Paradox: Do secular mindfulness programs bring spiritual and non-spiritual individuals closer?**

Prieto-Botella, D., Rodríguez-Moreno, S., Ramírez-Riveros, E. S., Martín-Azañedo, C., Horrillo-Álvarez, B., & Roca, P.

---

# Overview

This study examined whether baseline religious/spiritual (R/S) versus atheist/agnostic (A/A) orientation was associated with:

1. Pre-intervention differences in psychological functioning
2. Differential change following an 8-week Mindfulness-Based Stress Reduction (MBSR) program
3. Differences in the mechanisms of psychological change following mindfulness training

The dataset includes pre- and post-intervention psychological measures collected from adults enrolled in a standardized MBSR program delivered in a community setting.

---

# Repository Contents

```text
data/
   data_final.csv

codebook/
   Data_Codebook.xlsx

README.md
```

---

# Dataset Description

The dataset contains anonymized quantitative data from adult participants who completed an 8-week standardized Mindfulness-Based Stress Reduction (MBSR) program.

Participants self-identified at baseline as either:

* Religious/Spiritual (R/S)
* Atheist/Agnostic (A/A)

The dataset includes:

## Sociodemographic variables

* Age
* Sex
* Educational level
* Employment status
* Meditation experience
* Religious/spiritual orientation

## Psychological measures

The dataset includes total scores and composite variables from the following validated instruments:

* Five Facet Mindfulness Questionnaire (FFMQ)
* Multidimensional Assessment of Interoceptive Awareness (MAIA)
* Experience Questionnaire (EQ)
* Self-Compassion Scale – Short Form (SCS-SF)
* Depression Anxiety Stress Scales – 21 items (DASS-21)
* Ruminative Responses Scale (RRS)
* Pemberton Happiness Index (PHI)
* Interpersonal Reactivity Index – Empathic Concern (IRI)

## Derived variables

The repository also includes:

* Pre-intervention scores (`_PRE`)
* Post-intervention scores (`_POST`)
* Delta change scores (`delta_`)
* Residualized change scores (`res_`)
* Composite residualized variables (`mind_res`, `scs_res`)

---

# Study Design

* Quasi-experimental longitudinal pre-post design
* Repeated measures assessment
* Community-based MBSR intervention

## Intervention Characteristics

* 8-week MBSR program
* Weekly face-to-face sessions
* Daily mindfulness practice
* Delivered by trained MBSR instructors

---

# Statistical Analyses

Analyses reported in the manuscript included:

* Descriptive statistics
* Student’s t-tests
* Fisher’s exact tests
* Linear mixed-effects models
* Structural equation modeling (SEM)
* Residualized change score analyses

All analyses were conducted using **R**.

---

# Ethical Considerations

All participants:

* Provided informed consent
* Participated voluntarily
* Were anonymized prior to analysis

No directly identifiable personal information is included in this repository.

---

# Data Availability

This repository contains the cleaned dataset used for the analyses reported in the manuscript.

The shared dataset:

* Excludes personally identifiable information
* Includes only variables used in the reported analyses

---

# License

This dataset is shared exclusively for:

* Academic research
* Scientific transparency
* Educational purposes

Users must cite the associated manuscript when using these data.

---

# Suggested Citation

Prieto-Botella, D., Rodríguez-Moreno, S., Ramírez-Riveros, E. S., Martín-Azañedo, C., Horrillo-Álvarez, B., & Roca, P. *The Mindfulness Paradox: Do secular mindfulness programs bring spiritual and non-spiritual individuals closer?* Dataset and materials repository.

---

# Contact

**Precision Mind Lab (Premind)**
Universidad Villanueva
Madrid, Spain

📩 [precisionmindlab@gmail.com](mailto:precisionmindlab@gmail.com)
