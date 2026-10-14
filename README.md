# SACDCS – Software Quality Engineering (Open-Ended Lab)

**Smart Autonomous Cold-Chain Delivery & Control System**
Autonomous robots deliver vaccines from a central warehouse to 20 pilot clinics,
supervised from a Mission Control Centre (MCC).

**Role:** Software Quality Engineering Lead

## Tasks
| Task | Title (as in OEL paper) | Folder |
|---|---|---|
| Task 1 | Requirement Extraction (Scenario-Based) | [Open](Task-1-Requirement-Extraction/) |
| Task 2 | Change Requests & Traceability Matrix (RTM) | [Open](Task-2-Change-Requests-and-Traceability-Matrix/) |
| Task 3 | State Modelling & Transition Verification | [Open](Task-3-State-Modelling-and-Transition-Verification/) |
| Task 4 | Operation Identification & Operation Schema (Conservation Chamber) | [Open](Task-4-Operation-Identification-and-Operation-Schema/) |
| Task 5 | Constraints, Formalisation & Violations (Railway Crossing) | [Open](Task-5-Constraints-Formalisation-and-Violations/) |

## ID Scheme (used across all tasks)
| Prefix | Meaning | Defined in |
|---|---|---|
| FR / NFR / HR | Requirements | Task 1 |
| CR | Change Request | Task 2 |
| TC | Test Case | Task 2 |
| S / E / T | State / Event / Transition | Task 3 |
| CH | Chamber state | Task 4 |
| OP | Operation | Task 4 |
| C | Constraint | Task 5 |

## Verification Methods
- **Test (T):** run the system and check the result
- **Inspection (I):** review documents or code manually
- **Analysis (A):** calculation, simulation or model checking
- **Demonstration (D):** show the feature working to a reviewer

## Versions
- `v1.0-baseline` – Task 1 approved requirements
- `v1.1` – after CR-01, CR-02, CR-03 (see [CHANGELOG](CHANGELOG.md))
