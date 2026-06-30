---
title: "Rare-cell-aware Coreset for Single-cell Clustering"
excerpt: "AI4S project on scalable scRNA-seq clustering, rare-cell preservation, and coreset-based data selection."
collection: portfolio
---

This project studies quality-oriented data selection for large-scale single-cell RNA sequencing analysis. Instead of uniformly down-sampling cells, the method prioritizes informative cells that better preserve rare populations, local boundaries, and transitional states.

## Highlights

- Designed a rare-cell-aware coreset sampling framework for large-scale scRNA-seq clustering.
- Combined graph connectivity, inverse-density weighting, and micro-cluster rebalancing into a multi-view sampling strategy.
- Reconstructed the sampled graph using a Self-Tuning Gaussian Kernel and extended labels to the full dataset through 1-NN mapping.
- Evaluated the framework on multiple real biological tissue datasets including Brain, Human Liver, Retina, Trachea, Blood, and Bone.
- Achieved strong efficiency-quality trade-offs, including about 8,300x speedup on a Bone dataset with 66,613 cells in the reported setting.

## Keywords

AI4S, scRNA-seq, coreset, spectral clustering, rare-cell discovery, graph learning.
