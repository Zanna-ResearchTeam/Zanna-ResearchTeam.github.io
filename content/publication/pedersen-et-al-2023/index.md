---
title: 'Reliable coarse-grained turbulent simulations through combined offline learning and neural emulation'
authors:
  - Chris_Pedersen
  - J. Bruna
  - admin
date: '2023-04-04T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2307.13144'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-04T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: '*ICML, Workshop on The Synergy of Scientific and Machine Learning Modeling*, arXiv:2307.13144'
publication_short: ''

abstract: "Integration of machine learning (ML) models of unresolved dynamics into numerical simulations of fluid dynamics has been demonstrated to improve the accuracy of coarse resolution simulations. However, when trained in a purely offline mode, integrating ML models into the numerical scheme can lead to instabilities. In the context of a 2D, quasi-geostrophic turbulent system, we demonstrate that including an additional network in the loss function, which emulates the state of the system into the future, produces offline-trained ML models that capture important subgrid processes, with improved stability properties."

# Summary. An optional shortened abstract.
summary: 
tags:
  - Source Themes
featured: false

links:
#  - name: Preprint
#    url: https://doi.org/10.5194/egusphere-2022-186
url_pdf: /files/Pedersen_et_al_2023.pdf
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
