# visual_intelligence
# 🫁 Lung Cancer Detection using CNN and ScatNet with XAI

This project aims to detect lung cancer from medical images using two different deep learning models — a **Convolutional Neural Network (CNN)** and a **Scattering Network (ScatNet)**. It includes performance validation and comprehensive explainability analysis using three popular eXplainable AI (XAI) methods: **DeepLIFT**, **SHAP**, and **Occlusion**.

---

## 🧠 Models Used

### 1. CNN (Convolutional Neural Network)
- Custom-designed convolutional layers.
- Trained using PyTorch.
- Suitable for end-to-end feature learning from input images.

### 2. ScatNet (Scattering Network)
- Combines scattering transforms with standard neural network classifiers.
- Provides better stability to small deformations and preserves interpretability.

---

## 📊 Performance Evaluation

Each model was evaluated using:
- Accuracy, Precision, Recall, F1 Score
- Confusion Matrix
- Cross-validation for robustness
- Best model saving with validation tracking

---

## 🔍 Explainability (XAI)

We implemented three model-agnostic and model-specific explainability techniques:

### ✅ DeepLIFT
- Highlights contribution of each input pixel compared to a reference input.

### ✅ SHAP (SHapley Additive exPlanations)
- Provides feature importance based on game theory.

### ✅ Occlusion
- Analyzes sensitivity of the model by masking regions of the input image.

### 💡 Both Captum and manual implementations (for learning and comparison) are included.

