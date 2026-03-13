# Dovetail Joint Finite Element Analysis

Finite Element Analysis (FEA) of a dovetail joint performed using **ANSYS Workbench** to investigate stress distribution, deformation behavior, and structural response under loading conditions.

This project was completed as part of a **Mechanics of Solids** course and focuses on building a complete FEA workflow from geometry creation to result validation.

---

# Project Objective

The goal of this project was to analyze the structural behavior of a dovetail joint using finite element methods and evaluate whether the numerical predictions are consistent with theoretical expectations.

The study focused on:

- Reconstructing the dovetail joint geometry in ANSYS
- Assigning realistic material properties
- Applying boundary conditions and loading
- Modeling contact interaction between joint surfaces
- Analyzing stress and deformation results
- Comparing simulation results with analytical predictions

---

# Geometry Definition

The geometry of the dovetail joint was created based on the dimensions provided in the lab instructions.  
The profile includes the blade, disk, and assembly configuration used in compressor dovetail connections.

<img width="450" alt="Dovetail Geometry" src="https://github.com/user-attachments/assets/d63637a0-4221-446b-80be-ca3bed751286">

*Figure 1. Detailed geometry of the dovetail joint.*

---

# ANSYS Model Setup

The geometry was recreated in **ANSYS Workbench** to prepare it for finite element analysis.  
Material properties including **Young's modulus** and **Poisson’s ratio** were defined before applying loads and constraints.

<img width="320" alt="ANSYS Geometry Model" src="https://github.com/user-attachments/assets/0a3b18be-a2ed-4278-85b0-fda85b23e0de">

*Figure 2. Dovetail joint geometry recreated in ANSYS Workbench.*

---

# Mesh Generation

The model was discretized using quadrilateral elements to accurately capture stress gradients near curved and contact regions.  
A refined mesh was used near the dovetail interface to improve the resolution of local stress concentrations.

<img width="350" alt="Finite Element Mesh" src="https://github.com/user-attachments/assets/3b8dab7e-61e7-4eef-8790-311acc0718dc">

*Figure 3. Discretized geometry of the dovetail joint using quadrilateral finite elements.*

---

# Stress Analysis Results

The finite element simulation produced **equivalent (von Mises) stress** distributions across the dovetail joint.

The results show stress concentrations near the curved contact region, which is consistent with expectations for dovetail-type mechanical connections.

<img width="650" alt="Equivalent Stress Result" src="https://github.com/user-attachments/assets/72bc76c2-c308-457a-8f43-5c025cce5b58">

*Figure 4. Equivalent stress distribution predicted by ANSYS Workbench.*

---

# Deformation Results

Total deformation results indicate the structural displacement of the joint under applied loading conditions.

The deformation pattern follows the expected bending and load transfer behavior across the dovetail interface.

<img width="500" alt="Total Deformation Result" src="https://github.com/user-attachments/assets/d64fa126-d5af-4f8b-b013-5bae0ef14dc3">

*Figure 5. Total deformation distribution from the ANSYS simulation.*

---

# Model Validation

To verify the accuracy of the finite element model, the deformation trends were compared with simplified analytical predictions based on beam theory.

While analytical solutions cannot fully capture the geometric complexity and contact behavior of the dovetail joint, the overall stress distribution and deformation trends were consistent with theoretical expectations.

This comparison confirmed that the mesh density, material properties, and boundary conditions were appropriately defined.

---

# Skills Demonstrated

- Finite Element Analysis (FEA)
- ANSYS Workbench
- Static Structural Simulation
- Contact Modeling
- Stress and Deformation Interpretation
- Mesh Refinement
- Engineering Validation

---

# Key Takeaways

Through this project, I developed hands-on experience with the full FEA workflow, including:

- Geometry preparation
- Mesh generation
- Boundary condition implementation
- Stress analysis interpretation
- Validation of simulation results

The project demonstrates how finite element methods can be used to evaluate complex joint behavior that would be difficult to analyze using purely analytical methods.
