---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Image Segmentation"
summary: "We have developed multiple image segmentation methods."
authors: []
tags: ["segmentation"]
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

# [here]({{<ref "/publication/dblp-journalscorrabs-2006-10330/index.md" >}})

---

### Non-deep Learning based Segmentation Approaches

We have worked on a number of different general methods for image segmentation based on convex relaxations ({{<cite "zach09a">}}{{<cite "zach09b">}}). We have also devised segmentation methods for the segmentations of fiber bundles from diffusion weighted images ({{<cite "niethammer09">}}) and to extract connectivity information from diffusion tensor images ({{<cite "niethammer10">}}). For the segmentation of biological structures it is often know a-priori how large a particular object should be. We have therefore explored a segmentation method which can impose constraints on the segmentation area ({{<cite "niethammer13">}}).

### Multi-atlas Segmentation

We developed multi-atlas segmentation approaches for knee cartilage ({{<cite "shan14">}}) and have most recently explored deep-learning approaches to predict the trustworthiness of individual atlases for multi-atlas segmentation approaches ({{<cite "ding19">}}).

### Image Segmentation via Deep Learning

As one of our main research directions is image registration, we are exploring image segmentation approaches based on deep-learning which can benefit from our fast deep-learning registration approaches. This has led us so far, for example, to an approach for joint segmentation and registration ({{<cite "xu19">}}) as well as to a segmentation approach based on data augmentation at test time ({{<cite "shen20">}}).

### References

{{<putbib "/publication/dblp-confcvpr-zach-nf-09" "zach09a">}}
{{<putbib "/publication/dblp-confdagm-zach-sn-09" "zach09b">}}
{{<putbib "/publication/dblp-journalsneuroimage-niethammer-zmt-09" "niethammer09">}}
{{<putbib "/publication/dblp-confmiar-niethammer-bzsmss-10" "niethammer10">}}
{{<putbib "/publication/dblp-journalsmia-niethammer-z-13" "niethammer13">}}
{{<putbib "/publication/dblp-journalsmia-shan-zcn-14" "shan14">}}
{{<putbib "/publication/dblp-confmiccai-ding-hn-19" "ding19">}}
{{<putbib "/publication/dblp-confmiccai-xu-n-19" "xu19">}}
{{<putbib "/publication/pre-shen-2020-miccai" "shen20">}}