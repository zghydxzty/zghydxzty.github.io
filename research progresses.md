---
layout: page
permalink: /research progresses/index.html
title: Research Progresses
---

# Research Progresses

Our research group has been engaged in the numerical simulation of underground multiphase seepage under the condition of multi-physical and chemical fields for a long time, and has developed and applied open source numerical simulation software based on OGS and DUMUX, and is committed to the research of key scientific issues such as seawater intrusion in coastal zones, underground storage of carbon dioxide and shallow geothermal utilization.<br>

#### [① Developed a software system for numerical simulation of multi-field coupled multiphase flow]

Responsible for completing the programming, cloud-based automated testing (Jenkins), and version control and integration (Git) of modules such as thermodynamics, heat flow coupling, fluid-solid coupling, and thermofluid-solid coupling in OGS. Expanded the functionality and application areas of OGS. The developed software and related examples have been officially published by Springer (Kolditz et al., 2016, 2018a, 2018b).

1) Established and applied a coupled algorithm for multiphase flow full-size and dimensional reduction in underground carbon dioxide sequestration
<center>
Due to the long duration and large spatial scale of the carbon dioxide sequestration process, traditional three-dimensional two-phase flow models have low computational efficiency. Dimensional reduction models are often used to improve computational efficiency, but their application is limited by the local heterogeneity of the formation. Based on the IMPES algorithm, a coupled algorithm for multiphase flow full-size and dimensional reduction models was established. The full-size model is used in heterogeneous regions, while the dimensional reduction model is used in homogeneous regions. This coupled algorithm significantly improves computational efficiency compared to the full-size model while ensuring similar computational accuracy.
<center>
<img src="/figures/1.png">
</center>
<br>

2) Established and developed a thermofluid-solid coupling freezing model applied in shallow geothermal development

Based on leading the development of the OpenGeoSys thermofluid-solid coupling module, the constitutive equations for thermofluid-solid coupling under phase change freezing conditions were derived based on continuum solid mechanics and the principle of entropy inequality. Two algorithms, steady-state and dynamic, for simulating phase change freezing were proposed. The thermofluid-solid-ice full coupling calculation module was developed in OGS, successfully predicting changes in temperature and pipe stress in the fluid and surrounding formations in the presence of heat exchangers under low-temperature conditions, thereby improving the accuracy of efficiency calculations for ground-source heat pump systems.
<center>
<img src="/figures/2.png">
</center>
<br>

#### [② Developed the theory of seawater intrusion evaluation and management methodology]

1) Revealed the dynamic mechanism and environmental effects of seawater intrusion control by cutoff walls

By establishing a numerical model that couples solute transport with variable-density flow, the dynamic changes in the coastal groundwater flow field and solute concentration field under different cutoff wall scenarios were systematically elucidated. The effects of cutoff wall structure and aquifer properties on groundwater discharge, freshwater-saltwater distribution, and upstream nitrate enrichment were quantitatively evaluated under tidal and dynamic freshwater boundary conditions. This optimization improved the design and layout of cutoff walls.
<center>
<img src="/figures/3.png">
</center>
<br>

2) Established mechanisms and remediation schemes for purifying underground residual brackish water

A multiscale numerical model of groundwater flow and solute transport at the field scale was established to capture the self-purification behavior of underground residual brackish water. The dynamic mechanism of brackish water purification in aquifers under the influence of cutoff walls was revealed, and the actual timescale of brackish water purification was determined. Remediation schemes such as "natural purification," "pit lake drainage," and "well-lake joint discharge" were proposed and have been successfully applied, achieving good results.
<center>
<img src="/figures/4.png">
</center>
<br>

