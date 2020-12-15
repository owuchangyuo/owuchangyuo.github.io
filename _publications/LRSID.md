---
title: "Remote Sensing Image Stripe Noise Removal: From Image Decomposition Perspective"
collection: publications
permalink: /publications/LRSID
---  
[[PDF]](https://owuchangyuo.github.io/files/LRSID.pdf) 
[[Codes]](https://owuchangyuo.github.io/files/LRSID.rar)

## Abstract
Stripe noise removal (destriping) is a fundamental problem in remote sensing image processing that holds significant practical importance for subsequent applications. These variational destriping methods have obtained impressive results and attracted widely studied research interests. However, most of them are dedicated to estimate the clear image from the striped one, paying much attention to the image itself, while ignoring the structural characteristic of stripe, which would easily cause damages to the image structure and leave residual stripes in image recovery. In this paper, we treat the image and stripe components equally and convert the image destriping task as an image decomposition problem naturally. We first give a detailed analysis about the structural characteristic of stripes and the prior knowledge about the remote sensing images. Then, incorporating them, we propose a low-rank-based single-image decomposition model (LRSID) to separate the original image from the stripe component perfectly. This low-rank constraint for the stripe perfectly matches the fact that only parts of data vectors are corrupted but the others are not. Moreover, we further utilize the spectral information of the remote sensing images, and we extend our 2-D image decomposition method to the 3-D case. Extensive experiments on both simulated and real data have been carried out to validate the effectiveness and efficiency of the proposed algorithms.
