---
layout: project
title: MAE 4272 Blade Design Project
description: Wind Turbine Blade Design and Testing
technologies: [MATLAB, LabVIEW]
image: /assets/images/turbine-image.png
---


The objective of the project was to design a small-scale wind turbine optimized for power generation under specific operating conditions. The blade needed to satisfy geometric and structural constraints while maximizing power output across of range of wind speeds characterized by a Weibull distribution. 

During the design process, we utilized blade element theory and looked to maintain a constant angle of attack throughout the span. We assumed no wake rotation, no tip losses, and no drag. Our design process was an iterative loop in MATLAB. We started with an initial RPM and blade geometry would be generated using optimum blade equations. For each design, blade element momentum theory was used to calculate aerodynamic forces and power output. Structural constraints were enforced. The process was repeated over many RPM values, and the design which produced the highest expected power output was selected. 

![Photo of design in CAD]({{ "/assets/images/blade-image.png" | relative_url }}){: .inline-image-l}

During the testing process, we tested our blade across a range of wind velocities in the wind tunnel corresponding to fan frequencies between 6-10 Hz. For each wind condition, the turbine was oriented into the flow and a torque brake was increased incrementally until stall. At each increment, RPM and power output were recorded. This procedure was repeated for all wind speeds, and power vs RPM curves were generated to evaluate performance trends. 

![Graph of power vs RPM obtained from testing]({{ "/assets/images/rpm-graph.png" | relative_url }}){: .inline-image-l}

I worked on aspects of the design and testing procedures throughout the project. I developed the methodology for experimental testing for the wind turbine. 

