---
layout: project
title: 3270 Project
description: Torque Wrench Design
technologies: [MATLAB, Fusion360, ANSYS]
image: /assets/images/Materials.JPG
---


[Click here to view the Final Report]({{ "/assets/3270Final.pdf" | relative_url }})

Images of CAD Model:

Describe material used and its relevant mechanical properties

Our final design uses High Alloy Steel, AerMet 100 (solution treated and aged). This material was chosen because it is both strong and durable and allows the handle dimensions to be reduced for higher strain sensitivity while obtaining all required safety factors. Its mechanical properties are: Young’s modulus = 28 x 10^6 psi, Poisson’s ratio = 0.30, yield/tensile strength = 235 ksi, fracture toughness = 91,000 psi√(in), and fatigue strength at 10^6 cycles = 135 ksi. These properties ensure that the design meets and exceeds the requirements for yield, fracture, and fatigue safety margins. 

Diagram communicating how loads and boundary conditions were applied to your FEM model.

In Ansys mechanical, the boundary conditions and loads can be applied in the static structural tab. Figure 1 shows the streamline process of adding the clamped boundary condition by hiding the fillet body, selecting the faces of the drive, and adding a displacement boundary of 0 at each face for each direction. Figure 2 shows the process of adding the load given 600 lb-in torque at the end of the handle. Note hat the applied load is 600/8 = 75 lbf.

