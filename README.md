# Decoding Emotion Through Sentiment Analysis of Social Media Conversation

This project focuses on decoding human emotions expressed in social media conversations, especially on platforms like *YouTube* and *Instagram*. It uses Natural Language Processing (NLP) and machine learning to classify emotional states such as joy, anger, sadness, fear, and more from user comments.

---

## 📌 Real-World Use Case

- *Instagram*: Analyze sentiment in comments on celebrity posts or brand campaigns to assess public reception.
- *YouTube*: Gauge audience emotions in video comment sections—helpful for content creators, marketers, and political analysts.

---

## 🧠 Key Features

- Load and preprocess real-world comment datasets
- Handle noise: emojis, hashtags, mentions, and informal language
- Extract text features using TF-IDF
- Train and compare multiple ML models (Logistic Regression, Random Forest, XGBoost)
- Visualize model performance and insights using plots

---

## 🛠 Technologies Used

- *Programming Language*: Python
- *Libraries*:
  - pandas, numpy – Data manipulation
  - nltk – Text preprocessing
  - scikit-learn – Machine learning models
  - xgboost – Advanced boosting classifier
  - matplotlib, seaborn – Visualization
  - wordcloud – Visualizing key emotional keywords

---

## 📂 Project Structure


emotion-analysis/
│
├── data/                  # Contains the sample dataset
├── notebooks/             # (Optional) Jupyter notebooks
├── outputs/plots/         # Model visualization outputs
├── src/                   # Source code files
│   ├── data_preprocessing.py
│   └── model.py
├── main.py                # Entry point for model execution
├── requirements.txt       # Python dependencies
└── README.md              # Project documentation


---

## 📊 Sample Output

- Classification reports showing precision, recall, and F1-score
- Confusion matrices for each model
- Word clouds of common words for each emotion
- Heatmaps of misclassifications

---

## 📁 Demonstration

A sample gradio demonstration has been uploaded in this URL : https://eff91b9ddb774991a1.gradio.live

---

## 🙌 Contributors

- A. MOHAMED ASHIK – Data cleaning, modeling, documentation.
- V. VISHNUVASAN   – Project Manager & Analyst	Define project scope, oversee workflow, and coordinate tasks.
- K.LINGESHWARAN   – Data Engineer	Handle data collection from APIs (Twitter/Reddit), preprocessing and storage.
- A. SIBIRAJ       – NLP & ML Specialist	Build and evaluate ML/NLP models, tune parameters, and compare performance.


---

## 📬 Contact

For queries or contributions, reach out via GitHub Issues or [vishnuvasan2233@gmail.com].
