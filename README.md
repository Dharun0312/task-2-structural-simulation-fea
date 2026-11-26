# Task 2 — CATIA V5 Structural Simulation (FEA)

**Primary submission:** native CATIA V5 R21 Generative Structural Analysis of a 300 × 30 × 6 mm cantilever beam. Open the editable CATPart, solved CATAnalysis, scalar exports, plots, screenshots and report in [CATIA_V5_Native](CATIA_V5_Native/README.md).

## Solver results

| Load | Peak von Mises stress | Peak displacement | Estimated FoS* |
|---:|---:|---:|---:|
| 100 N | 83.41 MPa | 48.10 mm | 3.00 |
| 200 N | 166.82 MPa | 96.19 mm | 1.50 |

The end face at z = 0 mm is clamped. Each load is uniform pressure across the 300 × 30 mm top face. Both static solves completed in CATIA GSA. *FoS uses an assumed 250 MPa yield strength; confirm the steel grade.

## Review note

The exported displacement is much larger than a simple beam check predicts (about 3.13 mm at 100 N and 6.25 mm at 200 N). The detailed report flags this discrepancy. Review the displacement result, support, load and units in CATIA before calling the component design-validated.

## Open the submission

- [Detailed CATIA solver report](CATIA_V5_Native/structural_fea_report.html)
- [CATIA beam part](CATIA_V5_Native/task2_catia_solved.CATPart)
- [CATIA GSA analysis document](CATIA_V5_Native/task2_catia_solved.CATAnalysis)
- [Combined native nodal results](CATIA_V5_Native/catia_native_nodal_results.csv)

Earlier analytical files remain in the repository for reference; the CATIA-native folder is the primary submission.