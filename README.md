# LensTolerance
**This repo contains the official implementation for Paper "Tolerance-Aware Deep Optics".**

### [Project Page](https://openimaginglab.github.io/LensTolerance/) | [Paper](https://arxiv.org/abs/2502.04719) | [Dataset](https://drive.google.com/drive/folders/1gs_Qw7d7D4-9IHkBrxVSzFTUOMXibzkZ?usp=sharing)

Jun Dai, Liqun Chen, Xinge Yang, Yuyao Hu, Jinwei Gu, Tianfan Xue <br>
arXiv 2024 <br><br>

![teaser](./docs/static/images/teaser.png)
 We using tolerance-aware optimization, making deep optics getting more robust to potential tolerance perturbations.

## Installation
We implemented our tolerance-aware optimization framework based on [dO](https://github.com/vccimaging/DiffOptics) and [DeepLens](https://github.com/singer-yang/DeepLens). We make the ray tracing framework consider the effect of **Tolerances**.

### 0. Set up the Python environment
```
conda create 
```
