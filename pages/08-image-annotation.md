---
layout: home
permalink: /image-annotation
title: "Image Annotation"
excerpt: "<br>"
image:
  feature: /banner.jpg
layout: home
---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

## Annotation software

There is a range of readily available image annotation software and platforms available such as TransectMeasure ([www.seagis.com.au/transect.html](http://www.seagis.com.au/transect.html)), Squidle+ (squidle.org), CoralNet (coralnet.ucsd.edu), BenthoBox (benthobox.com), and ReefCloud (reefcloud.ai), all of which are suitable for mono video annotation. For stereo-video annotation, we have used SeaGIS EventMeasure (seagis.com.au/event.html) and recommend this as a widely used and well-supported software workflow for stereo-annotation and measurement. 


## Image annotation

For horizontally facing wide-field imagery, we recommend annotating 20 random points assigned to the lower 50% of each image. We provide example annotation and quality control workflows ([globalarchivemanual.github.io/CheckEM/](https://globalarchivemanual.github.io/CheckEM/articles/manuals/TransectMeasure_annotation_guide.html)). A simulation study of point annotation of downward-facing imagery found that 20 points would provide an adequate estimate of variance in benthic assemblage composition whereas 80 points would provide a highly consistent estimate (Dumas et al. 2009). Similarly, for the horizontal-facing images collected by the BOSS, we explored the implication of annotating one field of view, using 20 points, to up to four fields of view, a total of 80 points, across multiple independent tropical, subtropical, and temperate locations (Supporting Information 5, code publicly available at [github.com/UWA-Marine-Ecology-Group-projects/paper-boss-habitat/](https://github.com/UWA-Marine-Ecology-Group-projects/paper-boss-habitat/)). We found generally more precise estimates of habitat composition using 40 to 80 points, annotating two to four fields of view, justifying our recommendation to annotate the combined field of view (~270<sup>o</sup>) of the four cameras, to characterise benthic composition (Supporting Information 5).

For annotation of benthic composition, we recommend the CATAMI classification schema (Althaus et al., 2015), which classifies habitats into morphological groups. This schema is also recommended for similar marine sampling protocols for towed video, ROVs, AUVs (Przeslawski et al., 2023) and benthic composition from BRUV (Langlois et al., 2020). We provide a controlled repository of CATAMI formatted for use in TransectMeasure available at [github.com/GlobalArchiveManual/annotation-schema](https://github.com/GlobalArchiveManual/annotation-schema), which also includes species-specific annotation for certain common and easily identifiable taxa from the CAAB classification schema relevant to Australia (Rees et al., 1999). Also included is an annotation schema for visual estimates of structural complexity or relief (see Langlois et al., 2020).
