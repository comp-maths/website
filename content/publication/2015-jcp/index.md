---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A high-order boris integrator"
authors: [Mathias Winkel and Robert Speck and Daniel Ruprecht]
date: 2015-04-13
doi: "10.1016/j.jcp.2015.04.022"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-11-07T16:07:11+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Computational Physics"
publication_short: "Journal of Computational Physics"

abstract: "This work introduces the high-order Boris-SDC method for integrating the equations of motion for electrically charged particles in electric and magnetic fields. Boris-SDC relies on a combination of the Boris-integrator with spectral deferred corrections (SDC). SDC can be considered as preconditioned Picard iteration to compute the stages of a collocation method. In this interpretation, inverting the preconditioner corresponds to a sweep with a low-order method. In Boris-SDC, the Boris method, a second-order Lorentz force integrator based on velocity-Verlet, is used as a sweeper/preconditioner. The presented method provides a generic way to extend the classical Boris integrator, which is widely used in essentially all particle-based plasma physics simulations involving magnetic fields, to a high-order method. Stability, convergence order and conservation properties of the method are demonstrated for different simulation setups. Boris-SDC reproduces the expected high order of convergence for a single particle and for the center-of-mass of a particle cloud in a Penning trap and shows good long-term energy stability."

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
projects: [epsrc_boris_sdc]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
