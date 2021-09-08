---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Tighter Bounds on the Log Marginal Likelihood of Gaussian Process Regression
  Using Conjugate Gradients
subtitle: ''
summary: ''
authors:
- Artem Artemev
- David R. Burt
- Mark van der Wilk
tags: []
categories: []
date: '2021-07-01'
lastmod: 2021-05-13T10:09:00+01:00
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
publishDate: '2021-09-02T20:57:16.029118Z'
publication_types:
- '1'
abstract: We propose a lower bound on the log marginal likelihood of Gaussian process
  regression models that can be computed without matrix factorisation of the full
  kernel matrix. We show that approximate maximum likelihood learning of model parameters
  by maximising our lower bound retains many benefits of the sparse variational approach
  while reducing the bias introduced into hyperparameter learning. The basis of our
  bound is a more careful analysis of the log-determinant term appearing in the log
  marginal likelihood, as well as using the method of conjugate gradients to derive
  tight lower bounds on the term involving a quadratic form. Our approach is a step
  forward in unifying methods relying on lower bound maximisation (e.g. variational
  methods) and iterative approaches based on conjugate gradients for training Gaussian
  processes. In experiments, we show improved predictive performance with our model
  for a comparable amount of training time compared to other conjugate gradient based
  approaches.
publication: '*Proceedings of the 38th International Conference on Machine Learning
  (ICML)*'
url_pdf: https://proceedings.mlr.press/v139/artemev21a.html
---
