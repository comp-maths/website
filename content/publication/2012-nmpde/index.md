---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Transparent boundary conditions based on the pole condition for time-dependent, two-dimensional problems"
authors: [Daniel Ruprecht, Achim Schädle, Frank Schmidt]
date: 2012-12-18
doi: "10.1002/num.21759"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-14T12:06:26+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Numerical Methods for Partial Differential Equations"
publication_short: "Numerical Methods for Partial Differential Equations"

abstract: "The pole condition approach for deriving transparent boundary conditions is extended to the time‐dependent, two‐dimensional case. Nonphysical modes of the solution are identified by the position of poles of the solution's spatial Laplace transform in the complex plane. By requiring the Laplace transform to be analytic on some problem‐dependent complex half‐plane, these modes can be suppressed. The resulting algorithm computes a finite number of coefficients of a series expansion of the Laplace transform, thereby providing an approximation to the exact boundary condition. The resulting error decays super‐algebraically with the number of coefficients, so relatively few additional degrees of freedom are sufficient to reduce the error to the level of the discretization error in the interior of the computational domain. The approach shows good results for the Schrödinger and the drift‐diffusion equation but, in contrast to the one‐dimensional case, exhibits instabilities for the wave and Klein–Gordon equation. Numerical examples are shown that demonstrate the good performance in the former and the instabilities in the latter case."

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
