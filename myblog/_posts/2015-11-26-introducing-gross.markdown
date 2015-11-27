---
layout: post
title:  "Introducing GROSS"
date:   2015-11-26 15:00:00
categories: gross update
---
GROSS stands for GR-based Open Source Software. GR stands for "Génie Rural", which is the French for "Rural Engineering". [Irstea](http://webgr.irstea.fr/?lang=en) developed a series of rainfall-runoff models which have the GR prefix: [GR4J](http://dx.doi.org/10.1016/S0022-1694(03)00225-7) (a 4-parameter daily lumped model), GR4H (hourly), etc.

It also qualifies my approach to hydrological modelling, which consists in progressively refining a gross model. In particular, a lumped model acts as a black box: it is easy to fit to the streamflow at the outlet of a basin, but it offers no visibility inside the basin. GROSS aims at inferring the streamflow on any point of the basin's river network, still only needing the streamflow at the outlet for its calibration.
