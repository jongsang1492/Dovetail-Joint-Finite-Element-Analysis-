# Dovetail-Joint-Finite-Element-Analysis-
Conduct finite element analysis of a dovetail joint using ANSYS Workbench and examine the accuracy of the predictions. 
# Dovetail Joint Finite Element Analysis

This project was completed as part of the Mechanics of Solids course and focuses on analyzing the
structural behavior of a dovetail joint using ANSYS Workbench. The goal was to understand how
stress is distributed along the joint and to evaluate the accuracy of the finite element model by
comparing it with basic analytical predictions.

## Overview

The dovetail joint geometry was recreated in ANSYS based on the dimensions provided in the lab.
Material properties such as Young’s modulus, Poisson’s ratio, and yield strength were assigned
before running the analysis. The model was discretized using quadrilateral elements to better
capture the curvature and stress gradients around the mating surfaces.

## Boundary Conditions and Loading

Appropriate boundary conditions were applied to represent the way the joint is held in practice,
and external loads were added to simulate realistic operating conditions. Contact elements were
used between the two mating surfaces so that the interaction between components could be
captured during loading.

## Results

The analysis produced equivalent stress and total deformation plots for the joint. The results showed
high stress concentrations near the curved region of the joint, which matched the expected behavior
from lecture examples and earlier studies of dovetail connections. The deformation pattern also
followed what would be predicted when bending and twisting occur around the joint interface.

## Validation

To check the accuracy of the FE model, the deformation trends were compared with analytical beam
theory calculations. While the absolute values were not identical, the overall stress and deformation
patterns were consistent with theoretical expectations. This step helped confirm that the model was
set up correctly and that the mesh and boundary conditions were reasonable for this type of joint.

## Takeaways

Through this project, I gained experience setting up FEA problems from scratch, including geometry
preparation, meshing, defining material properties, applying loads and constraints, and interpreting
stress and deformation results. It also emphasized the importance of validating simulation resu<img 
against theoretical or experimental references.

## Appendix
<img width="291" height="184" alt="Screen Shot 2025-11-14 at 6 23 09 PM" src="https://github.com/user-attachments/assets/d63637a0-4221-446b-80be-ca3bed751286" />
<img width="256" height="273" alt="Screen Shot 2025-11-14 at 6 24 15 PM" src="https://github.com/user-attachments/assets/0a3b18be-a2ed-4278-85b0-fda85b23e0de" />
<img width="350" height="284" alt="Screen Shot 2025-11-14 at 6 24 45 PM" src="https://github.com/user-attachments/assets/3b8dab7e-61e7-4eef-8790-311acc0718dc" />
<img width="588" height="346" alt="Screen Shot 2025-11-14 at 6 25 45 PM" src="https://github.com/user-attachments/assets/72bc76c2-c308-457a-8f43-5c025cce5b58" />
<img width="455" height="277" alt="Screen Shot 2025-11-14 at 6 26 03 PM" src="https://github.com/user-attachments/assets/d64fa126-d5af-4f8b-b013-5bae0ef14dc3" />
