---
title: 'A Monte Carlo Framework for Calibrated Uncertainty Estimation in Sequence Prediction'

authors:
- Q Yang
- W Zhu
- J Keslin
- admin
- T GJ Rudner
- C Fernandez-Granda


date: '2024-10-30T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2410.23272'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-30T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: '*arXiv:2410.23272*'
publication_short: ''

abstract: "Probabilistic prediction of sequences from images and other high-dimensional data is a key challenge, particularly in risk-sensitive applications. In these settings, it is often desirable to quantify the uncertainty associated with the prediction (instead of just determining the most likely sequence, as in language modeling). In this paper, we propose a Monte Carlo framework to estimate probabilities and confidence intervals associated with the distribution of a discrete sequence. Our framework uses a Monte Carlo simulator, implemented as an autoregressively trained neural network, to sample sequences conditioned on an image input. We then use these samples to estimate the probabilities and confidence intervals. Experiments on synthetic and real data show that the framework produces accurate discriminative predictions, but can suffer from miscalibration. In order to address this shortcoming, we propose a time-dependent regularization method, which is shown to produce calibrated predictions."
summary: 

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.48550/arXiv.2410.23272"
url_pdf: '/files/Yang-et-al-2024.pdf'
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.48550/arXiv.2411.06604'
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
