# Project Web Repo for: VITA: ViT Acceleration for Efficient 3D Human Mesh Recovery

Welcome to the official project webpage projectfor VITA, a hardware-algorithm co-design framework aimed at accelerating Vision Transformer (ViT)-based 3D Human Mesh Recovery (HMR). This project showcases our approach to enhancing the performance and energy efficiency of ViT models, particularly for applications in augmented and virtual reality (AR/VR).

## Project Overview

**VITA** (ViT Acceleration) is designed to overcome the challenges of computational complexity, substantial memory footprint, and data locality issues in ViT-based HMR tasks. The key contributions of this project include:

- **Algorithm Design**: Introduction of an Average Pooling Block (APB) that replaces conventional multi-head attention in ViTs, optimized for improved data locality and reduced computational overhead.
- **Hardware Architecture**: Development of a custom accelerator that supports various dataflows and computations necessary for pooling, normalization, and convolution operations in ViT models.

Our results demonstrate significant speedups over state-of-the-art GPUs and CPUs, making VITA a promising solution for real-time 3D HMR in resource-constrained environments.

## Project Website

This project website is built using the **Academic Project Page Template**, which offers a customizable and user-friendly structure for presenting academic projects.

## Features

- **5.05× to 69.12× speedup** on average over existing hardware platforms for HMR tasks.
- **Hardware-algorithm co-design** to ensure both efficient computation and memory usage.
- **Custom ViT architecture** tailored for the unique demands of 3D HMR.

## Publications

For more details, please refer to our [paper](https://www.crcv.ucf.edu/chenchen/2024_DAC_VITA_Final.pdf) published in the 61st ACM/IEEE Design Automation Conference (DAC '24).

## License

This project is licensed under the Apache License 2.0. See the [LICENSE](LICENSE) file for details.

## Website License

The website template is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).