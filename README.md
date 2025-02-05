# Diffusion_Image_Compression

# [Pre-Print'25] Diffusion_Image_Enhancement
Official Pytorch implementation of **Leveraging Diffusion Knowledge for Realistic Image Compression with Frequency-Aware via Fractal Band Learning**. 


[Lingyu Zhu](https://scholar.google.com/citations?user=IhyTEDkAAAAJ&hl=zh-CN),
[Wenhan Yang](https://scholar.google.com/citations?user=S8nAnakAAAAJ&hl=zh-CN),
[Xiangrui Zeng](),
[Bolin Chen](https://scholar.google.com/citations?user=Z30kLzgAAAAJ&hl=zh-CN),
[Peilin Chen](https://scholar.google.com.tw/citations?user=b9k152sAAAAJ&hl=en),
[Yung-Hui Li](https://openreview.net/profile?id=~Yung-Hui_Li3)
[Shiqi Wang](https://scholar.google.com.tw/citations?user=Pr7s2VUAAAAJ&hl=en)


[[`Arxiv`]()] [[`Supplementary Material`]()]  [[`Video`]()] 

## Overview
By optimizing the rate-distortion-realism trade-off, generative image
compression approaches produce detailed, realistic images, instead of the only ``sharp-looking” reconstructions produced by rate-distortion optimized models. In this paper, we propose a novel deep-learning-based generative image compression method injected with intrinsic data distribution derived from pre-trained Stable Diffusion, obtaining the capacity to recover more realistic textures in practical scenarios. To this end, efforts are made from two perspectives to navigate the distortion-realism trade-off in image compression.  First, recognizing the strong connection between image compression and frequency-domain characteristics, we designed a Frequency-Aware Fractal Band (FAFB) learning network to effectively capture the multiscale and directional frequency components inherent in natural images. This network integrates commonly used band feature operations within a neural framework, enhancing its ability to capture discriminative features while retaining essential given information and filtering out unnecessary details. Second, to further enhance the generalization ability of the FAFB network for image compression across varying scales, we incorporate robust frequency and content-aware constraints to regularize the training of the compression network. These constraints ensure that the extracted features of an input image remain consistent in both content and frequency domains. Extensive experiments in quantitative and qualitative evaluations demonstrate the superiority of our method for generative image compression, advancing the boundaries of achievable distortion-realism pairs, i.e., our method achieves better distortions at high realism and better realism at low distortion than ever before.

## TODO List
This repository is still under active construction:
- [ ] Release training and testing codes
- [ ] Release pretrained models
- [ ] Clean the code

## Public Dataset


## Installation

## Contact

- Lingyu Zhu: lingyzhu-c@my.cityu.edu.hk

## Citation

If you find our work helpful, please consider citing:

```bibtex

```

