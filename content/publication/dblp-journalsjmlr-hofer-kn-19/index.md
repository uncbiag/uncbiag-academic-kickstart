---
title: "Learning Representations of Persistence Barcodes"
date: 2019-01-01
publishDate: 2020-07-07T22:54:11.026502Z
authors: ["Christoph D. Hofer", "Roland Kwitt", "Marc Niethammer"]
publication_types: ["2"]
abstract: "We consider the problem of supervised learning with summary representations of topological features in data. In particular, we focus on persistent homology, the prevalent tool used in topological data analysis. As the summary representations, referred to as barcodes or persistence diagrams, come in the unusual format of multi sets, equipped with computationally expensive metrics, they can not readily be processed with conventional learning techniques. While different approaches to address this problem have been proposed, either in the context of kernel-based learning, or via carefully designed vectorization techniques, it remains an open problem how to leverage advances in representation learning via deep neural networks. Appropriately handling topological summaries as input to neural networks would address the disadvantage of previous strategies which handle this type of data in a task-agnostic manner. In particular, we propose an approach that is designed to learn a task-specific representation of barcodes. In other words, we aim to learn a representation that adapts to the learning problem while, at the same time, preserving theoretical properties (such as stability). This is done by projecting barcodes into a finite dimensional vector space using a collection of parametrized functionals, so called structure elements, for which we provide a generic construction scheme. A theoretical analysis of this approach reveals sufficient conditions to preserve stability, and also shows that different choices of structure elements lead to great differences with respect to their suitability for numerical optimization. When implemented as a neural network input layer, our approach demonstrates compelling performance on various types of problems, including graph classification and eigenvalue prediction, the classification of 2D/3D object shapes and recognizing activities from EEG signals."
featured: false
publication: "*J. Mach. Learn. Res.*"
tags: ["topology", "deep learning", "JMLR"]
url_pdf: "http://jmlr.org/papers/v20/18-358.html"
---

