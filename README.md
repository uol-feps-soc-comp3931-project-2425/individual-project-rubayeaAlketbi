# 🧠 Glioma Segmentation Using Multi-Modal MRI Configurations

> A deep learning-based investigation on the effect of different MRI modality combinations for glioma brain tumor segmentation using a 3D U-Net architecture.

## 📌 Project Overview

This project focuses on **brain tumor segmentation** using the **BRaTS 2020 dataset**, employing various MRI modality configurations to evaluate their effectiveness:
- **Di-modal**: FLAIR + T1CE
- **Tri-modal**: FLAIR + T1CE + T2
- **Quad-modal**: FLAIR + T1CE + T2 + T1

The core idea is to **assess whether more input modalities lead to better segmentation results** or if redundancy introduces noise that affects performance.

All implementation, preprocessing, training, and evaluation are contained in **a single Jupyter notebook** for simplicity and reproducibility.

---

## 🗂️ Dataset Access

The notebook is designed to work with the **BRaTS 2020 dataset**, which provides multi-modal MRI scans and segmentation ground truth labels.

### ⚠️ How to Access the Dataset:

The dataset can be downloaded from:
- Official BRaTS website: [BRaTS Challenge](https://www.med.upenn.edu/cbica/brats2020/data.html)  
OR  
- Kaggle (Larxel repository):  
```bash
!kaggle datasets download andrewmvd/brain-tumor-segmentation-in-mri-brats-2015

