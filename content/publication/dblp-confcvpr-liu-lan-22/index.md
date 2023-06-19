---
title: "Deep Decomposition for Stochastic Normal-Abnormal Transport"
date: 2022-01-01
publishDate: 2023-06-19T20:19:09.346127Z
authors: ["Peirong Liu", "Yueh Z. Lee", "Stephen R. Aylward", "Marc Niethammer"]
publication_types: ["1"]
abstract: "Advection-diffusion equations describe a large family of natural transport processes, e.g., fluid flow, heat transfer, and wind transport. They are also used for optical flow and perfusion imaging computations. We develop a machine learning model, D2-SONATA, built upon a stochastic advection-diffusion equation, which predicts the velocity and diffusion fields that drive 2D/3D image time-series of transport. In particular, our proposed model incorporates a model of transport atypicality, which isolates abnormal differences between expected normal transport behavior and the observed transport. In a medical context such a normal-abnormal decomposition can be used, for example, to quantify pathologies. Specifically, our model identifies the advection and diffusion contributions from the transport time-series and simultaneously predicts an anomaly value field to provide a decomposition into normal and abnormal advection and diffusion behavior. To achieve improved estimation performance for the velocity and diffusion-tensor fields underlying the advection-diffusion process and for the estimation of the anomaly fields, we create a 2D/3D anomaly-encoded advection-diffusion simulator, which allows for supervised learning. We further apply our model on a brain perfusion dataset from ischemic stroke patients via transfer learning. Extensive comparisons demonstrate that our model successfully distinguishes stroke lesions (abnormal) from normal brain regions, while reconstructing the underlying velocity and diffusion tensor fields."
featured: false
publication: "*IEEE/CVF Conference on Computer Vision and Pattern Recognition, CVPR 2022, New Orleans, LA, USA, June 18-24, 2022*"
tags: ["perfusion", "stroke", "CVPR"]
url_pdf: "https://drive.google.com/file/d/1E64NrDAHZyIXs21CC_qAEPlfTsHGASmU"
doi: "10.1109/CVPR52688.2022.01823"
---

