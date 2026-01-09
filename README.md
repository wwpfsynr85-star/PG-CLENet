# PET-Guided CT Local Enhancement and Cross-Modality Fusion for Volumetric Lung Tumor Segmentation

## Summary
This repository provides the implementation of **PG-CLENet**, a PET-guided CT enhancement and cross-modality fusion framework for volumetric lung tumor segmentation.

The proposed method leverages PET-derived metabolic priors to enhance CT images in lesion-relevant regions, improving lesion localization and segmentation robustness under challenging imaging conditions. By integrating PET-guided CT local enhancement with effective cross-modality fusion, PG-CLENet achieves superior performance on both self-collected and public datasets.

<!-- Method overview figure -->
<p align="center">
  <img src="figures/Fig1.png" width="800">
</p>

---

## Dataset
- **Self-collected dataset**  
  PET/CT scans collected under institutional approval.  
  Due to patient privacy and ethical regulations, this dataset is **not publicly available**.

- **AutoPET dataset**  
  A public benchmark dataset for PET/CT tumor segmentation.  
  Official website: https://autopet.org/

The same preprocessing pipeline is applied to both datasets to ensure fair and reproducible evaluation.

---

## Requirements
The code has been tested with the following environment:

- Python ≥ 3.8  
- PyTorch ≥ 1.10  
- MONAI  
- NumPy  
- SciPy  
- scikit-image  

Additional dependencies will be specified upon code release.

---

## 🔔 Repository Status
This repository is currently under preparation.  
The complete inference code and pretrained model weights will be **publicly released upon acceptance** of the associated manuscript.


