---
title: 'Implementation and Evaluation of a Machine Learned Mesoscale Eddy Parameterization into a Numerical Ocean Circulation Model'
authors:
  - C. Zhang
  - Pavel_Perezhogin
  - C. Gultekin
  - A. Adcroft
  - C. Fernandez-Granda
  - admin
date: '2023-10-10T00:00:00Z'
doi: 'https://doi.org/10.1029/2023MS003697'

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

abstract: "We address the question of how to use a machine learned (ML) parameterization in a general circulation model (GCM), and assess its performance both computationally and physically. We take one particular ML parameterization (Guillaumin & Zanna, 2021, https://doi.org/10.1002/essoar.10506419.1) and evaluate the online performance in a different model from which it was previously tested. This parameterization is a deep convolutional network that predicts parameters for a stochastic model of subgrid momentum forcing by mesoscale eddies. We treat the parameterization as we would a conventional parameterization once implemented in the numerical model. This includes trying the parameterization in a different flow regime from that in which it was trained, at different spatial resolutions, and with other differences, all to test generalization. We assess whether tuning is possible, which is a common practice in GCM development. We find the parameterization, without modification or special treatment, to be stable and that the action of the parameterization to be diminishing as spatial resolution is refined. We also find some limitations of the machine learning model in implementation: (a) tuning of the outputs from the parameterization at various depths is necessary; (b) the forcing near boundaries is not predicted as well as in the open ocean; (c) the cost of the parameterization is prohibitively high on central processing units. We discuss these limitations, present some solutions to problems, and conclude that this particular ML parameterization does inject energy, and improve backscatter, as intended but it might need further refinement before we can use it in production mode in contemporary climate models."

# Summary. An optional shortened abstract.
summary: 
tags:
  - Source Themes
featured: false

links:
#  - name: Preprint
#    url: https://doi.org/10.5194/egusphere-2022-186
url_pdf: /files/Zhang_et_al_2023.pdf
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
