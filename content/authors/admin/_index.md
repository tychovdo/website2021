---
# Display name
title: Mark van der Wilk

# Is this the primary user of the site?
superuser: true

# Role/position/tagline
role: Lecturer in Machine Learning

# Organizations/Affiliations to show in About widget
organizations:
- name: Imperial College London
  url: https://www.imperial.ac.uk/computing/

# Short bio (displayed in user profile at end of posts)
bio: More automatic, more robust models for reinforcement learning.

# Interests to show in About widget
# interests:
# - Artificial Intelligence
# - Computational Linguistics
# - Information Retrieval

# Education to show in About widget
# education:
#   courses:
#   - course: PhD in Artificial Intelligence
#     institution: Stanford University
#     year: 2012
#   - course: MEng in Artificial Intelligence
#     institution: Massachusetts Institute of Technology
#     year: 2009
#   - course: BSc in Artificial Intelligence
#     institution: Massachusetts Institute of Technology
#     year: 2008

# Social/Academic Networking
# For available icons, see: https://sourcethemes.com/academic/docs/page-builder/#icons
#   For an email link, use "fas" icon pack, "envelope" icon, and a link in the
#   form "mailto:your-email@example.com" or "/#contact" for contact widget.
social:
- icon: envelope
  icon_pack: fas
  link: mailto:m.vdwilk@imperial.ac.uk
- icon: twitter
  icon_pack: fab
  link: https://twitter.com/markvanderwilk
- icon: graduation-cap  # Alternatively, use `google-scholar` icon from `ai` icon pack
  icon_pack: fas
  link: https://scholar.google.co.uk/citations?user=PKcjcT4AAAAJ
- icon: github
  icon_pack: fab
  link: https://github.com/markvdw
# - icon: linkedin
#   icon_pack: fab
#   link: https://www.linkedin.com/

# Link to a PDF of your resume/CV.
# To use: copy your resume to `static/media/resume.pdf`, enable `ai` icons in `params.toml`, 
# and uncomment the lines below.
# - icon: cv
#   icon_pack: ai
#   link: media/resume.pdf

# Enter email to display Gravatar (if Gravatar enabled in Config)
email: ""

# Highlight the author in author lists? (true/false)
highlight_name: false
---

# Research

In January 2020 I joined the [Department of Computing](https://www.imperial.ac.uk/computing) at [Imperial College London](http://www.imperial.ac.uk) as a lecturer (assistant professor). My research works towards developing systems which learn to accomplish tasks through experience from interacting with the environment, with as little experience as possible. I aim to let the underlying principles of inference and learning guide my work, both from the point of view of developing practical methods from first principles, and from finding underlying principles in existing methods.

My research is motivated by **reinforcement learning** methods which use explicit **predictive models** of the world to plan behaviour. This approach improves **data efficiency**, as knowledge about the world generalises strongly to new situations. Learning good models of the world, with a reliable estimate of their own **uncertainty**, is crucial to the success of these methods. In addition, they need to be **automatic**, in the sense that they should not rely on human design or intervention as they learn.

Currently, the main component of my research is building better predictive models. In reinforcement learning / decision making applications, we require **a)** uncertainty estimates, for avoiding or taking calculated risks, and **b)** automatic adaptation with increasing data, as more experience is gained. **Bayesian inference** provides an elegant framework for representing uncertainty, and automating many aspects of the modelling process.
Currently, I am interested in bringing the benefits of Bayesian inference to deep learning models, using **Gaussian processes** as a building block.

My work has been presented at the leading machine learning conferences ([NeurIPS](http://neurips.cc) and [ICML](http://icml.cc)), including an [oral presentation](https://papers.nips.cc/paper/6877-convolutional-gaussian-processes) and a [best paper award](http://proceedings.mlr.press/v97/burt19a.html). Personally, I'm currently enthusiastic about our [paper](https://papers.nips.cc/paper/8199-learning-invariances-using-the-marginal-likelihood) on learning what [invariance](https://twitter.com/markvanderwilk/status/1030372400322543618) should be used as an inductive bias for a particular dataset.


## Working with me
I will have spaces for a small number (~2) of PhD students a year in the next few years. I am looking for people with a strong academic background (particularly strong mathematical skills) who are keen to work on topics that are aligned with my interests (see below).

A strong mathematical background is usually demonstrated by a first-class (or equivalent) degree in information or electrical engineering, physics, maths, or computer science. A background in e.g. linear algebra, probability, statistics, and optimisation are particularly important. You can demonstrate alignment with my research interests with a short research statement that outlines **1)** what problem you are interested in, **2)** why this problem is interesting or important, and **3)** what techniques you think will be useful or necessary for reaching your goals.

## Topics
- Bayesian inference and approximations to it (variational inference, EP, MCMC, ...).
- Gaussian process models (deep GPs, GPSSM, GPLVM, ...) or their theoretical properties.
- Bayesian deep learning (inference over weights, using GPs as building blocks, ...).
- Neural networks / other models with invariance properties (e.g. rotation, scale, or more arbitrary) and learning invariances.
- Analysis of deep neural networks (infinite limits and GP relations).
- Model-based reinforcement learning.
- Differentially private machine learning.
- Connections between Bayesian inference and generalisation error bounds.


# About


Before starting at Imperial, I worked with [James Hensman](https://twitter.com/jameshensman) for two years as a machine learning researcher at [PROWLER.io](https://www.prowler.io), a research-led startup aiming to solve a wide variety of decision making problems. I did my PhD in the [Machine Learning Group](http://mlg.eng.cam.ac.uk) at the University of Cambridge, working with [Carl Rasmussen](http://mlg.eng.cam.ac.uk/carl/), and completing my [thesis](vanderwilk-thesis.pdf) in 2017. I was funded by the EPSRC and awarded a [Qualcomm Innovation Fellowship](https://www.qualcomm.com/invention/research/university-relations/innovation-fellowship) for my final year.
During my PhD, I occasionally worked as a machine learning consultant, and I also spent a few months as a visiting researcher at Google in Mountain View, CA. I moved to the UK from the Netherlands for my undergraduate degree in Engineering at [Jesus College](https://www.jesus.cam.ac.uk), University of Cambridge.

<!-- # {{< icon name="download" pack="fas" >}} Download my {{< staticref "media/demo_resume.pdf" "newtab" >}}resumé{{< /staticref >}}. -->
