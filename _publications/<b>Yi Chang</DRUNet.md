---
title: "Infrared Small UAV Target Detection Based on Residual Image Prediction via Global and Local Dilated Residual Networks"
collection: publications
permalink: /publications/DRUNet
---  
[[PDF]](https://owuchangyuo.github.io/files/DRUNet.pdf) 

## Abstract
Thermal infrared imaging possesses the ability to monitor unmanned aerial vehicles (UAVs) in both day and night conditions. However, long-range detection of the infrared UAVs often suffers from small/dim targets, heavy clutter, and noise in the complex background. The conventional local prior-based and the nonlocal prior-based methods commonly have a high false alarm rate and low detection accuracy. In this letter, we propose a model that converts small UAV detection into a problem of predicting the residual image (i.e., background, clutter, and noise). Such novel reformulation allows us to directly learn a mapping from the input infrared image to the residual image. The constructed image-to-image network integrates the global and the local dilated residual convolution blocks into the U-Net, which can capture local and contextual structure information well and fuse the features at different scales both for image reconstruction. Additionally, subpixel convolution is utilized to upscale the image and avoid image distortion during upsampling. Finally, the small UAV target image is obtained by subtracting the residual image from the input infrared image. The comparative experiments demonstrate that the proposed method outperforms state-of-the-art ones in detecting real-world infrared images with heavy clutter and dim targets.
