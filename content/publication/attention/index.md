---
title: "Paying Attention to Other Animal Detections Improves Camera Trap Classification Models"
authors:
- Gaspard Dussert
- Stéphane Dray
- Simon Chamaillé-Jammes
- Vincent Miele
date: "2025-07-19T00:00:00Z"
doi: "https://doi.org/10.1101/2025.07.15.664849"

# Schedule page publish date (NOT publication's date).
publishDate: "2025-07-19T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["preprint"]

# Publication name and optional abbreviated publication name.
publication: "bioRxiv"

abstract: In ecological studies, automated species classification models are increasingly used to process large volumes of camera trap images. Most current classification models rely on a two-step pipeline: a detector first locates and crops animals, followed by a classifier that predicts species independently for each crop. While effective, these models still struggle under challenging conditions and ignore temporal context or information from nearby animals available in sequences of camera trap images, whereas human annotators often use it in difficult cases. We propose to leverage self-attention, a core mechanism of Large Language Models and Vision Transformers, to enable the model to learn relationships between crops occurring in similar contexts. Our self-attention module operates directly on the set of crop embeddings, producing new representations enriched with information from other crops, improving species classification. The module fits into the two-step pipeline without requiring structural change and adds only minimal computational overhead. To address the lack of annotated multi-species sequences, we develop a training strategy that synthetically generates multi-species sequences from mono-specific ones. Compared to an independent classifier baseline, our multi-crop model achieves higher accuracy on mono-specific sequences, both real and synthetic. In multi-species settings, evaluated using synthetic test sets, we also observe a substantial improvement in accuracy. Using real but weakly annotated multi-species sequences, we reformulate the task as multi-label set classification, and conduct a visual analysis, to highlight the benefits of our approach. By leveraging the information brought by all detections of animals in the image and others of the same sequence, our approach reduces species misclassifications and enables more accurate estimates for downstream ecological analyses focusing on, for instance, species richness, occupancy, and species interaction.

featured: true

# links:
# - name: ""
#   url: ""
url_pdf: https://www.biorxiv.org/content/10.1101/2025.07.15.664849v1.full.pdf
url_code: 'https://github.com/gdussert/MCA_Classifier'
url_dataset: 'https://zenodo.org/records/15736090'
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
