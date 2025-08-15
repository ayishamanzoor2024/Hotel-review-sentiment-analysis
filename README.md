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
![Distribution of Review Ratings](<https://imgur.com/XtSO3Ya>)

---

#### **2. Average Rating by Trip Type**
An analysis of average ratings by trip type revealed interesting patterns in how different customer segments rate their experience.
![Average Rating by Trip Type](<https://imgur.com/ciEll8A>)

---

#### **3. Impact of Service Quality on Ratings**
A boxplot analysis shows the relationship between service quality and customer rating, highlighting that higher ratings are strongly associated with good service.
![Impact of Service Quality on Ratings](<https://imgur.com/P0sKNm6>)

---

#### **4. Trends in Ratings Over Time**
This plot shows the trend of average ratings over time, revealing changes in customer satisfaction across different months.
![Trend of Average Ratings Over Time](<https://imgur.com/D3lzdqa>)

---

#### **5. Sentiment Distribution of Reviews**
A chart showing the distribution of positive, negative, and neutral sentiments across the dataset, based on VADER sentiment analysis.
![Sentiment Distribution of Reviews](<https://imgur.com/NQCYoNq>)

---

#### **6. Word Clouds of Positive and Negative Reviews**
Word clouds were generated to highlight the most frequently used words.

**Positive Reviews**
![WordCloud of Positive Reviews](<https://imgur.com/Fd78CE8>)

**Negative Reviews**
![WordCloud of Negative Reviews](<https://imgur.com/UEDwr6y>)

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
