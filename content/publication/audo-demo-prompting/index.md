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
publication: "arxiv. [Cited by 1]"
publication_short: ""

abstract: Batch prompting is a common technique in large language models (LLMs) used to process multiple inputs simultaneously, aiming to improve computational efficiency. However, as batch sizes increase, performance degradation often occurs due to the model's difficulty in handling lengthy context inputs. Existing methods that attempt to mitigate these issues rely solely on batch data arrangement and majority voting rather than improving the design of the batch prompt itself. In this paper, we address these limitations by proposing "Auto-Demo Prompting," a novel approach that leverages the question-output pairs from earlier questions within a batch as demonstrations for subsequent answer inference. We provide a formal theoretical analysis of how Auto-Demo Prompting functions within the autoregressive generation process of LLMs, illustrating how it utilizes prior outputs to optimize the model's internal representations. Our method effectively bridges the gap between batch prompting and few-shot prompting, enhancing performance with only a slight compromise in token usage. Experimental results across five NLP tasks demonstrate its effectiveness in mitigating performance degradation and occasionally outperforming single prompts. Furthermore, it opens new avenues for applying few-shot learning techniques, such as demonstration selection, within batch prompting, making it a robust solution for real-world applications. 

# Summary. An optional shortened abstract.
summary: 

tags:
- Large Language Models

featured: true

links:
# - name: Cited by 1
#   url: http://example.org
url_pdf: 'https://arxiv.org/abs/2410.01724'
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
  caption: 'Auto-Demo Prompting: Single prompts are combined into a batch prompt with a special output control for generating question-answer pairs, along with optional batch data selection. This prompt is fed into the autoregressive generation process of a decoder-only LLM, forming demonstrations for subsequent generation'
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
