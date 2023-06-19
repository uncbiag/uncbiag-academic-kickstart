---
title: "Unsupervised Discovery of 3D Hierarchical Structure with Generative Diffusion Features"
date: 2023-01-01
publishDate: 2023-06-19T20:19:09.342105Z
authors: ["Nurislam Tursynbek", "Marc Niethammer"]
publication_types: ["2"]
abstract: "Inspired by recent findings that generative diffusion models learn semantically meaningful representations, we use them to discover the intrinsic hierarchical structure in biomedical 3D images using unsupervised segmentation. We show that features of diffusion models from different stages of a U-Net-based ladder-like architecture capture different hierarchy levels in 3D biomedical images. We design three losses to train a predictive unsupervised segmentation network that encourages the decomposition of 3D volumes into meaningful nested subvolumes that represent a hierarchy. First, we pretrain 3D diffusion models and use the consistency of their features across subvolumes. Second, we use the visual consistency between subvolumes. Third, we use the invariance to photometric augmentations as a regularizer. Our models achieve better performance than prior unsupervised structure discovery approaches on challenging biologically-inspired synthetic datasets and on a real-world brain tumor MRI dataset."
featured: false
publication: "*CoRR*"
tags: ["deep learning", "segmentation", "unsupervised", "diffusion", "MICCAI"]
url_pdf: "https://doi.org/10.48550/arXiv.2305.00067"
doi: "10.48550/arXiv.2305.00067"
---

