
# Branch Flow Based Distribution System Optimization Models

This directory contains branch flow based optimization models for distribution system optimal power flow (DOPF).

## Implemented Models

### 1. Nonlinear AC DOPF
Full nonlinear unbalanced AC optimal power flow formulation using branch flow equations.

### 2. Second Order Cone Programming (SOCP) AC DOPF
Convex relaxation of AC DOPF using second-order cone constraints.

### 3. Semidefinite Programming (SDP) AC DOPF
Convex relaxation using semidefinite matrix formulations.

### 4. Linearized LinDist3Flow AC DOPF
Linear approximation of three-phase distribution feeder power flow for computationally efficient optimization.

## Requirements

- Python
- Pyomo
- IPOPT
- IDAES
- NumPy
- Pandas
- HIGHS
- SCS
