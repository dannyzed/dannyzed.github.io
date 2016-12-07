---
layout: page
title: Research
permalink: /research/
---
The primary focus of my research is in the fields of atmospheric radiative transfer and remote sensing.

The bulk of my PhD thesis work has been devoted to developing better techniques to retrieve trace species in the atmosphere (such as ozone) from limb scattered sunlight.
To help with this task, I wrote the [SASKTRAN-HR](https://doi.org/10.5194/amt-8-2609-2015) radiative transfer model, which is a set of `C++` libraries designed to accurately model radiative transfer in the Earth's atmosphere.
The model focuses on the ultraviolet, visible, and near infrared spectral regions where radiative transfer is challenging due to the large amount of scattering in the atmosphere.
SASKTRAN-HR is unique in the fact that it is able to handle fine scale spatial structures while maintaining reasonable speed.

The second part of my project deals with the inverse problem; given we have measurements of how bright the atmosphere is, how can we determine the amount of a trace species such as ozone?
In particular I am interested in analyzing the accuracy of current retrieval methods, and creating new ones which are better suited for finding fine scale structures.
Here I have developed a retrieval package written primarily in Python which uses the SASKTRAN-HR radiative transfer model to answer this question.
We are currently using the software to obtain higher resolution ozone profiles from the NASA satellite instrument the [Ozone Mapping and Profiler Suite Limb Profiler](https://ozoneaq.gsfc.nasa.gov/omps).


# Publications

Elash, B. J., Bourassa, A. E, Rieger, L. A, Dueck, S. R., Zawada, D. J., and Degenstein, D. A.: The sensitivity to polarization in stratospheric aerosol retrievals from limb scattered sunlight measurements, J. Quant. Spectrosc. Radiat. Transfer, 189, 75-85, http://dx.doi.org/10.1016/j.jqsrt.2016.11.014, 2017.

Zawada, D. J., Dueck, S. R., Rieger, L. A., Bourassa, A. E., Lloyd, N. D., and Degenstein, D. A.: High-resolution and Monte Carlo additions to the SASKTRAN radiative transfer model, Atmos. Meas. Tech., 8, 2609-2623, https://doi.org/10.5194/amt-8-2609-2015, 2015.

Cheviakov, A. F., Zawada, D. J.: Narrow-escape problem for the unit sphere: Homogenization limit, optimal arrangements of large numbers of traps, and the $$ N^2 $$ conjecture. Phys. Rev. E 87, 042118, https://doi.org/10.1103/PhysRevE.87.042118, 2013.