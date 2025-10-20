# Consumer Complaint Text Classification System

An end-to-end machine learning project that automatically classifies consumer financial complaints into 4 categories using Natural Language Processing (NLP) and supervised learning techniques.

📋 Project Overview

This project builds an intelligent classification system that processes consumer complaint narratives and categorizes them into one of four complaint types:

- Category 0: Credit reporting, repair, or other personal consumer reports
- Category 1: Debt collection
- Category 2: Consumer Loan (including student loans, vehicle loans, personal loans)
- Category 3: Mortgage

The system achieves **88.63% classification accuracy** on unseen data, making it suitable for real-world deployment in financial institutions and regulatory bodies.

🎯 Problem Statement

With over 11 million consumer complaints in the database, manual classification is:
- Time-consuming and expensive
- Prone to human error and inconsistency
- Difficult to scale as complaint volume grows

This automated system provides instant, accurate classification to help route complaints to appropriate departments and identify emerging consumer protection issues.

🚀 Key Features

- Accuracy: 88.63% classification accuracy on test data
- Fast Training: Model trains in just 39 seconds
- Balanced Performance: Consistent accuracy across all categories (87-90%)
- Real-time Prediction: Classifies new complaints in milliseconds
- Interpretable Results: Provides confidence scores and feature importance
- Production-Ready: Includes complete prediction function with error handling

📊 Dataset

- Total Records: 11,522,175 complaints
- Used for Training: 200,000 balanced samples (50,000 per category)
- Features: Complaint narrative text (primary), plus 7 engineered features
- Time Period: Historical complaints from multiple years

🛠️ Technologies Used

Core Libraries
- Python 3: Primary programming language
- Pandas & NumPy: Data manipulation and numerical computing
- Scikit-learn: Machine learning algorithms and evaluation
- NLTK: Natural language processing and text preprocessing
- XGBoost: Advanced gradient boosting implementation

Visualization
- Matplotlib & Seaborn: Statistical visualizations and charts
- WordCloud: Visual representation of frequent terms

Text Processing
- TF-IDF Vectorization: Converting text to numerical features
- TextBlob: Sentiment analysis
- Regular Expressions: Text cleaning and pattern matching