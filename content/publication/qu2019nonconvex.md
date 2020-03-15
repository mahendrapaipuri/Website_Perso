---
title: "A Nonconvex Approach for Exact and Eﬃcient Multichannel Sparse Blind Deconvolution"
authors: 
- Qing Qu
- Xiao Li
- Zhihui Zhu
date: "2019-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "In Submission to SIAM Journal on Imaging Science (appearing in NeurIPS'19, spotlight, top 3%)"
publication_short: "SIIMS"

abstract: We study the multi-channel sparse blind deconvolution (MCS-BD) problem, whose task is to simultaneously recover a kernel $a$ and multiple sparse inputs $x_i$ from their circulant convolution $y_i=a ⊛x_i$ ($i=1,...,p$). We formulate the task as a nonconvex optimization problem over the sphere. Under mild statistical assumptions of the data, we prove that the vanilla Riemannian gradient descent (RGD) method, with random initializations, provably recovers both the kernel $a$ and the signals $x_i$ up to a signed shift ambiguity. In comparison with state-of-the-art results, our work shows significant improvements in terms of sample complexity and computational efficiency. Our theoretical results are corroborated by numerical experiments, which demonstrate superior performance of the proposed approach over the previous methods on both synthetic and real datasets.

# Summary. An optional shortened abstract.
summary: We prove first-order method with random initialization solves nonconvex multichannel sparse blind deconvolution with linear rate.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://arxiv.org/pdf/1908.10776.pdf
url_code: https://github.com/qingqu06/MCS-BD
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: "pdf/MCSBD.pdf"
url_source: ''
url_video: ''
url_preprint: https://arxiv.org/abs/1908.10776

# links:
# - name: ""
#   url: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
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
slides: example
---
