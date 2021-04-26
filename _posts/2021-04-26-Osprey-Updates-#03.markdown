---
layout: post
title:  "MRSinMRS mardown in Osprey"
date:   2021-04-26 18:00:00 -0500
categories: Osprey update
tags: Osprey open-source open-science
---
Dear MRS community,

we are happy to announce a new module in Osprey that automatically creates a table following the consensus recommendations. The output format is markdown which allows opening in any text editor independently of your OS. The final document can easily be used to generate a PDF to attach for publication.

Hopefully, this easy and open implementation allows other developers to join us and make this a standard output of any MRS analysis software. This could be very helpful to further increase the standardization and transparency of MRS studies.

The new module will be included in the next Osprey release and is currently available in [Osprey's develop branch](https://github.com/schorschinho/osprey).

We are happy for your feedback!


 # Summary following minimum reporting standards in MRS generated in Osprey
 See Lin et al. 'Minimum Reporting Standards for in vivo Magnetic Resonance Spectroscopy (MRSinMRS): Experts' consensus recommendations. NMR in Biomedicine. 2021;e4484.
 [doi.org/10.1002/nbm.4448](https://doi.org/10.1002/nbm.4448)


 You may need to add information that was not avaialble in the raw data.

|1. Hardware|  |
|--|--|
|a. Field strength [T]| 3 T|
|b. Manufacturer| Philips|
|c. Model (software version if available)| R 5.7.1|
|d. RF coils: nuclei (transmit/receive), number of channels, type, body part| 1H |
|e. Additional hardware| -|


|2. Acquisition|  |
|--|--|
|a. Pulse sequence | MEGA_PRESS_FF|
|b. Volume of interest (VOI) locations | -|
|c. Nominal VOI size [mm^3]| 30 x 30 x 30 mm^3|
|d. Repetition time (TR), echo time (TE) [ms]| TR 2000 ms, TE 90 ms|
|e. Total number of averages per spectrum <br> i. Number of averaged specra per subspectrum | 384 total averages with 192 averages per subspectrum|
|f. Additional sequence parameters <br> i. editing pulse frequencies | F1: 2000 Hz, 2048 points <br> ppm<sub>ON</sub> = 3.22 ppm<sub>OFF</sub> = 7.50 |
|g. Water suppression method | -|
|h. Shimming method, refernce peak, and threshold of acceptance of shim chosen | -|
|i. Trigger or motion correction| -|


|3. Data analysis methods and outputs|  |
|--|--|
|a. Analysis software | Osprey 1.0.1|
|b. Processing steps deviating from Osprey | None|
|c. Output measure | tCr, rawWaterScaled
|d. Quantification references and assumptions, fitting model assumptions| Basis set list:<br> AscAsp,Cr,CrCH2,GABA,GPC,GSH,Gln,Glu,Ins,<br>Lac,NAA,NAAG,PCh,PCr,PE,Scyllo,Tau,MM09,<br>MM12,MM14,MM17,MM20,Lip09,Lip13,Lip20 <br>Fitting method: Osprey basline knot spacing 0.32 ppm


|4. Data quality|  |
|--|--|
|a. SNR (NAA), linewidth (NAA) [Hz] | SNR: 263 +- 37, linewidth 5.49 +- 0.45 Hz|
|b. Data exclusion criteria | None|
|c. Quality measures of postporcessing model fitting (Mean Relative Amplitude Residual (Residual/Noise)) <br> off <br> diff1 |<br> 22.14 +- 8.14  <br> 16.19 +- 4.15
|d. Mean spectrum created with OspreyOverview| Figure 1
