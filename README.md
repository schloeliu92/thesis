# Association of CCL5 with Arterial Stiffness in Obstructive Sleep Apnea: The Modifying Role of Excessive Daytime Sleepiness

This repository contains the Python code used in my Master's thesis for the MSPH in Epidemiology at Emory University. The thesis explores how **CCL5**, a pro-inflammatory chemokine, is associated with **arterial stiffness** in patients with **obstructive sleep apnea (OSA)**, and whether this relationship is modified by **excessive daytime sleepiness (EDS)**.

---

## Project Overview

- **Study Design**: Cross-sectional analysis using data from the Emory Metabolomics of Sleepiness Symptoms (EMOSS) study.
- **Sample Size**: 63 participants with confirmed OSA.
- **Primary Exposure**: Plasma **CCL5** levels measured via multiplex ELISA.
- **Primary Outcome**: Arterial stiffness measured by **pulse wave velocity (PWV)**.
- **Stratification**: Participants categorized as *Sleepy* (ESS ≥ 10) or *Non-Sleepy* (ESS < 10).

---

## Key Findings

- Linear regression showed **no significant association** between CCL5 and PWV in the full sample.
- However, **generalized additive models (GAMs)** revealed a **significant non-linear relationship** between CCL5 and PWV **among sleepy individuals**, suggesting symptom-specific vascular risk.
- CCL5 may serve as a biomarker for **inflammation-amplified cardiovascular risk** in OSA.

---

## Repository Structure
thesis/
├── thesis.py # Python script for data cleaning, modeling, and visualization
├── data/ # (Not included) EMOSS dataset (restricted)
├── README.md # Project documentation

---

## Tools & Libraries

- Python 3.10
- `pandas`, `numpy`, `matplotlib`
- `statsmodels` for linear regression
- `pyGAM` for generalized additive models

---

## Public Health Implications
This research highlights sleepiness as a modifier of inflammation-related cardiovascular risk in OSA. Subjective symptoms like EDS may help identify high-risk subgroups more vulnerable to vascular damage—suggesting a potential role for CCL5 in personalized risk stratification and symptom-informed intervention.

