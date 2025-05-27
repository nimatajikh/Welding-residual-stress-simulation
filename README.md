# **Welding Residual Stress Simulation**

This repository contains the source code and simulation files used to analyze residual stresses in welded built-up steel box columns, as presented in the associated research paper.

# **Overview**

Welded box-shaped steel columns are commonly used in construction due to their strength, stiffness, and ease of fabrication. However, the welding process introduces residual stresses that can affect structural performance. This study investigates the distribution and magnitude of these stresses in fillet and complete joint penetration (CJP) groove welded corner joints.

A sequential welding simulation approach is used—similar to methods applied in 3D printing simulations—by activating each weld line individually. The shielded metal arc welding process is modeled in Abaqus using DFLUX user-defined subroutines written in Fortran. 

The simulation results are validated against experimental data available in the literature. Findings show that:

Fillet welds result in lower residual stresses than CJP groove welds.

# **Contents**

Code: Fortran DFLUX subroutine used in the Abaqus simulation

Model: Abaqus model input file

README.md: This file

# **Requirements**

Abaqus (tested with version 2024)

Visual Studio 2019

Fortran compiler (Intel oneAPI)

# **License**

This project is shared for academic and research purposes. Please cite the associated paper if you use this work.

Paper: Comparative Numerical Analysis of Residual Stresses in Fillet and CJP Welded Built-Up Steel Box-Shaped Columns

DOI: https://doi.org/10.1061/JSDCCC.SCENG-1665

