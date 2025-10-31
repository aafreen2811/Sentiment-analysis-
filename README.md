# Sentiment Analysis of COVID-19 Tweets  
*A data analytics capstone project*

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

## 📊 Key Steps & Methods  
1. **Data Loading & Inspection**: Load the tweet dataset and inspect for missing values, duplicates, etc.  
2. **Data Preprocessing**: Clean tweet text — remove URLs, mentions, punctuation, stop words, convert to lowercase.  
3. **Exploratory Data Analysis (EDA)**:  
   - Visualize distribution of sentiments.  
   - Generate word clouds for each sentiment class.  
   - Track sentiment trend over time.  
   - Identify most frequent hashtags and keywords.  
4. **Feature Engineering**:  
   - Use techniques such as TF-IDF or count vectorisation to convert text into numeric features.  
   - Possibly add features like tweet length, number of hashtags, etc.  
5. **Model Building & Evaluation**:  
   - Split data into training and testing sets.  
   - Build multiple models (Logistic Regression, Decision Tree, XGBoost, KNN, SVM).  
   - Compare models using metrics such as accuracy, precision, recall, F1-score.  
6. **Results & Interpretation**:  
   - Choose the best performing model.  
   - Interpret features and resist overfitting.  
   - Provide insights on how sentiment varied and what keywords/topics drove positive/negative tweets.

## ✅ Findings & Insights (Summary)  
- The dataset leaned more toward *neutral* and *negative* sentiments during key pandemic peaks.  
- Tweets with mentions of terms like “lockdown”, “cases”, “fear” often aligned with negative sentiment.  
- Hashtags related to community support, healthcare heroes tended to align with positive sentiment.  
- Model comparison showed that **XGBoost** (for example) achieved strong F1-scores compared to simpler models, although it required more tuning.

