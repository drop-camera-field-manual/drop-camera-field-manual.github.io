---
layout: home
permalink: /image-synchronisation-compositing-stereo-calibration
title: "Image Synchronisation, Compositing and stereo Calibration"
excerpt: "<br>"
image:
  feature: /banner.jpg
layout: home
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

To ensure that the imagery from each camera can be effectively composited to be viewed simultaneously, both the lightweight mono-video and the larger stereo-video drop camera systems require synchronisation. In particular, for stereo-video imagery, we recommend a minimum of four intermittent synchronisations should be done throughout the day. We propose the use of a flexible strip of waterproof LED lights, for synchronisation, to generate a simultaneous flash in the fields of view of all eight or four horizontally facing cameras (Fig. 2c). We provide wiring diagrams for this synchronisation hardware in Supporting Information 4. Video from each set of four horizontally facing cameras must be synchronised and composited into a single video stream (Fig. 5). We recommend using VidComp software which is freely available from seagis.com.au. For the stereo-video version of this platform, the use of a video composite is formed from standard fields of view, to minimise barrel distortion, rather than the typical 360o image which is formed using ‘fish-eye’ or ‘omnidirectional’ lenses. Standard lenses result in a less distorted image that is more suitable for stereo-calibration. For the stereo-video calibration procedures, we recommend the widely used and supported SeaGIS CAL (seagis.com.au/bundle.html) software and recommend calibrating cameras frequently, before and after each field campaign (e.g every two weeks or 300 deployments). Frequent calibration will ensure against loss of stereo capability which could come from camera misalignment or swapping of cameras (i.e. optical properties vary within camera models). 

![alt_text](images/figure5.png "image_tooltip")

**Figure 5**. Synchronised and composited imagery from four horizontal cameras.

## Synchronisation diode

We recommend that video rather than still imagery is collected and by using action cameras with external battery packs and large capacity memory cards, it is possible to record video for the whole day of field work and not require the camera housings to be opened until the end of the day. 

However, to ensure that the imagery from each camera can be synchronised, both the lightweight mono-video and the larger stereo-video wide-field drop camera systems will require intermittent synchronisation with diodes, out of the water, throughout field deployment to enable imagery to be composited (see below for Image compositing). 

For stereo-video imagery, we recommend intermittent with a minimum of four synchronisations should be done throughout the day. We propose the use of a flexible strip of waterproof LED lights, as synchronisation diodes, to generate a simultaneous flash in all eight or four horizontally facing cameras (Fig. 7) and provide wiring diagrams for this synchronisation diode (Fig. 8).


![alt_text](images/image1.jpg "image_tooltip")

**Figure 7.** Synchronisation diode.


![alt_text](images/image2.png "image_tooltip")
**Figure 8.** Schematic diagram of synchronisation diode wiring.
