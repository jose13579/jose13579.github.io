---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Multi-Scale Patch Partitioning for Image Inpainting Based on Visual Transformers
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
- '"Multi-Scale Patch Partitioning"'
categories: []
date: '2022-10-27'
lastmod: 2022-10-27T23:55:30-03:00
featured: true
draft: false

# Custom links (uncomment lines below)
links:
 - name: Link
   url: http://sibgrapi.sid.inpe.br/col/sid.inpe.br/sibgrapi/2022/09.16.03.51/doc/paper.pdf

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
publishDate: '2022-10-27T02:55:30.416217Z'
publication_types:
- '2'
abstract: 'Image inpainting is a challenging task that aims to reconstruct missing pixels with semantically coherent content and realistic texture using available information. Modern inpainting works rely on neural networks to generate realistic images. However, due to their limited receptive field in convolution operators, they may produce distorted content when a large region needs to be filled. Recent methods have employed transformers to deal with this problem, but their high computational cost makes it difficult to work with global image information. To address this, we propose a multi-scale patch partitioning strategy to subdivide feature maps into non-overlapping patches and a transformer with a variable number of heads to control the computational cost growth according to the number of patches. Smaller patches enable a broader image coverage, helping to recover structural information, whereas larger patches lead to a reduced computational cost. In contrast to the fixed and small sizes employed in other literature methods, here we explore different patch sizes in the transformer blocks to achieve a good balance between the computational cost and the number of pixel references used in the reconstruction. Extensive experiments on three datasets show that our method achieves very competitive results compared to the state-of-the-art, reaching the best scores in various scenarios, especially for metrics based on human perception. Moreover, our model presented the smallest size. Our qualitative results suggest that the proposed method can reconstruct structural content such as parts of human faces.'
publication: '*35th Conference on Graphics, Patterns and Images*'
doi: 10.1109/SIBGRAPI55357.2022.9991754
---
