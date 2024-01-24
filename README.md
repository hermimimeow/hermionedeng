Chi-Square Feature Selection Applied to Sentiment Analysis on Indian Twitter Data

Overview:
This project is an experimental application of chi-square feature selection in conjunction with logistic regression and random forest models for sentiment analysis on Indian Twitter data. The dataset comprises 162,980 words, with sentiment categorized into three classes: -1 (negative), 0 (neutral), and 1 (positive).

Methodology:
Chi-Square Feature Selection
The chi-square statistic is pivotal in our analysis, measuring the independence between a feature (a term within a tweet) and its class (positive, neutral, or negative sentiment). A higher chi-square score indicates a stronger relationship with a particular class, making it highly effective for categorical analysis like ours. We employed chi-square selection to identify and utilize features with the most significant relationship to the output variable. This approach aids in constructing a more accurate model by reducing dimensionality, enhancing performance, and preventing overfitting.

Model Performance
Logistic Regression Model:
With chi-square feature selection: Accuracy = 0.86
Without chi-square feature selection: Accuracy = 0.78
Random Forest Model:
With chi-square feature selection: Accuracy = 0.85
Without chi-square feature selection: Accuracy = 0.71
Conclusion
The incorporation of chi-square feature selection notably improved the accuracy of both logistic regression and random forest models. By focusing on words with higher chi-square scores, our models could make more precise predictions. This experiment underscores the effectiveness of chi-square feature selection in sentiment analysis, particularly for datasets with high dimensionality.
  


  
Data link: https://www.kaggle.com/datasets/saurabhshahane/twitter-sentiment-dataset
<!---
hermimimeow/hermimimeow is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
