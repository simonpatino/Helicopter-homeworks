# Helicopter Dynamics - Assignment 1

## Overview
This repository contains the first assignment for the university course on helicopter fundamentals. The focus of this assignment is to explore and calculate key aspects of induced power in rotor systems, including adjustments for real-world conditions like rotor cut-out and tip losses. The calculations and theoretical explanations are presented in a Jupyter Notebook format.

---

## Assignment Details

**Institution:** Universidad de Antioquia  
**Course Topic:** Helicopters - Fundamentals  
**Assignment Title:** Assignment 1 - Induced Power Calculations  
**Presented by:**  
- Simón Patiño Idárraga  
- Andrés Felipe Muñoz Cabrera  
**Presented to:** PhD. Diego Francisco Hidalgo

---

## Key Objectives
The assignment aims to:
1. Derive the formula for induced power in a rotor system.
2. Analyze the effects of real-world factors such as rotor cut-out and tip losses.
3. Compare ideal and actual power requirements based on specific parameters.

---

## Calculations and Concepts
The notebook includes:
- Theoretical derivations of the induced power equation:
  \[ P = k \cdot \frac{T^{3/2}}{\sqrt{2 \rho A}} \]
  where:
  - \( P \): Induced power
  - \( k \): Power factor considering rotor losses
  - \( T \): Thrust
  - \( \rho \): Air density
  - \( A \): Rotor area
- Derivation of the effective rotor area (\( A_e \)) accounting for:
  - Blade efficiency \( B \)
  - Cut-out percentage
- Comparison of ideal and actual power outputs.

---

## Tools and Resources
- **Programming Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries Used:**
  - NumPy
  - Matplotlib
  - scipy

---


# Helicopter Dynamics - Assignment 2

## Overview
This repository contains the second assignment for the university course on helicopter fundamentals. The focus of this assignment is to explore and integrate rotor blade dynamics, including numerical solutions for dynamic models and blade flapping motion under hover conditions. The calculations and theoretical explanations are presented in a Jupyter Notebook format.


## Key Objectives
The assignment aims to:
1. Analyze the blade dynamics under hover conditions.
2. Derive and solve dynamic equations governing blade flapping motion.
3. Implement numerical solutions for higher-order differential equations.

---

## Calculations and Concepts
The notebook includes:
- Hover condition analysis with zero advance ratio (\( \mu = 0 \)):
  \[ \lambda^2 = \frac{C_T}{2} \]
  where:
  - \( \lambda \): Inflow ratio
  - \( C_T \): Thrust coefficient
- Calculation of induced inflow ratio (\( \lambda_i \)):
  \[ \lambda_i = \frac{v_i}{\Omega R} \]
- Dynamic model describing blade flapping motion:
  \[ I_{b f} \ddot{\beta} + I_{b f} \Omega^2 \beta = M_{L f l a p} \]
  where:
  - \( I_{b f} \): Blade moment of inertia
  - \( \ddot{\beta} \): Blade flapping acceleration
  - \( \Omega \): Rotor angular velocity
  - \( M_{L f l a p} \): Aerodynamic moment
- Transformation of the higher-order equation into a system of first-order differential equations for numerical solutions.

---

## Tools and Resources
- **Programming Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries Used:**
  - NumPy
  - SciPy
  - Matplotlib

---

Acknowledgments
PhD. Diego Francisco Hidalgo: For guidance and support throughout the assignment.


