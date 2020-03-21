---
title: "Comparison and coupling of continuous and hybridizable discontinuous Galerkin methods$:$ Application to multi-physics problem"
authors: 
- Mahendra Paipuri
date: "2018-03-21T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["7"]

# Publication name and optional abbreviated publication name.
publication: "*Instituto Superior Técnico* and *Universitat Politecnica de Catalunya*"
publication_short: "*Instituto Superior Técnico* and *Universitat Politecnica de Catalunya*"

abstract: This thesis proposes a coupled continuous and hybridizable discontinuous Galerkin formulation to solve conjugate heat transfer problems. This model is then used to find the thermal response of Glass Fiber Reinforced Polymer (GFRP) tubular cross-section under fire. The first step of this thesis is to compare the computational efficiency of high-order Continuous Galerkin (CG) and Hybridizable Discontinuous Galerkin (HDG) methods for incompressible fluid flow problems in low Reynolds number regimes. Only 2-D examples and direct solvers are considered in the present work. A thoroughly comparison in terms of CPU time and accuracy for both discretization methods is made under the same platform. Various results presented suggests that HDG can be more efficient than CG when the CPU time, for a given degree, is considered. The stability of HDG and CG is studied using a manufactured solution that produces a sharp boundary layer, confirming that HDG provides smooth converged solutions in the presence of sharp fronts whereas, CG failed to converge due to the presence of numerical oscillations. %Backward Differentiation Formulae (BDF) schemes are used to solve the unsteady Navier--Stokes equations and an adaptive time stepping scheme is proposed. Following, the solution of the coupled Navier--Stokes/convection-diffusion problem, using Boussinesq approximation, is formulated within the HDG framework and analysed using numerical experiments and benchmark problems. A coupling strategy between HDG and CG methods is proposed in the framework of second-order elliptic operators. The coupled formulation is implemented and its convergence properties are established numerically by using manufactured solutions.  Finally, the proposed coupled formulation between HDG and CG for heat equation is combined with the coupled Navier--Stokes/convection diffusion equations to formulate a new CG-HDG model for solving conjugate heat transfer problems. Benchmark examples are solved using the proposed model and validated with literature values. The final part of the thesis applies the proposed CG-HDG coupled formulation to predict the thermal response of the GFRP tubular cross-section. The radiosity equation that governs the internal radiation is added to the CG-HDG coupled model. Estimates of the discretization errors are computed in order to establish the confidence intervals for quantities of interest. Results with the geometry having curved corners in the cavity are presented and shown to be within the estimated uncertainty intervals. CPU times for the linear solver suggests that the proposed CG-HDG model is more efficient than CG-CG model in all the cases considered. 

# Summary. An optional shortened abstract.
summary: The thesis compares CG and HDG methods for computational efficiency and stability for incompressible fluid flows. Following, a coupling strategy is proposed between CG and HDG methods for heat equation. The final part deals with the validation of proposed CG-HDG formulation for coupled Navier-Stokes convection-diffusion radiosity heat equations with the experimental data of GFRP tubular cross section subjected to fire.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: 'pdf/ThesisPhD.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'pdf/PhD.pdf'
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
slides: ""
---
