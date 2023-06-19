---
title: "GradICON: Approximate Diffeomorphisms via Gradient Inverse Consistency"
date: 2023-01-01
publishDate: 2023-06-19T20:42:27.046950Z
authors: ["Lin Tian", "Hastings Greer", "François-Xavier Vialard", "Roland Kwitt", "Raúl San José Estépar", "Marc Niethammer"]
publication_types: ["2"]
abstract: "We present an approach to learning regular spatial transformations between image pairs in the context of medical image registration. Contrary to optimization-based registration techniques and many modern learning-based methods, we do not directly penalize transformation irregularities but instead promote transformation regularity via an inverse consistency penalty. We use a neural network to predict a map between a source and a target image as well as the map when swapping the source and target images. Different from existing approaches, we compose these two resulting maps and regularize deviations of the Jacobian of this composition from the identity matrix. This regularizer - GradICON - results in much better convergence when training registration models compared to promoting inverse consistency of the composition of maps directly while retaining the desirable implicit regularization effects of the latter. We achieve state-of-the-art registration performance on a variety of real-world medical image datasets using a single set of hyperparameters and a single non-dataset-specific training protocol. Code is available at https://github.com/uncbiag/ICON."
featured: false
publication: "*CVPR*"
tags: ["CVPR", "registration", "gradient inverse consistency", "lung", "knee", "brain"]
url_pdf: "https://drive.google.com/file/d/1j8u5n50knQUxhnHp1OMGEwsl8CX-lODX"
doi: "10.48550/arXiv.2206.05897"
---

