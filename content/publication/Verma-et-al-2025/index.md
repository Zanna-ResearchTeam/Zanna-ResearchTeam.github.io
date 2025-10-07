---
title: 'Deep Learning of Systematic Ocean Model Errors in a Coupled GCM from Data Assimilation Increments'
authors:
 - Tarun Verma
 - Feiyu Lu
 - Alistair Adcroft
 - admin
 - Anand Gnandesikan
date: '2025-04-24T00:00:00Z'
doi: 'https://doi.org/10.22541/essoar.174547920.05119265/v1'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-24T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
# publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: '*Submitted to JAMES*'
publication_short: ''


# Summary. An optional shortened abstract.
abstract: We present a novel, data-driven approach to predict systematic model errors in the ocean component of a coupled general circulation model leveraging deep learning and data assimilation. We examine the skill of the proposed scheme in learning systematic model errors, including their spatial patterns, variance, scales, and test its sensitivity to different predictors and neural network architecture. The scheme utilizes local state variables such as ocean temperature, salinity, velocities, and surface fluxes to predict corrections to temperature tendency for the upper 1000 meters in the ocean on daily timescales. The performance is evaluated on the withheld test dataset and compared against the empirical climatological temperature corrections that are geographically dependent. The performance is depth-dependent, with significant improvements over the benchmark in the upper 20 meters in the ocean. It degrades rapidly with depth but remains comparable to the climatology benchmark. Neural networks can capture up to 40-50% of the daily variance in temperature increments in the upper 20 meters relative to the benchmark’s 20%. The improvements are associated with networks predicting finer spatiotemporal scales than the benchmark. They are expected to perform better in reducing surface ocean mixed layer bias than previously used techniques. Despite being column-local without geographical inputs, networks can sufficiently reproduce spatial patterns on daily and longer timescales. The patterns consist of corrections to regional dynamical features such as western boundary currents, equatorial undercurrents, bathymetry-related corrections in the Southern Ocean, and warm surface increments over subtropical and midlatitude belts.
tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.22541/essoar.174547920.05119265/v1"
url_pdf: /files/Verma-et-al-2025.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.22541/essoar.174547920.05119265/v1'
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
