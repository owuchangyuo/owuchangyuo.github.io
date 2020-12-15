---
title: "Weighted Low-rank Tensor Recovery for Hyperspectral Image Restoration"
collection: publications
permalink: /publications/WLRTR
---
[[PDF]](https://owuchangyuo.github.io/files/WLRTR.pdf)
[[Codes]](https://owuchangyuo.github.io/files/WLRTR.zip)

## Abstract
Hyperspectral imaging, providing abundant spatial and spectral information simultaneously, has attracted a lot of interest in recent years. Unfortunately, due to the hardware limitations, the hyperspectral image (HSI) is vulnerable to various degradations, such as noises (random noise), blurs (Gaussian and uniform blur), and down-sampled (both spectral and spatial downsample), each corresponding to the HSI denoising, deblurring and super-resolution task, respectively. Previous HSI restoration methods are designed for one specific task only. Besides, most of them start from the 1-D vector or 2-D matrix models and cannot fully exploit the structurally spectral-spatial correlation in 3-D HSI. To overcome these limitations, in this work, we propose a unified low-rank tensor recovery model for comprehensive HSI restoration tasks, in which non-local similarity within spectral-spatial cubic and spectral correlation are simultaneously captured by 3-order tensors. Furthermore, to improve the capability and flexibility, we formulate it as a weighted low-rank tensor recovery (WLRTR) model by treating the singular values differently, and study its analytical solution. We also consider the stripe noise in HSI as the sparse error by extending WLRTR to robust principal component analysis (WLRTR-RPCA). Extensive experiments demonstrate the proposed WLRTR models consistently outperform state-of-the-art methods in typical HSI low-level vision tasks, including denoising, destriping, deblurring, and super-resolution.
