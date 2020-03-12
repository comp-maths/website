---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Parallel-in-time integration of Kinematic Dynamos"
authors: [Andrew T. Clarke, Christopher J. Davies, Daniel Ruprecht, Steven M. Tobias]
date: 2020-03-12T09:04:33+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-12T09:04:33+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv:1902.00387 [physics.comp-ph]"
publication_short: "arXiv:1902.00387 [physics.comp-ph]"

abstract: "The precise mechanisms responsible for the natural dynamos in the Earth and Sun are still not fully understood. Numerical simulations of natural dynamos are extremely computationally intensive, and are carried out in parameter regimes many orders of magnitude away from real conditions. Parallelization in space is a common strategy to speed up simulations on high performance computers, but eventually hits a scaling limit. Additional directions of parallelization are desirable to utilise the high number of processor cores now available. Parallel-in-time methods can deliver speed up in addition to that offered by spatial partitioning but have not yet been applied to dynamo simulations. This paper investigates the feasibility of using the parallel-in-time algorithm Parareal to speed up initial value problem simulations of the kinematic dynamo, using the open source Dedalus spectral solver. Both the time independent Roberts and time dependent Galloway-Proctor 2.5D dynamos are investigated over a range of magnetic Reynolds numbers. Speed ups beyond those possible from spatial parallelization are found in both cases. Results for the Galloway-Proctor flow are promising, with Parareal efficiency found to be close to 0.3. Roberts flow results are less efficient, but Parareal still shows some speed up over spatial parallelization alone. Parallel in space and time speed ups of ∼300 were found for 1600 cores for the Galloway-Proctor flow, with total parallel efficiency of ∼0.16."

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

url_pdf: https://arxiv.org/abs/1902.00387
url_code:
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video:

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
