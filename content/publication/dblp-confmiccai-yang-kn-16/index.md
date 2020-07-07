---
title: "Fast Predictive Image Registration"
date: 2016-01-01
publishDate: 2020-07-07T23:41:09.634852Z
authors: ["Xiao Yang", "Roland Kwitt", "Marc Niethammer"]
publication_types: ["1"]
abstract: "We present a method to predict image deformations based on patch-wise image appearance. Specifically, we design a patch-based deep encoder-decoder network which learns the pixel/voxel-wise mapping between image appearance and registration parameters. Our approach can predict general deformation parameterizations, however, we focus on the large deformation diffeomorphic metric mapping (LDDMM) registration model. By predicting the LDDMM momentum-parameterization we retain the desirable theoretical properties of LDDMM, while reducing computation time by orders of magnitude: combined with patch pruning, we achieve a 1500 x/66 x speed up compared to GPU-based optimization for 2D/3D image registration. Our approach has better prediction accuracy than predicting deformation or velocity fields and results in diffeomorphic transformations. Additionally, we create a Bayesian probabilistic version of our network, which allows evaluation of deformation field uncertainty through Monte Carlo sampling using dropout at test time. We show that deformation uncertainty highlights areas of ambiguous deformations. We test our method on the OASIS brain image dataset in 2D and 3D."
featured: false
publication: "*Deep Learning and Data Labeling for Medical Applications - First International Workshop, LABELS 2016, and Second International Workshop, DLMIA 2016, Held in Conjunction with MICCAI 2016, Athens, Greece, October 21, 2016, Proceedings*"
tags: ["MICCAI", "registration", "deep learning", "brain"]
url_pdf: "https://drive.google.com/file/d/11QwMifHkk_NwumSWdtTWCENJVF6I8LsA"
doi: "10.1007/978-3-319-46976-8_6"
---

