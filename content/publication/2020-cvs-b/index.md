---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Performance of parallel-in-time integration for Rayleigh Bénard Convection"
authors: [Andrew Clarke, Chris Davies, Daniel Ruprecht, Steven Tobias, Jeffrey S. Oishi]
date: 2020-03-12T09:04:25+01:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-03-12T09:04:25+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "arXiv:2001.01609 [physics.comp-ph]"
publication_short: "arXiv:2001.01609 [physics.comp-ph]"

abstract: "Rayleigh-Bénard convection (RBC) is a fundamental problem of fluid dynamics, with many applications to geophysical, astrophysical, and industrial flows. Understanding RBC at parameter regimes of interest requires complex physical or numerical experiments. Numerical simulations require large amounts of computational resources; in order to more efficiently use the large numbers of processors now available in large high performance computing clusters, novel parallelisation strategies are required. To this end, we investigate the performance of the parallel-in-time algorithm Parareal when used in numerical simulations of RBC. We present the first parallel-in-time speedups for RBC simulations at finite Prandtl number. We also investigate the problem of convergence of Parareal with respect to to statistical numerical quantities, such as the Nusselt number, and discuss the importance of reliable online stopping criteria in these cases."

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

url_pdf: https://arxiv.org/abs/2001.01609
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
