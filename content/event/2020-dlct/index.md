---
title: Learning Invariances using the Marginal Likelihood

event: "Deep Learning Classics & Trends"
# event_url: https://twitter.com/CambridgeMLG/status/1387805261524619265

location: "Deep Learning Classics & Trends Reading Group (Online)"
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: A tutorial on Bayesian model selection, and how it can be used to learn invariances using backprop.
abstract: "To improve generalisation in supervised learning, it is common to encourage invariance in the solution, i.e. keeping the output relatively constant to irrelevant transformations of the input. Many techniques can be seen as introducing invariance, such as data augmentation, convolutional structure, or more general group structure. 
But how do we learn what invariances should be used for a dataset? In this talk, we will discuss why the usual training loss is not the right objective function. We instead use the marginal likelihood as suggested by Bayesian inference, and develop a procedure which learns a useful invariance through gradient-based optimisation. Our model learns to be invariant to perturbations that are commonly hand-crafted in data augmentation, and learns very different perturbations depending on the dataset. We finish by speculating on how procedures like these can help automate the creation of network architectures."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2020-06-08"
# date_end: "2020-06-08"
all_day: false

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: [Mark van der Wilk]
tags: []

# Is this a featured talk? (true/false)
featured: false

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
- name: Event
  url: https://rosanneliu.com/dlct/
# - name: Slides (no pause)
#   url: "talk-slides/qualcomm-talk-handout.pdf"
url_code: ""
url_slides: "https://rosanneliu.com/dlctfs/dlct_200608.pdf"
url_handout: ""
url_video: "https://drive.google.com/file/d/10NzfNXz-gp-0hQ_nHfmuKx0qA_t1I83A/view?usp=sharing"

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
# - example
---

