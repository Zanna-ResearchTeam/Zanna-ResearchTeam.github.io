---
title: 'Data-Driven Probabilistic Air-Sea Flux Parameterization'
authors:
 - Jiarong_Wu
 - Pavel_Perezhogin
 - David John Gagne
 - Brandon Reichl
 - Aneesh C Subramanian
 - Elizabeth Thompson
 - admin
date: '2025-03-06T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2503.03990'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-03-06T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: '*Submitted to GRL*'
publication_short: ''


# Summary. An optional shortened abstract.
abstract: Accurately quantifying air-sea fluxes is important for understanding air-sea interactions and improving coupled weather and climate systems. This study introduces a probabilistic framework to represent the highly variable nature of air-sea fluxes, which is missing in deterministic bulk algorithms. Assuming Gaussian distributions conditioned on the input variables, we use artificial neural networks and eddy-covariance measurement data to estimate the mean and variance by minimizing negative log-likelihood loss. The trained neural networks provide alternative mean flux estimates to existing bulk algorithms, and quantify the uncertainty around the mean estimates. Stochastic parameterization of air-sea turbulent fluxes can be constructed by sampling from the predicted distributions. Tests in a single-column forced upper-ocean model suggest that changes in flux algorithms influence sea surface temperature and mixed layer depth seasonally. The ensemble spread in stochastic runs is most pronounced during spring restratification.
tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.48550/arXiv.2503.03990"
url_pdf: /files/Wu-et-al-2025.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.48550/arXiv.2503.03990'
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
