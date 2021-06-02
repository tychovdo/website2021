---
# Documentation: https://wowchemy.com/docs/managing-content/

title: Rates of Convergence for Sparse Variational Gaussian Process Regression
subtitle: ''
summary: ''
authors:
- David Burt
- Carl Edward Rasmussen
- Mark van der Wilk
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
publishDate: '2021-05-17T09:33:35.875406Z'
publication_types:
- '1'
abstract: Excellent variational approximations to Gaussian process posteriors have
  been developed which avoid the $mathcalOłeft(N^3i̊ght)$ scaling with dataset size
  $N$. They reduce the computational cost to $mathcalOłeft(NM^2g̊ht)$, with $Młl N$
  the number of inducing variables, which summarise the process. While the computational
  cost seems to be linear in $N$, the true complexity of the algorithm depends on
  how $M$ must increase to ensure a certain quality of approximation. We show that
  with high probability the KL divergence can be made arbitrarily small by growing
  $M$ more slowly than $N$. A particular case is that for regression with normally
  distributed inputs in D-dimensions with the Squared Exponential kernel, $M=mathcalO(łog^D
  N)$ suffices. Our results show that as datasets grow, Gaussian process posteriors
  can be approximated cheaply, and provide a concrete rule for how to increase $M$
  in continual learning scenarios.
publication: '*Proceedings of the 36th International Conference on Machine Learning
  (ICML)*'
url_pdf: http://proceedings.mlr.press/v97/burt19a.html
---
