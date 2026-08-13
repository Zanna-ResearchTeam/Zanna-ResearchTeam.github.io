---
title: 'FloeNet: A mass-conserving global sea ice emulator that generalizes across climates'
authors:
 - W. Gregory 
 - M. Bushuk
 - J. Duncan
 - E. Wu
 - Adam_Subel
 - S K. Clark
 - B Hurlin
 - O Watt-Meyer 
 - A. Adcroft
 - C Bretherton
 - admin

date: '2026-07-12T00:00:00Z'
doi: 'https://doi.org/10.1029/2026GL122981' 

# Schedule page publish date (NOT publication's date).
publishDate: '2026-07-12T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*GRL*'
publication_short: ''

abstract: 'We introduce FloeNet, a graph neural network trained to emulate the Geophysical Fluid Dynamics Laboratory global sea ice model, SIS2. FloeNet is a mass-conserving model, emulating 6-hr mass and area budget tendencies related to sea ice and snow-on-sea-ice growth, melt, and advection. We train FloeNet using SIS2 data from a reanalysis-forced ice-ocean simulation and test its ability to generalize to pre-industrial and 1% CO2 forcing conditions. FloeNet outperforms a non-conservative model at reproducing sea ice and snow-on-sea-ice mean state, trends, and inter-annual variability, with volume anomaly correlations above 0.96 in the Antarctic and 0.76 in the Arctic, across all forcings. FloeNet also produces the correct thermodynamic-dynamic response to forcing, enabling physical interpretability of emulator output. Finally, we show that FloeNet outputs high-fidelity coupling-related variables, including ice-surface temperature, ice-to-ocean salt flux, and melting energy fluxes. We hypothesize that FloeNet will improve polar climate processes within existing atmosphere and ocean emulators.'
# Summary. An optional shortened abstract.

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#url: 'https://doi.org/10.1029/2026GL122981'
#url_pdf: 'arxiv.org/pdf/arXiv.2603.12449.pdf'
url_pdf: /files/Gregory_et_al_2026b.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.1029/2026GL122981'
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
