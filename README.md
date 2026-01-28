**# Social Media Sentiment & Engagement Analysis

## 📌 Project Overview
Social media platforms generate massive amounts of user-generated content that reflect public opinions and emotions.  
This project applies **Natural Language Processing (NLP)** techniques to analyze social media sentiment and presents insights through an **interactive Power BI dashboard**.

---

## 🎯 Objectives
- Perform sentiment analysis on social media text data
- Classify posts into **Positive, Negative, and Neutral**
- Analyze engagement metrics such as likes
- Visualize insights using Power BI

---

## 🧠 Task 1: Sentiment Analysis (NLP)

### 🔹 Dataset Description
- Total Records: **732 social media posts**
- Platforms: Facebook, Instagram, Twitter
- Features:
  - Text content
  - Platform
  - Likes
  - Time (Year, Month, Hour)
  - Country

---

### 🔹 Data Preprocessing Steps
- Converted text to lowercase
- Removed punctuation, numbers, emojis, and special characters
- Removed stopwords
- Applied lemmatization
- Cleaned hashtags and mentions

---

### 🔹 Sentiment Classification
- Sentiment categories:
  - Positive
  - Negative
  - Neutral
- Output file generated:
  - **Sentiment_Analysis_Output.csv**

This dataset was used as the final input for dashboard creation.

---

## 📊 Task 2: Power BI Dashboard Creation

### 🔹 Dashboard Overview
**Title:** Social Media Sentiment & Engagement Dashboard

---

### 🔹 KPI Metrics
- Total Posts: **732**
- Total Likes: **31.40K**
- Positive Posts
- Negative Posts
- Neutral Posts
- Positive Sentiment Percentage: **39.34%**

---

### 🔹 Visualizations
- Sentiment Distribution (Donut Chart)
- Platform-wise Engagement (Bar Chart)
- Monthly Sentiment Trend (Line Chart)
- Hourly Posting Activity
- Country-wise Sentiment Distribution

---

### 🔹 Interactivity
Interactive slicers included for:
- Platform
- Year
- Country
- Sentiment

---

## 📈 Key Insights
- Neutral sentiment dominates the dataset
- Instagram shows the highest engagement
- Positive sentiment consistently exceeds negative sentiment
- Posting activity peaks during specific hours
- USA and UK contribute the most posts

---

## 🛠 Tools & Technologies
- **Python** (Pandas, NLP Libraries)
- **NLTK**
- **Matplotlib & WordCloud**
- **Power BI**

---

## 📁 Repository Structure
** Social-Media-Sentiment-Analysis/
│
├── data/
├── notebooks/
├── dashboard/
├── images/
├── README.md
└── requirements.txt **


---

## 📷 Dashboard Preview
![Dashboard Preview](https://github.com/muhammed-saheer/Social-Media-Sentiment-Analysis/blob/main/Images/Dashboard_img.png)

---

## ✅ Conclusion
This project demonstrates how NLP and data visualization techniques can be combined to extract meaningful insights from social media data and support data-driven decision-making.

