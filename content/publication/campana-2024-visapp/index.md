---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Image Inpainting on the Sketch-Pencil Domain with Vision Transformers
subtitle: ''
summary: ''
authors:
- Jose Luis Flores Campana
- Luis Gustavo Lorgus Decker
- Marcos Roberto e Souza
- Helena de Almeida Maia
- Helio Pedrini
tags:
- '"Image Inpainting"'
- '"Vision Transformers"'
- '"Sketch-Pencil"'
- '"Image Processing"'
categories: []
date: '2024-02-27'
lastmod: 2024-02-27T23:55:30-03:00
featured: true
draft: false

# Custom links (uncomment lines below)
links:
 - name: Link
   url: https://www.insticc.org/node/TechnicalProgram/visigrapp/2024/presentationDetails/123635

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2024-02-27T02:55:30.416217Z'
publication_types:
- '2'
abstract: 'Image inpainting aims to realistically fill missing regions in images, which requires both structural and textural understanding. Traditionally, methods in the literature have employed Convolutional Neural Networks (CNN), especially Generative Adversarial Networks (GAN), to restore missing regions in a coherent and reliable manner. However, limited receptive fields of the CNNs can sometimes result in unreliable outcomes due to their inability to capture the broader context of the image. Transformer-based models, on the other hand, can learn long-range dependencies through self-attention mechanisms. In order to generate more consistent results, some approaches have further incorporated auxiliary information to guide the understanding of structural information of the model. In this work, we propose a new method for image inpainting that uses sketch-pencil information to guide the restoration of structural, as well as textural elements. Unlike previous works that employ edges, lines, or segmentation maps, we leverage the sketch-pencil domain and the capabilities of Transformers to learn long-range dependencies to properly match structural and textural information, resulting in more consistent results. Experimental results show the effectiveness of our approach, demonstrating either superior or competitive performance when compared to existing methods, especially in scenarios involving complex images and large missing areas.'
publication: '*19th International Joint Conference on Computer Vision, Imaging and Computer Graphics Theory and Applications*'
doi: 10.5220/0012363500003660
---
