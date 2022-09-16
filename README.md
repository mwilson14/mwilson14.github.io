---
title: "About Me"
permalink: "/about/"
layout: page
---
![me on TORUS22](/photos/torus_badlands.jpg)

I'm currently a PhD candidate in the Earth and Atmospheric Science department at the University of Nebraska-Lincoln. My PhD research focuses on evaluating the impact of assimilating targeted UAS, mobile mesonet, and radiosonde observations from the Targeted Observations by Radars and UAS (TORUS) field campaign on storm-scale ensemble forecasts of supercell storms. Other research interests of mine include examining what dual-pol signatures of supercells can tell us about these storms and their environments, developing automated algorithms to identify and quantify these signatures quickly for use by researchers and forecasters, and exploring how small-scale variations in storm environments in space and time affect the evolution of nearby supercells. 

[Here's a link to my CV!][CV_link]

# Projects

## Assimilating TORUS Observations into a Storm-Scale Ensemble

![DA summary slide](/photos/DA_summarywebsite.png)

NWP forecasts of severe storms depend heavily on having accurate model initial conditions; however, storm evolution often depends on mesoscale features which may not be sampled well by our current observational network. Would forecast accuracy improve if we had dense, targeted observations around developing storms from UAS and other platforms? Which regions of the atmosphere (surface, PBL, or the free atmosphere above the PBL) might it be most helpful to have these observations in? This project seeks to take a first step toward answering some of these questions by assimilating TORUS observations in and around two supercells (one nontornadic, the other cyclically tornadic) on 8 June 2019 into a storm-scale WRF ensemble using the Data Assimiation Research Testbed (DART). In a series of data denial experiments, the impact of assimilating TORUS UAS, mobile mesonet, and radiosonde observations from the surface, PBL, and free atmosphere on short-term storm-scale ensemble forecasts is explored for this case. Preliminary results presented at AMS 2022 indicated that assimilating the TORUS observations improved the representation of the first supercell's cold pool--stay tuned for a more in-depth examination of the impacts of the different observation subsets!

## 8 June 2019 Proximate Supercells Case Study

![case study summary slide](/photos/June8thcasestudy_web.png)

As a companion project to the data assimilation work described above, I'm also conducting an observational case study of the two 8 June 2019 supercells to determine why the second storm was able to become tornadic in close proximity to where the first storm dissipated just a short while later. Using mobile mesonet, UAS, radiosonde, and P-3 Tail Doppler Radar (TDR) datasets collected by TORUS as well as observationally-available datasets, I've examined how mesoscale boundaries, rapid changes in the storm-scale environment, differences in CI forcing, storm mergers, and internal storm processes may have led to the drastic differences between the two supercells. An example dual-Doppler analysis from my case study work on the second 8 June supercell, as well as a photo of that storm I took as it was producing an anticyclonic tornado, is included above.

## The Supercell Polarimetric Observation Research Kit (SPORK)

Supercell polarimetric signatures, including ZDR columns, ZDR arcs, KDP-ZDR separation signatures, and polarimetrically-inferred hailfall, have shown promise in distinguishing between tornadic and nontornadic supercells. However, they can be difficult to quantify quickly and consistently, which makes analyses of large samples of supercells for research (and potential operational use of these signatures) difficult. SPORK is an automated Python algorithm which I designed with my MS advisor (Dr. Matthew Van Den Broeke) to meet this need by objectively identifying supercell dual-pol signatures quickly and quantifying their characteristics. It can quickly read in and analyze archived level II radar data to produce time series of dual-pol signatures for a storm, and a real-time version of SPORK can also generate placefiles to display in GR2 (as seen in the screenshot below). A paper describing SPORK and using it to examine how dual-pol characteristics vary between tornadic and nontornadic supercells and with different environmental parameters in a sample of 206 storms has recently been accepted in the Electronic Journal of Severe Storms Meteorology (a link will be posted here as soon as it's published), and code for SPORK is available at [https://github.com/mwilson14/SPORK-SPIN][spork_link] (realtime code at [https://github.com/mwilson14/SPORK-Realtime][spork_link_rt]). 

![spork example](/photos/spork_website_example.jpg)

[spork_link]: https://github.com/mwilson14/SPORK-SPIN
[spork_link_rt]: https://github.com/mwilson14/SPORK-Realtime
[CV_link]: https://github.com/mwilson14/mwilson14.github.io/photos/MWILSON_CV2022.pdf
