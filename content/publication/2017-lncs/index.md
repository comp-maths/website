---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Shared Memory Pipelined Parareal"
authors: [Daniel Ruprecht]
date: 2017-08-01
doi: "10.1007/978-3-319-64203-1_48"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-10-28T14:54:47+01:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Lecture Notes in Computer Science"
publication_short: "Lecture Notes in Computer Science"

abstract: "For the parallel-in-time integration method Parareal, pipelining can be used to hide some of the cost of the serial correction step and improve its efficiency. The paper introduces a basic OpenMP implementation of pipelined Parareal and compares it to a standard MPI-based variant. Both versions yield almost identical runtimes, but, depending on the compiler, the OpenMP variant consumes about 7% less energy and has a significantly smaller memory footprint. However, its higher implementation complexity might make it difficult to use in legacy codes and in combination with spatial parallelisation."

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
url_code: https://github.com/Parallel-in-Time/PararealF90
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
