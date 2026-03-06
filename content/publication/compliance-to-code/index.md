---
title: 'Compliance-to-Code: Enhancing Financial Compliance Checking via Code Generation'
authors:
  - admin
  - Jian Chen
  - Rui Yao
  - Xuming Hu
  - Peilin Zhou
  - Weihua Qiu
  - Simin Zhang
  - Chucheng Dong
  - Zhiyao Li
  - Qipeng Xie
  - Zixuan Yuan
author_notes:
  - 'Equal contribution'
  - 'Equal contribution'
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
  - ''
date: '2025-05-19T00:00:00Z'
doi: ''
publishDate: '2025-01-01T00:00:00Z'
publication_types: ['paper-conference']
publication: In *KDD 2026 Dataset & Benchmark Track* Poster
publication_short: In *KDD 2026* Poster
abstract: Regulatory compliance has become a cornerstone of corporate governance, ensuring adherence to systematic legal frameworks. At its core, financial regulations often comprise highly intricate provisions, layered logical structures, and numerous exceptions, which inevitably result in labor-intensive or comprehension challenges. To mitigate this, recent Regulatory Technology (RegTech) and Large Language Models (LLMs) have gained significant attention in automating the conversion of regulatory text into executable compliance logic. However, their performance remains suboptimal particularly when applied to Chinese-language financial regulations, due to three key limitations - (1) incomplete domain-specific knowledge representation, (2) insufficient hierarchical reasoning capabilities, and (3) failure to maintain temporal and logical coherence. To fill these gaps, we present Compliance-to-Code, the first large-scale Chinese dataset dedicated to financial regulatory compliance. Covering 1,159 annotated clauses from 361 regulations across ten categories, each clause is modularly structured with four logical elements—subject, condition, constraint, and contextual information—along with regulation relations. We provide deterministic Python code mappings, detailed code reasoning, and code explanations to facilitate automated auditing. To demonstrate utility, we present FinCheck - a pipeline for regulation structuring, code generation, and report generation.
summary: The first large-scale Chinese dataset for financial regulatory compliance with automated checking pipeline.
tags:
  - Financial Compliance
  - Code Generation
  - Large Language Models
featured: true
links:
  - name: ArXiv
    url: https://arxiv.org/abs/2505.19804
url_pdf: 'https://arxiv.org/pdf/2505.19804.pdf'
url_code: 'https://github.com/AlexJJJChen/Compliance-to-Code'
url_dataset: 'https://huggingface.co/datasets/GPS-Lab/Compliance-to-Code'
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''
image:
  caption: 'Compliance-to-Code Framework'
  focal_point: ''
  preview_only: false
projects: []
slides: ""
---

## Abstract

This paper presents Compliance-to-Code, a large-scale Chinese dataset for financial regulatory compliance, containing 1,159 annotated clauses from 361 regulations across ten categories. Each clause is structured with four logical elements: subject, condition, constraint, and contextual information. The dataset includes deterministic Python code mappings and detailed reasoning to facilitate automated compliance checking.

## Dataset Overview

- **Scale**: 1,159 annotated regulatory clauses
- **Coverage**: 361 regulations across ten financial categories  
- **Structure**: Modular compliance units with logical elements
- **Code Mappings**: Python implementations for automated checking

## FinCheck Pipeline

The paper introduces FinCheck, a pipeline system for automated compliance checking that processes natural language regulations and generates executable compliance code.
