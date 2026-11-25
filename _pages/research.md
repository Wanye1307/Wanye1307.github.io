---
layout: page
permalink: /research/
title: research
description: Research on trustworthy artificial intelligence, medical vision-language models, and multimodal learning.
nav: true
nav_order: 2
---

## Research interests

My research focuses on trustworthy artificial intelligence and AI for healthcare, especially the reliability of medical vision-language models.

`Trustworthy AI` · `AI for Healthcare` · `Medical Vision-Language Models` · `Uncertainty Quantification` · `LLM Alignment and Preference Optimization` · `Multimodal Large Language Models` · `Agents`

## Research experience

### Improving Visual Grounding in Medical Vision-Language Models

**University of Science and Technology of China (USTC)** · September 2026–Present<br>
Advisor: Prof. S. Kevin Zhou

- Constructing a counterfactual medical VQA dataset to assess whether model responses are grounded in clinically relevant visual evidence rather than linguistic or answer-choice shortcuts.
- Training medical VLMs with supervised fine-tuning (SFT) and counterfactual direct preference optimization (DPO) to strengthen evidence-sensitive prediction and robustness under controlled visual interventions.

### Trustworthy Medical Vision-Language Models

**Renmin University of China (RUC)** · January–September 2026<br>
Advisor: Prof. Qingsong Yao

#### Counterfactual Answer Sensitivity for Reliable Medical VLM Evaluation

- Identified stable wrongness in closed-ended medical VLMs, where models produce confident but incorrect predictions despite corrupted or missing visual evidence.
- Proposed Counterfactual Answer Sensitivity (CAS), a vision-grounded uncertainty framework using counterfactual visual interventions and evidence sensitivity features for reliability assessment.
- Evaluated across 7 VLMs and 3 VQA benchmarks (VQA-RAD, SLAKE, VQA-Med-2019), achieving a +0.150 AUROC improvement over HAC-based uncertainty methods.

#### ClinEviD: Decision-Token Evidence Discrepancy for Medical VQA Uncertainty Quantification

- Identified decision-token dilution in medical VQA uncertainty estimation, where response-level aggregation overlooks critical clinical tokens.
- Developed ClinEviD, a training-free, single-pass framework that localizes evidential uncertainty to decision-bearing tokens through token-level evidence discrepancy modeling.
- Designed token-level evidence discrepancy modeling by contrasting generated clinical tokens with their strongest competing alternatives, followed by top-k aggregation and lightweight logistic calibration for answer-level risk estimation.
- Evaluated on 7 VLMs, 3 medical VQA datasets, and 42 model-dataset settings, achieving 0.7535 mean AUROC, +0.0798 AUROC over HAC, and 18x lower inference cost.

### The Exploration of Preference Optimization in LLMs for Recommendation Systems

**University of Science and Technology of China (USTC)** · January–June 2025<br>
Advisor: Prof. Xiangnan He

- Explored and optimized alignment and preference optimization methods, including PPO, DPO, and SimPO.
- Explored LLM preference optimization to improve recommendation-system performance.
- Explored negative-sampling strategies for LLM-based recommendation systems.
