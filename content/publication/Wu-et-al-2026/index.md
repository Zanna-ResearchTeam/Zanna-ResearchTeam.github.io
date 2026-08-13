---
title: 'Sampling sea state using a diffusion model
'
authors:
 - Jiarong_Wu
 - Bertrand Chapron
 - admin
date: '2026-06-24T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2606.26389'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-06-24T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: '*Arxiv*'
publication_short: ''


# Summary. An optional shortened abstract.
abstract: Sea state prediction is essential for operational maritime applications and coupled earth system modeling, yet current spectral wave models remain computationally prohibitive for many use cases, including online coupling to climate simulations and making probabilistic (ensemble-based) predictions. While deep learning has recently demonstrated strong performance in weather forecasting, existing AI-based wave models are predominantly deterministic and largely limited to bulk variables such as significant wave height, leaving probabilistic sea state estimation largely unexplored. In this work, we propose a diffusion-based generative model for global sea state estimation that conditions on a relatively long history (5 days) of global wind forcing. This generative model directly samples the complex conditional distribution of sea state without autoregressive time-stepping. Unlike prior approaches, our framework naturally extends beyond bulk variables to estimate partition-related variables and derived quantities, such as Stokes drift and mean square slope. Trained on a 30-year global WAVEWATCH-III hindcast, the model achieves substantial computational acceleration compared with numerical spectral models while delivering skillful predictions and a calibrated ensemble spread for the bulk variables. Our results suggest that diffusion-based sea state sampling offers a promising path toward probabilistic wave forecasting and efficient coupling of sea state information into broader earth system models.
tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.48550/arXiv.2606.26389"
url_pdf: /files/Wu-et-al.2026.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.48550/arXiv.2606.26389'
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
