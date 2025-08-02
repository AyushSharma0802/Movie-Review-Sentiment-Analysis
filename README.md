# 🎬 Movie Review Sentiment Analysis

This project uses **Logistic Regression** with **TF-IDF vectorization** to classify IMDB movie reviews as **positive** or **negative**.


---

## 📊 Dataset

- Dataset: [IMDB Dataset](https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews)
- Format: CSV
- Columns:
  - `review`: Raw movie review text
  - `sentiment`: Label (`positive` or `negative`)

## 🧠 How It Works

1. Text reviews are cleaned and vectorized using **TF-IDF**.
2. A **Logistic Regression** model is trained to classify the sentiment.
3. The trained model and vectorizer are saved using `pickle` for reuse.
4. You can load them using `predict.py` and make predictions on new reviews.


📊 Model Evaluation
Accuracy: ~89%

Precision, Recall, F1-score available in classification_report

🧠 Libraries Used
pandas

numpy

nltk

scikit-learn

seaborn, matplotlib
### 📌 1. Install dependencies


pip install -r requirements.txt

📌 2. Train the model 

python train.py

📌 3. Predict a new review

python predict.py

📌 Example Output

Review: This movie was absolutely amazing!

Predicted Sentiment: Positive

👨‍💻 Author

Ayush Sharma

