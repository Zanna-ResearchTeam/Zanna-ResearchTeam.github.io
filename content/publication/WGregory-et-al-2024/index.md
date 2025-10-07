---
title: 'Machine Learning for Online Sea Ice Bias Correction Within Global Ice-Ocean Simulations'

authors:
- W. Gregory
- M. Bushuk
- Y. Zhang
- A. Adcroft
- admin


date: '2024-01-30T00:00:00Z'
doi: 'https://doi.org/10.1029/2023GL106776'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-04T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*Geophysical Research Letters*'
publication_short: ''

abstract: "In this study, we perform online sea ice bias correction within a Geophysical Fluid Dynamics Laboratory global ice-ocean model. For this, we use a convolutional neural network (CNN) which was developed in a previous study (Gregory et al., 2023, https://doi.org/10.1029/2023ms003757) for the purpose of predicting sea ice concentration (SIC) data assimilation (DA) increments. An initial implementation of the CNN shows systematic improvements in SIC biases relative to the free-running model, however large summertime errors remain. We show that these residual errors can be significantly improved with a novel sea ice data augmentation approach. This approach applies sequential CNN and DA corrections to a new simulation over the training period, which then provides a new training data set to refine the weights of the initial network. We propose that this machine-learned correction scheme could be utilized for generating improved initial conditions, and also for real-time sea ice bias correction within seasonal-to-subseasonal sea ice forecasts."
summary: 

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.1175/JCLI-D-21-0407.1"
url_pdf: '/files/WGregory-et-al.2024.pdf'
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.48550/arXiv.2306.14433'
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
