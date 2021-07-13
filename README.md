# Sniffy Bug: A fully autonomous swarm of gas-seeking nano quadcopters in cluttered environments

![](figures/sniffygif.gif)


Nano quadcopters are ideal for gas source localization (GSL) as they are safe, agile and inexpensive. However, their
extremely restricted sensors and computational resources make
GSL a daunting challenge. In this work, we propose a novel bug
algorithm named ‘Sniffy Bug’, which allows a fully autonomous
swarm of gas-seeking nano quadcopters to localize a gas source in
an unknown, cluttered and GPS-denied environments. The computationally efficient, mapless algorithm foresees in the avoidance
of obstacles and other swarm members, while pursuing desired
waypoints. The waypoints are first set for exploration, and, when
a single swarm member has sensed the gas, by a particle swarm
optimization-based procedure. We evolve all the parameters of
the bug (and PSO) algorithm, using our novel simulation pipeline,
‘AutoGDM’. It builds on and expands open source tools in order
to enable fully automated end-to-end environment generation and
gas dispersion modeling, allowing for learning in simulation.
Flight tests show that Sniffy Bug with evolved parameters
outperforms manually selected parameters in cluttered, realworld environments. 

# Content

This repository contains the following:
- sniffybug-firmware: the firmware used to run experiments onboard the BitCraze CrazyFlie 2.1.
- sniffybug-swarmulator: a fork of swarmulator, a lightweight c++ robot simulator. This version of swarmulator allows for testing gas source localization algorithms in a variety of environments.
- AutoGDM: coming soon!
- CrazyFlie gas deck PCB files: coming soon!

# Links
- arXiv: https://arxiv.org/abs/2107.05490
- videos: https://bit.ly/37MmtdL

This repository is a work in progress, more documentation will be added soon.
Please reach out if you have any questions or ideas, you can reach us at: b.p.duisterhof@gmail.com or g.c.h.e.decroon@tudelft.nl 


