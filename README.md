# Quantum Optimization of EV Charging using QUBO

## Overview
This project demonstrates a quantum-inspired approach to optimizing electric vehicle (EV) charging using QUBO (Quadratic Unconstrained Binary Optimization).

## Problem Statement
In EV charging systems, multiple vehicles share limited power resources. It is necessary to determine which EVs should charge simultaneously while minimizing energy consumption and avoiding overload.

## Approach
Each EV is represented as a binary variable (0 = not charging, 1 = charging).  
All possible charging combinations are evaluated.

## Constraints
- At least 1 EV must charge
- At most 2 EVs can charge simultaneously

## Objective
Minimize total energy consumption of selected EVs.

## Methodology
- Generate all possible EV charging combinations
- Apply constraints to filter valid states
- Compute energy cost for each valid state
- Select the configuration with minimum cost

## Results
The system identifies the optimal charging configuration based on minimum energy usage while satisfying constraints.

## Tools Used
- Python
- Qiskit (conceptual inspiration)
- Google Colab
- Matplotlib

## Key Insight
This project shows how optimization problems in energy systems can be modeled using quantum-inspired techniques such as QUBO.

## Future Scope
- Implement using QAOA (Quantum Approximate Optimization Algorithm)
- Scale to larger EV networks
- Run on real quantum hardware using IBM Quantum Platform

## Author
Sai Venkat  
Electrical and Electronics Engineering  
PVP Siddhartha Institute of Technology
