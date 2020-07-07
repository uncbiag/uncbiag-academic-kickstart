---
title: "Automatic cortical thickness analysis on rodent brain"
date: 2011-01-01
publishDate: 2020-07-07T23:41:09.690867Z
authors: ["Joohwi Lee", "Cindy Ehlers", "Fulton Crews", "Marc Niethammer", "François Budin", "Beatriz Paniagua", "Kathy Sulik", "Josephine Johns", "Martin Styner", "Ipek Oguz"]
publication_types: ["1"]
abstract: "Localized difference in the cortex is one of the most useful morphometric traits in human and animal brain studies. There are many tools and methods already developed to automatically measure and analyze cortical thickness for the human brain. However, these tools cannot be directly applied to rodent brains due to the different scales; even adult rodent brains are 50 to 100 times smaller than humans. This paper describes an algorithm for automatically measuring the cortical thickness of mouse and rat brains. The algorithm consists of three steps: segmentation, thickness measurement, and statistical analysis among experimental groups. The segmentation step provides the neocortex separation from other brain structures and thus is a preprocessing step for the thickness measurement. In the thickness measurement step, the thickness is computed by solving a Laplacian PDE and a transport equation. The Laplacian PDE first creates streamlines as an analogy of cortical columns; the transport equation computes the length of the streamlines. The result is stored as a thickness map over the neocortex surface. For the statistical analysis, it is important to sample thickness at corresponding points. This is achieved by the particle correspondence algorithm which minimizes entropy between dynamically moving sample points called particles. Since the computational cost of the correspondence algorithm may limit the number of corresponding points, we use thin-plate spline based interpolation to increase the number of corresponding sample points. As a driving application, we measured the thickness difference to assess the effects of adolescent intermittent ethanol exposure that persist into adulthood and performed t-test between the control and exposed rat groups. We found significantly differing regions in both hemispheres."
featured: false
publication: "*Medical Imaging 2011: Image Processing, Lake Buena Vista, Florida, USA, February 14-16, 2011*"
tags: ["SPIE", "brain"]
url_pdf: "https://doi.org/10.1117/12.878305"
doi: "10.1117/12.878305"
---

