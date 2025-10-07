---
title: 'Fourier analysis of the physics of transfer learning for data-driven subgrid-scale models of ocean turbulence'
authors:
 - Moein Darman
 - Pedram Hassanzadeh 
 - admin
 - Ashesh Chattopadhyay
date: '2025-04-21T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2504.15487'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
# publication: '**'
publication_short: ''

abstract: "Transfer learning (TL) is a powerful tool for enhancing the performance of neural networks (NNs) in applications such as weather and climate prediction and turbulence modeling. TL enables models to generalize to out-of-distribution data with minimal training data from the new system. In this study, we employ a 9-layer convolutional NN to predict the subgrid forcing in a two-layer ocean quasi-geostrophic system and examine which metrics best describe its performance and generalizability to unseen dynamical regimes. Fourier analysis of the NN kernels reveals that they learn low-pass, Gabor, and high-pass filters, regardless of whether the training data are isotropic or anisotropic. By analyzing the activation spectra, we identify why NNs fail to generalize without TL and how TL can overcome these limitations: the learned weights and biases from one dataset underestimate the out-of-distribution sample spectra as they pass through the network, leading to an underestimation of output spectra. By re-training only one layer with data from the target system, this underestimation is corrected, enabling the NN to produce predictions that match the target spectra. These findings are broadly applicable to data-driven parameterization of dynamical systems."
# Summary. An optional shortened abstract.
summary: ''
tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.48550/arXiv.2504.15487"
url_pdf: /files/Darman-et-al-2025.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.48550/arXiv.2504.15487'
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ''
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
slides:
---
