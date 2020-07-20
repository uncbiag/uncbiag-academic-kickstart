---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Image Registration"
summary: "Deformable image registration approaches via numerical optimization and deep learning."
authors: ["Marc Niethammer"]
tags: ["registration","deep learning"]
categories: []
date: 2020-07-01T03:14:43-10:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---

Our group has a long history of developing [image registration approaches]({{<ref "/tags/registration/">}}). In particular, we have been focusing on non-parametric approaches to image registration, where deformations are directly or indirectly parameterized via vector fields. Specifically, we have explored approaches related to the large deformation metric mapping model (LDDMM) and stationary velocity fields for [computational anatomy](https://en.wikipedia.org/wiki/Computational_anatomy).

{{% toc %}}

### Image registration and optimal control

A lot of recent image registration work has moved to deep learning approaches which make use of automatic differentiation. Automatic differentiation in turn is related to adjoint optimization approaches and are intimately related to optimal control. We introduced optimal control approaches for the LDDMM model ({{<cite "hart09a">}}{{<cite "hart09b">}}) which greatly increased ease of formulating and the solution of related registration problems by simplifying gradient formulation due to the adjoint approach. This approach also paved the way for shooting approaches for image registration and geodesic regression ({{<cite "niethammer11">}} which parameterize a deformation only via initial conditions as well as for more general models, such as splines for diffeomorphisms ({{<cite "singh15">}}). Most recently we developed an approach to parameterize neural networks via initial conditions based on this viewpoint ({{<cite "vialard20">}}).

### Image registration in the presence of pathologies or appearance changes

Most registration methods existing today assume that there is perfect correspondence between image pairs to be registered, that transformations are globally smooth, and that image appearance is consistent between modalities or over time. While this is a reasonable assumption for many applications, it is ill suited in case of image pathologies (e.g., tumors, lesions, traumatic brain injury), to capture sliding image motions (e.g., the lung or liver sliding with respect to surrounding tissue), or to model brain maturation during myelination. We have developed multiple approaches to tackle these challenges: 1) by modifying deformation models to make them more realistic ({{<cite "pace13">}}), 2) by modifying image similarity measures to model anticipated changes of appearance ({{<cite "csapo13">}}{{<cite "cao14">}}), and 3) by exploiting population data to infer what should be considered normal and what should be considered abnormal appearance ({{<cite "liu15">}}{{<cite "han18">}}).

### Deep learning approaches for image registration

Deep learning approaches to image registration dramatically reduce the runtime of registration algorithms as costly numerical optimization is replaced by the evaluation of a pre-trained regression network. This now allows registrations of typical 3D magnetic resonance image volumes in about a second on a modern GPU. We developed the first work on deep-learning for non-parametric medical image registration ({{<cite "yang16">}}) which predicted the initial momentum of an LDDMM solution, hence was already able to guarantee diffeomorphic transformations. Because this work is based on patch-wise predictions, it can be applied to very large images if needed. This work was extended and extensively analyzed in {{<cite "yang17">}}, showing competitive performance with state-of-the-art optimization-based deformable image registration approaches; it also included deep-network models to predict displacement and velocity fields. Follow-up work focused on learning the registration metric ({{<cite "niethammer19">}}); jointly learning to predict affine transformations and a nonparametric transformation ({{<cite "shen19a">}}) (including multi-step approaches and training to encourage symmetric models); as well as extensions of the LDDMM approach to spatio-temporal regularizers (i.e., that move with the deforming images) also within a deep-network approach ({{<cite "shen19b">}}). We have also worked on deep registration models which jointly learn to segment and register ({{<cite "xu19">}}) allowing to train a segmentation network with very few samples while improving registration accuracy. Implementations for many of these approaches can be found in our [mermaid]({{<ref "/software/mermaid">}}) and [easyreg]({{<ref "/software/easyreg">}}) registration toolboxes.


### References

{{<putbib "dblp-journalstmi-pace-an-13" "pace13">}}
{{<putbib "dblp-journalsmia-cao-zmpcn-14" "cao14">}}
{{<putbib "dblp-journalstmi-csapo-dsssn-13" "csapo13">}}
{{<putbib "liu-2015-low" "liu15">}}
{{<putbib "dblp-journalsneuroimage-han-kabmavhn-18" "han18">}}

{{<putbib "dblp-confcvpr-hart-zn-09" "hart09a">}}
{{<putbib "dblp-confcdc-niethammer-hz-09" "hart09b">}}
{{<putbib "dblp-confmiccai-niethammer-hv-11" "niethammer11">}}
{{<putbib "dblp-journalsmia-singh-vn-15" "singh15">}}
{{<putbib "dblp-journalscorrabs-2006-10330" "vialard20">}} 

{{<putbib "dblp-confmiccai-yang-kn-16" "yang16">}}
{{<putbib "dblp-journalsneuroimage-yang-ksn-17" "yang17">}}
{{<putbib "dblp-confcvpr-niethammer-kv-19" "niethammer19">}}
{{<putbib "dblp-confcvpr-shen-hxn-19" "shen19a">}}
{{<putbib "dblp-confnips-shen-vn-19" "shen19b">}}
{{<putbib "dblp-confmiccai-xu-n-19" "xu19">}}