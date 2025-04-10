# 🌿 AI-Driven Plant Health Assessment  
### A Comparative Analysis of Inception V3, ResNet-50 and ViT with SHAP for Accurate Disease Identification in Taro

**Authors**:  
Valeria Maeda-Gutiérrez¹† · Juan José Oropeza-Valdez²*† · Luis C. Reveles-Gómez¹† · Cristian Padron-Manrique³˒⁴† · Osbaldo Resendis-Antonio²˒⁴˒⁵ · Luis Octavio Solís-Sánchez⁶ · Hector A. Guerrero-Osuna⁶ · Carlos Alberto Olvera Olvera⁷*

**Published in**: *Agronomy*, 2025, 15(1), 77  
📅 **Published**: December 30, 2024  
🔗 DOI: [10.3390/agronomy15010077](https://doi.org/10.3390/agronomy15010077)

---
**Authors** † = First authors
## 📌 Overview

This project explores the potential of deep learning for plant disease detection, with a focus on **taro (Colocasia esculenta)** leaf diseases. We benchmark three state-of-the-art computer vision architectures:

- **Inception V3**
- **ResNet-50**
- **Vision Transformer (ViT)**

In addition, we apply **SHAP (SHapley Additive exPlanations)** to interpret the models and highlight critical visual features for transparent and explainable AI in plant phenotyping.

---

## 🚀 Objectives

- Compare model performance on a curated dataset of taro leaf images.
- Assess classification accuracy for disease identification.
- Use SHAP values to uncover model decision patterns and explainability.
- Provide a practical tool for **AI-assisted agriculture and early disease detection**.

---

## 🧠 Methods

- **Data**: Taro leaf dataset categorized into healthy and various diseased conditions.
- **Preprocessing**: Image normalization, data augmentation.
- **Models**: Fine-tuned pretrained versions of Inception V3, ResNet-50, and ViT.
- **Evaluation**: Accuracy, Precision, Recall, F1-Score.
- **Explainability**: SHAP visualizations for model interpretability.

---

## 📊 Results

- **ViT** achieved the **highest accuracy**, followed closely by Inception V3.
- SHAP highlighted disease-specific leaf features that aligned with expert annotations.
- The **explainability approach supports trustworthiness** in model predictions.

---

## 📍 Institutions

- **UAZ**: Universidad Autónoma de Zacatecas  
- **UNAM**: Universidad Nacional Autónoma de México  
- **INMEGEN**: Instituto Nacional de Medicina Genómica  

---

## 📁 Repository Structure

```
├── data/                # Image dataset (not included due to size)
├── models/              # Trained models
├── notebooks/           # Jupyter notebooks for training and SHAP analysis
├── src/                 # Source code for model training and evaluation
├── shap_outputs/        # SHAP explanations and visualizations
├── requirements.txt     # Python dependencies
└── README.md            # Project overview
```

---

## 🛠️ Installation

```bash
git clone https://github.com/your-repo/taro-plant-health.git
cd taro-plant-health
pip install -r requirements.txt
```

---

## 📌 Citation

If you use this code or dataset in your research, please cite:

> Maeda-Gutiérrez, V.; Oropeza-Valdez, J.J.; Reveles-Gómez, L.C.; Padron-Manrique, C.; Resendis-Antonio, O.; Solís-Sánchez, L.O.; Guerrero-Osuna, H.A.; Olvera Olvera, C.A.  
> **AI-Driven Plant Health Assessment: A Comparative Analysis of Inception V3, ResNet-50 and ViT with SHAP for Accurate Disease Identification in Taro**.  
> *Agronomy* 2025, 15(1), 77. https://doi.org/10.3390/agronomy15010077

---

## 📬 Contact

For questions or collaboration opportunities, feel free to contact:

- Juan José Oropeza-Valdez · [ORCID](https://orcid.org/)  
- Carlos Alberto Olvera Olvera · [ORCID](https://orcid.org/)
