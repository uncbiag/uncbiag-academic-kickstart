---
title: "Active Mean Fields for Probabilistic Image Segmentation: Connections with Chan-Vese and Rudin-Osher-Fatemi Models"
date: 2017-01-01
publishDate: 2020-07-08T19:54:41.908155Z
authors: ["Marc Niethammer", "Kilian M. Pohl", "Firdaus Janoos", "William M. Wells III"]
publication_types: ["2"]
abstract: "Segmentation is a fundamental task for extracting semantically meaningful regions from an image. The goal of segmentation algorithms is to accurately assign object labels to each image location. However, image-noise, shortcomings of algorithms, and image ambiguities cause uncertainty in label assignment. Estimating the uncertainty in label assignment is important in multiple application domains, such as segmenting tumors from medical images for radiation treatment planning. One way to estimate these uncertainties is through the computation of posteriors of Bayesian models, which is computationally prohibitive for many practical applications. On the other hand, most computationally efficient methods fail to estimate label uncertainty. We therefore propose in this paper the Active Mean Fields (AMF) approach, a technique based on Bayesian modeling that uses a mean-field approximation to efficiently compute a segmentation and its corresponding uncertainty. Based on a variational formulation, the resulting convex model combines any label-likelihood measure with a prior on the length of the segmentation boundary. A specific implementation of that model is the Chan–Vese segmentation model (CV), in which the binary segmentation task is defined by a Gaussian likelihood and a prior regularizing the length of the segmentation boundary. Furthermore, the Euler–Lagrange equations derived from the AMF model are equivalent to those of the popular Rudin-Osher-Fatemi (ROF) model for image denoising. Solutions to the AMF model can thus be implemented by directly utilizing highlyefficient ROF solvers on log-likelihood ratio fields. We qualitatively assess the approach on synthetic data as well as on real natural and medical images. For a quantitative evaluation, we apply our approach to the icgbench dataset."
featured: false
publication: "*SIAM J. Imaging Sciences*"
tags: ["segmentation", "JIS", "variational"]
url_pdf: "https://doi.org/10.1137/16M1058601"
doi: "10.1137/16M1058601"
---

