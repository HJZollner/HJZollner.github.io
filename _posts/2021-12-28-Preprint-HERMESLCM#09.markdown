---
layout: post
title:  Importance of linear combination modeling for quantification of Glutathione and GABA levels using Hadamard-edited MRS
date:   2021-12-28 10:00:00 -0500
thumbnail-img: /assets/img/HERMES_LCM.jpg
tags: [Osprey, HERMES, LCM, open-source, GABA, GSH]
---

Happy to share this amazing work of my colleague Yulu Song implying improved quantification accuracy of GABA-GSH-edited HERMES data with linear-combination modeling compared to simple peak fitting. This work strenghtens recent consenus to employ LCM to model edited MRS data. LCM and processing was performed in Osprey and the implemeted models are freely available on [GitHub](https://github.com/schorschinho/osprey) using the accuarlty parametrization of co-edited MMs at 3 ppm to improve general modeling results.

![Test-retest quantification HERMES](/assets/img/HERMES_LCM.jpg){:class="img-responsive"}
*Test-retest results for GABA+ and GSH metabolite levels acquired with MEGA-PRESS or HERMES and modeled in Gannet and Osprey. The results imply improved quantification of HERMES acquired GSH levels quantified with LCM (Osprey) compared to simple peak fitting (Gannet).*

#### Links
[![Preprint](/assets/img/doi.png)](https://doi.org/10.1101/2021.12.28.474256)[![Analysis](/assets/img/Osprey.png)](https://github.com/schorschinho/osprey)
