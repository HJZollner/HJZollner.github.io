---
layout: post
title:  Comparison of linear combination modeling strategies for edited magnetic resonance spectroscopy at 3T
date:   2021-09-24 10:00:00 -0500
thumbnail-img: /assets/img/Graphical_Abstract.png
tags: [Osprey, SpecVis, LCM, paper, open-source, open-science, GABA]
---

Happy to announce that our paper about Linear-combination modeling of [GABA-edited MRS](https://doi.org/10.1002/nbm.4618) is now available at NMR in Biomedicine. A well-parameterized macromolecule (MM) basis function at 3 ppm improved overall modeling performance.

GABA-edited MRS is best quantified by LCM with a well-parameterized coedited MM basis function constraint to the non-overlapped macromolecule peak at 0.9 ppm combined with sparse spline knot spacing and modeling range between 0.5 and 4 ppm.

![Open-source environment](/assets/img/Graphical_Abstract.png){:class="img-responsive"}
*Graphical abstract: Smallest GABA+ CVs were found when the co-edited MM was hard constraint by the non-overlapped 0.9 ppm macromolecule peak.*		

Thank you to those who contributed to this work - co-authors, my mentors and supervisors [Georg Oeltzschner](https://www.specfitlab.com/) and [Richard Edden](http://www.gabamrs.com/).

#### Links
[![Preprint](/assets/img/doi.png)](https://doi.org/10.1002/nbm.4618)[![Code](/assets/img/OSF.png)](https://osf.io/aqm8f/)   [![Analysis](/assets/img/Osprey.png)](https://github.com/schorschinho/osprey)   [![Visualization](/assets/img/SpecVis.png)](https://github.com/HJZollner/SpecVis)
