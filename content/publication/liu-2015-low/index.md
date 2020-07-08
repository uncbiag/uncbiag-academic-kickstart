---
title: "Low-rank atlas image analyses in the presence of pathologies"
date: 2015-01-01
publishDate: 2020-07-08T04:28:37.834980Z
authors: ["Xiaoxiao Liu", "Marc Niethammer", "Roland Kwitt", "Nikhil Singh", "Matt McCormick", "Stephen Aylward"]
publication_types: ["2"]
abstract: "We present a common framework, for registering images to an atlas and for forming an unbiased atlas, that tolerates the presence of pathologies such as tumors and traumatic brain injury lesions. This common framework is particularly useful when a sufficient number of protocol-matched scans from healthy subjects cannot be easily acquired for atlas formation and when the pathologies in a patient cause large appearance changes. Our framework combines a low-rank-plus-sparse image decomposition technique with an iterative, diffeomorphic, group-wise image registration method. At each iteration of image registration, the decomposition technique estimates a “healthy” version of each image as its low-rank component and estimates the pathologies in each image as its sparse component. The healthy version of each image is used for the next iteration of image registration. The low-rank and sparse estimates are refined as the image registrations iteratively improve. For unbiased atlas formation, at each iteration, the average of the low-rank images from the patients is used as the atlas image for the next iteration, until convergence. Since each iteration's atlas is comprised of low-rank components, it provides a population-consistent, pathology-free appearance. Evaluations of the proposed methodology are presented using synthetic data as well as simulated and clinical tumor MRI images from the brain tumor segmentation (BRATS) challenge from MICCAI 2012."
featured: false
publication: "*IEEE transactions on medical imaging*"
url_pdf: "https://drive.google.com/file/d/1epFJu4_gS2nMvwhD9G2PJ6tKPnw7Jl3P"
---

