---
title: "Region-specific Diffeomorphic Metric Mapping"
date: 2019-01-01
publishDate: 2020-07-05T06:52:41.320644Z
authors: ["Zhengyang Shen", "François-Xavier Vialard", "Marc Niethammer"]
publication_types: ["1"]
abstract: "We introduce a region-specific diffeomorphic metric mapping (RDMM) registration approach. RDMM is non-parametric, estimating spatio-temporal velocity fields which parameterize the sought-for spatial transformation. Regularization of these velocity fields is necessary. In contrast to existing non-parametric registration approaches using a fixed spatially-invariant regularization, for example, the large displacement diffeomorphic metric mapping (LDDMM) model, our approach allows for spatially-varying regularization which is advected via the estimated spatio-temporal velocity field. Hence, not only can our model capture large displacements, it does so with a spatio-temporal regularizer that keeps track of how regions deform, which is a more natural mathematical formulation. We explore a family of RDMM registration approaches: 1) a registration model where regions with separate regularizations are pre-defined (e.g., in an atlas space or for distinct foreground and background regions), 2) a registration model where a general spatially-varying regularizer is estimated, and 3) a registration model where the spatially-varying regularizer is obtained via an end-to-end trained deep learning (DL) model. We provide a variational derivation of RDMM, showing that the model can assure diffeomorphic transformations in the continuum, and that LDDMM is a particular instance of RDMM. To evaluate RDMM performance we experiment 1) on synthetic 2D data and 2) on two 3D datasets: knee magnetic resonance images (MRIs) of the Osteoarthritis Initiative (OAI) and computed tomography images (CT) of the lung. Results show that our framework achieves comparable performance to state-of-the-art image registration approaches, while providing additional information via a learned spatio-temporal regularizer. Further, our deep learning approach allows for very fast RDMM and LDDMM estimations. Code is available at https://github.com/uncbiag/registration."
featured: false
publication: "*Advances in Neural Information Processing Systems 32: Annual Conference on Neural Information Processing Systems 2019, NeurIPS 2019, 8-14 December 2019, Vancouver, BC, Canada*"
tags: ["LDDMM", "RDMM", "deep learning", "knee", "registration", "NeurIPS"]
url_pdf: "http://papers.nips.cc/paper/8394-region-specific-diffeomorphic-metric-mapping"
---

