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

  ## 📂 Project Structure

├── src/DeepLearning_mini_project.ipynb    

├── data/3.png    # For Testing the prediction   

├── models/ann.h5  # Saved trained model (ANN)

├── models/cnn.h5  # Saved trained model (CNN)

├── requirements.txt

├── README.md

