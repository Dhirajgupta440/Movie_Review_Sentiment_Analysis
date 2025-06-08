# 🎬 Movie Review Sentiment Analysis

This project classifies movie reviews as **Positive 😊** or **Negative 😞** using a **Neural Network** built with **TensorFlow** and **Keras**. It includes natural language processing techniques and is deployed using **Gradio** for live demo interaction.

![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue)
![Deep Learning](https://img.shields.io/badge/Deep%20Learning-TensorFlow-yellow)
![Deployed](https://img.shields.io/badge/Deployed-Gradio-orange)
![License: MIT](https://img.shields.io/badge/License-MIT-green)

---

### 🔗 Live Demo
👉 [Try the Model on Gradio](https://6f551d04667e273e96.gradio.live)

---

## ✨ Features

- Predicts sentiment of movie reviews: **Positive 😊** or **Negative 😞**
- Uses **TensorFlow + Keras Sequential Neural Network**
- Trained on an **IMDB-style** dataset
- Hosted using **Gradio** on Hugging Face
- Text preprocessing includes:
  - Lowercasing
  - Punctuation removal
  - Tokenization and padding
- Clean, interactive web interface

---

## 📁 Project Structure

Movie_Review_Sentiment_Analysis/
├── movie_review_sentiment_analysis.ipynb  # Jupyter Notebook for model training & testing
├── model_testing.ipynb                     # Jupyter Notebook for testing the trained model
├── model.h5                               # Trained Keras model file
├── tokenizer.pkl                         # Tokenizer object for text preprocessing
└── README.md                             # Project documentation




---

## 🧠 Model Details

- **Model Type:** Sequential Neural Network  
- **Layers:** Dense layers with ReLU and Sigmoid  
- **Loss Function:** Binary Crossentropy  
- **Optimizer:** Adam  
- **Metric:** Accuracy  

---

## 📊 Dataset Overview

- **Source:** IMDB-style movie reviews dataset (custom/open-source)
- **Text Preprocessing Includes:**
  - Lowercasing
  - Removing punctuation
  - Tokenization
  - Padding sequences for uniform shape

---

## 💡 Future Improvements

- 🔁 Integrate **LSTM** / **Bidirectional LSTM** for better sequence modeling
- 🧠 Add **confidence scores** in output
- 🌍 Introduce **multilingual support**
- 📱 Build a **mobile app** or **full-stack web app** with REST API
- 🧪 Use **explainability tools** like SHAP or LIME for interpretability

---

## 👨‍💻 Author

**Dhiraj Kumar**  
📧 dhiraj.300012723016@csvtu.ac.in  
🔗 [GitHub Profile](https://github.com/Dhirajgupta440)

---

## 📄 License

This project is licensed under the **MIT License** – see the `LICENSE` file for details.
