---
title: 'CAMulator: Fast Emulation of the Community Atmosphere Model'
authors:
 - William E Chapman
 - John S Schreck
 - Yingkai Sha
 - David John Gagne II
 - Dhamma Kimpara
 - admin
 - Kirsten J Mayer
 - Judith Berner
date: '2025-04-08T00:00:00Z'
doi: 'https://doi.org/10.48550/arXiv.2504.06007'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-04-08T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: '*Arxiv*'
publication_short: ''


# Summary. An optional shortened abstract.
abstract: We introduce CAMulator version 1, an auto-regressive machine-learned (ML) emulator of the Community Atmosphere Model version 6 (CAM6) that simulates the next atmospheric state given the prescribed sea surface temperatures and incoming solar radiation. CAMulator explicitly conserves global dry air mass, moisture, and total atmospheric energy while remaining numerically stable over indefinite climate integrations. It successfully reproduces the annual CAM6 climatology and key modes of climate variability, including the El Niño-Southern Oscillation, the North Atlantic Oscillation, and the Pacific-North American pattern, with slightly muted variability. When forced with sea surface temperature (SST) outside the training distribution, CAMulator exhibits a systematic cold bias in high-latitude regions, particularly in boreal winter, likely due to the absence of interactive land and sea ice. Nonetheless, CAMulator achieves these results with a 350 times speedup over CAM6, making it an efficient alternative for generating large ensembles.
tags:
  - Source Themes
featured: false

# links:
# - name: ""
#   url: "https://doi.org/10.48550/arXiv.2504.06007"
url_pdf: /files/Chapman-et-al-2025.pdf
url_code: ''
url_dataset: ''
url_DOI: 'https://doi.org/10.48550/arXiv.2504.06007'
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
