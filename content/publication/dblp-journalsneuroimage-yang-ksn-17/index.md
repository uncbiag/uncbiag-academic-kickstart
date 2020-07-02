---
title: "Quicksilver: Fast predictive image registration - A deep learning approach"
date: 2017-01-01
publishDate: 2020-07-02T21:36:10.880331Z
authors: ["Xiao Yang", "Roland Kwitt", "Martin Styner", "Marc Niethammer"]
publication_types: ["2"]
abstract: "This paper introduces Quicksilver, a fast deformable image registration method. Quicksilver registration for image-pairs works by patch-wise prediction of a deformation model based directly on image appearance. A deep encoder-decoder network is used as the prediction model. While the prediction strategy is general, we focus on predictions for the Large Deformation Diffeomorphic Metric Mapping (LDDMM) model. Specifically, we predict the momentum-parameterization of LDDMM, which facilitates a patch-wise prediction strategy while maintaining the theoretical properties of LDDMM, such as guaranteed diffeomorphic mappings for sufficiently strong regularization. We also provide a probabilistic version of our prediction network which can be sampled during the testing time to calculate uncertainties in the predicted deformations. Finally, we introduce a new correction network which greatly increases the prediction accuracy of an already existing prediction network. We show experimental results for uni-modal atlas-to-image as well as uni-/multimodal image-to-image registrations. These experiments demonstrate that our method accurately predicts registrations obtained by numerical optimization, is very fast, achieves state-of-the-art registration results on four standard validation datasets, and can jointly learn an image similarity measure. Quicksilver is freely available as an open-source software."
featured: false
publication: "*NeuroImage*"
url_pdf: "https://doi.org/10.1016/j.neuroimage.2017.07.008"
doi: "10.1016/j.neuroimage.2017.07.008"
---
