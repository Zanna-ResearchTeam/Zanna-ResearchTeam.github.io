---
title: "Paleoclimate Boundary Conditions as an Out-of-Sample Test for the Forced Response of Ocean Climate Emulators"
authors:
 - Adam_Subel
 - admin
date: '2026-08-13T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2608.13494'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-08-13T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: '*Arxiv*'
publication_short: ''


# Summary. An optional shortened abstract.
abstract: AI weather emulators benefit from clear objectives and metrics, which have led to the rapid development of models that outperform traditional benchmarks. In contrast, long-term climate emulators must reliably reproduce forced responses over months to centuries, while relying on training objectives that span a small number of model time steps. We assess autoregressive, full-depth ocean emulators using data from the midHolocene experiment of a numerical climate model to examine their skill in responding to surface forcings from an in-distribution, out-of-sample climate. We demonstrate that these emulators generalize to new orbital forcings, reproducing the spatial structure of the large-scale response as well as changes in seasonal patterns and in the spatial structure of ocean variability, while underestimating their amplitude. Baselines that infer the ocean state directly from the boundary forcings also recover much of the large-scale pattern, but only near the surface, and capture neither the seasonal nor the variability changes, indicating that these require some representation of dynamics. Despite these successes, the emulators fail to reproduce the slow, internally driven evolution of the ocean interior. We then show that the emulators' total forced response is well reconstructed by linearly composing their independent responses to each forcing component. Tracking response across training epochs, we find that convergence on mean state metrics in the training climate does not guarantee that the emulators capture the dynamics necessary for a skillful response. Together, these experiments establish the midHolocene as a controlled, ground-truthed setting for diagnosing forced-response failures before emulators are pushed to out-of-distribution climates.
tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.48550/arXiv.2608.13494"
url_pdf: /files/Subel-and-Zanna-2026.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.48550/arXiv.2608.13494'
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
