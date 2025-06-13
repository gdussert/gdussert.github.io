---
title: "Being confident in confidence scores: calibration in deep learning models for camera trap image sequences"
authors:
- Gaspard Dussert
- Simon Chamaillé-Jammes
- Vincent Miele
- Stéphane Dray
date: "2024-06-16T00:00:00Z"
doi: "https://doi.org/10.1002/rse2.412"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-02-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "Remote Sens Ecol Conserv"

abstract: In ecological studies, machine learning models are increasingly being used for the automatic processing of camera trap images. Although this automation facilitates and accelerates the identification step, the results of these models may lack interpretability and their immediate applicability to ecological downstream tasks (e.g. occupancy estimation) remains questionable. In particular, little is known about their calibration, a property that allows confidence scores to be interpreted as probabilities that model's predictions are true. Using a large and diverse European camera trap dataset, we investigate whether deep learning models for species classification in camera trap images are well calibrated. Additionally, as camera traps are often configured to take multiple photos of the same event, we also explore the calibration of predictions aggregated across sequences of images. Finally, we study the effect and the practicality of a post-hoc calibration method, i.e. temperature scaling, for predictions made at image and sequence levels. Based on five established models and three independent test sets, we show that averaging the logits over the sequence, selecting an appropriate architecture, and optionally using temperature scaling can produce well-calibrated models. Our findings have clear implication for, for instance, the calculation of error rates or the selection of confidence score thresholds in ecological studies making use of artificial intelligence models.

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://zslpublications.onlinelibrary.wiley.com/doi/10.1002/rse2.412
url_code: ''
url_dataset: 'https://zenodo.org/records/10014376'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
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
slides: example
---
