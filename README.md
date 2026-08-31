# alzheimers-cost-effectiveness-r
Cost-effectiveness modelling in early Alzheimer’s disease using cohort Markov modelling, uncertainty analysis and patient-level simulation in R.

# Cost-Effectiveness Modelling in Early Alzheimer's Disease

This repository is a learning and portfolio project exploring health economic
modelling in R using early Alzheimer's disease as a case study.

The project begins with a transparent cohort Markov model comparing an
illustrative disease-modifying therapy plus standard care with standard care
alone in people with early symptomatic Alzheimer's disease.

The model will then be extended progressively to include deterministic and
probabilistic sensitivity analysis, patient-level simulation, and a comparison
between conventional and vectorised R implementations.

## Project aims

The repository is intended to demonstrate and refresh practical skills in:

- cohort Markov modelling
- cost and QALY accumulation
- incremental cost-effectiveness analysis
- deterministic sensitivity analysis
- probabilistic sensitivity analysis
- patient-level simulation
- vectorised programming in R
- computational performance and model validation

## Planned modelling framework

The initial cohort model will use the following simplified disease pathway:

MCI due to Alzheimer's disease  
→ Mild Alzheimer's disease  
→ Moderate Alzheimer's disease  
→ Severe Alzheimer's disease  
→ Death

The intervention will be modelled as an illustrative disease-modifying therapy
that slows disease progression during eligible early disease stages.

The initial model is intended as a methodological demonstration rather than a
reproduction of a specific HTA submission or branded treatment model.

## Repository structure

```text
R/
├── 01_parameters.R
├── 02_markov_model.R
├── 03_base_case.R
├── 04_dsa.R
├── 05_psa.R
├── 06_patient_simulation.R
├── 07_vectorised_simulation.R
└── 08_performance_comparison.R
