---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Histology"
summary: "We have developed analysis approaches for histology images. In particular, we have pioneered approaches for appearance normalization."
authors: []
tags: ["histology","breast","skin"]
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

Skin cancer is an important application area, since it is estimated that one in every 75 North Americans will develop a malignant melanoma in their lifetime. If not diagnosed early, malignant melanoma are frequently lethal. Standard practice is to perform biopsies for suspicious-looking skin. These biopsies are then evaluated by dermatopathologists (by inspecting histology slides) and classified into subtypes, which guides further treatment. This problem is an ideal playground to develop new image analysis methods for microscopy because (1) it requires the analysis of cellular and nuclear features, but also the development of methods to assess large-scale architectonic arrangements, (2) it motivates methods for segmentations with area constraints, because cell arrangements range from sparse to densly packed, (3) there is a large amount of data available including survival data with will allow to assess performance of the developed methods in the context of classification and grading in comparison to experts, and (4) developed methods could have immediate clinical impact to guide diagnosis. (Note that while some genetic markers exist they are insufficient to guide clinical diagnosis at this point.)

We are working on methods for slide normalization to allow for quantitative analysis of image features between sets of slides and on methods for feature extraction and classification ({{<cite "couture15">}}
).

{{<putbib "/publication/dblp-confmiccai-couture-mptn-18" "couture18" 2>}}
{{<putbib "/publication/dblp-confisbi-couture-mtpn-15" "couture15" 2>}}
{{<putbib "/publication/dblp-journalscmig-vicory-ctbmwn-15" "vicory15" 2>}}
{{<putbib "/publication/miedema-2011" "miedema11" 2>}}
{{<putbib "/publication/dblp-confmiccai-niethammer-bmwt-10" "niethammer10" 2>}}
{{<putbib "/publication/dblp-confisbi-macenko-nmbwgst-09" "macenko09" 2>}}
{{<putbib "/publication/dblp-confmiccai-singh-cmpn-14" "singh14" 2>}}





