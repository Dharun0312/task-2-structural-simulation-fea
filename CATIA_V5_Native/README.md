# CATIA V5 Native FEA

Open [the detailed solver report](structural_fea_report.html) first. The editable CATIA V5 R21 files are [the beam part](task2_catia_solved.CATPart) and [the GSA analysis document](task2_catia_solved.CATAnalysis). Keep both together when opening the analysis.

## CATIA solver outputs

- [Combined nodal stress and displacement data](catia_native_nodal_results.csv)
- [Stress distribution plot](catia_stress_distribution.svg)
- [Displacement distribution plot](catia_displacement_distribution.svg)
- [CATIA mesh captures: 100 N](task2_catia_case_100N_stress.jpg) and [200 N](task2_catia_case_200N_stress.jpg)
- Raw CATIA exports: [100 N stress](catia_native_case_100N_stress.txt), [200 N stress](catia_native_case_200N_stress.txt), [100 N displacement](catia_native_case_100N_displacement.txt), [200 N displacement](catia_native_case_200N_displacement.txt)

The native GSA solve completed for 100 N and 200 N with a clamp on the z = 0 mm end face and uniform pressure on the top face. The displacement export is unusually high compared with a simple beam estimate; the report documents the mismatch. FoS uses an assumed 250 MPa yield strength and must be checked against the chosen steel grade.