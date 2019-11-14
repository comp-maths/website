---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A massively space-time parallel N-body solver"
authors: [Robert Speck, Daniel Ruprecht, Rolf Krause, Matthew Emmett, Michael Minion, Mathias Winkel, Paul Gibbon]
date: 2012-11-12
doi: "10.1109/SC.2012.6"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-14T13:11:43+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference for High Performance Computing, Networking, Storage and Analysis"
publication_short: "International Conference for High Performance Computing, Networking, Storage and Analysis"

abstract: "We present a novel space-time parallel version of the Barnes-Hut tree code PEPC using PFASST, the Parallel Full Approximation Scheme in Space and Time. The naive use of increasingly more processors for a fixed-size N-body problem is prone to saturate as soon as the number of unknowns per core becomes too small. To overcome this intrinsic strong-scaling limit, we introduce temporal parallelism on top of PEPC's existing hybrid MPI/PThreads spatial decomposition. Here, we use PFASST which is based on a combination of the iterations of the parallel-in-time algorithm parareal with the sweeps of spectral deferred correction (SDC) schemes. By combining these sweeps with multiple space-time discretization levels, PFASST relaxes the theoretical bound on parallel efficiency in parareal. We present results from runs on up to 262,144 cores on the IBM Blue Gene/P installation JUGENE, demonstrating that the spacetime parallel code provides speedup beyond the saturation of the purely space-parallel approach."

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

url_pdf: http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.651.1809&rep=rep1&type=pdf
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
