---
date: 2017-04-06
published: true
title: "Computer Modelling of Panic Evacuations"
description: "Project to understand and implement an appropriate agent-based model, test its predictive capabilities, investigate a panic evacuation scenario, and propose ideas for preventing fatalities and injuries"
thumbnail: "/projects/panic-evacuation/thumb.png"
disciplines: "C++, Python, Git, Gnuplot, Linux, OpenFOAM, ParaView, LaTeX, Discrete simulations, Agent-based modelling, Verification and validation, Optimisation"
where: University of Edinburgh, MEng Final Project
when: 2016 - 2017
link:
  button_text: Report
  url: "/assets/pdf/modelling_of_panic_evacuations.pdf"
---

The pedestrian dynamics models developed over last 50 years proved useful in understanding the human behaviour during panic evacuations. Simulations became an important tool allowing for better design of infrastructure, and predicting and mitigating dangerous crowd situations. The main objectives of the project were to understand and implement an appropriate agent-based model, test its predictive capabilities, investigate a panic evacuation scenario, and propose ideas for preventing fatalities and injuries. The Helbing social force model was implemented in the OpenFOAM framework using standard C++ scripting. It described the motion of agents as if they would be subject to “social forces” representing their motivations to perform movement.

During the project, I first worked with the highest level of the code where I defined agents’ properties, geometry of the environment, and other parameters necessary to set up simulations. On top of that I learnt enough C++ syntax and OpenFOAM architecture to implement and modify the solver algorithms. Those, for example, included the agent-walls detection and repulsion, or the visibility graph and Dijkstra path finding. I also used Python to process data about borders and visualise them using a Python shell in ParaView.

{% include youtube-player.html id="j2eqtGvMH_s" description="Experiments were developed to test different features of the code (pathfinding above). Verification was also performed by simulating the self-organisation of collective phenomena of pedestrian behaviour like lane formation or arching." %}

{% include youtube-player.html id="Y_hmm9uhZ3s" description="A real evacuation of a classroom during an earthquake in China was used to assess the model authenticity and calibrate the parameters." %}

{% include youtube-player.html id="Tns_BJG25nY" description="An evacuation experiment in a movie theatre was used to further validate the model. The egress times through both the front and rear exits were compared."%}

{% include youtube-player.html id="pw_l12lhWXw" description="The fully calibrated model was used to investigate the evacuation of The Station nightclub where panic tragedy occurred in 2003." %}
