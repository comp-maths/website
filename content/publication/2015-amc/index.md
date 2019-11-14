---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A stencil-based implementation of Parareal in the C++ domain specific embedded language STELLA"
authors: [Andrea Arteaga, Daniel Ruprecht, Rolf Krause]
date: 2015-01-20
doi: "10.1016/j.amc.2014.12.055"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-07T16:08:30+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Applied Mathematics and Computation"
publication_short: "Applied Mathematics and Computation"

abstract: "In view of the rapid rise of the number of cores in modern supercomputers, time-parallel methods that introduce concurrency along the temporal axis are becoming increasingly popular. For the solution of time-dependent partial differential equations, these methods can add another direction for concurrency on top of spatial parallelization. The paper presents an implementation of the time-parallel Parareal method in a C++ domain specific language for stencil computations (STELLA). STELLA provides both an OpenMP and a CUDA backend for a shared memory parallelization, using the CPU or GPU inside a node for the spatial stencils. Here, we intertwine this node-wise spatial parallelism with the time-parallel Parareal. This is done by adding an MPI-based implementation of Parareal, which allows us to parallelize in time across nodes. The performance of Parareal with both backends is analyzed in terms of speedup, parallel efficiency and energy-to-solution for an advection–diffusion problem with a time-dependent diffusion coefficient."

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
