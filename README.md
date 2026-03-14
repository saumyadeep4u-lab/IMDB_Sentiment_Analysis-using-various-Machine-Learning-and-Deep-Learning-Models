# IMDB_Sentiment_Analysis-using-various-Machine-Learning-and-Deep-Learning-Models
This project focuses on sentiment analysis of IMDb movie reviews using Natural Language Processing (NLP). The goal is to classify reviews as positive or negative by applying both Traditional Machine Learning models and Deep Learning models.

The project compares multiple algorithms to determine which model performs best for sentiment classification.

📂 Dataset

The dataset used is the IMDb Movie Reviews Dataset, which contains thousands of movie reviews labeled as:

Positive

Negative

Each review is processed and converted into numerical representations for machine learning models.

⚙️ Technologies Used

Python

NumPy

Pandas

NLTK

Scikit-learn

TensorFlow / Keras

🧠 NLP Techniques Used
Text Preprocessing

Tokenization

Stopword removal

Text cleaning

Feature Engineering

TF-IDF Vectorization (for Machine Learning models)

Tokenization + Padding (for Deep Learning models)

🤖 Machine Learning Models Implemented

The following traditional machine learning models were trained using TF-IDF features:

Multinomial Naive Bayes

Logistic Regression

Support Vector Machine (SVM)

Random Forest

Each model was evaluated using:

Accuracy Score

Classification Report

📊 Model Performance
Best Machine Learning Model

✅ Logistic Regression achieved the best performance among traditional models.

Best Deep Learning Model

🚀 Convolutional Neural Network (CNN) performed best among deep learning architectures.

These models showed strong ability to capture patterns and contextual information in text data.

📈 Evaluation Metrics

Models were evaluated using:

Accuracy

Precision

Recall

F1-Score

Classification Report

🚀 Project Workflow

1️⃣ Load IMDb dataset
2️⃣ Perform text preprocessing
3️⃣ Split dataset into training and testing sets
4️⃣ Apply TF-IDF vectorization for ML models
5️⃣ Train ML models and evaluate performance
6️⃣ Tokenize and pad sequences for deep learning models
7️⃣ Train CNN, RNN, LSTM, and GRU models
8️⃣ Compare results and identify best-performing models

💡 Key Findings

TF-IDF works effectively for traditional machine learning models.

Logistic Regression provides the best accuracy among ML models.

CNN captures local textual patterns efficiently, leading to better deep learning performance.

Deep learning models perform well for contextual understanding in large text datasets.
