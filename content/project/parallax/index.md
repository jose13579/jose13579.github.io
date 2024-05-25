---
title: Parallax effect motion generation
summary: I and my team were part of a project to generate parallax effect motion from single view images using depth information, segmentation maps, and inpainting methods.
tags:
- Deep Learning
- Machine Learning
date: "2020-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Parallax Effect Motion
  focal_point: Smart

url_code: ""
url_pdf: uploads/2020-Pinto2020ICIP.pdf
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
{{< video src="featured.mp4" controls="yes" >}}

Stereo vision is a growing topic in computer vision due to the innumerable opportunities and applications this technology offers for the development of modern solutions,  such as virtual and augmentedreality applications. To enhance the user’s experience in three-dimensional virtual environments, the motion parallax estimation isa promising technique to achieve this objective. In this paper, we propose an algorithm for generating parallax motion effects from a single image, taking advantage of state-of-the-art instance segmentation and depth estimation approaches.  This work also presents acomparison against such algorithms to investigate the trade-off between efficiency and quality of the parallax motion effects, taking into consideration a multitask learning network capable of estimating instance segmentation and depth estimation at once. Experimental results and visual quality assessment indicate that the PyD-Netnetwork (depth estimation) combined with Mask R-CNN or FBNet networks (instance segmentation) can produce parallax motion effects with good visual quality
