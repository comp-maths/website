---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Integrating an N-body problem with SDC and PFASST"
authors: [Robert Speck, Daniel Ruprecht, Rolf Krause, Matthew Emmett, Michael Minion, Mathias Winkel, Paul Gibbon]
date: 2014-04-21
doi: "10.1007/978-3-319-05789-7_61"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-14T11:45:11+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Lecture Notes in Computational Science and Engineering"
publication_short: "Lecture Notes in Computational Science and Engineering"

abstract: "Vortex methods for the Navier–Stokes equations are based on a Lagrangian particle discretization, which reduces the governing equations to a first-order initial value system of ordinary differential equations for the position and vorticity of N particles. In this paper, the accuracy of solving this system by time-serial spectral deferred corrections (SDC) as well as by the time-parallel Parallel Full Approximation Scheme in Space and Time (PFASST) is investigated. PFASST is based on intertwining SDC iterations with differing resolution in a manner similar to the Parareal algorithm and uses a Full Approximation Scheme (FAS) correction to improve the accuracy of coarser SDC iterations. It is demonstrated that SDC and PFASST can generate highly accurate solutions, and the performance in terms of function evaluations required for a certain accuracy is analyzed and compared to a standard Runge–Kutta method."

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
