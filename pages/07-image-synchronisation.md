---
layout: home
permalink: /image-synchronisation-compositing-stereo-calibration
title: "Image Synchronisation, Compositing and stereo Calibration"
excerpt: "<br>"
image:
  feature: /FK200308-SuBastianRecoveryTwilight-20200316-Ingle-5814.jpg
layout: home
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

To ensure that the imagery from each camera can be effectively composited to be viewed simultaneously, both the lightweight mono-video and the larger stereo-video drop camera systems require synchronisation. In particular, for stereo-video imagery, we recommend a minimum of four intermittent synchronisations should be done throughout the day. We propose the use of a flexible strip of waterproof LED lights, for synchronisation, to generate a simultaneous flash in the fields of view of all eight or four horizontally facing cameras (Fig. 2c). We provide wiring diagrams for this synchronisation hardware in Supporting Information 4. Video from each set of four horizontally facing cameras must be synchronised and composited into a single video stream (Fig. 5). We recommend using VidComp software which is freely available from seagis.com.au. For the stereo-video version of this platform, the use of a video composite is formed from standard fields of view, to minimise barrel distortion, rather than the typical 360o image which is formed using ‘fish-eye’ or ‘omnidirectional’ lenses. Standard lenses result in a less distorted image that is more suitable for stereo-calibration. For the stereo-video calibration procedures, we recommend the widely used and supported SeaGIS CAL (seagis.com.au/bundle.html) software and recommend calibrating cameras frequently, before and after each field campaign (e.g every two weeks or 300 deployments). Frequent calibration will ensure against loss of stereo capability which could come from camera misalignment or swapping of cameras (i.e. optical properties vary within camera models). 

![alt_text](images/figure5.png "image_tooltip")

**Figure 5**. Synchronised and composited imagery from four horizontal cameras.
