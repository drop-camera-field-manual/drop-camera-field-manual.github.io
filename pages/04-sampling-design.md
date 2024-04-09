---
layout: home
permalink: /sampling-design
title: "Sampling Design"
excerpt: "<br>"
image:
  feature: /FK200308-SuBastianRecoveryTwilight-20200316-Ingle-5814.jpg
layout: home

---
{% include toc.html class="toc-left" h_min=2 h_max=2 %}

Using sampling strategies appropriate for the study objectives will allow valid inferences, interpretations, and generalisation of resulting data (Robertson et al., 2013). For surveys of habitat composition to ground-truth remote sensed data or existing spatial predictive models, we recommend spatially balanced a priori stratification of survey locations as per Balanced Acceptance Sampling (BAS) or Generalised Randomised Tessellation Structures (GRTS) (Robertson et al., 2013). BAS and GRTS approaches can be implemented using R packages ‘MBHdesign’ (Foster et al., 2020) or ‘spsurvey’ respectively (Kincaid et al., 2007). Resampling and spatial coverage can be minimised by separating individual samples in space. Minimum separation distance is dependent on the spatial heterogeneity in the acquired data and should be tested during statistical analysis with spatial variograms, and any significant autocorrelation taken into account (Robertson et al., 2013).
