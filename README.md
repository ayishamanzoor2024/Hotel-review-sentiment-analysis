# Hotel Review Sentiment Analysis

### **Project Overview**
This project performs an in-depth analysis of a large dataset of hotel reviews. The goal is to gain insights into customer satisfaction, identify key trends in feedback, and perform sentiment analysis to classify reviews as positive, negative, or neutral.

### **Methodology**
The analysis followed a standard data science pipeline:
- **Data Cleaning and Pre-processing**: Handled missing values, dropped irrelevant columns, and converted data types to prepare the dataset for analysis.
- **Exploratory Data Analysis (EDA)**: Explored the distribution of review ratings, analyzed the relationship between different review questions (e.g., trip type, service) and ratings, and visualized trends in ratings over time.
- **Sentiment Analysis**: Applied a sentiment analysis model to classify reviews and understand the overall sentiment of the feedback.

---

### **Exploratory Data Analysis (EDA) & Key Findings**

#### **1. Distribution of Review Ratings**
The majority of reviews were positive, with a large spike at a specific high rating, indicating a high level of customer satisfaction.

![Distribution of Review Ratings](https://i.imgur.com/your-image-url-here.png)

_Note: The `Hotel_Reviews.csv` data file is over 100 MB and is not included in this repository. It is stored using Git LFS._

#### **2. Average Rating by Trip Type**
An analysis of average ratings by trip type (e.g., business vs. vacation) revealed interesting patterns in how different customer segments rate their experience.

#### **3. Word Clouds of Positive and Negative Reviews**
Word clouds were generated for positive and negative reviews to highlight the most frequently used words.

- **Positive Words**:
    * Words like "clean," "friendly staff," "excellent," and "service" were frequently used, suggesting these are key drivers of positive feedback.
- **Negative Words**:
    * Words like "bad," "room," and "review provided" were prominent in negative reviews, pointing to potential issues with rooms and a general lack of detailed feedback in many low-rated reviews.

---

### **Sentiment Analysis**
The project used the **VADER (Valence Aware Dictionary and sEntiment Reasoner)** sentiment analysis model to classify reviews. The results showed a clear distribution of positive, negative, and neutral sentiments across the dataset.

### **Technologies Used**
- Python
- Pandas
- Matplotlib
- Seaborn
- NLTK (VADER)
- Hugging Face Transformers
