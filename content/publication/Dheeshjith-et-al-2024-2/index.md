---
title: 'Samudra: An AI Global Ocean Emulator for Climate'
authors:
 - Surya_Dheeshjith
 - Adam_Subel
 - A. Adcroft
 - J. Busecke
 - C. Fernandez-Granda
 - Shubham_Gupta
 - admin
date: '2025-05-24T00:00:00Z'
doi: 'https://doi.org/10.1029/2024GL114318'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-05-24T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: '*GRL*'
publication_short: ''


# Summary. An optional shortened abstract.
summary: AI emulators for forecasting have emerged as powerful tools that can outperform conventional numerical predictions. The next frontier is to build emulators for long climate simulations with skill across a range of spatiotemporal scales, a particularly important goal for the ocean. Our work builds a skillful global emulator of the ocean component of a state-of-the-art climate model. We emulate key ocean variables, sea surface height, horizontal velocities, temperature, and salinity, across their full depth. We use a modified ConvNeXt UNet architecture trained on multidepth levels of ocean data. We show that the ocean emulator - Samudra - which exhibits no drift relative to the truth, can reproduce the depth structure of ocean variables and their interannual variability. Samudra is stable for centuries and 150 times faster than the original ocean model. Samudra struggles to capture the correct magnitude of the forcing trends and simultaneously remains stable, requiring further work.

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.1029/2024GL114318"
url_pdf: /files/Dheeshjith-et-al-2025.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.1029/2024GL114318'
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
