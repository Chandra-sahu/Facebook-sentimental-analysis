# 📘 Facebook Sentiment Analysis using Machine Learning

A Machine Learning-based sentiment analysis project that analyzes Facebook text data and classifies user comments/posts into **Positive, Neutral, and Negative sentiments** using Natural Language Processing (NLP) techniques.

---

## 🚀 Project Overview

Social media platforms generate massive amounts of textual data every day. Understanding public sentiment from this data helps organizations analyze customer feedback, opinions, and engagement trends.

This project performs **Facebook Sentiment Analysis** by cleaning text data, applying NLP preprocessing, extracting features using TF-IDF, and training machine learning models for sentiment classification.

---

## 🎯 Features

- Data Cleaning & Preprocessing
- Text Tokenization
- Stopword Removal
- Lowercase Conversion
- Sentiment Label Generation
- Exploratory Data Analysis
- Sentiment Distribution Visualization
- Word Cloud Visualization
- TF-IDF Feature Extraction
- Machine Learning Model Training
- Sentiment Prediction for New Text

---

# 🛠️ Technologies Used

### Programming Language
- Python

### Libraries
- Pandas
- NumPy
- NLTK
- Scikit-learn
- Matplotlib
- Seaborn
- WordCloud

---

# 📂 Project Structure

```bash
Facebook-Sentiment-Analysis/
│
├── Facebook.csv
├── Facebook_sentimental_analysis_project.ipynb
├── README.md
└── requirements.txt
```

---

# ⚙️ Installation

## Clone Repository

```bash
git clone https://github.com/your-username/Facebook-Sentiment-Analysis.git
```

## Navigate to Folder

```bash
cd Facebook-Sentiment-Analysis
```

## Install Dependencies

```bash
pip install -r requirements.txt
```

## Run Notebook

```bash
jupyter notebook
```

---

# 📊 Dataset Information

The dataset contains Facebook text content with sentiment scores.

### Features:

- **Content** → Facebook post/comment text
- **Score** → Sentiment score
- **Sentiment Name** → Positive / Neutral / Negative

---

# 🔍 Data Preprocessing Steps

The text preprocessing pipeline includes:

- Removing punctuation
- Converting text to lowercase
- Tokenization
- Removing stopwords
- Text normalization

Example:

**Original Text**

```python
"This is the BEST experience ever!!"
```

**Processed Text**

```python
best experience ever
```

---

# 📈 Exploratory Data Analysis

Visualizations included:

- Sentiment Count Plot
- Score Distribution
- Pie Chart Analysis
- Word Clouds for:
  - Positive Sentiment
  - Neutral Sentiment
  - Negative Sentiment

---

# 🤖 Machine Learning Models Used

## 1. Logistic Regression

Used for multiclass sentiment classification.

---

## 2. Naive Bayes

Fast probabilistic classifier for text classification.

---

## 3. Support Vector Machine (SVM)

High-performance classifier for text sentiment prediction.

---

# 🧠 Feature Extraction

TF-IDF Vectorization converts cleaned text into numerical feature vectors.

```python
TfidfVectorizer(max_features=5000)
```

This helps models understand word importance.

---

# 📊 Model Evaluation Metrics

Models are evaluated using:

- Accuracy Score
- Classification Report
- Prediction Testing

---

# 🔮 Prediction Example

Input:

```python
"This is the worst and bad experience ever"
```

Output:

```python
Negative
```

---

# 📷 Sample Output

### Sentiment Distribution Visualization

(Add Screenshot Here)

### Word Cloud Output

(Add Screenshot Here)

### Prediction Output

(Add Screenshot Here)

---

# 📌 Real-World Applications

This project can be used for:

- Social Media Monitoring
- Customer Feedback Analysis
- Brand Reputation Tracking
- Product Review Analysis
- Opinion Mining
- Marketing Strategy Optimization

---

# 🔥 Future Improvements

- Deep Learning (LSTM / BERT)
- Real-time Sentiment Detection
- Flask Web App Deployment
- API Integration
- Dashboard Visualization

---

# 👨‍💻 Author

## Chandra Shekhar Sahu

**MCA Graduate | Data Science & Machine Learning Enthusiast**

Focused on:

- Machine Learning
- NLP
- Data Science
- AI Solutions

---

# 🤝 Contribution

Contributions are welcome.

1. Fork Repository
2. Create Feature Branch
3. Commit Changes
4. Push Branch
5. Open Pull Request

---

# ⭐ Support

If you found this project useful:

⭐ Star this repository  
🍴 Fork it  
📢 Share it


