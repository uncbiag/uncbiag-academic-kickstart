---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Histology"
summary: "Analysis approaches for histology images; in particular, for appearance normalization."
authors: ["Marc Niethammer"]
tags: ["histology","breast","skin","deep learning"]
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

We have developed various image analysis approaches in the context of skin and breast cancer, based on histology images obtained via tissue biopsies. In many cases tissue suptypes are of interest which can, for example, be defined from genomics or derived from image characteristics. This is an ideal playground to develop new image analysis methods for microscopy, for example, to 1) extract cellular and nuclear features, to 2) assess large-scale architectonic arrangements, 3) to relate image characteristics to survival and recurrence, and 4) to develop methods with the potential for clinical impact on diagnosis and treatment.

To this end, we have worked on methods for slide normalization to allow for quantitative analysis of image features between sets of slides ({{<cite "macenko09">}}{{<cite "niethammer10">}}{{<cite "vicory15">}}), on methods to characterize cell arrangements ({{<cite "miedema11">}}{{<cite "singh14">}}), as well as on machine learning approaches for feature extraction and classification ({{<cite "couture15">}}{{<cite "couture18">}}).

{{<putbib "/publication/dblp-confmiccai-couture-mptn-18" "couture18" 2>}}
{{<putbib "/publication/dblp-confisbi-couture-mtpn-15" "couture15" 2>}}
{{<putbib "/publication/miedema-2011" "miedema11" 2>}}
{{<putbib "/publication/dblp-journalscmig-vicory-ctbmwn-15" "vicory15" 2>}}
{{<putbib "/publication/dblp-confmiccai-niethammer-bmwt-10" "niethammer10" 2>}}
{{<putbib "/publication/dblp-confisbi-macenko-nmbwgst-09" "macenko09" 2>}}
{{<putbib "/publication/dblp-confmiccai-singh-cmpn-14" "singh14" 2>}}





