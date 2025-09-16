# CNN + ANN MNIST Classifier

## 📌 Overview
This project implements a **deep learning hybrid model** that combines:
- **CNN (Convolutional Neural Networks)** → for feature extraction  
- **ANN (Artificial Neural Networks)** → for classification  

The model is trained and evaluated on the **MNIST dataset** (handwritten digits 0–9).

✅ Achieves **~99% accuracy on the test set** without overfitting.


---

## 🚀 Features
- Uses `keras.datasets.mnist` for training data
- Normalization and preprocessing with OpenCV & NumPy
- CNN layers to extract spatial features
- Dense ANN layers for final classification
- Model saving & loading with `load_model`
- Evaluation with confusion matrix & classification report
- Visualization using Seaborn & Matplotlib

---

## 🛠️ Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/moonmido/cnn-ann-mnist-classifier.git
   cd cnn-ann-mnist-classifier

---


## 📈 Results
The model achieves **~99% accuracy** on the MNIST test set without overfitting.  

### 🔹 Classification Report

                 precision    recall  f1-score   support

           0       0.98      1.00      0.99       980
           1       0.99      0.99      0.99      1135
           2       0.98      0.99      0.99      1032
           3       1.00      0.99      0.99      1010
           4       0.99      0.99      0.99       982
           5       0.97      0.99      0.98       892
           6       0.99      0.98      0.99       958
           7       0.99      0.98      0.98      1028
           8       0.98      0.99      0.98       974
           9       1.00      0.96      0.98      1009

    accuracy                           0.99     10000
    macro avg       0.99     0.99      0.99     10000
    weighted avg    0.99     0.99      0.99     10000

---



### 🔹 Key Points
- Overall accuracy: **99%**  
- All digits (0–9) have precision, recall, and f1-score ≥ **0.97**  
- No class is significantly underperforming  
- Training and validation accuracy are close → **no overfitting observed**  
- Confusion matrix visualization shows very few misclassifications  


---


  ## 📂 Project Structure

├── src/DeepLearning_mini_project.ipynb    

├── data/3.png    # For Testing the prediction   

├── models/ann.h5  # Saved trained model (ANN)

├── models/cnn.h5  # Saved trained model (CNN)

├── requirements.txt

├── README.md

