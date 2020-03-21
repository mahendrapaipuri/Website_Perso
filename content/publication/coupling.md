---
title: "Coupling of continuous and hybridizable discontinuous Galerkin methods for conjugate heat transfer problem"
authors: 
- Mahendra Paipuri
- Sonia Fernández-Méndez
- Carlos Tiago
date: "2018-07-05T00:00:00Z"
doi: "https://doi.org/10.1007/s10915-018-0769-8"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Journal of Scientific Computing*, 78, 321–350, July 2018"
publication_short: "*Journal of Scientific Computing*"

abstract: A coupling strategy between hybridizable discontinuous Galerkin (HDG) and continuous Galerkin (CG) methods is proposed in the framework of second-order elliptic operators. The coupled formulation is implemented and its convergence properties are established numerically by using manufactured solutions. Afterwards, the solution of the coupled Navier–Stokes convection–diffusion problem, using Boussinesq approximation, is formulated within the HDG framework and analysed using numerical experiments. Results of Rayleigh–Bénard convection flow are also presented and validated with literature data. Finally, the proposed coupled formulation between HDG and CG for heat equation is combined with the coupled Navier–Stokes/convection diffusion equations to formulate a new CG–HDG model for solving conjugate heat transfer problems. Benchmark examples are solved using the proposed model and validated with literature values. The proposed CG–HDG model is also compared with a CG–CG model, where all the equations are discretized using the CG method, and it is concluded that CG–HDG model can have a superior computational efficiency when compared to CG–CG model.

# Summary. An optional shortened abstract.
summary: The paper proposes two different coupling formulations between Hybridizable Discontinuous Galerkin (HDG) and Continuous Galerkin (CG) methods for second-order elliptic operators.

tags:
- Source Themes
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://link.springer.com/article/10.1007/s10915-018-0769-8
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'pdf/coupling.pdf'
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
