---
title: "Scene Parsing with Object Instance Inference Using Regions and Per-exemplar Detectors"
date: 2015-01-01
publishDate: 2020-07-05T06:52:41.339684Z
authors: ["Joseph Tighe", "Marc Niethammer", "Svetlana Lazebnik"]
publication_types: ["2"]
abstract: "This paper describes a system for interpreting a scene by assigning a semantic label at every pixel and inferring the spatial extent of individual object instances together with their occlusion relationships. First we present a method for labeling each pixel aimed at achieving broad coverage across hundreds of object categories, many of them sparsely sampled. This method combines region-level features with per-exemplar sliding window detectors. Unlike traditional bounding box detectors, per-exemplar detectors perform well on classes with little training data and high intra-class variation, and they allow object masks to be transferred into the test image for pixel-level segmentation. Next, we use per-exemplar detections to generate a set of candidate object masks for a given test image. We then select a subset of objects that explain the image well and have valid overlap relationships and occlusion ordering. This is done by minimizing an integer quadratic program either using a greedy method or a standard solver. We alternate between using the object predictions to refine the pixel labels and using the pixel labels to improve the object predictions. The proposed system obtains promising results on two challenging subsets of the LabelMe dataset, the largest of which contains 45,676 images and 232 classes."
featured: false
publication: "*Int. J. Comput. Vis.*"
tags: ["IJCV"]
url_pdf: "https://doi.org/10.1007/s11263-014-0778-5"
doi: "10.1007/s11263-014-0778-5"
---

