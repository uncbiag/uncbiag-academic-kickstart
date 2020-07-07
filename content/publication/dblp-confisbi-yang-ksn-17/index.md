---
title: "Fast predictive multimodal image registration"
date: 2017-01-01
publishDate: 2020-07-07T23:41:09.624925Z
authors: ["Xiao Yang", "Roland Kwitt", "Martin Styner", "Marc Niethammer"]
publication_types: ["1"]
abstract: "We introduce a deep encoder-decoder architecture for image deformation prediction from multimodal images. Specifically, we design an image-patch-based deep network that jointly (i) learns an image similarity measure and (ii) the relationship between image patches and deformation parameters. While our method can be applied to general image registration formulations, we focus on the Large Deformation Diffeomorphic Metric Mapping (LDDMM) registration model. By predicting the initial momentum of the shooting formulation of LDDMM, we preserve its mathematical properties and drastically reduce the computation time, compared to optimizationbased approaches. Furthermore, we create a Bayesian probabilistic version of the network that allows evaluation of registration uncertainty via sampling of the network at test time. We evaluate our method on a 3D brain MRI dataset using both T1- and T2-weighted images. Our experiments show that our method generates accurate predictions and that learning the similarity measure leads to more consistent registrations than relying on generic multimodal image similarity measures, such as mutual information. Our approach is an order of magnitude faster than optimization-based LDDMM."
featured: false
publication: "*14th IEEE International Symposium on Biomedical Imaging, ISBI 2017, Melbourne, Australia, April 18-21, 2017*"
tags: ["registration", "brain", "ISBI", "deep learning"]
url_pdf: "https://drive.google.com/file/d/1upWddxmHodmYu62eDXtUzS4dqJjFlw0J"
doi: "10.1109/ISBI.2017.7950652"
---

