---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Parallel-in-Space-and-Time Simulation of the Three-Dimensional, Unsteady Navier-Stokes Equations for Incompressible Flow"
authors: [Roberto Croce, Daniel Ruprecht, Rolf Krause]
date: 2014-08-26
doi: "10.1007/978-3-319-09063-4_2"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-11T13:30:56+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Modeling, Simulation and Optimization of Complex Processes"
publication_short: "Modeling, Simulation and Optimization of Complex Processes"

abstract: "In this paper we combine the Parareal parallel-in-time method together with spatial parallelization and investigate this space-time parallel scheme by means of solving the three-dimensional incompressible Navier-Stokes equations. Parallelization of time stepping provides a new direction of parallelization and allows to employ additional cores to further speed up simulations after spatial parallelization has saturated. We report on numerical experiments performed on a Cray XE6, simulating a driven cavity flow with and without obstacles. Distributed memory parallelization is used in both space and time, featuring up to 2,048 cores in total. It is confirmed that the space-time-parallel method can provide speedup beyond the saturation of the spatial parallelization."

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
