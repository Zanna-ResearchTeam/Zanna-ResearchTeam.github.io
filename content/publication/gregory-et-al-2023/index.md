---
title: 'Deep learning of systematic sea ice model errors from data assimilation increments'
authors:
 - W. Gregory 
 - M. Bushuk
 - A. Adcroft
 - Y. Zhang
 - admin
date: '2023-09-27T00:00:00Z'
doi: 'https://doi.org/10.1029/2023MS003757' 

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

abstract: "Data assimilation is often viewed as a framework for correcting short-term error growth in dynamical climate model forecasts. When viewed on the time scales of climate however, these short-term corrections, or analysis increments, can closely mirror the systematic bias patterns of the dynamical model. In this study, we use convolutional neural networks (CNNs) to learn a mapping from model state variables to analysis increments, in order to showcase the feasibility of a data-driven model parameterization which can predict state-dependent model errors. We undertake this problem using an ice-ocean data assimilation system within the Seamless system for Prediction and EArth system Research (SPEAR) model, developed at the Geophysical Fluid Dynamics Laboratory, which assimilates satellite observations of sea ice concentration every 5 days between 1982 and 2017. The CNN then takes inputs of data assimilation forecast states and tendencies, and makes predictions of the corresponding sea ice concentration increments. Specifically, the inputs are states and tendencies of sea ice concentration, sea-surface temperature, ice velocities, ice thickness, net shortwave radiation, ice-surface skin temperature, sea-surface salinity, as well as a land-sea mask. We find the CNN is able to make skillful predictions of the increments in both the Arctic and Antarctic and across all seasons, with skill that consistently exceeds that of a climatological increment prediction. This suggests that the CNN could be used to reduce sea ice biases in free-running SPEAR simulations, either as a sea ice parameterization or an online bias correction tool for numerical sea ice forecasts."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#url: 'arxiv.org/abs/2302.07984'
#url_pdf: 'arxiv.org/pdf/2302.07984.pdf'
url_pdf: /files/Gregory_et_al_2023.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.1029/2023MS003757'
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
