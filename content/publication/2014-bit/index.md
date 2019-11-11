---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A multi-level spectral deferred correction method"
authors: [Robert Speck, Daniel Ruprecht, Matthew Emmett, Michael Minion, Matthias Bolten, Rolf Krause]
date: 2014-08-26
doi: "10.1007/s10543-014-0517-x"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-11T13:34:44+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "BIT Numerical Mathematics"
publication_short: "BIT Numerical Mathematics"

abstract: "The spectral deferred correction (SDC) method is an iterative scheme for computing a higher-order collocation solution to an ODE by performing a series of correction sweeps using a low-order timestepping method. This paper examines a variation of SDC for the temporal integration of PDEs called multi-level spectral deferred corrections (MLSDC), where sweeps are performed on a hierarchy of levels and an FAS correction term, as in nonlinear multigrid methods, couples solutions on different levels. Three different strategies to reduce the computational cost of correction sweeps on the coarser levels are examined: reducing the degrees of freedom, reducing the order of the spatial discretization, and reducing the accuracy when solving linear systems arising in implicit temporal integration. Several numerical examples demonstrate the effect of multi-level coarsening on the convergence and cost of SDC integration. In particular, MLSDC can provide significant savings in compute time compared to SDC for a three-dimensional problem."

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

url_pdf:
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
