---
layout: post
title:  In vivo spectral editing of phosphorylethanolamine
date:   2021-08-18 10:00:00 -0500
thumbnail-img: /assets/img/PE.png
tags: [Osprey, paper, PE]
---

Another exciting paper on edited MRS using LCM for modelling from my colleague Steve Hui. Here two editing schemes to investigate phosphorylethanolamine were implemented on a clincal scanner and analyzed using Osprey. Easy and highly flexible pre-processing and modeling modules in Osprey made this work possible - again showcasing rapid method adaption is possible with open-source implementations such as Osprey. For this work we did implement a new method for sub-spectra alignment into Osprey using a L1 norm optimization across the whole spectral range.

*Linear-combination modeling of PE-edited MEGA-PRESS data performed in Osprey. This showcases the modeling of the four proposed editing schemes.*

![PE LCM ](/assets/img/PE.png){:class="img-responsive"}

The whole pipeline is added into Osprey if you are interested in applying those methods in your own work.

#### Links
[![Paper](/assets/img/doi.png)](https://doi.org/10.1002/mrm.28976)[![Analysis](/assets/img/Osprey.png)](https://github.com/schorschinho/osprey)
