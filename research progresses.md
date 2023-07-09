---
layout: page
permalink: /research progresses/index.html
title: Research Progresses
---

# Research Progresses

Our research group has been engaged in the numerical simulation of underground multiphase seepage under the condition of multi-physical and chemical fields for a long time, and has developed and applied open source numerical simulation software based on OGS and DUMUX, and is committed to the research of key scientific issues such as seawater intrusion in coastal zones, underground storage of carbon dioxide and shallow geothermal utilization.<br>

#### [① A software system for numerical simulation of multi-field coupled multiphase flow is developed](https://fzuiot.site/)

Responsible for the completion of OGS thermal, heat flow coupling, fluid-structure coupling, thermal fluid-structure coupling and other modules of the program writing, calculation examples of cloud automatic testing (Jenkens) and version control and fusion (Git) research work, expanded the function and application field of OGS. The developed software and associated examples have been published by Springer (Kolditz et al. 2016, 2011A, 2018b).
1) The coupling algorithm of full-size and dimensionality reduction of multiphase flow is established and applied to the underground storage of carbon dioxide
In view of the long duration and large spatial scale of carbon dioxide storage process, the traditional 3D two-phase flow model is very inefficient, so dimension reduction model is often used to improve the computational efficiency. However, the local heterogeneity of strata limits the application of dimension reduction model. Based on the IMPES algorithm, a coupling algorithm of the full-size model and dimensionality reduction model of multiphase flow is established. The full-size model is used in the heterogeneous region, and the dimensionality reduction model is used in the homogeneous region. Compared with the full-size model, this coupling algorithm can greatly improve the computational efficiency and ensure similar computational accuracy.

<center>
<img src="/figures/1.png">
</center>

2) The heat-fluid-solid coupling icing model was established and developed and applied in shallow geothermal development
On the basis of leading the development of OpenGeoSys thermo-fluid-solid coupling module, based on the principle of solid mechanics and entropy inequality of continuum, the thermo-fluid-solid coupling constitutive equation under the condition of phase-change icing is derived, and two algorithms for simulating phase-change icing are proposed, both steady-state and dynamic, and a fully coupled calculation module for thermo-fluid-solid icing is developed in OGS. The temperature change of the fluid in the heat exchange tube and the surrounding strata and the force change of the pipe are predicted successfully, and the accuracy of the efficiency calculation of the ground source heat pump system is improved.

<center>
<img src="/figures/2.png">
</center>

<br>

#### [② The assessment theory and treatment method of seawater intrusion are developed](https://caihanlin.com/mypaper/modeling/202302COMAP.pdf)

1) The dynamic mechanism and environmental effects of seepage containment wall on preventing seawater intrusion were revealed
By establishing a numerical model of seawater intrusion of solute transport coupled with variable density flow, the dynamic change characteristics of coastal groundwater flow field and solute concentration field under different seepage interception projects were systematically clarified, and the effects of seepage interception wall structure and aquifer properties on groundwater bottom discharge, brachy-water distribution and upstream nitrate enrichment under tidal and dynamic freshwater boundary conditions were quantitatively evaluated. The structure and layout of the seepage interception wall are optimized.

<center>
<img src="/figuress/3.png">
</center>

2) The purification mechanism and treatment plan of underground residual salt water have been established
A multi-scale numerical model of groundwater seepage and solute transport at the field scale was established to capture the automatic purification behavior of subsurface residual brackish water, reveal the dynamic mechanism of the purification of residual brackish water in aquifers under the action of seepage cutting engineering, clarify the real time scale of brackish water purification, and put forward such brackish water treatment schemes as "natural purification", "drainage of pit lake" and "combined drainage of well and lake". Good application effect has been obtained.

<center>
<img src="/figures/4.png">
</center>

<br>

