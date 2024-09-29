---
title: "Pairwise Judgment Formulation for Semantic Embedding Model in Web Search"
authors:
- admin
- Chen Jason Zhang

date: "2024-08-08T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "arxiv"
publication_short: ""

abstract: Semantic Embedding Model (SEM), a neural network-based Siamese architecture, is gaining momentum in information retrieval and natural language processing. In order to train SEM in a supervised fashion for Web search, the search engine query log is typically utilized to automatically formulate pairwise judgments as training data. Despite the growing application of semantic embeddings in the search engine industry, little work has been done on formulating effective pairwise judgments for training SEM. In this paper, we make the first in-depth investigation of a wide range of strategies for generating pairwise judgments for SEM. An interesting (perhaps surprising) discovery reveals that the conventional pairwise judgment formulation strategy wildly used in the field of pairwise Learning-to-Rank (LTR) is not necessarily effective for training SEM. Through a large-scale empirical study based on query logs and click-through activities from a major commercial search engine, we demonstrate the effective strategies for SEM and highlight the advantages of a hybrid heuristic (i.e., Clicked > Non-Clicked) in comparison to the atomic heuristics (e.g., Clicked > Skipped) in LTR. We conclude with best practices for training SEM and offer promising insights for future research. 

# Summary. An optional shortened abstract.
summary: 

tags:
- Information Retrieval

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://arxiv.org/abs/2408.04197
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

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

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
