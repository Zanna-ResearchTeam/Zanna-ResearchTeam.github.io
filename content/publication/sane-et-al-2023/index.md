---
title: 'Parameterizing Vertical Mixing Coefficients in the Ocean Surface Boundary Layer using Neural Networks'
authors:
 - A. Sane
 - B. G. Reichl
 - A. Adcroft
 - admin
date: '2023-10-23T00:00:00Z'
doi: 'https://doi.org/10.1029/2023MS003890'

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

abstract: "Vertical mixing parameterizations in ocean models are formulated on the basis of the physical principles that govern turbulent mixing. However, many parameterizations include ad hoc components that are not well constrained by theory or data. One such component is the eddy diffusivity model, where vertical turbulent fluxes of a quantity are parameterized from a variable eddy diffusion coefficient and the mean vertical gradient of the quantity. In this work, we improve a parameterization of vertical mixing in the ocean surface boundary layer by enhancing its eddy diffusivity model using data-driven methods, specifically neural networks. The neural networks are designed to take extrinsic and intrinsic forcing parameters as input to predict the eddy diffusivity profile and are trained using output data from a second moment closure turbulent mixing scheme. The modified vertical mixing scheme predicts the eddy diffusivity profile through online inference of neural networks and maintains the conservation principles of the standard ocean model equations, which is particularly important for its targeted use in climate simulations. We describe the development and stable implementation of neural networks in an ocean general circulation model and demonstrate that the enhanced scheme outperforms its predecessor by reducing biases in the mixed-layer depth and upper ocean stratification. Our results demonstrate the potential for data-driven physics-aware parameterizations to improve global climate models."

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#url: 'arxiv.org/abs/2302.07984'
#url_pdf: 'arxiv.org/pdf/2302.07984.pdf'
url_pdf: /files/Sane_et_al_2023.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.1029/2023MS003890'
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
