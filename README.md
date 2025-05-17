# Kindey_disease_classifier_DL
# Kidney CT Image Classification using InceptionResNetV2 and Hybrid Stacking Ensemble

This project focuses on the automated classification of kidney CT images into four categories: **Normal, Cyst, Tumor, and Stone**, using a hybrid deep learning and machine learning approach. We use **InceptionResNetV2** as a feature extractor and apply a **stacking ensemble of classifiers** to enhance classification accuracy.

## 🚀 Project Highlights

- **Model Architecture:** InceptionResNetV2 used for deep feature extraction.
- **Ensemble Learning:** Hybrid stacking ensemble using SVM, Random Forest, XGBoost, and KNN with Logistic Regression as the meta-learner.
- **Dataset Size:** Over 12,000 kidney CT images.
- **Performance:** Achieved **99.33% accuracy** on test data.
- **Visualization:** Applied Grad-CAM and t-SNE for interpretability and feature space analysis.

## 🧠 Technologies Used

- Python
- TensorFlow / Keras
- Scikit-learn
- XGBoost
- Matplotlib / Seaborn
- Grad-CAM for heatmaps
- t-SNE for dimensionality reduction

## 🗂 Dataset Description

| Class  | Images |
|--------|--------|
| Normal | 5077   |
| Cyst   | 3709   |
| Tumor  | 2283   |
| Stone  | 1377   |

> Dataset Source: [Kaggle - CT Kidney Dataset](https://www.kaggle.com/datasets/nazmul0087/ct-kidney-dataset-normal-cyst-tumor-and-stone)

- **Train/Val/Test Split:** 70% / 21% / 9% (Stratified)

## 📊 Results

- **Base CNN (InceptionResNetV2) Accuracy:** 96.44%
- **Stacked Ensemble Accuracy:** 99.33%
- **Metrics:** Precision, Recall, F1-score for all four classes
- **Visualization:** Confusion Matrix, Grad-CAM, t-SNE
## 🧪 How to Run

Clone the repository:
```bash
git clone https://github.com/your-username/kidney-ct-classification.git
cd kidney-ct-classification
```


## ✍️ Author

**Arun Kumar Gnanasekar**

- 🔗 LinkedIn: [linkedin.com/in/your-profile](https://linkedin.com/in/your-profile)
- 💻 GitHub: [github.com/ArunKumarSekar](https://github.com/ArunKumarSekar0712)

## 📄 License

This project is licensed under the MIT License.
