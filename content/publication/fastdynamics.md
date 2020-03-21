---
title: "Macroscopic traffic dynamics under fast-varying demand"
authors: 
- Ludovic Leclercq
- Mahendra Paipuri
date: "2019-10-23T00:00:00Z"
doi: "https://doi.org/10.1287/trsc.2019.0908"

# Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "*Transportation Science*, 53(6): 1526–1545, Oct. 2019"
publication_short: "*Transportation Science*"

abstract: Aggregated dynamic traffic models based on the network macroscopic fundamental diagram (MFD) have been founded on stationary or steady-state approximations. Theoretically, they are only qualified with slow-varying demand profiles as inputs. In practice, MFD models are often fed with fast-varying demand patterns classically observed during peak hours. This paper investigates the accuracy of existing MFD model outputs in such a case. It also provides a fresh look at hysteresis loops that may arise on MFD shapes and shows how they are connected to the demand profile. First derived are the exact solutions of the Lighthill, Whitham, and Richards (LWR) model for a simple but meaningful test case corresponding to the loading and the recovery of an arterial with a single bottleneck. The spatial integration of these solutions permits to derive the average flow- and outflow-MFD patterns. The average flow-MFD exhibits a clockwise hysteresis loop with higher flows during the network loading than during the recovery. The outflow MFD shows an opposite trend with a counterclockwise hysteresis loop. The detailed analysis of the LWR solution highlights that these patterns are fully driven by the congestion dynamics and different wave propagation during both periods. This complements existing studies that tend to explain hysteresis by heterogeneous network loading due to unbalanced flows at intersections. It should be noted that the size of the production-MFD hysteresis loop is influenced by the demand loading profile, which means that the MFD is more sensitive to the demand than initially expected. The second part of the paper is about the implications of these observations on the MFD simulation. The main conclusion is that the accumulation-based formulation captures properly the aggregate dynamics of the LWR model during saturation but not in free-flow. It should be calibrated with an average flow-MFD that does not account for the hysteresis pattern to properly estimate the outflow. On the contrary, the original formulation of the trip-based model is only valid in free-flow. During saturation, it should be patched to modify the outflow values. The best approach is a hybrid model that combines the trip-based model in free-flow and the accumulation-based model during saturation. Note that in free-flow the trip-based model is better fed by the average flow-MFD with hysteresis as it gives better estimation for the mean speed. Finally, some evidences are presented and tend to confirm that all the conclusions remain valid for more complex urban settings.

# Summary. An optional shortened abstract.
summary: The paper investigates the production-MFD and outflow-MFD hysteresis using exact solutions of LWR model. 

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://pubsonline.informs.org/doi/10.1287/trsc.2019.0908
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
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
