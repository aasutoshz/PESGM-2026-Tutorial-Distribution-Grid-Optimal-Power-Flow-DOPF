## Distribution-Grid-Optimal-Power-Flow-DOPF-Model
A comprehensive collection of Distribution Optimal Power Flow (DOPF) models for active distribution networks based on the branch-flow formulation. This repository provides mathematical formulations and optimization frameworks for the unbalanced distribution systems with distributed energy resources (DERs).

The repository includes implementations of nonlinear programming (NLP), second-order cone programming (SOCP), semidefinite programming (SDP), and linear powerflow model (Lindist3flow) for solving multiphase optimal power flow problems. Application for loss minimization and volatge deviation is demonstrated but the problem formulation can be extended to use for various objective problem formulations.

## Features

- Branch-flow-based DOPF formulations for radial distribution networks
- Multiphase unbalanced power flow modeling
- NLP, SOCP, and SDP optimization models
- IEEE test feeder implementations and case studies
- Convex relaxation and approximation techniques for scalable optimization


## Contributors
This repository contains Python-based optimization models and distribution network test feeders developed through the contributions of:\
Aashutosh Neupane- Florida International University, USA


This Python code was derived from the MATLAB code , tested on the first 20 nodes of the IEEE 123 Node Test Feeder. The contributors of the MATLAB code are:
Sumit Paudyal, Florida International University (FIU), USA\
Anamika Dubey, Washignton State University (WSU), USA\
Sukumar Kamalasadan, University of North Carolina at Charlotte (UNCC), USA

## Citation

If you use this code, model, or any part of this repository in your research, publications, reports, or derivative works, please cite this repository and acknowledge the author.

> A. Neupane, S. Paudyal and O. Ceylan, "Dynamic Droop Setting of Smart Inverters for Volt-VAr Control in Active Distribution Grids," *2025 IEEE Power & Energy Society General Meeting (PESGM)*, Austin, TX, USA, 2025, pp. 1–5.  
> DOI: https://doi.org/10.1109/PESGM52009.2025.11225698

>A. Neupane and S. Paudyal, "Dynamic Droop Setting of Smart Inverters in Active Distribution Grid Using Neural Networks," 2024 56th North American Power Symposium (NAPS), El Paso, TX, USA, 2024, pp. 1-6.
> DOI: https://doi.org/10.1109/NAPS61145.2024.10741718. 






