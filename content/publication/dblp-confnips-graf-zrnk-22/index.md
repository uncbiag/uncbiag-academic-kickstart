---
title: "On Measuring Excess Capacity in Neural Networks"
date: 2022-01-01
publishDate: 2023-06-19T20:19:09.348376Z
authors: ["Florian Graf", "Sebastian Zeng", "Bastian Rieck", "Marc Niethammer", "Roland Kwitt"]
publication_types: ["1"]
abstract: "We study the excess capacity of deep networks in the context of supervised classification. That is, given a capacity measure of the underlying hypothesis class – in our case, empirical Rademacher complexity – to what extent can we (a priori) constrain this class while retaining an empirical error on a par with the unconstrained regime? To assess excess capacity in modern architectures (such as residual networks), we extend and unify prior Rademacher complexity bounds to accommodate function composition and addition, as well as the structure of convolutions. The capacitydriving terms in our bounds are the Lipschitz constants of the layers and an (2, 1) group norm distance to the initializations of the convolution weights. Experiments on benchmark datasets of varying task difficulty indicate that (1) there is a substantial amount of excess capacity per task, and (2) capacity can be kept at a surprisingly similar level across tasks. Overall, this suggests a notion of compressibility with respect to weight norms, complementary to classic compression via weight pruning. Source code is available at https://github.com/rkwitt/excess_capacity."
featured: false
publication: "*NeurIPS*"
tags: ["deep learning", "capacity", "generalization", "NeurIPS"]
url_pdf: "https://drive.google.com/file/d/1O9LlGse4ZDWBEjvBKBDxDfTFfFkRVmRo"
---

