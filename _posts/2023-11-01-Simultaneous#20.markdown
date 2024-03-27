---
layout: post
title:  Simultaneous multi-transient linear-combination modeling of MRS data improves uncertainty estimation
date:   2023-11-01 10:00:00 -0500
thumbnail-img: /assets/img/gLCM.png
tags: [MRS, LCM, Osprey]
---

Over the last year we have been working on a new generalized linear-combination modeling in Osprey. Generalized means that every modeling decision can be controlled by the user through a single interface json file. The implementation also allows for modeling of arbitrary 2D experiments.

In the first study, we used benchmarked the new algorithm by designing a simple synthetic MRS dataset representing a multi-transient conventional MRS experiment of a single metabolite (Scyllo-Inositol and GABA). The data was modeled using traditional methods (averaging and 1D-LCM) and multi-transient 2D-LCM of all averages at once. Bias in concentration estimates agreed well between both methods. Interestingly we found a slight reduction in the variance of the CRLBs for 2D-LCM compared to traditional 1D-LCM. In case of correlated noise, 2D-LCM CRLB showed a significant improvement and higher agreement with the ground-truth CRLBs.

All results and code are available on [OSF](https://doi.org/10.17605/OSF.IO/K9HZX).

#### Links
[![Paper](/assets/img/biorxiv-square.png)](https://doi.org/10.1101/2023.11.01.565164)[![Code](/assets/img/OSF.png)](https://doi.org/10.17605/OSF.IO/K9HZX)[![Analysis](/assets/img/Osprey.png)](https://github.com/schorschinho/osprey/tree/MSM)
