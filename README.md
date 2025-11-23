# Chlorhexidine-Impact-On-Prevention-VAP--python
Survival Analysis of Chlorhexidine 0.12% vs 0.20% for Prevention of Ventilator-Associated Pneumonia (VAP)

This repository contains a full survival-analysis–based re-evaluation of the Chlorhexidine RCT dataset, originally published in Annals of International Medical and Dental Research (2021). The goal is to analyze whether chlorhexidine mouthwash at 0.20% is more effective than 0.12% in preventing ventilator-associated pneumonia (VAP) among mechanically ventilated ICU patients.

All analyses are performed using Python, lifelines, and reproducible Jupyter Notebook workflows.
This project demonstrates the full pipeline of a clinical survival analysis: data cleaning, event-time creation, Kaplan–Meier estimation, Cox modeling, PH assumption testing, and interpretation.


Project Overview:

Clinical Question:
Does 0.20% chlorhexidine mouthwash improve VAP-free survival compared with 0.12% chlorhexidine in intubated ICU patients?

Primary Outcome:
Time to VAP defined by CPIS ≥ 6, consistent with the scoring system used in the original RCT.

Methods Used:
Kaplan–Meier Survival Curves (overall & by treatment group)
Log-Rank comparison
Cox Proportional Hazards Model
Schoenfeld residual tests (PH assumption)
Life-table generation
