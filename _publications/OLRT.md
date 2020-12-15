---
title: "Hyperspectral Image Restoration: Where Does the Low-Rank Property Exist"
collection: publications
permalink: /publications/OLRT
---
[[PDF]](http://owuchangyuo.github.io/files/OLRT.pdf)
[[Codes]](http://owuchangyuo.github.io/files/OLRT.rar)


## Abstract
Hyperspectral images (HSIs) restoration is to recover the clean image from degraded version, such as the noisy, blurred or damaged. Recent low-rank tensor-based recovery methods have been widely explored in HSIs restoration. Most of previous methods, however, neglect an inconspicuous but important phenomenon that the physical meaning and dimension along the spatial, spectral and non-local mode are markedly different. In this work, we discover the low-rank property discrepancy along spatial, spectral and non-local self-similarity mode in the HSIs, and argue that the intrinsic low-rank correlations along each mode contribute different to the final restoration results. Consequently, we figure out that the combination of the spectral and non-local induced low-rank is most beneficial for HSIs modeling, and propose an optimal low-rank tensor model (OLRT) for HSIs restoration. Further, we not only explore the low-rank property in the image component, but also in the sparse error component (stripe noise in HSIs). Thus, we extend OLRT to the OLRT-RPCA with low-rank tensor priors for both the HSIs and sparse error. Besides, previous methods are usually designed for one specific HSIs task, which is less robust to various tasks. We prove that the proposed optimal low-rank prior is very flexible for various HSIs restoration problems including denoising, deblurring, inpainting and destriping. The proposed methods have been extensively evaluated on several benchmarks and tasks, and greatly outperform state-of-the-arts. We show the simple yet effective OLRT strategy is also beneficial to STOA.
