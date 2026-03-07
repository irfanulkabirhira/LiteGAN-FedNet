
# LiteGAN-FedNet: Explainable Federated Learning for Brain Tumor MRI Classification

LiteGAN-FedNet is a lightweight and explainable federated learning framework designed for multi-class brain tumor MRI classification in privacy-constrained medical environments. The framework enables collaborative model training across decentralized institutions without sharing raw patient data.

The proposed approach integrates deep feature extraction, feature augmentation, dimensionality reduction, and explainable AI within a unified federated learning pipeline.

## Key Components

- **ResNet18 Feature Extraction**  
  Extracts discriminative deep feature embeddings from MRI images.

- **Conditional GAN (cGAN) Feature Augmentation**  
  Generates class-conditioned feature representations to address class imbalance across decentralized clients.

- **PCA-based Feature Compression**  
  Reduces feature dimensionality to minimize communication overhead during federated aggregation.

- **Federated Learning (FedAvg)**  
  Enables collaborative training across multiple simulated hospital clients without sharing raw medical images.

- **Explainable AI (XAI)**  
  Provides model interpretability using:
  - Grad-CAM (spatial explanations)
  - SHAP (global feature importance)
  - LIME (local instance explanations)

## Features

- Privacy-aware distributed medical AI framework
- Communication-efficient federated learning
- Class imbalance mitigation using generative models
- Multi-level explainability for clinical interpretability
- Reproducible experimental pipeline

## Applications

- Brain tumor MRI classification
- Privacy-preserving medical AI
- Federated healthcare analytics
- Explainable clinical decision support systems
