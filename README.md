# 🫁 Multiclass Lung Disease Detection using Chest X-Ray Images

## 📌 Overview
This project implements a deep learning–based system for **multiclass lung disease detection** using chest X-ray images.  
Multiple CNN architectures were evaluated, with **VGG16 achieving the best performance**.

---

## 🧠 Diseases Classified
- Normal
- Pneumonia
- COVID-19

---

## 📂 Dataset Information
- **Source:** Mendeley Data (Public Chest X-ray Dataset)
- **Type:** Medical imaging (X-ray)
- **Classes:** Multiple lung disease categories
- **Images:** Labeled chest X-ray images
- **Usage:** Training, validation, and testing

🔗 **Dataset link:** <https://data.mendeley.com/datasets/m4s2jn3csb/1>


⚠️ **Note:** Dataset images are not included in this repository due to size and licensing constraints.  
Please download the dataset separately.

---

## 🏆 Best Model
- **Architecture:** VGG16
- **Accuracy:** **97.14%**
- **Optimizer:** Adam
- **Loss Function:** Categorical Cross-Entropy

---

## ⚙️ Tech Stack
- Python
- TensorFlow / Keras
- OpenCV
- NumPy, Pandas
- Matplotlib, Seaborn
- Scikit-learn

---

## 🧪 Methodology
1. Image resizing and normalization
2. Data augmentation
3. CNN model training (VGG16, DenseNet, ResNet)
4. Performance evaluation using accuracy and classification metrics

---

## 📊 Results
The **VGG16-based model achieved 97.14% accuracy**, outperforming other tested CNN architectures on the dataset.

---

## ▶️ How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/model_training.ipynb
