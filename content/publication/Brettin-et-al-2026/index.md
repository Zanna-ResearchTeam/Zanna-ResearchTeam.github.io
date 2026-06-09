---
title: 'Estimation of temperature and precipitation uncertainties using quantile neural networks'
authors:
 - Andrew_Brettin
 - admin
 
date: '2026-01-24T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2601.17243'

# Schedule page publish date (NOT publication's date).
publishDate: '2026-01-24T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
# publication: '**'
publication_short: ''


# Summary. An optional shortened abstract.
abstract: "Extreme events pose significant risks and are challenging to predict. Assessing climate hazards requires placing quantitative constraints on geophysical fields under observable but fluctuating conditions. We propose a framework for estimating uncertainties -- a ReLU-bias loss quantile neural network (RBLQNN) -- with two novel modifications to the loss function to enforce uniform quantile accuracy and reduce degenerate predicted probability distributions. We evaluate the RBLQNN against other probabilistic baselines on a suite of datasets: synthetic datasets, observed daily temperature maxima from 1,501 NOAA Global Surface Summary of the Day (GSOD) weather stations, and altimetry-observed precipitation from the Tropical Rainfall Measuring Mission (TRMM). On synthetic datasets, the RBLQNN accurately predicts conditional distributions where more restrictive methods like linear quantile regression (LQR) or mean-variance estimation (MVE) neural networks fail, mitigates shortcomings of some other quantile neural networks, and converges stably under a range of hyperparameters. When applied to daily temperature maxima, the RBLQNN reveals that temperature distributions are relatively well described by Gaussian statistics, though nonlinear dependencies on local sea level pressure and geopotential heights appear important. For precipitation statistics, the RBLQNN strongly outperforms both LQR and MVE baselines, demonstrating its capacity to capture highly nonlinear and non-Gaussian conditional distributions. The RBLQNN's performance across varied datasets demonstrates it is a flexible and general approach for constraining uncertainties in geophysical quantities with nonlinear or non-Gaussian conditional dependencies."
tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.48550/arXiv.2601.17243"
url_pdf: /files/Brettin-et-al-2026.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.48550/arXiv.2601.17243'
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
