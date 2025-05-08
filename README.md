# Cancer-Detection-From-DNA-using-Deep-learning-and-hybrid-Method
Detecting various types of cancer from DNA sequences using deep learning models. By leveraging Convolutional Neural Networks (CNN) and a Hybrid CNN-LSTM model, the system aims to accurately classify cancer types based on high-dimensional genetic data.

## 🚀 Project Overview
Early detection of cancer significantly increases treatment success. This project uses deep learning techniques to identify mutations in DNA sequences that are linked to specific cancer types. The models are trained on real-world data sourced from **The Cancer Genome Atlas (TCGA)**.

## 🎯 Objectives
- Build an AI-driven system to detect cancer types from DNA sequence data.
- Compare the performance of traditional CNN and a Hybrid CNN-LSTM model.
- Improve accuracy and generalization using robust training and optimization techniques.

---

## 🧠 Models Developed

### 🔹 1. Deep Learning Model (1D CNN)
- **Model Development**: Implemented a 1D Convolutional Neural Network to extract spatial/local features from DNA sequences.
- **Training**: Used categorical crossentropy loss and the Adam optimizer.
- **Cross-Validation**: Employed k-fold cross-validation for robustness.
- **Optimization**: Applied dropout and early stopping to reduce overfitting.
- **Evaluation Metrics**: Accuracy, Precision, Recall, Confusion Matrix.

### 🔹 2. Hybrid Model (CNN + LSTM)
- **Model Development**: Combined CNN for feature extraction and LSTM for capturing sequential dependencies.
- **Training**: Similar training setup with categorical crossentropy and Adam optimizer.
- **Cross-Validation**: Used k-fold cross-validation to ensure model reliability.
- **Optimization**: Included dropout layers and early stopping.
- **Evaluation Metrics**: Accuracy, Precision, Recall, Confusion Matrix.

## 📊 Results & Conclusion
- Both models demonstrated the ability to accurately classify cancer types from DNA sequences.
- The Hybrid CNN-LSTM model showed improved performance by learning both spatial and sequential patterns.
- Evaluation included precision, recall, and confusion matrix for detailed performance analysis.
- This project lays a foundation for more advanced AI-based cancer diagnostic systems in healthcare.

## 📦 Dataset
- **Source**: [The Cancer Genome Atlas (TCGA)](https://www.cancer.gov/about-nci/organization/ccg/research/structural-genomics/tcga)
- **Content**: High-dimensional DNA sequences and associated cancer labels.

