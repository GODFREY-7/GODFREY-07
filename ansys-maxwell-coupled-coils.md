# Coupled-Coil Electromagnetic Simulation — ANSYS Maxwell 3D

## Overview

This project documents my experience using **ANSYS Maxwell 3D** to model and analyze electromagnetic coupling between coil systems as part of faculty-guided engineering work.

The purpose of this public repository is to demonstrate the **simulation workflow, engineering reasoning, troubleshooting process, and technical skills I developed**.

Specific research geometry, proprietary parameters, unpublished datasets, and other potentially sensitive details are intentionally omitted.

---

## What I Worked On

My work involved:

* Creating and modifying 3D electromagnetic geometry
* Assigning materials and conductor properties
* Defining windings and coil terminals
* Configuring electromagnetic excitations
* Applying mesh settings and simulation boundaries
* Running magnetostatic/electromagnetic analyses
* Evaluating magnetic-field behavior at different coil separations
* Troubleshooting simulation setup and solver errors
* Interpreting simulation outputs and field visualizations
* Documenting the workflow so the analysis could be reproduced

---

## Engineering Workflow

The general workflow was:

**Geometry → Materials → Windings → Excitations → Mesh → Boundaries → Solve → Post-process → Compare Results**

One of the most useful parts of the project was learning that successful simulation depends heavily on the **quality of the physical setup and boundary conditions**, not simply pressing the solve button.

---

## Problems I Had to Solve

During the project I encountered several practical issues, including:

* Distinguishing between **coil terminals and windings**
* Correctly assigning conductor properties
* Resolving excitation setup errors
* Fixing conductor-count and resistance-related solver warnings
* Understanding differences between geometry-selection and excitation-selection workflows
* Configuring post-processing reports correctly
* Determining which magnetic-field quantities were meaningful for comparison

Working through these issues helped me become much more comfortable diagnosing engineering simulation problems rather than treating the software as a black box.

---

## Analysis

The simulation was used to investigate how electromagnetic coupling changes when the relative position and separation of the coils are changed.

The results showed the expected reduction in magnetic-field interaction as separation increased.

Exact experimental geometry and research-specific numerical parameters are intentionally excluded from this public version.

---

## Tools

* **ANSYS Electronics Desktop**
* **ANSYS Maxwell 3D**
* Electromagnetic field visualization
* 3D CAD-style geometry construction
* Engineering data analysis

---

## What I Learned

This project improved my understanding of:

* Electromagnetic field simulation
* Coil and winding modeling
* Magnetic-field behavior
* Simulation boundary conditions
* Meshing
* Solver configuration
* Engineering troubleshooting
* Technical documentation

More importantly, I learned how to move from:

**“The simulation is not working”**

to:

**identify the physical assumption → inspect the model setup → isolate the error → correct it → validate the result.**

That troubleshooting process is one of the skills I want to continue developing across engineering projects.

---

## Research Confidentiality

This repository represents a **public portfolio summary of my individual technical experience**.
<img width="1252" height="777" alt="Rx 5mm separation true" src="https://github.com/user-attachments/assets/5d74c6fb-55ad-43c4-9fa1-373c9a47fd5c" />


It does not contain confidential research information, unpublished intellectual property, proprietary geometry, complete experimental datasets, or materials that belong to collaborators or faculty researchers.

Additional technical details can be discussed where appropriate.

