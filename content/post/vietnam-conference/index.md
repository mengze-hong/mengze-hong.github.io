---
title:  ✈️ A paper is accepted by ACML 2024. See you in Hanoi, Vietnam!
summary: Meeting c.
date: 2024-12-06
authors:
  - admin
tags:
  - AI
  - Travel
image:
  caption: 'Image credit: [**Mengze Hong**]'
---

Excited to announce our paper [**InfantCryNet: A Data-driven Framework for Intelligent Analysis of Infant Cries**](https://proceedings.mlr.press/v260/hong25a.html) accepted at ACML 2024 in Hanoi, Vietnam. Addresses challenges in detecting and classifying infant cries amid noise and data scarcity. It was especially fortunate to have met and had a brief conversation with Jensen Huang, the CEO and President of NVIDIA, gaining valuable insights into the future of AI.

### Framework Overview
InfantCryNet uses pre-trained audio models for feature extraction. Employs CNN-10 for detection and CNN-14 for classification into six reasons: awake, hug, sleepy, uncomfortable, diaper, hungry. Introduces statistic pooling and multi-head attention pooling for better feature aggregation. Applies knowledge distillation and quantization for model compression.

### Experiments
Datasets: 6,600 clips for detection (6,000 train, 600 test); 835 clips for classification (750 train, 85 test). Baselines: CNN-10, ResNet-22, Wavegram-Logmel-CNN. Trained with Adam optimizer on GPUs.

### Results
Detection: 99.8% accuracy for both CNN-10 and CNN-14. Classification: CNN-14 with pretraining achieves 74.73%, outperforming baselines by 4.4%. Statistic pooling best at 74.73%. Compression: Quantization reduces size 7% no accuracy loss; distillation + quantization reduces 28% with 8% accuracy drop.

### Discussion
Framework enhances efficiency for mobile deployment. Suggests hybrid models and federated learning for future work.