---
title: 'InfantCryNet: A Data-driven Framework for Intelligent Analysis of Infant Cries'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - admin
  - Chen Jason Zhang
  - Lingxiao Yang
  - Yuanfeng Song
  - Di Jiang

# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-09-28T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2017-01-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: The 16th Asian Conference on Machine Learning (ACML 2024)
publication_short: ACML 2024

abstract: Understanding the meaning of infant cries is a significant challenge for young parents in caring for their newborns. The presence of background noise and the lack of labeled data present practical challenges in developing systems that can detect crying and analyze its underlying reasons. In this paper, we present a novel data-driven framework, ``InfantCryNet,'' for accomplishing these tasks. To address the issue of data scarcity, we employ pre-trained audio models to incorporate prior knowledge into our model. We propose the use of statistical pooling and multi-head attention pooling techniques to extract features more effectively. Additionally, knowledge distillation and model quantization are applied to enhance model efficiency and reduce the model size, better supporting industrial deployment in mobile devices. Experiments on real-life datasets demonstrate the superior performance of the proposed framework, outperforming state-of-the-art baselines by 4.4% in classification accuracy. The model compression effectively reduces the model size by 7% without compromising performance and by up to 28% with only an 8% decrease in accuracy, offering practical insights for model selection and system design. 

# Summary. An optional shortened abstract.
summary: In this paper, we present a novel data-driven framework named InfantCryNet for detecting and analyzing infant cries.

tags:
  - Machine Learning System

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

# url_pdf: ''
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_poster: ''
# url_project: ''
# url_slides: ''
# url_source: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_video: 'https://youtube.com'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: 'Model architect: (a) CNN10 for infant cry detection, (b) CNN14 for infant cry classification, (c) Knowledge Distillation for model compression.'
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
slides: ""
---