---
title: "Compressing networks with super nodes"
date: 2017-01-01
publishDate: 2020-07-08T19:54:41.918229Z
authors: ["Natalie Stanley", "Roland Kwitt", "Marc Niethammer", "Peter J. Mucha"]
publication_types: ["2"]
abstract: "Community detection is a commonly used technique for identifying groups in a network based on similarities in connectivity patterns. To facilitate community detection in large networks, we recast the network as a smaller network of ‘super nodes’, where each super node comprises one or more nodes of the original network. We can then use this super node representation as the input into standard community detection algorithms. To define the seeds, or centers, of our super nodes, we apply the ‘CoreHD’ ranking, a technique applied in network dismantling and decycling problems. We test our approach through the analysis of two common methods for community detection: modularity maximization with the Louvain algorithm and maximum likelihood optimization for fitting a stochastic block model. Our results highlight that applying community detection to the compressed network of super nodes is significantly faster while successfully producing partitions that are more aligned with the local network connectivity and more stable across multiple (stochastic) runs within and between community detection algorithms, yet still overlap well with the results obtained using the full network."
featured: false
publication: "*CoRR*"
tags: ["SBM", "network"]
url_pdf: "http://arxiv.org/abs/1706.04110"
---

