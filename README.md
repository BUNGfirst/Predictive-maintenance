# Predictive Maintenance using Machine Learning

🚧 This project aims to build a predictive model that classifies:
- Whether a machine is going to fail (binary classification)
- The type of failure (multiclass classification: 0–5)

## 📁 Project Structure
- `Preprocessing.ipynb` → Clean and balance data
- `Model.ipynb` → Binary classification (fail or not)
- `Model2.ipynb` → Multiclass failure type classification
- `predictive_*.npz` → Processed datasets

## 📊 Result
- Binary model accuracy: 90.2%
- Multiclass model accuracy: 65.8%
- Confusion matrix + recall per class used for evaluation

## ⚙️ Techniques
- Neural Networks with TensorFlow/Keras
- class_weight to handle data imbalance
- Evaluation using accuracy, confusion matrix, recall per class

## 💡 What I learned
- Handling imbalanced classification
- Designing multi-model architecture
- Model evaluation beyond just accuracy
