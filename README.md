# 🧠 Neural Network Projects: CNN & ANN in TensorFlow

This repository contains **two deep learning projects** implemented with TensorFlow/Keras:

1. 🐶 **Convolutional Neural Network (CNN)** - Image classification of cats vs dogs
2. 🏦 **Artificial Neural Network (ANN)** - Customer churn prediction for a bank

Each project includes complete data preprocessing, model building, training, and evaluation steps.

---

## 📁 Contents

- [`cnn_cat_dog_classifier`](#-cnn-cat-vs-dog-image-classifier)
- [`ann_bank_churn_prediction`](#-ann-bank-customer-churn-prediction)
- [Dependencies](#-dependencies)
- [License](#-license)

---

## 🐶 CNN: Cat vs Dog Image Classifier

A **Convolutional Neural Network** is used to classify whether an image contains a **cat or a dog**.

---

### 📂 Dataset

Download the dataset from the link below:

📦 [Download dataset.zip](https://www.dropbox.com/scl/fi/ppd8g3d6yoy5gbn960fso/dataset.zip?rlkey=lqbqx7z6i9hp61l6g731wgp4v&e=1&st=gdn6pydw&dl=0)

Unzip the file and ensure the following structure:

---
### 🚀 CNN Workflow

1. **Preprocessing** the training and test image sets
2. **Building** a CNN with:
   - 2 convolution + pooling layers
   - 1 fully connected layer
3. **Training** on 25 epochs
4. **Predicting** a single image
   
---

## 🏦 ANN: Bank Customer Churn Prediction
This Artificial Neural Network predicts whether a customer will leave a bank (churn) based on their personal and account details.

### 📂 Dataset
The dataset Churn_Modelling.csv is already in the repository.

### 🚀 ANN Workflow
1. Data Preprocessing

2. Label encoding (Gender)

3. One-hot encoding (Geography)

4. Feature scaling

5. Building a 3-layer ANN

6. Training on 100 epochs

7. Predicting a single user and evaluating test predictions

## 🙋‍♂️ Acknowledgments
Dataset for CNN provided via Dropbox link

ANN dataset from Churn Modelling challenge (common in ML courses)

Projects built with educational and demonstration purposes in mind
## License
This project is licensed under the [MIT License](https://opensource.org/license/MIT).
