---
title: 'Samudra 2: Scaling Ocean Emulators across Resolutions'
authors:
 - Yuan_Yuan
 - Jesse Rusak
 - Alexander Merose
 - Adam_Subel
 - Pavel_Perezhogin
 - A. Adcroft
 - C. Fernandez-Granda
 - admin
date: '2026-05-24T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2606.02610'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-05-24T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: '*Arxiv*'
publication_short: ''


# Summary. An optional shortened abstract.
abstract: "Ocean general circulation models (OGCMs) are essential to climate science but computationally expensive, limiting ensemble size and forcing scenarios. Neural emulators promise orders-of-magnitude speedups, yet existing ocean emulators have not combined fine spatial resolution with multi-year autoregressive rollouts. Samudra, the first autoregressive neural ocean emulator to produce multi-decade global rollouts, is limited to 1∘ resolution and exhibits two long-horizon failure modes: \emph{variance collapse}, the loss of temporal variability, and \emph{imprinting artifacts}, in which velocity patterns leak into deep-ocean fields. We present Samudra 2, which introduces a wider U-Net backbone with modified ConvNeXt-style blocks and a reduced block-internal expansion factor, together with a dynamic loss that reweights output channels according to their prediction errors, strengthening gradients for slow-evolving deep-ocean fields. At 1∘, Samudra 2 increases upper-ocean global-mean temperature R2 from 0.56 to 0.87 and reduces deep-ocean temperature error by roughly sevenfold. The same architecture scales to 1/2∘ and 1/4∘ over approximately 8-year autoregressive rollouts, recovering mesoscale eddies and sharp western boundary currents. Running on a single GPU, Samudra 2 enables larger ensembles for sea-level projections, ocean heat uptake, and climate variability studies. "
tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.48550/arXiv.2606.02610"
url_pdf: /files/Yuan-et-al.2026.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.48550/arXiv.2606.02610'
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
