---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Bayesian Image Classification with Deep Convolutional Gaussian Processes
subtitle: ''
summary: ''
authors:
- Vincent Dutordoir
- Mark van der Wilk
- Artem Artemev
- James Hensman
tags: []
categories: []
date: '2020-08-01'
lastmod: 2021-05-13T10:08:57+01:00
featured: false
draft: false

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
publishDate: '2021-09-02T20:57:13.745605Z'
publication_types:
- '1'
abstract: In decision-making systems, it is important to have classifiers that have
  calibrated uncertainties, with an optimisation objective that can be used for automated
  model selection and training. Gaussian processes (GPs) provide uncertainty estimates
  and a marginal likelihood objective, but their weak inductive biases lead to inferior
  accuracy. This has limited their applicability in certain tasks (e.g. image classification).
  We propose a translation insensitive convolutional kernel, which relaxes the translation
  invariance constraint imposed by previous convolutional GPs. We show how we can
  use the marginal likelihood to learn the degree of insensitivity. We also reformulate
  GP image-to-image convolutional mappings as multi-output GPs, leading to deep convolutional
  GPs. We show experimentally that our new kernel improves performance in both single-layer
  and deep models. We also demonstrate that our fully Bayesian approach improves on
  dropout-based Bayesian deep learning methods in terms of uncertainty and marginal
  likelihood estimates.
publication: '*Proceedings of the Twenty Third International Conference on Artificial
  Intelligence and Statistics (AISTATS)*'
url_pdf: http://proceedings.mlr.press/v108/dutordoir20a.html
---
