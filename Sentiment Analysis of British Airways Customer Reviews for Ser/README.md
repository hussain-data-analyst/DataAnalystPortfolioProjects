# British Airways Customer Reviews Sentiment Analysis

## 📝 Project Summary
In this project, I performed a comprehensive sentiment analysis on 3,000 customer reviews scraped from the Skytrax website about British Airways. The goal was to uncover key customer sentiments, identify prevalent concerns, and classify reviews to provide actionable insights that could drive service improvements. Through data cleaning, feature engineering, and advanced text processing, I employed machine learning models to categorize reviews into positive, negative, and neutral sentiments. I evaluated various models under different conditions and applied multiple resampling techniques to address class imbalance. The final model achieved 83% accuracy.

## 🎯 Objective
To analyze and classify customer reviews to assess sentiment, identify common concerns, and provide data-driven recommendations to enhance customer satisfaction and service quality at British Airways.

## 🚀 Approach and Methodology
1. **Data Scraping**: Scraped 3,000 customer reviews from the Skytrax website to create a robust dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Conducted a thorough exploration of the dataset, visualized key trends using word clouds, and identified significant patterns.
3. **Text Processing**: Cleaned and preprocessed the review text, including tokenization, stop-word removal, and stemming, to prepare it for machine learning models.
4. **Resampling Techniques**: 
   - **Random UnderSampling**: Reduced the number of majority class samples to balance the dataset.
   - **Random OverSampling**: Increased the number of minority class samples to balance the dataset.
   - **SMOTE**: Used Synthetic Minority Over-sampling Technique (SMOTE) to generate synthetic samples of the minority class.
5. **Model Development and Classification**:
   - **Logistic Regression**
   - **Random Forest Classifier**
   - **Multinomial Naive Bayes (MultinomialNB)**
6. **Model Evaluation**: Evaluated model performance using accuracy, precision, recall, and F1-score. The final model achieved **83% accuracy**.

## 💻 Technologies and Tools
- **Programming Language**: Python
- **Libraries**: Pandas, Matplotlib, Seaborn, Scikit-learn, NLTK (Natural Language Toolkit)

## 🌟 Key Findings and Impact
- **Sentiment Distribution**:
   - **23.7% Positive**: Customers appreciated comfortable seats, friendly crew, and smooth in-flight experience.
   - **65.5% Negative**: Common complaints included delays, poor customer service, and subpar business class experiences.
   - **10.8% Neutral**: Neutral reviews often discussed non-emotional aspects of the flight experience.
- **Key Insights**:
   - Positive reviews often mentioned aspects like comfort and crew service.
   - Negative reviews were primarily related to delays and dissatisfaction with customer service and cabin crew.

## 🏆 Results and Value
This analysis provided valuable insights for British Airways to focus on improving areas such as punctuality, customer service, and cabin crew performance. By identifying the key concerns of passengers, the airline can implement data-driven strategies to enhance customer satisfaction and drive continuous improvement in service quality. The final model achieved an **83% accuracy**, providing a reliable tool for classifying future customer reviews.

## 🚧 Challenges Encountered
A significant challenge was dealing with a highly imbalanced dataset, where negative reviews vastly outnumbered positive and neutral ones. To address this, I employed multiple resampling techniques — Random UnderSampling, Random OverSampling, and SMOTE — to balance the dataset and ensure fair model training and evaluation.

## 📘 Learnings
- Gained expertise in **data analysis** and **exploratory data analysis (EDA)**, including effective data visualization techniques.
- Strengthened skills in **Natural Language Processing (NLP)**, particularly in text cleaning, tokenization, and sentiment analysis.
- Developed and fine-tuned **machine learning models** for text classification and gained experience with various resampling strategies to handle imbalanced datasets, resulting in an **83% model accuracy**.
