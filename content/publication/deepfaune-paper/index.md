---
title: "The DeepFaune initiative: a collaborative effort towards the automatic identification of European fauna in camera trap images"
authors:
- Noa Rigoudy
- Gaspard Dussert
- the DeepFaune consortium
- Bruno Spataro
- Vincent Miele
- Simon Chamaillé-Jammes
date: "2023-10-20T00:00:00Z"
doi: "10.1007/s10344-023-01742-7"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-10-20T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "European Journal of Wildlife Research"

abstract: Camera traps have revolutionized how ecologists monitor wildlife, but their full potential is realized only when the hundreds of thousands of collected images can be readily classified with minimal human intervention. Deep learning classification models have allowed extraordinary progress towards this end, but trained models remain rare and are only now emerging for European fauna. We report on the first milestone of the DeepFaune initiative [https://www.deepfaune.cnrs.fr](https://www.deepfaune.cnrs.fr), a large-scale collaboration between more than 50 partners involved in wildlife research, conservation and management in France. We developed a classification model trained to recognize 26 species or higher-level taxa that are common in Europe, with an emphasis on mammals. The classification model achieved 0.97 validation accuracy and often > 0.95 precision and recall for many classes. These performances were generally higher than 0.90 when tested on independent out-of-sample datasets for which we used image redundancy contained in sequences of images. We implemented our model in a software to classify images stored locally on a personal computer, so as to provide a free, user-friendly, and high-performance tool for wildlife practitioners to automatically classify camera trap images. The DeepFaune initiative is an ongoing project, with new partners joining regularly, which allows us to continuously add new species to the classification model.

featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://link.springer.com/article/10.1007/s10344-023-01742-7
url_code: 'https://plmlab.math.cnrs.fr/deepfaune/software'
url_dataset: ''
url_poster: ''
url_project: 'https://www.deepfaune.cnrs.fr/'
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
projects: [deepfaune]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---
