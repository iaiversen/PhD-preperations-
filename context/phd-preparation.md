# PhD Preparation — "Day and Night of Bipolar Disorder"

## Status

Ingebjorg got the job offer. She has been accepted for the PhD stipendiat position at Oslo University Hospital (OUS), Seksjon for klinisk psykoseforskning, in the research group Kliniske symptommekanismer led by Professor Trine Vik Lagerberg. The interview preparation phase is over. She is now preparing to begin the scholarship/stipendiat position.

---

## PhD Project Description

**Title:** "Day and night of bipolar disorder"

**Core research question:** Understanding circadian disruption and sleep disruption/patterns in bipolar disorder — specifically investigating directionality:
- Does sleep/circadian disruption precede mood episodes?
- Or do mood episodes precede sleep/circadian disruption?

This is a question about temporal ordering and causality within individuals over time. The project sits at the intersection of chronobiology, clinical psychiatry, and intensive longitudinal methods.

---

## Data Description

The data has already been collected (pre-acquired). Ingebjorg will not be collecting new data — she will be working with an existing dataset.

**Participants:** Approximately 70 patients with bipolar disorder.

**Actigraphy data:**
- Patients wore actigraphy wrist bands for several months
- This provides continuous, objective measurements of activity, rest-activity rhythms, and sleep/wake patterns

**Ecological Momentary Assessment (EMA) data:**
- Patients answered self-report questionnaires on mobile phones
- Multiple time scales of reporting:
  - Some questionnaires were daily
  - Some were weekly
  - Some were every 2-3 weeks
- Content likely includes mood ratings, sleep quality, energy levels, and other subjective experiences

**Data characteristics:**
- Intensive longitudinal design — many repeated measurements within each individual
- Multimodal — combining objective (actigraphy) with subjective (EMA) data streams
- Nested structure — observations nested within individuals over time
- Multiple temporal resolutions — different questionnaires at different intervals
- Likely irregular and missing data — real-world clinical data collection over months

---

## Key Tasks and Goals

1. **Analyse group-level patterns:** Identify general trends in the relationship between circadian/sleep disruption and mood episodes across the full sample of ~70 patients with bipolar disorder.

2. **Analyse individual-level patterns:** Use idiographic (person-centered) approaches to understand how circadian disruption and mood episodes relate within specific individuals — because the directionality may differ between people.

3. **Investigate directionality:** Determine whether sleep/circadian disruption leads to mood episodes, whether mood episodes lead to sleep/circadian disruption, or whether both directions occur (possibly varying across individuals).

4. **Bridge group and individual findings:** Integrate nomothetic (group) and idiographic (individual) analyses to build a nuanced picture of the sleep-mood relationship in bipolar disorder.

---

## What Ingebjorg Needs to Prepare For

### 1. Understanding bipolar disorder

- Clinical presentation: mania, hypomania, depression, mixed episodes, euthymia
- The course of illness: episode patterns, prodromal signs, triggers
- How sleep and circadian disruption manifests in different mood states
- The social zeitgeber theory and interpersonal and social rhythm therapy (IPSRT)
- Chronobiology basics: circadian rhythms, melatonin, light exposure, rest-activity cycles

### 2. Understanding the data types

- **Actigraphy:** What accelerometers measure, how raw actigraphy data is processed into sleep/wake variables (total sleep time, sleep onset latency, wake after sleep onset, sleep efficiency, interdaily stability, intradaily variability, relative amplitude, etc.), common software and algorithms (e.g., Cole-Kripke), limitations and artifacts
- **EMA / experience sampling:** Design considerations, compliance and missing data patterns, reactive effects, question design, momentary vs. retrospective reports

### 3. Statistical methodology

This is the most demanding preparation area. Key methods to study:

- **Multilevel models for intensive longitudinal data** — the backbone of most analyses with this data structure
- **Dynamic Structural Equation Modeling (DSEM)** — combines multilevel modeling with time-series analysis; can handle both within-person and between-person variance
- **Vector autoregression (VAR)** — for modeling temporal dynamics and Granger-type causality between variables; both group-level and idiographic (N=1) applications
- **Cross-lagged panel models (CLPM) and Random-Intercept CLPM (RI-CLPM)** — for distinguishing within-person from between-person effects in longitudinal data
- **Time-series analysis** — autocorrelation, stationarity, detrending, lagged effects
- **Idiographic / N-of-1 methods** — person-specific modeling approaches
- **Handling missing data** — multiple imputation, full information maximum likelihood (FIML), pattern analysis
- **Software:** R (primary), potentially Mplus for DSEM, familiarity with relevant R packages (e.g., mlVAR, graphicalVAR, lme4/nlme, brms)

### 4. Data analysis workflow

- Data cleaning and preprocessing of actigraphy data
- Merging multimodal data streams (actigraphy + EMA) with different temporal resolutions
- Variable creation from raw actigraphy signals
- Exploratory data analysis and visualization of intensive longitudinal data
- Reproducible analysis pipelines (R, Quarto, Git — skills she already has)

### 5. Practical and professional preparation

- Familiarize herself with Professor Trine Vik Lagerberg's recent publications and the group's published work
- Read any existing publications from this dataset or project
- Understand the ethical framework for the study (REK approval, data handling)
- Prepare for the transition from research technician/assistant role to independent PhD researcher
- Understand the structure of a Norwegian PhD: courses, midway evaluation, articles, thesis

---

## Existing Strengths to Build On

- Strong R and Quarto skills — already her primary tools
- Git and version control experience — essential for reproducible research
- Machine learning course (PSY9511) — provides some statistical foundations
- Coursework in consciousness studies that included sleep and circadian rhythms
- Experience with systematic reviews — useful for writing introduction and discussion sections
- Experience coordinating data collection at a hospital (Rikshospitalet/fMRI) — helpful for navigating the OUS environment
- Publication record — demonstrates she can complete research projects to a high standard
- Open science practices — aligns well with modern research standards

## Known Gaps to Address

- No prior experience with actigraphy data (needs to learn from scratch)
- No prior experience with EMA data (needs to learn from scratch)
- No experience with the specific statistical methods listed above (DSEM, VAR, RI-CLPM) — though she has general statistical training
- No clinical experience with bipolar disorder or psychiatric patients
- No experience with intensive longitudinal data analysis
