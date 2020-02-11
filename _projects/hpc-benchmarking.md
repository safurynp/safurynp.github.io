---
date: 2018-11-01
published: true
title: "High Performance Computing Benchmarking"
description: "Developed a benchmarking framework allowing for exploratory data analysis and data-driven decision making when selecting new HPC platforms and monitoring existing supercomputers"
thumbnail: "/projects/hpc-benchmarking/hpc.png"
disciplines: "Python (numpy, pandas, matplotlib, scikit-learn), C/C++, High Performance Computing, Data Science"
where: Rolls-Royce, High Performance Computing team
when: Jun 2018 - Nov 2018
link:
  button_text:
  url: 
---

High Performance Computing (HPC) at Rolls-Royce underpins the simulation-based design optimisation of the aero engines. The team manages the supercomputers and applications used across the whole business to run Computational Fluid Dynamics and Finite Element Analysis simulations.

My project in the team was to develop automated benchmarking software to verify computational performance of different codes and platforms. The software automated the whole benchmarking process from job setup to data analysis, and enabled detailed investigation of speed, performance, scalability, and physics validity of the simulations. Using developed understanding of HPC and software development, I designed the system architecture and planned for implementation of the project. I then built and tested the sofware, and demonstrated its use by benchmarking Rolls-Royce's existing HPC platforms.

The tools used during the project included Python and its most popular scientific libraries (numpy, pandas, matplotlib, h5py, scikit-learn, bokeh), as well as Message Passing Interface (MPI) - a library of routines used to create parallel programs in C.

{% include image.html url="/projects/hpc-benchmarking/flow.png" description="Diagram showing the functionality of the automated benchmarking framework." %}