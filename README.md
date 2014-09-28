timenet
=======

TimeNET implementation for Transforming UML State Machines into Stochastic Petri Nets for Energy Consumption Estimation of Embedded Systems.i

Energy consumption in embedded and mobile systems is of prime concern today. With new and tiny embedded systems like wireless sensors which are bound to do enormous work with as low energy consumption as possible, this non functional property of the systems requires analysis and design.

This project is based on implementation of the idea proposed in "Transforming UML State Machines into Stochastic Petri Nets for Energy Consumption Estimation of Embedded Systems." authored by Dmitriy Shorin, Armin Zimmermann, and Paulo Maciel. As UML (Unified Modeling Language) models are not well-defined semantically for a specification of stochastic processes, this project transforms the UML models into a model for which analysis algorithms exist, specificly into SPNs (Stochastic Petri Nets). 

This project adds capabilities into TimeNET (Timed Net Evaluation Tool) to create Operational & Appliction models corresponding to an embedded system. These models are then transformed into a SPN model for analysis. During analysis, the properties of a state, for instance, the probability, power consumption, paths to other states, etc. are also considered for final computations. The report provides a detailed insight of the design and implementation.

*Due to license rights, the code is not committed to Git.
