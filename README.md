# Sentiment Analysis of COVID-19 Tweets  


## 🧠 Project Overview  
In this project, I perform sentiment analysis on tweets related to the COVID-19 pandemic. The main goal is to classify tweets as **positive**, **negative**, or **neutral** and uncover insights into how public sentiment evolved during the crisis.

## 🎯 Objectives  
- Clean and preprocess real-world tweet data (remove noise, handle missing values).  
- Explore the data via EDA: word clouds, sentiment trends over time, top hashtags, etc.  
- Build classification models (Logistic Regression, Decision Tree, XGBoost, K-NN, SVM) to predict tweet sentiment.  
- Evaluate model performance using metrics such as accuracy, precision, recall, and F1-score.  
- Visualize results and draw meaningful conclusions about public sentiment during the pandemic.

## 🛠 Technologies & Tools  
- **Python**: Core programming language used.  
- **Pandas**, **NumPy**: For data manipulation and numerical operations.  
- **Matplotlib**, **Seaborn**, **WordCloud**: For data visualization.  
- **Scikit-learn**, **XGBoost**: For machine learning modelling.  
- **Jupyter Notebook**: Main environment for development and analysis.

## ✅ Findings & Insights (Summary)  
- The dataset leaned more toward *neutral* and *negative* sentiments during key pandemic peaks.  
- Tweets with mentions of terms like “lockdown”, “cases”, “fear” often aligned with negative sentiment.  
- Hashtags related to community support, healthcare heroes tended to align with positive sentiment.
  
1. We applied 5 different machine learing models namely, Logistic Regression with Grid Search CV, Desision Tree Classifier, XG Boost, KNN, SVM Classifier for both Count Vector And TF IDF Vectorisation techniques.
2. We conclude that the machine is generating best results for Logistic Regression with Grid Search CV model with and Accuracy score of 78.28% and 77.43% respectively for Count vector and TF/idf Vector, followed by SVM
3. Also, we observed that no overfitting is seen for the data, and we can deploy this model.
4. The sentiments of future tweets can be easily predicted using this model
