---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Variable-hyperparameter visual transformer for efficient image inpainting
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
- '"Variable-hyperparameter Strategy"'
categories: []
date: '2023-05-11'
lastmod: 2023-05-11T23:55:30-03:00
featured: true
draft: false

# Custom links (uncomment lines below)
links:
 - name: Link
   url: https://www.sciencedirect.com/science/article/abs/pii/S0097849323000614

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
publishDate: '2023-05-11T02:55:30.416217Z'
publication_types:
- '2'
abstract: 'Image inpainting has shown a great evolution in the reconstruction of damaged regions or holes since the advent of deep neural networks. Recently, transformers have been used in the field of computer vision to capture global information about the image, which cannot be done with convolutional neural networks due to the limitation of their local receptive fields. Therefore, the transformer may be essential to achieve realistic results when damaged regions cover a large part of the image. However, the quadratic computational and memory costs in the self-attention layer have led to its prohibited usage in high-resolution images and restricted devices, especially for image inpainting when the method must deal with large masks. To overcome this problem, we propose a variable-hyperparameter visual transformer architecture that (i) subdivides the feature maps into a variable number of multi-scale patches, (ii) distributes the feature map into a variable number of heads to balance the complexity of the self-attention operation, and (iii) includes a new strategy based on depth-wise convolution to reduce the number of channels of the feature map sent to each transformer block. We conduct experiments on three datasets from the literature. Our experiments show that our method consistently achieved the best results for the FID and LPIPS metrics on the CelebA dataset. We obtained competitive results for Places2 and Paris StreetView datasets compared to state-of-the-art methods. Moreover, our model presents the best performance in terms of model size, number of parameters, and FLOPS. Our qualitative results indicate that our proposed method is capable of reconstructing semantic content, such as parts of human faces.'
publication: '*Computers & Graphics*'
doi: https://doi.org/10.1016/j.cag.2023.05.006
---
