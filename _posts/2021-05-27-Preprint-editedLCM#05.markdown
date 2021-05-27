---
layout: post
title:  Comparison of linear combination modeling strategies for GABA-edited MRS at 3T
date:   2021-05-27 10:00:00 -0500
tags: [preprint, open-source, open-science, GABA]
---

[Our new preprint is out](https://doi.org/10.1101/2021.05.26.445817)! We evaluated different modeling strategies for linear combination modeling of GABA-edited MRS at 3T. Parameterizing the co-edited macromolecules at 3-ppm improved overall fitting performance.

Different modeling strategies were tested: combining six approaches to account for co-edited MMs, three modeling ranges, three baseline knot spacings, and using basis sets with and without homocarnosine.

Significantly different GABA+ and GABA estimates were found when a well-parameterized MM basis function at 3 ppm was included. The mean GABA estimates were significantly lower when modeling MM, while CVs remained similar. Sparser knot spacing led to lower variation in the GABA and GABA+ estimates and a narrower modeling range - only including signals of interest - did not substantially improve or degrade modeling performance. Additioanlly, results suggest that LCM can separate GABA and the underlying co-edited MM.

GABA-edited MRS is best quanitfied by LCM with a well-parameterized co-edited MM basis fucntion constraint to the non-overlapped MM0.93 in combination with a sparse spline knot spacing and a mdoeling range between 0.5 and 4 ppm.

[Preprint](https://doi.org/10.1101/2021.05.26.445817)
[Code](https://osf.io/aqm8f/)
[Analysis](https://github.com/schorschinho/osprey)
[Visualization](https://github.com/HJZollner/SpecVis)					

Thank you to those who contributed to this work - my mentors and supervisors [Georg Oeltzschner](https://www.specfitlab.com/) and [Richard Edden](http://www.gabamrs.com/).
