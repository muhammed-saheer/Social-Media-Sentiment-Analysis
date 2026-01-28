# Social Media Sentiment & Engagement Analysis

## 📌 Project Overview
Social media platforms generate a massive amount of user-generated content that reflects public opinions, emotions, and engagement behavior.  
This project applies **Natural Language Processing (NLP)** techniques to analyze sentiment from social media text data and presents the insights using an **interactive Power BI dashboard**.

The project is divided into two main tasks:
- **Task 1:** Sentiment Analysis using Python & NLP  
- **Task 2:** Interactive Dashboard Creation using Power BI  

---

## 🎯 Project Objectives
- Clean and preprocess raw social media text data
- Perform sentiment analysis on user posts
- Classify posts into **Positive, Negative, and Neutral**
- Analyze engagement metrics such as likes
- Visualize sentiment and engagement insights through Power BI

---

## 🧠 Task 1: Sentiment Analysis using NLP

### Step 1: Import Required Libraries
Python libraries required for data processing, text analysis, and visualization were imported:
- **Pandas & NumPy** for data handling
- **NLTK** for text preprocessing
- **Matplotlib** for visualizations
- **WordCloud** for text frequency visualization

**Result:**  
The environment was successfully set up for NLP and sentiment analysis.

---

### Step 2: Load the Dataset
The social media sentiment dataset was loaded into a Pandas DataFrame.

The dataset includes:
- Social media text posts
- Sentiment labels
- Hashtags
- Platform information
- Likes and retweets

**Result:**  
Raw social media text data was successfully loaded and ready for inspection.

---

### Step 3: Dataset Inspection
Initial exploration was performed to understand the dataset:
- Checked dataset shape and structure
- Verified column data types
- Identified missing values
- Detected unnecessary index columns

**Result:**  
Dataset structure was clearly understood and issues requiring cleaning were identified.

---

### Step 4: Data Cleaning
Data cleaning steps included:
- Removing unnecessary index columns
- Selecting only relevant columns required for analysis
- Ensuring consistency in column naming

**Result:**  
A clean and structured dataset was prepared for text preprocessing.

---

### Step 5: Text Preprocessing
To prepare text for sentiment analysis, the following NLP preprocessing steps were applied:
- Converted text to lowercase
- Removed punctuation, numbers, emojis, and special characters
- Cleaned hashtags (#) and mentions (@)
- Removed stopwords
- Applied lemmatization to normalize words
- Stored cleaned text in a new column

**Result:**  
Noise-free, standardized text data suitable for sentiment analysis was created.

---

### Step 6: Sentiment Analysis
Sentiment analysis was performed using the cleaned text data:
- Existing sentiment labels were utilized
- Each post was classified into:
  - Positive
  - Negative
  - Neutral

**Result:**  
Each social media post was successfully associated with a sentiment category.

---

### Step 7: Sentiment Distribution Visualization
To understand overall sentiment trends:
- A bar chart was created to show sentiment counts
- Distribution of Positive, Neutral, and Negative sentiments was analyzed

**Result:**  
A clear understanding of the dominant sentiment within the dataset was obtained.

---

### Step 8: Word Cloud Generation
Text frequency analysis was performed using word clouds:
- Generated a word cloud using cleaned text
- Created a separate word cloud for positive sentiment posts

**Result:**  
Frequently used words and emotional patterns were visually identified.

---

### Step 9: Engagement Analysis
User engagement metrics were analyzed:
- Calculated average likes and retweets for each sentiment
- Compared engagement levels across sentiment categories

**Result:**  
Positive sentiment posts showed higher user engagement compared to other sentiments.

---

### Step 10: Platform-Wise Sentiment Analysis
Sentiment behavior across different platforms was examined:
- Analyzed sentiment distribution by platform
- Used stacked bar charts for comparison

**Result:**  
Different social media platforms showed varying sentiment patterns.

---

### Step 11: Final Analysis & Dataset Creation
- Overall sentiment trends were reviewed
- Engagement and platform-specific insights were summarized
- A final processed dataset was generated

**Output File Created:**  
`Sentiment_Analysis_Output.csv`

This dataset was used as the input for dashboard creation.

---

## 📊 Task 2: Dashboard Creation using Power BI

### Step 1: Importing the Dataset
The processed dataset `Sentiment_Analysis_Output.csv` was imported into Power BI.
- Unnecessary columns were removed
- Data types were verified and corrected

---

### Step 2: DAX Measures Creation
Custom DAX measures were created to support KPIs:
- Total Posts
- Total Likes
- Positive Posts
- Negative Posts
- Neutral Posts
- Positive Sentiment Percentage

These measures enable quick and dynamic insights.

---

### Step 3: Dashboard Design & Visualizations
An interactive dashboard titled  
**“Social Media Sentiment & Engagement Dashboard”** was created with:

#### 🔹 KPI Cards
- Total Posts (732)
- Total Likes (31.40K)
- Positive, Negative & Neutral Posts
- Positive Sentiment Percentage (39.34%)

#### 🔹 Charts & Visuals
- Sentiment Distribution (Donut Chart)
- Platform-Wise Engagement (Bar Chart)
- Monthly Sentiment Trend (Line Chart)
- Hourly Posting Activity
- Country-Wise Sentiment Analysis (Stacked Bar Chart)

---

### Step 4: Interactivity Features
Interactive slicers were added for:
- Platform
- Year
- Country
- Sentiment

These slicers allow users to explore insights dynamically.

---

## 📈 Key Insights
- Neutral sentiment dominates the dataset
- Instagram shows the highest engagement in terms of likes
- Positive sentiment consistently remains higher than negative sentiment
- Posting activity peaks during specific hours
- USA and UK contribute the most posts

---

## 🛠 Tools & Technologies Used
- **Python**
- **Pandas & NumPy**
- **NLTK**
- **Matplotlib & WordCloud**
- **Power BI**

---

## 📁 Repository Structure


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
This project demonstrates the effective use of **NLP techniques and data visualization** to extract meaningful insights from social media data.  
The Power BI dashboard enables intuitive exploration of sentiment trends, engagement behavior, and geographical distribution, supporting data-driven decision-making.

