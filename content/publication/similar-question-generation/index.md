---
title: "Auto-Demo Prompting: Leveraging Generated Outputs as Demonstrations for Enhanced Batch Prompting"
authors:
- Longyu Feng
- admin
- Chen Jason Zhang

date: "2024-10-02T00:00:00Z"
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

abstract: Reliable responses of service chatbots are often achieved by employing retrieval-based methods that restrict answers to a knowledge base comprising predefined question-answer pairs (QA pairs). To accommodate potential variations in how a customer's query may be expressed, it emerges as the favored solution to augment these QA pairs with similar questions that are possibly diverse while remaining semantic consistency. This augmentation task is known as Similar Question Generation (SQG). Traditional methods that heavily rely on human efforts or rule-based techniques suffer from limited diversity or significant semantic deviation from the source question, only capable of producing a finite number of useful questions. To address these limitations, we propose an SQG approach based on Large Language Models (LLMs), capable of producing a substantial number of diverse questions while maintaining semantic consistency to the source QA pair. This is achieved by leveraging LLMs' natural language understanding capability through fine-tuning with specially designed prompts. The experiments conducted on a real customer-service dataset demonstrate that our method surpasses baseline methods by a significant margin in terms of semantic diversity. Human evaluation further confirms that integrating the answer that reflects the customer's intention is crucial for increasing the number of generated questions that meet business requirements.

# Summary. An optional shortened abstract.
summary: 

tags:
- Large Language Models

featured: true

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: 'https://arxiv.org/abs/2410.12444'
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
# url_dataset: '#'
# url_poster: '#'
# url_project: ''
# url_slides: ''
# url_source: '#'
# url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: "Simplified schematic overview of a chatbot based on a knowledge base that consists of a set of QA pairs. The yellow region highlights the questions augmented by the similar question generation method. The incoming customer's request is matched with the questions in QA pairs. Then the answer to the best-matched question is selected as the response to the customer."
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
slides: ""
---

<!-- This work is driven by the results in my [previous paper](/publication/conference-paper/) on LLMs.

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/). -->
