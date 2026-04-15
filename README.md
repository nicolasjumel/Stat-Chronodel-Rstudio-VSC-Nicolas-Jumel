# Stat Chronodel Rstudio VSC

## Delirium

Delirium is an acute clinical syndrome (ACS) that typically develops in older adults. It is characterized by disturbances in attention, awareness, and cognition, with a reduced ability to focus, sustain, or shift attention. It develops over a short period of time and tends to fluctuate throughout the day. The clinical presentation may vary, often including psychomotor and behavioral disturbances such as hyperactivity or hypoactivity, as well as alterations in sleep duration and architecture.(1)

The clinical features are defined by the DSM-5 as follows: a disturbance in attention (Criterion A); a rapid onset of symptoms (Criterion B); symptoms associated with an additional cognitive disturbance (Criterion C). These symptoms must not be better explained by a pre-existing neurocognitive disorder (NCD) or by a severely reduced level of arousal such as coma (Criterion D). There must also be evidence from the medical history, physical examination, or additional investigations supporting a direct medical cause, substance intoxication, medication use, or withdrawal (Criterion E).(2)

## Chronodel presentation

The aim of this study is to analyze data from the Chronodel test, which assesses the ability to perform a task within 30 seconds—specifically, counting from 0 to 30 in the correct order, without repetition and without skipping any numbers. The dataset includes a sample of participants (n = 43).

The objectives were to evaluate the Chronodel test, describe the distribution of results, and compare its performance with two other tests assessing similar cognitive functions: Day Of The Week Backward *DOTWB* and Month Of The Year Backward *MOTYB*. (3)

## Methodological Adjustment: Change in Primary Objective

**Initially**, sensitivity, specificity, positive predictive value, and negative predictive value were planned for the Chronodel test. **However**, due to a **low variability** in the results — with most participants scoring 1 (indicating success) — this analysis **was not appropriate**.

# Python Project

## Python objective

Therefore, the analysis plan was revised to focus on :

- **the percentage of success** for each test (*DOTWB*, *MOTYB*, *Chronodel*)
- **the concordance** between tests
- **the distribution** of results to assess variability and potential ceiling effects

## Data preparation

The dataset was first loaded and preprocessed. Subjects who did not meet the study’s inclusion criteria were excluded from the analysis.

Preliminary descriptive analyses were performed to assess the distribution of the variables and the corresponding success rates, including graphical visualizations.

The dataset was then restricted to the variables relevant to the study objectives.

The following outcome variables were retained:

- `jour_reussite` (DOTWB)
- `mois_reussi` (MOTYB)
- `chrono_reussi` (Chronodel)
