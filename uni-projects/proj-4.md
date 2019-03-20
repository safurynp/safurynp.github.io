---
layout: page
title: 'Vertical Axis Wind Turbine'
---

One of my design projects at the University of Pennsylvania involved designing and bulding a vertical axis wind turbine to generate electical power. Because of vagaries of the wind, the final wind turbine was tested indoors using human power (running). We worked in a team of 3 and the goal was to maximize electrical power generation. The design process involved several steps including: predicting turbine performance by testing  a small-scale model, designing a transmission between the turbine and DC motor used as a generator and selecting appropriate electrical load (resistor) to which the power was delivered.

First of all, we had to decide whether we will build a drag-based Savonius or a lift-based Darrieus wind turbine. The differences in the design between the two theoretically make the Darrieus wind turbine more difficult to manufacture but also capable of generating more power. Hence, as maximizing power generation was the goal and because it seemed more fun and challenging, we decided to build a lift-based turbine.

# Small-scale testing
Before full-scale construction, a series of wind tunnel tests were performed. We tested 4 different Darriues and 2 Savonius turbines which were made out of cardboard, lasercut parts or 3D printed parts. We then nondimensionalised the data to make predictions of the aerodynamic characteristics and energy generation of the full-scale device. The data helped us compare different designs and find an optimal gear ratio and electic load to maximize the power generated in a DC motor used as a generator.

{% include respframe.html id="lQjyqbgQux8" %}

# Full-scale design and manufacturing
The most effective design was picked for full-scale manufacturing. It was a three-blade Darrieus with NACA0021 airfoil. The turbine was built from a variety of different parts which included: laser-cut balsa and MDF wing profiles, aluminium bars and cardboard tubes, 3D printed connections and MonoKote coating of the airfoils. As it can be seen in the video on the right, the wind turbine outdoor test was a success.

![]({{ site.url }}/assets/img/uni-projects/proj-4/img1.jpg)  |  ![]({{ site.url }}/assets/img/uni-projects/proj-4/img2.jpg) | ![]({{ site.url }}/assets/img/uni-projects/proj-4/img3.jpg)  
 
{% include respframe.html id="mYG0ju5gSm4" %}

# Gearbox sizing and DC motor analysis
Next, the DC motor used as a generator had to be characterised and optimum gear ratio and electrical load had to be chosen to minimize energy losses in converting mechanical energy into electrical energy. No-load current, speed, emf and torque constants of the motor were found experimentally and then MATLAB software was used find the optimum external resistance and rotational speed. A successful final demonstration was then delivered!