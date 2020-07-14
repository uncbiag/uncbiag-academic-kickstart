---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Osteoarthritis"
summary: "Image analysis approaches for the quantitative analysis of osteoarthritis in the knee."
authors: []
tags: ["segmentation","registration","knee","deep learning"]
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

The goal of this project is to optimize and openly provide to the osteoarthritis (OA) community a new technology to rapidly and automatically measure cartilage thickness, appearance and changes on magnetic resonance images (MRI) of the knee for very large image databases. This will allow prediction of OA progression and associations of risk factors for OA with OA progression on an unprecedented scale; future work will focus on incorporating additional disease markers, ranging from MRI-derived biomarkers for bone and synovial lesions, to biochemical biomarkers, to genetic information. OA is the most frequent form of arthritis and a common cause of disability. Knee OA (KOA), in particular, leads to substantial morbidity due to mobility limitations and is the most common indication for total knee arthroplasty (TKA). Although OA is a disease of the joint as an organ, cartilage loss is a central feature.

MRI is a promising technology for more detailed and sensitive assessments of KOA for research purposes. However, MRI technology remains expensive, and although acquisition times have gradually decreased, the post-processing, segmentation, and interpretation of the images remain a rate-limiting step, particularly for large cohort studies. Hence, large datasets cannot be meaningfully analyzed, resulting in multiple small, under-powered studies of select groups. This particularly limits studies of infrequent outcomes (e.g. TKA, disability). Furthermore, the lack of sensitive outcome measures for OA progression limits the ability to establish associations with putative OA risk factors.

Our group initially developed a reliable, validated, and automated atlas-based cartilage segmentation method that allows rapid determination of local cartilage thickness over a large number of images {{<cite "shan14">}}. This method successfully analyzed the full dataset for the Pfizer Longitudinal Study (>700 images total) in about 10,000 CPU hours (four days on a medium-sized cluster) and allowed assessment of cartilage thickness across all time points and all available images in the cohort. We are currently working on advanced analysis approaches that are applicable to datasets orders of magnitude larger. Specifically our goal is the  analysis of the full image dataset of the Osteoarthritis Initiative (OAI). So far we have developed a variety of approaches for automatic cartilage segmentation ({{<cite xu18>}}{{<cite xu19>}}) and registration via deep learning ({{<cite "shen19a">}}{{<cite "shen19b">}}). We have also developed approaches to quantify cartilage thickness based on the resulting cartilage segmentations and to evaluate them in a common atlas coordinate system. Using these approaches, we have successfully processed the entire OAI image dataset (on the order of 40,000 3D images). We have also developed various longitudinal statistical analysis approachs (see for example, {{<cite "huang15">}}) and are currently working on applying extensions of these approaches to the OAI data. Lately, we have also focused efforts on data augmentation approaches which allow training deep segmentation networks with small numbers of labeled images ({{<cite "shen20">}}{{<cite "olut20">}}). 

{{< figure src="oai_analysis_pipeline.png" title="OAI analysis pipeline. From left to right. 1) Input MR image; 2) Automatic segmentation result as obtained from our convolutional neural network; 3) Extracted cartilage in 3D based on which the cartilage thickness is computed; 4) Registration of the input image to atlas space using our fast deep-learning based registration algorithm (this registration then also brings the cartilage segmentation and its associated thickness values to atlas space); 5) Now that everything is in atlas space it is represented in the plane for easy statistical analysis (via unrolling based on a cylinder for the femoral cartilage and projection onto the best-fitting plane for the tibial cartilage). Statistical analyses start from the images on the right." lightbox="true" >}}

### Acknowledgements

This work is currently supported by the  National  Institutes of Health (NIH) under award number NIH 1R01AR072013. The content of our work is solely the responsibility of the authors and does not necessarily represent the official views of the NIH.


{{<putbib "/publication/dblp-journalsmia-shan-zcn-14" "shan14" 2>}}
{{<putbib "/publication/dblp-journalstmi-huang-scwnz-15" "huang15" 2>}}

{{<putbib "/publication/dblp-confcvpr-shen-hxn-19" "shen19a" 2>}}
{{<putbib "/publication/dblp-confnips-shen-vn-19" "shen19b" 2>}}

{{<putbib "/publication/dblp-confmiccai-xu-sn-18" "xu18" 2>}}
{{<putbib "/publication/dblp-confmiccai-xu-n-19" "xu19" 2>}}

{{<putbib "/publication/pre-shen-2020-miccai" "shen20" 2>}}
{{<putbib "/publication/pre-olut-2020-eccv" "olut20" 2>}}