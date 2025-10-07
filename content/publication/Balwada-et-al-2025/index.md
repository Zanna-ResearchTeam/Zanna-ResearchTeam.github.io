---
title: 'Design and implementation of a data-driven parameterization for mesoscale thickness fluxes'
authors:
 - D. Balwada
 - Pavel_Perezhogin
 - A. Adcroft
 - admin

date: '2025-05-27T00:00:00Z'
doi: 'https://doi.org/10.22541/essoar.174835313.30541637/v1'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-27T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: '*Submitted to JAMES*'
publication_short: ''
Abstract: 'Mesoscale eddies are a major sink of available potential energy (APE) in the ocean. When
 these eddies are not resolved or only partially resolved in a model, this effect needs to
 be parameterized to simulate a realistic large-scale state. Traditionally, the Gent-McWilliams
 (GM) parameterization has provided this sink of APE. However, the GM parameterization, which diffuses isopycnal heights, is not accompanied by a skillful prescription for
GM diffusivity rooted in data from observations or models. Also, at eddy permitting resolutions, GM diffusion can negatively impact resolved eddies, and the only scale-aware
prescription is to turn GM off in regions where eddies are permitted. Here we present a novel data-driven parameterization, as a substitute for GM, that extracts APE without overly negative impacts on the resolved flow. It is both flow-aware and scale-aware,
 and its magnitude can be tuned using an O(1) non-dimensional number. Features like
 non-dimensional inputs/outputs, lateral non-locality, flow-dependent coordinates, and
 range limitations improve the generalization of the data-driven scheme. Functional forms
 are learned via a small multi-layer perceptron, ensuring low computational cost and simple implementation in ocean models. The parameterization performs skillfully in offline
 evaluation, especially at scales smaller than the largest eddies. It is implemented in NOAA
 GFDL MOM6 and shown to be skillful in online tests in two-layer idealized simulations of a zonal channel and wind-driven gyre, at both eddy-permitting and non-eddying
 resolutions. This work suggests a path towards leveraging high-resolution simulations
for the reduction of structural error and improvement in the fidelity of climate simulations.'

summary: 

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.22541/essoar.174835313.30541637/v1"
url_pdf: /files/Balwada-et-al-2025.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.22541/essoar.174835313.30541637/v1'
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
