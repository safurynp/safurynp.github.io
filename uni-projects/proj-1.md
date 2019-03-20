---
layout: page
title: 'Computer Modelling of Panic Evacuations'
---

[Report PDF]({{ site.url }}/assets/pdf/modelling_of_panic_evacuations.pdf)

The pedestrian dynamics models developed over last 50 years proved useful in understanding the human behaviour during panic evacuations. Simulations became an important tool allowing for better design of infrastructure, and predicting and mitigating dangerous crowd situations. The main objectives of the project were to understand and implement an appropriate agent-based model, test its predictive capabilities, investigate a panic evacuation scenario, and propose ideas for preventing fatalities and injuries. The Helbing social force model was implemented in the OpenFOAM framework using standard C++ scripting. It described the motion of agents as if they would be subject to “social forces” representing their motivations to perform movement.

First of all, I worked with the highest level of the code where I defined agents’ properties, geometry of the environment, and other parameters necessary to set up simulations. On top of that I learnt enough C++ syntax and OpenFOAM architecture to implement and modify the solver algorithms. Those, for example, included the agent-walls detection and repulsion, or the visibility graph and Dijkstra path finding. I also used Python to process data about borders and visualise them using a Python shell in ParaView.

# Verification
After implementing the physical models, a series of experiments was developed to test different features of the code like agent-agent and agent-walls interactions, fluctuation forces or path finding methods (set of local goals and visibility graph with Dijkstra's algorithm). The verification was also performed by simulating the self-organisation of collective phenomena of pedestrian behaviour like lane formation or arching.

{% include respframe.html id="j2eqtGvMH_s" %}

# Validation
Validation procedure was needed to assess the model authenticity and calibrate the parameters used in the simulations. The goal was to evaluate the quality of the model and determine the degree to which it is an accurate representation of the real world.​

A real evacuation of a classroom during an earthquake in China was used as the first validation case. Total evacuation times were compared.

{% include respframe.html id="Y_hmm9uhZ3s" %}

An evacuation experiment in a movie theatre was used to further validate the model. The egress times through both the front and rear exits were compared.

{% include respframe.html id="Tns_BJG25nY" %}

# Final Simulations
The fully calibrated model was used to investigate the evacuation of The Station nightclub where panic tragedy occurred in 2003. Simulations were run to identify the main bottlenecks and analyse the effect of geometry modifications on the outflow of people.​

{% include respframe.html id="pw_l12lhWXw" %}