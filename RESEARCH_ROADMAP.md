# Future research and portfolio roadmap

This roadmap records useful next studies without presenting unfinished work as completed evidence. New repositories should be created only when the research question, data rights, implementation, and verification plan are clear.

## Priority 1 — strengthen existing evidence

### Sepsis missingness and observation-window audit

Evaluate how first-6-hour, first-12-hour, and first-24-hour windows affect cohort size, missingness, and feature availability in the MIMIC-III Demo. Publish cohort statistics and limitations before model comparisons.

### QRS matching-tolerance sensitivity

Measure how annotation-matching tolerances such as 50, 100, and 150 ms change sensitivity, precision, F1, and timing error for the same records. This demonstrates why evaluation protocol matters.

### HRV artifact-handling sensitivity

Compare HRV outputs before and after ectopic/artifact filtering and quantify how rejected gaps affect RMSSD, pNN50, Poincare, and frequency-domain eligibility.

### Denoising robustness matrix

Compare the CNN and spectral-subtraction baseline across several SNR levels and, when lawful data are available, more realistic noise types. Report all held-out conditions and failed cases.

### Mortality calibration audit

After creating an authorized 24-hour cohort, compare discrimination with calibration, event prevalence, threshold trade-offs, and subgroup uncertainty. Avoid reducing the project to accuracy alone.

## Priority 2 — connect engineering, quality, and data

### Preventive-maintenance case-study template

Create a non-confidential engineering case-study format covering device function, inspection steps, observed issue, safety relevance, action under supervision, verification, documentation, and lessons learned.

### Medical-device FMEA mini-study

Build a transparent educational FMEA example for one device subsystem. Clearly distinguish illustrative scores from manufacturer or hospital risk records.

### ISO 13485 document-control demonstration

Create a fictional, non-regulated document-control and CAPA workflow showing versioning, traceability, root-cause analysis, corrective action, effectiveness review, and audit evidence.

### Healthcare FHIR data mini-project

Use synthetic or officially provided sample resources to demonstrate safe healthcare-data transformation, validation, and documentation without claiming formal Microsoft certification or clinical deployment.

## Priority 3 — career-facing technical communication

- Turn each verified repository into one concise portfolio case study.
- Create one diagram explaining leakage prevention across healthcare machine-learning projects.
- Publish short MATLAB code walkthroughs with limitations.
- Write one clinical-engineering post and one data/research post each week.
- Add reviewed figures or demonstrations only after privacy and provenance checks.

## Publication gate

A future project becomes public only when it has:

1. A precise question and honest contribution statement.
2. Data authorization and provenance.
3. A leakage and privacy review.
4. Reproducible code and configuration.
5. Tests or documented verification.
6. Results that include failures and limitations.
7. No clinical or performance claim beyond the evidence.
8. A clear connection to Aboubakr Ibrahim's biomedical engineering career direction.

The goal is not to maximize repository count. The goal is to make every public repository credible, understandable, and useful.
