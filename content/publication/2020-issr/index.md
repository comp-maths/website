---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Combining Coarse and Fine Physics for Manipulation using Parallel-in-Time Integration"
authors: [Wisdom C. Agboh, Daniel Ruprecht, Mehmet R. Dogar]
date: 2020-03-12T09:04:30+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-12T09:04:30+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Symposium on Robotics Research (ISRR), 2019"
publication_short: "International Symposium on Robotics Research (ISRR), 2019"

abstract: "We present a method for fast and accurate physics-based predictions during non-prehensile manipulation planning and control. Given an initial state and a sequence of controls, the problem of predicting the resulting sequence of states is a key component of a variety of model-based planning and control algorithms. We propose combining a coarse (i.e. computationally cheap but not very accurate) predictive physics model, with a fine (i.e. computationally expensive but accurate) predictive physics model, to generate a hybrid model that is at the required speed and accuracy for a given manipulation task. Our approach is based on the Parareal algorithm, a parallel-in-time integration method used for computing numerical solutions for general systems of ordinary differential equations. We adapt Parareal to combine a coarse pushing model with an off-the-shelf physics engine to deliver physics-based predictions that are as accurate as the physics engine but run in substantially less wall-clock time, thanks to parallelization across time. We use these physics-based predictions in a model-predictive-control framework based on trajectory optimization, to plan pushing actions that avoid an obstacle and reach a goal location. We show that with hybrid physics models, we can achieve the same success rates as the planner that uses the off-the-shelf physics engine directly, but significantly faster. We present experiments in simulation and on a real robotic setup."

# Summary. An optional shortened abstract.
summary: ""

tags: []
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: https://arxiv.org/abs/1903.08470
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: https://www.youtube.com/watch?v=5e9oTeu4JOU&feature=youtu.be

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
