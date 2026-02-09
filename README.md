# ProALIGN-Net: Joint Deformable Registration and Segmentation of Prostate MRI via Cross-Modal Adaptive Frequency Fusion

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Framework: PyTorch](https://img.shields.io/badge/Framework-PyTorch-orange.svg)](https://pytorch.org/)
[![Status: Active](https://img.shields.io/badge/Status-Active-green)]()

This repository contains the official PyTorch implementation of the paper: **"ProALIGN-Net: Joint Deformable Registration and Segmentation of Prostate MRI via Cross-Modal Adaptive Frequency Fusion"**.

**Code Release:**
The source code and configuration files will be made publicly available in this repository upon the publication of the paper.

**Datasets:**
The public datasets analyzed during this study are available in their respective repositories:
* The **PI-CAI challenge** [Saha et al., 2024](https://pi-cai.grand-challenge.org/)
* The **Prostate158 dataset** [Prostate158, 2022](https://github.com/kbressem/prostate158)

To facilitate reproducibility, the paired modality-specific (T2W and DWI) whole-gland annotations generated in this study for the registration task will be made publicly available upon publication.

## 📋 Abstract

Accurate alignment and segmentation of multi-parametric MRI (mpMRI) are critical for the diagnosis and staging of prostate cancer. However, physical distortions in Diffusion-Weighted Imaging (DWI) often lead to misalignment with T2-Weighted (T2W) anatomical scans, compromising downstream analysis. **ProALIGN-Net** is a novel joint learning framework that simultaneously performs bidirectional deformable registration and modality-specific segmentation. By introducing a **Cross-Modal Adaptive Frequency Fusion (CMAFF)** module, we leverage spectral domain information to bridge the intensity gap between modalities, enhancing feature alignment robustness where spatial-only methods often fail.
