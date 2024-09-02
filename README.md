## Sentimental Analysis on Twitter Data of Vaccination-Related Tweets

# Introduction
Vaccination is critical in modern medicine for preventing infectious diseases. 
The COVID-19 vaccine rollout has faced unique challenges, including scientific complexities and public acceptance issues. 
Public sentiment on social media platforms, especially Twitter, is pivotal in shaping vaccine discourse.

This project analyzes sentiments expressed on Twitter regarding COVID-19 vaccinations using Natural Language Processing (NLP) techniques. 
By understanding public sentiment, we aim to improve communication strategies, identify trends, and combat misinformation.

# Objectives
- Sentiment Analysis: Conduct sentiment analysis on tweets from Indian users about COVID-19 vaccination.
- Sentiment Evaluation: Assess the prevailing sentiment (positive, negative, neutral) towards COVID-19 vaccines among Indian Twitter users.
- Model Development: Develop and train machine learning models using NLP techniques to predict tweet sentiment.
- Communication Strategy Analysis: Analyze the effectiveness of communication strategies in shaping public opinion and promoting vaccine acceptance.

# Dataset
The dataset comprises two integrated datasets from Kaggle, each with columns related to vaccination discourse. 
The unified dataset includes 78,168 rows with 16 features. For sentiment analysis, a new dataset focused on India with 9,900 rows was created.

# Exploratory Data Analysis (EDA)
EDA involved:
- Descriptive Statistics: Summarizing key dataset features.
- Visualizations: Using histograms, box plots, and time series plots.
- Text Mining: Extracting insights from tweet content.
- Word Clouds: Identifying prevalent words and topics.

# Methodology
- Data Collection: Twitter API was used to gather tweet data related to COVID-19 vaccination.
- Preprocessing: Handled missing values, cleaned text, and refined features.
- Sentiment Analysis: VADER tool was employed to classify sentiment.
- Model Training: Various models (Logistic Regression, Decision Tree, Random Forest, SVM, etc.) were trained and tested.
- Clustering Analysis: K-means and hierarchical clustering were used to group similar tweets.

# Comparative Analysis
The performance of machine learning models was compared based on accuracy and silhouette scores.

Table 1: Models and Accuracy Scores

| Algorithm/Model              | Accuracy | Silhouette Score         |
|------------------------------|----------|--------------------------|
| Logistic Regression          | 93.28%   | N/A                      |
| Decision Trees                | 86.16%   | N/A                      |
| KNN                          | 33.13%   | N/A                      |
| SVM                          | 93.43%   | N/A                      |
| Naive Bayes (multinomial)    | 92.88%   | N/A                      |
| Gradient Boosting            | 93.08%   | N/A                      |
| Random Forest                | 90.96%   | N/A                      |
| XGBoost                      | 93.23%   | N/A                      |
| KMeans                       | N/A      | 0.1244 (for k=1000)      |
| Agglomerative Clustering     | N/A      | 0.00335 (for k=3)        |


# Findings
- Sentiment: Majority of tweets were neutral.
- Trending Topics: Key concerns included vaccine efficacy, side effects, and policies.
- Influential Users: Public figures and media influenced discourse.
- Model Performance: SVM and Logistic Regression performed best.
- Communication Strategies: Effective strategies foster positive sentiment and vaccine acceptance.

# Conclusion
The project sheds light on public sentiment regarding COVID-19 vaccination on Twitter. 
Insights gained can help in crafting better communication strategies and addressing vaccine hesitancy.

