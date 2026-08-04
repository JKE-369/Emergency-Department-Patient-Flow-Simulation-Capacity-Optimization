# Emergency Department Patient Flow Simulation & Capacity Optimization

A **Discrete-Event Simulation (DES)** developed in **AnyLogic** to analyze emergency department patient flow, resource utilization, and capacity requirements.

The model evaluates how changes in **ED beds, doctors, triage nurses, fast-track rooms, and inpatient beds** affect patient **Length of Stay (LOS)** and resource utilization.

## Objectives

- Analyze emergency department patient flow
- Evaluate resource utilization and patient LOS
- Identify capacity bottlenecks
- Explore the effect of different staffing and bed-capacity scenarios

## Technologies

- AnyLogic
- Discrete-Event Simulation
- Process Modeling Library
- Resource & Queue Modeling
- Parameter Variation Experiments

## Experiments

Five parameter-variation experiments were conducted:

| Resource | Capacity Range |
|---|---:|
| Inpatient Beds | 10–40 |
| ED Beds | 15–30 |
| Doctors | 2–8 |
| Triage Nurses | 1–5 |
| Fast-Track Rooms | 2–10 |

## Key Findings

- Increasing ED bed capacity from 15 to 16 significantly reduced overall LOS, with limited improvement beyond that point.
- Fast-track LOS improved up to approximately 4–5 rooms, after which additional capacity provided little benefit.
- Increasing inpatient capacity reduced admitted-patient LOS and resource utilization, with diminishing returns at higher capacities.
- Doctor and nurse capacity experiments showed non-monotonic results, highlighting the importance of downstream constraints and replication variability.

## Project Files

- `EdPatientFlow.alp` — AnyLogic simulation model
- `ED_Patient_Flow_Simulation_Report.pdf` — Detailed project documentation, methodology, experiments, results, assumptions, and limitations

## How to Run

1. Open `EdPatientFlow.alp` in AnyLogic.
2. Run the **Simulation** experiment for the baseline scenario.
3. Run the **Parameter Variation** experiments to reproduce the capacity analyses.

## Documentation

For the complete model description, assumptions, distributions, results, verification and validation, reproducibility information, and future improvements, see:

**[ED Patient Flow Simulation Report](./ED_Patient_Flow_Simulation_Report.pdf)**

## Academic Project

**Module:** Simulation of Production Systems (SS26)  
**Platform:** AnyLogic  
**Modeling Approach:** Discrete-Event Simulation

## Author

**Joel Kuriyen Elias**

M.Sc. Applied Artificial Intelligence for Digital Production Management  
Technische Hochschule Deggendorf
