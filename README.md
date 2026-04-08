# Toxic Comment Classification using Deep Learning (NLP)

This project focuses on **detecting toxic comments using Natural Language Processing (NLP) and Deep Learning**.
The model is trained on text data to classify comments into multiple toxicity categories such as abusive, insulting, threatening, or hateful content.

It is built using **TensorFlow / Keras**, **Text Vectorization**, and **Neural Networks** for multi-label text classification.

---

## 📌 Project Objective

The objective of this project is to build a **multi-label classification model** that can automatically identify toxic comments from text data.

This helps in:

* Content moderation
* Social media comment filtering
* Cyberbullying detection
* Harmful text classification
* Online community safety

---

## 📊 Dataset

The dataset used in this project is from the **Jigsaw Toxic Comment Classification Challenge**.

It contains:

* Comment text
* Multiple toxicity labels

### Target Labels

The model predicts the following categories:

* Toxic
* Severe Toxic
* Obscene
* Threat
* Insult
* Identity Hate

---

## 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* TensorFlow
* Keras
* Scikit-learn
* Matplotlib
* NLP
* TextVectorization

---

## ⚙️ Workflow

### 1. Data Preprocessing

* Loaded dataset
* Checked null values
* Cleaned text data
* Split input and target variables

### 2. Text Vectorization

Used TensorFlow's **TextVectorization layer** to convert text comments into numerical sequences.

### 3. Model Building

Built a **Deep Learning Neural Network** for multi-label classification.

### 4. Model Training

Trained the model on comment text and toxicity labels.

### 5. Prediction & Evaluation

Predicted toxicity probabilities for each label.

---

## 🧠 Model Used

Deep Learning Neural Network using:

* Embedding Layer
* Dense Layers
* Activation Functions
* Sigmoid Output Layer

Since this is a **multi-label classification problem**, sigmoid activation is used in the output layer.

---

## 📈 Key Features

* NLP-based text classification
* Multi-label prediction
* Toxicity detection
* Deep learning implementation
* Real-world moderation use case

---

## 🚀 Business Use Case

This project can be used by:

* Social media platforms
* Comment moderation systems
* Online forums
* Chat applications
* Content safety tools

to automatically detect harmful comments.

---

## 📷 Output

The model predicts whether a comment belongs to one or more toxic categories.

Example:

Input:

> "You are such an idiot"

Output:

* Toxic ✅
* Insult ✅

---

## 📁 Project Structure

```text
Toxicity.ipynb
README.md
dataset/
model/
```

---

## ⭐ Conclusion

This project demonstrates the practical application of **Deep Learning and NLP for text classification problems**.
It showcases preprocessing, vectorization, model training, and toxicity prediction for real-world content moderation systems.

---

## 👨‍💻 Author

Developed by **Deependra Kumar**
