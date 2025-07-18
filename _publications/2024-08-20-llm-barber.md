---
title: "LLM-Barber: Block-Aware Rebuilder for Sparsity Mask in One-Shot for Large Language Models"
collection: publications
category: manuscripts
permalink: /publication/2024-08-20-llm-barber
excerpt: 'A novel one-shot pruning framework that rebuilds the sparsity mask of pruned models without any retraining or weight reconstruction.'
date: 2024-08-20
venue: 'arXiv preprint'
paperurl: 'https://arxiv.org/abs/2408.10631'
citation: 'Yupeng Su, Ziyi Guan, Xiaoqun Liu, Tianlai Jin, Dongkuan Wu, Graziano Chesi, Ngai Wong, Hao Yu. (2024). &quot;LLM-Barber: Block-Aware Rebuilder for Sparsity Mask in One-Shot for Large Language Models.&quot; <i>arXiv preprint</i>.'
---

Large language models (LLMs) have grown significantly in scale, leading to a critical need for efficient model pruning techniques. Existing post-training pruning techniques primarily focus on measuring weight importance on converged dense models to determine salient weights to retain. However, they often overlook the changes in weight importance during the pruning process, which can lead to performance degradation in the pruned models.

To address this issue, we present LLM-Barber (Block-Aware Rebuilder for Sparsity Mask in One-Shot), a novel one-shot pruning framework that rebuilds the sparsity mask of pruned models without any retraining or weight reconstruction. LLM-Barber incorporates block-aware error optimization across Self-Attention and MLP blocks, ensuring global performance optimization. Inspired by the recent discovery of prominent outliers in LLMs, LLM-Barber introduces an innovative pruning metric that identifies weight importance using weights multiplied by gradients.

Our experiments show that LLM-Barber can efficiently prune models like LLaMA and OPT families with 7B to 13B parameters on a single A100 GPU in just 30 minutes, achieving state-of-the-art results in both perplexity and zero-shot performance across various language benchmarks. 