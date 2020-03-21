---
title: "Comparison of high-order continuous and hybridizable discontinuous Galerkin methods in incompressible fluid flow problems"
authors: 
- Mahendra Paipuri
- Carlos Tiago
- Sonia Fernández-Méndez
date: "2018-05-26T00:00:00Z"
doi: "https://doi.org/10.1016/j.matcom.2018.05.012"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Mathematics and Computers in Simulation*, 153, 35-58, Nov. 2018"
publication_short: "*Mathematics and Computers in Simulation*"

abstract: The computational efficiency and the stability of Continuous Galerkin (CG) methods, with Taylor–Hood approximations, and Hybridizable Discontinuous Galerkin (HDG) methods are compared for the solution of the incompressible Stokes and Navier–Stokes equations at low Reynolds numbers using direct solvers. A thorough comparison in terms of CPU time and accuracy for both discretization methods is made, under the same platform, for steady state problems, with triangular and quadrilateral elements of degree $k=2-9$. Various results are presented such as error *vs.* CPU time of the direct solver, error vs. ratio of CPU times of HDG to CG, *etc.* CG can outperform HDG when the CPU time, for a given degree and mesh, is considered. However, for high degree of approximation, HDG is computationally more efficient than CG, for a given level of accuracy, as HDG produces lesser error than CG for a given mesh and degree. Finally, stability of HDG and CG is studied using a manufactured solution that produces a sharp boundary layer, confirming that HDG provides smooth converged solutions for Reynolds numbers higher than CG, in the presence of sharp fronts.

# Summary. An optional shortened abstract.
summary: The paper compares the accuracy and robustness of Hybridizable Discontinuous Galerkin (HDG) and Continuous Galerkin (CG) methods for Navier-Stokes equations.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/abs/pii/S0378475418301241
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'pdf/comaprison.pdf'
url_source: ''
url_video: ''
url_preprint: ''

# links:
# - name: ""
#   url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ""
#   preview_only: false

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
slides: example
---
