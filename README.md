# FedDG-GATNet

**FedDG-GATNet: A Federated Dynamic Graph Attention Framework for Privacy-Preserving Pneumonia Detection from Chest X-ray Images**

Accepted at *4th International Conference on Computing Advancements (ICCA 2026)*, Dhaka, Bangladesh.

## Overview
This repository contains the implementation of FedDG-GATNet, integrating:
- EfficientNetV2-based feature extraction
- Dynamic Adaptive Graph construction
- Edge-Aware GATv2 attention
- Prototype Contrastive Learning
- Federated Attention Aggregation
- Grad-CAM explainability

## Dataset
[Chest X-ray Pneumonia Balanced Dataset](https://www.kaggle.com/datasets/yusufmurtaza01/chest-xray-pneumonia-balanced-dataset) — 8,498 chest X-ray images (Normal & Pneumonia classes).

## Results
| Metric | Score |
|---|---|
| Accuracy | 97.15% |
| F1-Score | 97.17% |
| ROC-AUC | 0.9929 |

## Requirements
- Python 3.x
- TensorFlow 2.x
- PyTorch Geometric
- scikit-learn, NumPy, OpenCV

## Citation
If you use this code, please cite our paper:
[BibTeX entry will be added after publication]
