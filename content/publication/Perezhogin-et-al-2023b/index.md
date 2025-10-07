---
title: 'A Stable Implementation of a Data-Driven Scale-Aware Mesoscale Parameterization'
authors:
 - Pavel_Perezhogin 
 - C. Zhang
 - A. Adcroft
 - C. Fernandez-Granda
 - admin
date: '2024-10-21T00:00:00Z'
doi: 'https://doi.org/10.1029/2023MS004104'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-21T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*JAMES*'
publication_short: ''

abstract: 'Ocean mesoscale eddies are often poorly represented in climate models, and therefore, their effects on the large scale circulation must be parameterized. Traditional parameterizations, which represent the bulk effect of the unresolved eddies, can be improved with new subgrid models learned directly from data. Zanna and Bolton (2020), https://doi.org/10.1029/2020gl088376 (ZB20) applied an equation-discovery algorithm to reveal an interpretable expression parameterizing the subgrid momentum fluxes by mesoscale eddies through the components of the velocity-gradient tensor. In this work, we implement the ZB20 parameterization into the primitive-equation GFDL MOM6 ocean model and test it in two idealized configurations with significantly different dynamical regimes and topography. The original parameterization was found to generate excessive numerical noise near the grid scale. We propose two filtering approaches to avoid the numerical issues and additionally enhance the strength of large-scale energy backscatter. The filtered ZB20 parameterizations led to improved climatological mean state and energy distributions, compared to the current state-of-the-art energy backscatter parameterizations. The filtered ZB20 parameterizations are scale-aware and, consequently, can be used with a single value of the non-dimensional scaling coefficient for a range of resolutions. The successful application of the filtered ZB20 parameterizations to parameterize mesoscale eddies in two idealized configurations offers a promising opportunity to reduce long-standing biases in global ocean simulations in future studies.'

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#url: 'arxiv.org/abs/2302.07984'
#url_pdf: 'arxiv.org/pdf/2302.07984.pdf'
url_pdf: /files/Perezhogin-et-al-2024.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.1029/2023MS004104'
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
