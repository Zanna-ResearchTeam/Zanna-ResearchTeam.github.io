---
title: 'ClimSim: A large multi-scale dataset for hybrid physics-ML climate emulations'

authors:
- S. Yu
- W. Hannah
- L. Peng 
- J. Lin
- M.A. Bhouri
- R. Gupta
- B. Lütjens
- J. C Will
- G. Behrens
- J. Busecke
- Nora_Loose
- C. Stern
- T. Beucler
- B. Harrop
- B. Hillman
- A. Jenney
- S.L. Ferretti
- N. Liu
- A. Anandkumar
- N. Brenowitz
- V. Eyring
- N. Geneva
- P. Gentine
- S. Mandt
- J. Pathak
- A. Subramaniam
- C. Vondrick
- R. Yu
- admin
- and others


date: '2024-01-30T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2306.08754'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-04-04T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: '*Advances in Neural Information Processing Systems 36 (NeurIPS 2023)*'
publication_short: ''

abstract: "Modern climate projections lack adequate spatial and temporal resolution due to computational constraints, leading to inaccuracies in representing critical processes like thunderstorms that occur on the sub-resolution scale. Hybrid methods combining physics with machine learning (ML) offer faster, higher fidelity climate simulations by outsourcing compute-hungry, high-resolution simulations to ML emulators. However, these hybrid ML-physics simulations require domain-specific data and workflows that have been inaccessible to many ML experts. As an extension of the ClimSim dataset (Yu et al., 2024), we present ClimSim-Online, which also includes an end-to-end workflow for developing hybrid ML-physics simulators. The ClimSim dataset includes 5.7 billion pairs of multivariate input/output vectors, capturing the influence of high-resolution, high-fidelity physics on a host climate simulator's macro-scale state. The dataset is global and spans ten years at a high sampling frequency. We provide a cross-platform, containerized pipeline to integrate ML models into operational climate simulators for hybrid testing. We also implement various ML baselines, alongside a hybrid baseline simulator, to highlight the ML challenges of building stable, skillful emulators. The data (this https URL) and code (this https URL and this https URL) are publicly released to support the development of hybrid ML-physics and high-fidelity climate simulations."
summary: 

tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.48550/arXiv.2306.08754"
url_pdf: '/files/ClimSim.pdf'
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.48550/arXiv.2306.08754'
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
