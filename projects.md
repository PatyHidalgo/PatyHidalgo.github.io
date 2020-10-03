---
layout: page
title: Projects
subtitle: Current, future and past work
---

The REAM lab  has a myriad of projects that analyze renewable energy integration, ranging from long-term planning to real-time operations. The following is a non-exhaustive list of research threads:
* Long-term planning in power systems
* Real-time operations of grids with high penetration of renewable energy
* Development and application of machine learning and AI methods for power systems controller design using safety guarantees from control theory
* Electricity market redesign for the efficient integration of renewable energy
* Distributed energy resources deployment (e.g. to mitigate wildfire risk), operation and tariff schemes designs


### Control of Power Dynamics with Variable and Low Inertia

As more non-synchronous RES participate in power systems, the system's inertia decreases 
and becomes time dependent, challenging the ability of existing control schemes to maintain
frequency stability. System operators, research laboratories, and academic institutes have
expressed the importance to adapt to this new power system paradigm. However, power dynamics
have been modeled as time-invariant, by not modeling the variability in the system's inertia.
To address this, **we propose a new  modeling  framework for power system dynamics to simulate 
a time-varying evolution of rotational inertia** coefficients in a network. Power dynamics are 
modeled as a hybrid system with discrete modes representing different rotational inertia regimes
 of the network.

Using this new hybrid model for power dynamics, we present a framework to design a fixed 
learned controller based on datasets of optimal time-varying LQR controllers. We test the 
performance of the controller in a twelve-bus system. By adding virtual inertia we can 
guarantee stability of high-renewable (low-inertia) modes. The novelty of our work is to 
propose a design framework for a stable controller with fixed gains for time-varying power 
dynamics. This is relevant because it would be simpler to implement a proportional controller 
with fixed gains compared to a time-varying control. To expand this work, we introduce a framework 
to learn sparse time-invariant frequency controllers in a power system network with a time-varying 
evolution of rotational inertia. We design a controller that uses as features the system’s states. 
In other words, we design a control proportional to the angles and frequencies. Virtual inertia 
is included in the controllers to ensure stability. One of the findings is that it is possible 
to restrict communication between the nodes by reducing the number of features in the controller 
(from 22 to 10 in our case study) without disrupting performance  and  stability. Furthermore, 
once communication between nodes has reached a threshold, increasing it beyond this threshold 
does not improve performance or stability. There is a correlation between optimal feature 
selection in sparse controllers and the topology of the network.


### Zero Emissions in the Western North American Grid

description
figure

### Stochastic Long-term Power System Planning in Western North America under Climate Change

Typical electricity-grid capacity expansion models make investment decisions with fixed inputs (e.g., 
fixed electricity demands and hydro-power availability). The resultant electricity supply system may 
not be robust to future climate change-driven uncertainties in energy demand and supply. **We present the first 
climate change stochastic long-term (2050) capacity expansion and operation electricity grid model for the 
Western North America electricity region**, with high temporal and spatial resolution. The Stochastic SWITCH 
WECC model generates a least cost portfolio of power plants that is robust to varying future climate 
conditions using a multi-stage optimization approach with varying electricity-demand and hydropower-availability 
inputs under three climate change scenarios. Results show that an optimal robust electricity supply portfolio 
in the WECC for 2050 has about 4% higher overall installed capacity than the average mix of the three 
scenarios modeled separately, and about 5.6% higher installed gas capacity, due to the greater need for 
operational flexibility under the wider range of possible conditions.


### Modeling of Long-Duration Storage for Decarbonization of California and the Western US Energy System 

The challenge is to meet all of California’s and Western US' clean-energy goals with low cost solutions. 
Low-cost solar and wind electricity are a partial solution, but the public would also like low-cost 
electricity when solar and wind electricity are not available (at night and/or on calm days). 
While many technologies show promise to provide the needed storage and/or demand management, 
none is established in a way that gives confidence or that elucidates how a zero-carbon electricity grid will function.

Modeling of the Western US electricity grid requires thousands of assumptions and the 
assumptions can vary widely. The state of California can implement time of use rates or 
demand management programs that can help to shift load to times when renewable electricity 
is available. These actions have the potential to greatly accelerate the adoption of new 
storage technologies for different durations if they are well planned. **Our challenge is 
to develop and implement mathematical methods to operate and optimize the capacity expansion 
of the grid, and with this framework, study the roles and cost targets of long-duration 
storage technologies**. 

### Wave Energy Technology Assessment for Optimal Grid Integration and Blue Economy Advancement


The marine energy potential in the United States is twice the current total national electricity
 consumption. Until recently, it has been cost prohibitive to take advantage of this tremendous 
 resource. Dramatic cost reductions are now taking place with a diverse suite of technology 
 options, and significant further reductions are possible through technological learning and
  by co-locating wave energy with other blue economy markets, specifically offshore wind, 
  seawater desalination, and aquaculture. By quantifying the benefits of co-location before 
  the build-out of these assets, the technical, regulatory, and economic opportunities can 
  be maximized. We propose **the first in-depth national study of the techno-economic performance of 
  wave and combined wind-wave farms for utility-scale grid connection and powering blue economy 
  industries**, such as seawater desalination. This analysis has the potential to guide wave 
  technology designs, stimulate the marine energy markets, and disrupt the national energy landscape.

### Learning to Control in Power Systems: Design and Analysis Guidelines for Concrete Safety Problems


Rapid progress in machine learning and artificial intelligence (AI) has brought renewed 
attention to its applicability in power systems for modern forms of control that help 
integrate higher levels of renewable generation and address increasing levels of uncertainty 
and variability. In this work we discuss these new applications and shine light on the most 
relevant new safety risks and considerations that emerge when relying on learning for control 
purposes in electric grid operations. We build on recent taxonomical work in AI safety and 
focus on four concrete safety problems. We draw on two case studies, one in frequency regulation 
and one in distribution system control, to exemplify these problems and show mitigating measures. 
We then **provide general guidelines and literature to help people working on integrating learning 
capabilities for control purposes to make safety risks a central tenet of design**.





### Wildfire Risk Mitigation and Power Systems Resilience

Electricity market design to allow the participation of distributed energy resources (DER) 
and microgrids in the market (TSO-DSO coordination). **The objective of this work is to design
 an effective scheme to aid the penetration of DER independently and within microgrids, while 
 at the same time ensuring reliability in the events of wildfire**. 
 
 
 ### Electricity Market and Ancillary Services Redesign
 
 As more renewable energy participates in power systems, the markets and requirements that govern its operation
 require to be modernized to be able to operate efficiently and reliably in this new setting. This projects aims to design
 new ancillary services that use state of the art mathematical methods (machine learning, reinforcement learning, 
 control theory, optimization) to guarantee  safe and reliable system's operation.
 
 
 
 
 
 