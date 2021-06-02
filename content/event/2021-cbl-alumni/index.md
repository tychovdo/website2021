---
title: How Accurate Gaussian Processes can help Deep Learning

event: Cambridge CBL Alumni Series
event_url: https://twitter.com/CambridgeMLG/status/1387805261524619265

location: Cambridge Computational & Biological Learning group (Online)
# address:
#   street: 450 Serra Mall
#   city: Stanford
#   region: CA
#   postcode: '94305'
#   country: United States

summary: How Accurate Gaussian Processes can help Deep Learning.
abstract: "In my opinion, model selection is the most appealing capability of Bayesian inference, which has the most to offer in deep learning. However, performing Bayesian model selection requires accurate approximate inference. In the first part of the talk, I will discuss accurate inference in the fundamental building block of deep neural networks: a single layer. Specifically, I will focus on the Gaussian process (GP) representation of neural network layers, and present some recent work on inducing point and conjugate gradient approximations, while paying close attention to the question of what we should expect from methods that we consider “good” or even “exact”. In the second part of the talk, I will discuss how these techniques can be of use in model selection in deep learning, with examples on learning invariances. I will close off with some thoughts on how these ideas may develop in the future."

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2021-04-30T16:00:00Z"
date_end: "2021-04-30T18:00:00Z"
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
  url: https://twitter.com/CambridgeMLG/status/1387805261524619265
- name: Slides (no pause)
  url: "talk-slides/cbl-alumni-talk-2021-handout.pdf"
url_code: ""
url_slides: "talk-slides/cbl-alumni-talk-2021-slides.pdf"
url_handout: ""
url_video: ""

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

### Context
This talk was given as part of a series where alumni of the group where I did my PhD were invited to return to discuss their research. This is one of those talks with a high-level overview of recent work, together with some opinions on how they relate to larger questions in the field.

<!-- {{% callout note %}}
Click on the **Slides** button above to view the built-in slides feature.
{{% /callout %}}

Slides can be added in a few ways:

- **Create** slides using Wowchemy's [*Slides*](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. --!>