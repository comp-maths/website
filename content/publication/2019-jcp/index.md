---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "An arbitrary order time-stepping algorithm for tracking particles in inhomogeneous magnetic fields"
authors: [Krasymyr Tretiak and Daniel Ruprecht]
date: 2019-08-23
doi: "10.1016/j.jcpx.2019.100036"

# Schedule page publish date (NOT publication's date).
publishDate: 2019-10-24T14:30:50+02:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "Journal of Computational Physics: X"
publication_short: "Journal of Computational Physics: X"

abstract: "The Lorentz equations describe the motion of electrically charged particles in electric and magnetic fields and are used widely in plasma physics. The most popular numerical algorithm for solving them is the Boris method, a variant of the Störmer-Verlet algorithm. Boris method is phase space volume conserving and simulated particles typically remain near the correct trajectory. However, it is only second order accurate. Therefore, in scenarios where it is not enough to know that a particle stays on the right trajectory but one needs to know where on the trajectory the particle is at a given time, Boris method requires very small time steps to deliver accurate phase information, making it computationally expensive. We derive an improved version of the high-order Boris spectral deferred correction algorithm (Boris-SDC) by adopting a convergence acceleration strategy for second order problems based on the Generalised Minimum Residual (GMRES) method. Our new algorithm is easy to implement as it still relies on the standard Boris method. Like Boris-SDC it can deliver arbitrary order of accuracy through simple changes of runtime parameter but possesses better long-term energy stability. We demonstrate for two examples, a magnetic mirror trap and the Solev'ev equilibrium, that the new method can deliver better accuracy at lower computational cost compared to the standard Boris method. While our examples are motivated by tracking ions in the magnetic field of a nuclear fusion reactor, the introduced algorithm can potentially deliver similar improvements in efficiency for other applications."

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
url_project: /project/epsrc_boris_sdc
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
