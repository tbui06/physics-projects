# 🧮 Physics Computational Projects

This repository contains three HTML reports submitted for **PHYS 210: Introduction to Computational Physics** at UBC. Each project explores a different physical system using numerical simulation techniques written in **Python** and rendered from Jupyter Notebook to static HTML format.

---

## 📁 Projects and Reports

1. [**Project 1: Egg Break Threshold in a Rotating Box**](https://tbui06.github.io/physics-projects/project%201.html)  
   Simulates the motion of an egg inside a 2D rotating box to determine the maximum angular velocity (ω) at which the box can spin without breaking the egg. The simulation considers fictitious forces (Coriolis, centrifugal, and friction) in a non-inertial frame and uses elastic collision models to calculate impact forces. A numerical analysis identifies the threshold angular velocity that produces a collision force exceeding the egg’s breaking limit (24.5 N).

2. [**Project 2: Electron Orbit Stability in a Two-Proton System**](https://tbui06.github.io/physics-projects/project%202.html)  
   Simulates the motion of an electron under the Coulomb forces from two fixed protons in 2D space. The electron's initial position and vertical velocity are varied to determine which conditions yield stable orbits. The system is numerically solved using `solve_ivp` and analyzed based on mechanical energy conservation. Results are visualized in both 3D parameter space and individual trajectory plots.

   ### 📊 Sample Results from Project 2

   #### Electron Orbit Stability by Initial Conditions
   <p align="center">
     <img src="images/project2_stability_3Dplot.png" width="500" alt="3D stability plot showing stable vs unstable orbits">
   </p>

   #### Electron Trajectories for Specific Initial Conditions
   <p align="center">
     <img src="images/project2_trajectory_comparison.png" width="500" alt="Trajectory comparison of stable and unstable paths">
   </p>

3. [**Project 3: Critical Volume of Impure ²³⁵U for a Self-Sustaining Nuclear Chain Reaction**](https://tbui06.github.io/physics-projects/project03.html)  
   Simulates a 3D nuclear chain reaction to determine the critical volume of an impure ²³⁵U cube where the third generation of neutrons yields a stable k-factor (k ≈ 1). Using Monte Carlo methods, it models random scattering and fission with spatial probability bias. The resulting k-values are computed over 250 trials, and a critical volume of approximately **0.0393 m³** is found.

   ### 📊 Sample Results from Project 3

   #### Volume vs. k-Factor
   <p align="center">
     <img src="images/project3_kfactor_vs_volume.png" width="500" alt="Graph showing stable volume that yields k ≈ 1">
   </p>

   #### Neutron Motion Validation
   <p align="center">
     <img src="images/project3_neutron_validation.png" width="500" alt="Histograms and 3D neutron positions used for validation">
   </p>

---

## ⚙️ Notes

- All simulations were implemented in **Python**, using:
  - `numpy`, `scipy`, `matplotlib`, and `random`
  - `solve_ivp` for numerical integration in Project 2
- Reports are static HTML exports — interactive widgets (if any) will not function.
- Source code (Python, Jupyter) is **not included in this repo**, only the final reports.
- You may reproduce these simulations by referring to the methods and formulas included in each report.

---

## 👤 Author

**Nam Bui**  
Student, Department of Physics, UBC  
[GitHub Profile →](https://github.com/tbui06)
