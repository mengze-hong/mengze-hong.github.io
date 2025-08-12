---
title: 📈 Released QualBench - benchmarking Chinese LLMs with localized professional qualifications. 
summary: Open-sourced Chinese LLMs (e.g., Qwen-7B) outperformed strongher English LLMs (e.g., GPT4o) in localized Chinese qualification exams!
date: 2025-05-08
authors:
  - admin
tags:
  - AI
  - LLMs
image:
  caption: 'Image credit: [**Mengze Hong**](https://arxiv.org/abs/2505.0522)'
---

### Introduction
[**QualBench**](https://arxiv.org/abs/2505.05225) is the first multi-domain Chinese QA benchmark for localized evaluation of Chinese LLMs. It uses 17,000+ questions from 24 professional qualifications across six vertical domains: Production Safety, Fire Safety, Civil Engineering, Economics and Finance, Oil and Gas, Banking and Insurance. Grounded in Chinese policies, it highlights gaps in domain knowledge.

### Dataset Construction
Data from 24 exams, spanning up to 10 years. Preprocessed to exclude non-textual questions, remove duplicates, and verify with experts. Includes 9,419 single-choice, 3,394 multiple-choice, and 4,485 True/False questions. Imbalanced towards overlooked domains like Production Safety.

### Experiments
Evaluated five Chinese LLMs (ChatGLM3, Qwen2.5, Baichuan2, Hunyuan-v2, Deepseek-v2) and four non-Chinese (Mistral-7B, LLaMA-7B, GPT-3.5, GPT-4o). One-shot prompting as Chinese domain experts. Also tested LLM crowdsourcing via majority and weighted voting.

{{% callout note %}}

Qwen2.5-7B topped at 75.26% accuracy, outperforming GPT-4o (61.61%). 

Chinese models beat non-Chinese, emphasizing localized knowledge. 

Crowdsourcing underperformed single strong models. 

{{% /callout %}}