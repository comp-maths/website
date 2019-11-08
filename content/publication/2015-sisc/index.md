---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Interweaving PFASST and Parallel Multigrid"
authors: [M. L. Minion and R. Speck and M. Bolten and M. Emmett and D. Ruprecht]
date: 2015-10-29
doi: "10.1137/14097536X"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-08T11:47:05+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "SIAM Journal on Scientific Computing"
publication_short: "SIAM Journal on Scientific Computing"

abstract: "The parallel full approximation scheme in space and time (PFASST) introduced by Emmett and Minion in 2012 is an iterative strategy for the temporal parallelization of ODEs and discretized PDEs. As the name suggests, PFASST is similar in spirit to a space-time full approximation scheme multigrid method performed over multiple time steps in parallel. However, since the original focus of PFASST was on the performance of the method in terms of time parallelism, the solution of any spatial system arising from the use of implicit or semi-implicit temporal methods within PFASST have simply been assumed to be solved to some desired accuracy completely at each substep and each iteration by some unspecified procedure. It hence is natural to investigate how iterative solvers in the spatial dimensions can be interwoven with the PFASST iterations and whether this strategy leads to a more efficient overall approach. This paper presents an initial investigation on the relative performance of different strategies for coupling PFASST iterations with multigrid methods for the implicit treatment of diffusion terms in PDEs. In particular, we compare full accuracy multigrid solves at each substep with a small fixed number of multigrid V-cycles. This reduces the cost of each PFASST iteration at the possible expense of a corresponding increase in the number of PFASST iterations needed for convergence. Parallel efficiency of the resulting methods is explored through numerical examples.


Read More: https://epubs.siam.org/doi/10.1137/14097536X"

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
