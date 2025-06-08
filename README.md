🎬 Movie Review Sentiment Analysis
This project classifies movie reviews as Positive 😊 or Negative 😞 using a Neural Network built with TensorFlow and Keras. It applies Natural Language Processing (NLP) techniques to preprocess text and delivers predictions via an interactive Gradio web app.





🔗 Live Demo
👉 Try the Model on Gradio

✨ Features
Predicts sentiment polarity: Positive 😊 or Negative 😞

Built with TensorFlow and Keras Sequential Neural Network

Trained on IMDB-style movie reviews dataset

Hosted using Gradio on Hugging Face

Clean and interactive web interface for live testing

Text preprocessing includes:

Lowercasing

Removing punctuation

Tokenization and padding

📁 Project Structure
bash
Copy
Edit
Movie_Review_Sentiment_Analysis/
├── movie_review_sentiment_analysis.ipynb   # Main notebook with model training & testing
├── requirements.txt                        # Project dependencies
└── README.md                               # Project documentation
🧠 Model Details
Model Type: Sequential Neural Network

Layers: Dense layers with ReLU and Sigmoid activations

Loss Function: Binary Crossentropy

Optimizer: Adam

Evaluation Metric: Accuracy

📊 Dataset Overview
Source: Custom or open IMDB-style movie reviews dataset

Preprocessing Techniques:

Text lowercasing

Punctuation removal

Tokenization and padding for uniform input

🚀 Future Improvements
🔁 Use LSTM or Bidirectional LSTM for better sequence learning

📈 Display confidence scores with each prediction

🌍 Add multilingual support for broader language coverage

📱 Build and deploy a mobile or full-stack web app

🧪 Add explainability using SHAP or LIME

👨‍💻 Author
Dhiraj Kumar
📧 dhirajguptaofficial@gmail.com
🔗 GitHub Profile

📄 License
This project is licensed under the MIT License – see the LICENSE file for details.
