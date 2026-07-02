# AnemiaFusionNet_Setup
# AnemiaFusionNet 🩸
A Multimodal Feature Fusion Framework for Region-Aware Anemia Detection

## Overview
AnemiaFusionNet detects anemia by combining:
- 👁️ Conjunctiva eye images (ResNet50)
- 🏥 Clinical data: Hgb, Gender, Age
- 🌍 Geo-Risk weights from NFHS-5 (India)

## Results
| Metric | Score |
|--------|-------|
| Test Accuracy | 92.63% |
| F1 Score | 92.47% |
| Anemic Recall | 100% |

## Project Structure
- `notebooks/` — Main Colab training notebook
- `image_model/` — Image feature extractor
- `clinical_model/` — Clinical feature extractor
- `geo_risk_module/` — NFHS-5 geo risk module
- `fusion_network/` — Transformer fusion model
- `evaluation/` — Results and performance reports

## Dataset
Eyes-Defy-Anemia dataset from Kaggle
- 202 patients (Italy + India)
- 631 valid conjunctiva images

## Tech Stack
PyTorch | ResNet50 | Transformers | Google Colab | Python
