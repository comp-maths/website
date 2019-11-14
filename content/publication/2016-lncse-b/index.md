---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Parareal for Diffusion Problems with Space- and Time-Dependent Coefficients"
authors: [Daniel Ruprecht, Robert Speck, Rolf Krause]
date: 2016-01-01
doi: "10.1007/978-3-319-18827-0_37"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-07T16:03:03+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Lecture Notes in Computational Science and Engineering "
publication_short: "Lecture Notes in Computational Science and Engineering "

abstract: "The very rapidly increasing number of cores in state-of-the-art supercomputers fuels both the need for and the interest in novel numerical algorithms inherently designed to feature concurrency. In addition to the mature field of space-parallel approaches (e.g. domain decomposition techniques), time-parallel methods that allow concurrency along the temporal dimension are now an increasingly active field of research, although first ideas, like in [12], go back several decades. A prominent and widely studied algorithm in this area is Parareal, introduced in [10], which has the advantage that one can couple and reuse classical time-stepping schemes in an iterative fashion to parallelize in time. However, there also exist a number of other approaches, e.g. the “parallel implicit time algorithm” (PITA) from [5], the “parallel full approximation scheme in space and time” (PFASST) from [4] or “revisionist integral deferred corrections” (RIDC) from [3] to name a few. Parareal in particular and temporal parallelism in general has been considered early as an addition to spatial parallelism in order to extend strong scaling limits, see [11]. Efficacy of this approach in large-scale parallel simulations on hundreds of thousands of cores has been demonstrated for the PFASST algorithm in [14]."

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
