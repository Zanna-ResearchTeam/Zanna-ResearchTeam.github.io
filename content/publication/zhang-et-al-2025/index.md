---
title: 'Addressing Out-of-Sample Issues in Multi-Layer Convolutional Neural-Network Parameterization of Mesoscale Eddies Applied Near Coastlines'
authors:
  - C. Zhang
  - Pavel_Perezhogin
  - A. Adcroft
  - admin
date: '2025-05-25T00:00:00Z'
doi: 'https://doi.org/10.1029/2024MS004819'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-04T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*JAMES*'
publication_short: ''

abstract: "This study addresses the boundary artifacts in machine-learned (ML) parameterizations for ocean subgrid mesoscale momentum forcing, as identified in the online ML implementation from a previous study (Zhang et al., 2023, https://doi.org/10.1029/2023ms003697). We focus on the boundary condition (BC) treatment within the existing convolutional neural network (CNN) models and aim to mitigate the “out-of-sample” errors observed near complex coastal regions without developing new, complex network architectures. Our approach leverages two established strategies for placing BCs in CNN models, namely zero and replicate padding. Offline evaluations revealed that these padding strategies significantly reduce root mean squared error (RMSE) in coastal regions by limiting the dependence on random initialization of weights and restricting the range of out-of-sample predictions. Further online evaluations suggest that replicate padding consistently reduces boundary artifacts across various retrained CNN models. In contrast, zero padding sometimes intensifies artifacts in certain retrained models despite both strategies performing similarly in offline evaluations. This study underscores the need for BC treatments in CNN models trained on open water data when predicting near-coastal subgrid forces in ML parameterizations. The application of replicate padding, in particular, offers a robust strategy to minimize the propagation of extreme values that can contaminate computational models or cause simulations to fail. Our findings provide insights for enhancing the accuracy and stability of ML parameterizations in the online implementation of ocean circulation models with coastlines."

# Summary. An optional shortened abstract.
summary: 
tags:
  - Source Themes
featured: false

links:
#  - name: Preprint
#    url: https://doi.org/10.1029/2024MS004819
url_pdf: /files/Zhang_et_al_2025.pdf
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
