# E-commerce-Product-Categorization

## Introduction
In the rapidly evolving world of eCommerce, accurate product categorization is crucial for ensuring seamless customer experiences, reducing search friction, and increasing product discoverability. However, the sheer volume of diverse products poses a significant challenge. Current classification systems struggle to handle ambiguities, unconventional naming conventions, and multi-language data. This project aims to address these challenges through creating innovative solutions that enhance product categorization efficiency, accuracy, and scalability. We have to develop a text classification model that categorizes products with maximum accuracy based on description of the product.

---

## EDA
- We inspected the dataset to understand data structure, columns, summary statistics, checked and handled missing values, 
  dropped duplicate values and redundant columns.
- Analyzed the distribution of product categories to identify imbalances.
- Used bar plots to visualize the count of products in each category.
- Encoded product category column and visualized prominently appearing words in product description column using WordCloud.
  
---

## Feature Engineering
- Visualized Distribution of Product description text length
- We have done text processing, removed stopwords, lemmatize words
- Vectorized text data using TF-IDF
- Handled Class imbalance

---

## Model Training and testing
- Split the data into training and testing sets.
- Trained and evaluated various Machine learning and Deep learning models, tuned hyperparameters to improve model's performance.
- Performed evaluation with those models on new unseen test data, before evaluation we have done EDA, feature engineering, label encoding of that data.

---

## Performance Evaluation
- Used different evaluation metrics like accuracy, precision, recall, f1-score, confusion matrix.
- The confusion matrix provided actionable insights into misclassifications, helping identify areas where specific categories were harder to predict.
- Accuracy comparisons across models demonstrated the strengths of traditional machine learning approaches for this dataset.
- The XGBoost Classifier, Hyperparameter tuned Logistic Regression model, Multinomial Naive Bayes and Support Vector Machine outperformed other approaches,delivering high accuracy of **0.84** and showcasing their ability to handle structured text classification effectively.
- While the LSTM model was explored for its potential to capture sequential dependencies in textual data, it exhibited the lowest accuracy, indicating a need for more data and tuning.

---

## Conclusion
This project tackled the critical task of eCommerce product categorization, which plays a vital role in enhancing customer experience and streamlining product search. A variety of machine learning and deep learning models were implemented, evaluated, and compared to achieve accurate multi-class text classification.
