---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "YETI"
summary: ""
authors: ["Marc Niethammer"]
tags: ["perfusion imaging", "deep learning"]
categories: []
date: 2022-04-18T07:05:00-10:00

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

url_code: "https://github.com/uncbiag/YETI-General"
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
This software uses a learning framework (YETI) building on an auto-encoder structure between 2D and 3D image time-series, which incorporates an advection-diffusion model to capture blood perfusion. To help with identifiability, the deep learning model is trained via simulated data from an advection-diffusion simulator. Instead of directly learning the velocity and diffusion tensor fields of the advection diffusion equation, we use representations that
assure incompressible flow and symmetric positive semidefinite diffusion fields. 

The YETI repository can be found here:
https://github.com/uncbiag/YETI-General


