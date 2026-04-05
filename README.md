# Task-10
# Handwritten Digit Classification using KNN

## 📌 Project Overview
This project implements a Handwritten Digit Classification system using the K-Nearest Neighbors (KNN) algorithm. The model is trained on the Scikit-learn Digits dataset to classify images of digits (0–9).

---

## 📊 Dataset
- Source: Sklearn Digits Dataset (load_digits())
- Total Samples: 1797
- Features: 64 (8x8 pixel images)
- Classes: 10 (digits 0–9)

---

## 🛠 Tools & Technologies
- Python
- Scikit-learn
- NumPy
- Matplotlib

---

## ⚙️ Steps Performed

1. Loaded dataset using `load_digits()`
2. Visualized sample digit images
3. Split dataset into training and testing sets
4. Applied feature scaling using StandardScaler
5. Trained KNN model (K = 3)
6. Evaluated model accuracy
7. Tested multiple K values (3,5,7,9)
8. Plotted Accuracy vs K graph
9. Generated Confusion Matrix
10. Displayed predictions on test images

---

## 📈 Results

| K Value | Accuracy |
|--------|---------|
| 3      | ~98%    |
| 5      | ~97%    |
| 7      | ~97%    |
| 9      | ~96%    |

- Best performance observed at **K = 3**

---

## 🔍 Key Insights
- KNN performs well for image classification with small datasets
- Feature scaling is essential for distance-based algorithms
- Optimal K selection improves model performance

---

## 📊 Outputs
- Accuracy vs K plot
- Confusion Matrix
- Sample predictions visualization

---

## 🚀 How to Run

1. Install dependencies:
pip install numpy matplotlib scikit-learn

2. Run the Jupyter Notebook:
   jupyter notebook

---

## 📌 Future Improvements
- Use MNIST dataset for higher resolution images
- Optimize K using cross-validation
- Try other classifiers (SVM, CNN)

---

## 👨‍💻 Author
Your Navya Mahamkali
