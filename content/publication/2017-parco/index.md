---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Toward fault-tolerant parallel-in-time integration with PFASST"
authors: [Robert Speck and Daniel Ruprecht]
date: 2016-12-21
doi: "10.1016/j.parco.2016.12.001"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-10-28T14:53:20+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Parallel Computing"
publication_short: "Parallel Computing"

abstract: "We introduce and analyze different strategies for the parallel-in-time integration method PFASST to recover from hard faults and subsequent data loss. Since PFASST stores solutions at multiple time steps on different processors, information from adjacent steps can be used to recover after a processor has failed. PFASST’s multi-level hierarchy allows to use the coarse level for correcting the reconstructed solution, which can help to minimize overhead. A theoretical model is devised linking overhead to the number of additional PFASST iterations required for convergence after a fault. The potential efficiency of different strategies is assessed in terms of required additional iterations for examples of diffusive and advective type."

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
