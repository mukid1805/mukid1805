# Mukid Valsangkar
**Aerospace & Mechanical Engineer | Astrodynamics, Structural Dynamics & Space Autonomy**  
Cranfield University, United Kingdom  


[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/mukid-valsangkar)
[![ORCID](https://img.shields.io/badge/ORCID-A6CE39?style=flat-square&logo=orcid&logoColor=white)](https://orcid.org/0009-0007-8845-1605)
[![ResearchGate](https://img.shields.io/badge/ResearchGate-00CCBB?style=flat-square&logo=researchgate&logoColor=white)](https://www.researchgate.net/profile/Mukid-Valsangkar)

<!-- 
#[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=google-scholar&logoColor=white)](https://scholar.google.com)
-->
---

## Profile Summary

Aerospace Engineer with an MSc in Astronautics and Space Engineering (Distinction) and a foundational degree in Mechanical Engineering. Specializes in high-fidelity orbital propagation, non-linear structural dynamics, space propulsion hardware design, and autonomous multi-agent exploration systems. Experienced across computational modeling, finite element analysis (FEA), hands-on Assembly, Integration, and Testing (AIT), and concurrent engineering. Co-author of peer-reviewed space robotics research presented at IAC and ESA ASTRA.

---

## Technical Competencies

* **Programming & Computation:** Python, MATLAB, C, Linux, Git / GitHub CI/CD
* **Astrodynamics & Mission Design:** Orbital Perturbation Superposition ($J_2$ – $J_4$, SRP, Drag, Three-Body), Lambert Targeting, CR3BP Dynamics, Systems Tool Kit (STK), ESATAN-TMS, ESA COMET
* **Structural Mechanics & FEA:** ANSYS (Mechanical, APDL, Workbench, Thermal), Altair OptiStruct, Euler–Bernoulli Beam Theory, Newmark - $\beta$ Integration, Duffing Oscillators, Modal & Dynamic Analysis
* **CAD, Mechanical Design & AIT:** SolidWorks, CATIA, NX-CAD (Unigraphics), Autodesk Inventor, AutoCAD, GD&T, DFMA, Ground Hot-Fire Testing, Pressure & Leak Checks
* **Robotics, Vision & Autonomy:** Multi-Agent Task Allocation, $A^*$ Path Planning, YOLOv11x Object Detection, Embedded Systems (Raspberry Pi 4B, Arduino Uno)

---

## Featured Repositories

### [NewtonianPropagator: Multi-Body Orbital Dynamics & Swarm Simulation Engine](https://github.com/mukid1805/NewtonianPropagator)
*Python, Numerical Methods, Astrodynamics, Automated CI/CD*
* Modular 6-DOF/7-DOF numerical propagation engine with full environmental perturbation superposition ($J_2$ – $J_4$ geopotential harmonics, diurnal atmospheric drag, cannonball SRP with cylindrical umbra transitions, and third-body lunar gravity).
* Interplanetary trajectory module including Universal Variable Lambert targeting, automated Porkchop plot generation, and 3D calendar grid-search optimization for multi-leg gravity assists ($\Delta v$ deficit and hyperbolic turning angle matching).
* Circular Restricted Three-Body Problem (CR3BP) Earth-Moon synodic dynamics, collinear/triangular Lagrange point root-solvers, and Jacobi integral conservation tracking.
* Local-Vertical Local-Horizontal (LVLH / Hill's) frame coordinate transformations for multi-satellite swarm relative motion, with continuous low-thrust mass-depletion integration.

## Engineering Projects & Technical Research

### Simulation of Flexible, Large-Scale Space Structures
*Master's Thesis | Cranfield University | MATLAB, ANSYS Mechanical, Systems Tool Kit (STK)*
* Formulated an analytical and numerical simulation pipeline to characterize the non-linear vibrational response of Very Large Space Structures (VLSS) under gravity-gradient orbital excitations.
* Implemented Newmark - $\beta$ time-domain numerical integration coupled with a cubic stiffness Duffing oscillator model, capturing amplitude-dependent frequency shifts and jump resonance phenomena in slender beams ($>600\text{ m}$).
* Identified a critical orbital resonance condition at the second orbital harmonic ($\omega_n / \omega_0 \approx 2$) for beam lengths of $\sim 653\text{ m}$, proving the divergence and limits of classical linear Euler–Bernoulli formulations under resonant dynamic amplification.
* Validated the analytical reduced-order model against high-fidelity ANSYS FEA simulations, achieving $<1\%$ deviation in non-resonant regimes.

### Hybrid Rocket Engine Design & AIT (Race2Space 2025)
*Design Lead | CranSEDS | SolidWorks, ANSYS Workbench, Altair OptiStruct, MATLAB, Python*
* Led the mechanical and thermal design of a $2\text{ kN}$ flight-scale hybrid rocket motor assembly ($\text{HDPE} / \text{N}_2\text{O}$), delivering complete 3D CAD architectures, manufacturing drawings, and structural load-path layouts.
* Engineered the combustion chamber, converging-diverging nozzle, oxidiser tank, and internal structural bulkheads, reducing total structural mass by 46% via topology and structural optimization.
* Executed non-linear static, modal, and transient thermal FEA in ANSYS to confirm structural margins of safety under operational chamber pressures and thermal gradients.
* Directed hands-on Assembly, Integration, and Testing (AIT) campaigns, including hydrostatic proof testing, cold-flow leak checks, mechanical fit verification, and ground hot-fire test data acquisition using custom Python analytics pipelines.

### Autonomous Multi-Agent Task Allocation & Vision-Based Path Planning
*Payload Systems Engineer (CORE Project) | Cranfield University | Python, YOLOv11x, Raspberry Pi 4B*
* Architected a decentralized mission and task allocation framework for heterogeneous rovers (wheeled and quadruped platforms) operating in simulated extreme lunar environments.
* Deployed an embedded, fine-tuned YOLOv11x object detection pipeline on Raspberry Pi 4B hardware for real-time hazard classification and dynamic obstacle matrix generation.
* Formulated an $8$-connected $A^*$ path-planning algorithm incorporating Manhattan heuristics, rover footprint clearance margins, and terrain-specific mobility constraints.
* Validated operational viability across real-time testbed trials, translating mission-level goals into executable waypoint and heading arrays; co-authored papers accepted at IAC-25 and ESA ASTRA 2025.

### Spacecraft Thermal Control System Design (ESA Concurrent Engineering Challenge 2025)
*Thermal Subsystem Engineer | Cranfield University & European Space Agency | ESATAN-TMS, ANSYS Thermal, MATLAB, ESA COMET*
* Designed the Thermal Control System (TCS) for a 7-year comet sample return mission traversing deep-space environments from Venus flyby ($0.72\text{ AU}$) to Jupiter gravity assist ($5.5\text{ AU}$).
* Built spacecraft nodal thermal models in ESATAN-TMS, establishing transient thermal balances across worst-case hot/cold solar flux, planetary albedo, and internal subsystem dissipations.
* Calculated trajectory-dependent radiative heat fluxes in MATLAB and performed multi-layer insulation (MLI), optical solar reflector (OSR) coating, and radiator sizing trades via ESA's COMET concurrent engineering tool.

### Parametric CAD Architecture & Automated FEA Optimization Pipeline
*Shivaji University | SolidWorks API, ANSYS Mechanical, Python, Operations Research*
* Created a computational framework coupling SolidWorks parametric modeling, ANSYS Mechanical APDL, and Python numerical solvers to automate geometry regeneration and batch FEA execution.
* Implemented constrained numerical optimization algorithms from Operations Research to iterate over high-dimensional design spaces, optimizing mechanical stiffness-to-weight ratios under strict stress and displacement boundaries.

---

## Academic Publications & Conference Proceedings

* **IAC-25:** Bonet Garcia, G., **Valsangkar, M.**, et al. (2025). *"Technology Demonstration of a Cooperative Heterogeneous Robotic System for Planetary Terrain Exploration."* 76th International Astronautical Congress (IAC), D1: IAF Space Systems Symposium, Interactive Presentation.  
  [![DOI](https://img.shields.io/badge/DOI-181717?style=flat-square&logo=doi&logoColor=white)](https://doi.org/10.52202/083091-0083)
  [![Proceedings](https://img.shields.io/badge/IAF-Summary-181717?style=flat-square)](https://iafastro.directory/iac/paper/id/99824/summary/)

* **ESA ASTRA:** Zhang, Z., **Valsangkar, M.**, et al. (2025). *"Cooperative Heterogeneous Robotic System for Lunar South Pole Mapping and Exploration."* 18th Symposium on Advanced Space Technologies in Robotics and Automation (ESA ASTRA 2025).  
  [![PDF](https://img.shields.io/badge/PDF-181717?style=flat-square&logo=adobeacrobatreader&logoColor=white)](https://roboshare.esa.int/ASTRA/Astra2025/2025Papers/055_Zhang_Cooperative-Heterogeneous-Robotic-System-For-Lunar-South-Pole-Mapping-And-Exploration.pdf)

* **IJERA:** **Valsangkar, M.** and Pandit, H. (2024). *"Experimental Investigations of Yield Enhancement of Solanum tuberosum Using LED Lighting and Controlled Environment."* International Journal of Engineering Research and Applications, 14(4), pp. 185–192.  
  [![PDF](https://img.shields.io/badge/PDF-181717?style=flat-square&logo=adobeacrobatreader&logoColor=white)](https://www.ijera.com/papers/vol14no4/1404185192.pdf)
---
