# Diffusion_Image_Compression

# [Pre-Print'25] Diffusion_Image_Enhancement
Official Pytorch implementation of **Fractal Frequency-Aware Band Learning for Fine Detailed Texture Synthesis in Generative Image Compression**. 


## Overview
By optimizing the rate-distortion-realism trade-off, generative image compression methods produce detailed, realistic images, surpassing the ``sharp-looking" reconstructions produced by rate-distortion optimized models. In this paper, we introduce a novel deep learning-based generative image compression method infused with powerful diffusion knowledge, enabling the recovery of more realistic textures in practical scenarios. We approach the rate-distortion-realism trade-off from three perspectives in the generative image compression task. First, recognizing the strong link between image texture and frequency-domain characteristics, we design a \textbf{F}ractal \textbf{F}requency-\textbf{A}ware  \textbf{B}and \textbf{I}mage \textbf{C}ompression (\textbf{FFAB-IC}) network that effectively captures the directional frequency components, which correspond to both isotropic and anisotropic features inherent in natural images. This network integrates commonly used fractal band feature operations within a neural non-linear mapping design, enhancing its ability to preserve essential information while filtering out extraneous details. To further improve the visual quality of image reconstruction under limited bandwidth, we incorporate diffusion knowledge into the encoder and implement diffusion iterations in the decoder process, effectively recovering lost texture details.  Finally, we leverage both spatial and frequency intensity information by integrating frequency- and content-aware regularization terms, which enhance the training of the generative image compression network. Extensive quantitative and qualitative evaluations demonstrate the superiority of our proposed method, pushing the boundaries of achievable distortion-realism pairs. Specifically, our method alleviates distortions at high realism and enhances realism at low distortion levels, setting new benchmarks in the field. 

## TODO List
This repository is still under active construction:
- [ ] Release training and testing codes
- [ ] Release pretrained models
- [ ] Clean the code

## Public Dataset

## Installation

