---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Explicit Parallel-in-time Integration of a Linear Acoustic-Advection System"
authors: [Daniel Ruprecht and Rolf Krause]
date: 2012-03-01
doi: "	10.1016/j.compfluid.2012.02.015"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-08T12:21:24+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Computers & Fluids"
publication_short: "Computers & Fluids"

abstract: "The applicability of the Parareal parallel-in-time integration scheme for the solution of a linear, two-dimensional hyperbolic acoustic-advection system, which is often used as a test case for integration schemes for numerical weather prediction (NWP), is addressed. Parallel-in-time schemes are a possible way to increase, on the algorithmic level, the amount of parallelism, a requirement arising from the rapidly growing number of CPUs in high performance computer systems. A recently introduced modification of the “parallel implicit time-integration algorithm” could successfully solve hyperbolic problems arising in structural dynamics. It has later been cast into the framework of Parareal. The present paper adapts this modified Parareal and employs it for the solution of a hyperbolic flow problem, where the initial value problem solved in parallel arises from the spatial discretization of a partial differential equation by a finite difference method. It is demonstrated that the modified Parareal is stable and can produce reasonably accurate solutions while allowing for a noticeable reduction of the time-to-solution. The implementation relies on integration schemes already widely used in NWP (RK-3, partially split forward Euler, forward–backward). It is demonstrated that using an explicit partially split scheme for the coarse integrator allows to avoid the use of an implicit scheme while still achieving speedup."

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
