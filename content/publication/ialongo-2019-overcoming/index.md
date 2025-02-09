---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Overcoming Mean-Field Approximations in Recurrent Gaussian Process Models
subtitle: ''
summary: ''
authors:
- Alessandro Davide Ialongo
- Mark van der Wilk
- James Hensman
- Carl Edward Rasmussen
tags: []
categories: []
date: '2019-06-01'
lastmod: 2021-05-13T10:08:56+01:00
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
publishDate: '2021-09-02T20:57:12.729352Z'
publication_types:
- '1'
abstract: We identify a new variational inference scheme for dynamical systems whose
  transition function is modelled by a Gaussian process. Inference in this setting
  has either employed computationally intensive MCMC methods, or relied on factorisations
  of the variational posterior. As we demonstrate in our experiments, the factorisation
  between latent system states and transition function can lead to a miscalibrated
  posterior and to learning unnecessarily large noise terms. We eliminate this factorisation
  by explicitly modelling the dependence between state trajectories and the low-rank
  representation of our Gaussian process posterior. Samples of the latent states can
  then be tractably generated by conditioning on this representation. The method we
  obtain gives better predictive performance and more calibrated estimates of the
  transition function, yet maintains the same time and space complexities as mean-field
  methods.
publication: '*Proceedings of the 36th International Conference on Machine Learning
  (ICML)*'
url_pdf: http://proceedings.mlr.press/v97/ialongo19a.html
---
