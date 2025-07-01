# Restaurant-Business-Recommendation-System

This project helps restaurant investors decide the best **cuisine type** and **location** for opening a new restaurant in Florida. We used **Sentiment Analysis**, **Topic Modeling**, and **LSTM Deep Learning models** on Yelp review data to generate data-driven recommendations.

---

## 📌 Problem Statement

To recommend:
- **Where** in Florida to set up a new restaurant
- **What type** of Japanese cuisine to offer (e.g., Sushi, Ramen)
- Based on customer sentiment, topic trends, and business success indicators

---

## 📊 Methodology

1. **Data Preparation:** Filtered and cleaned Yelp business and review datasets
2. **EDA (Exploratory Data Analysis):** Rating trends across cities and cuisines
3. **Sentiment Analysis:** Used TextBlob to analyze review sentiment polarity
4. **Topic Modeling:** LDA for common themes and topics in customer reviews
5. **Deep Learning:** Built and evaluated an **LSTM model** for sentiment classification
6. **BERT Zero-Shot Classification:** For flexible category classification without retraining

---

## ✅ Key Findings

- **Japanese restaurants** in Florida have higher average ratings than others.
- Touristy cities like **Tampa** have both challenges (low avg. rating) and opportunities (high demand).
- **Fusion** and **Health-Conscious** menu options are growing trends.
- LSTM model showed overfitting—highlighting areas for model tuning in future work.

---

## 📂 Files Included

- `LSTM_COURSE_PROJECT.ipynb` – Full Jupyter Notebook (code + outputs)
- `Spring_Team_454_Presentation.pdf` – Final presentation slides
- `requirements.txt` – Python packages needed (Optional, but recommended if others want to run your code)

---

## 🚀 How to Run

1. Clone this repo:
```bash
git clone https://github.com/rohanj12/restaurant-business-recommendation.git
