# Data-Driven Insights: Sentiment Analysis for Movie Reviews

This project focuses on developing a natural language processing (NLP) classification model for Film Junky Union, a community dedicated to classic movie enthusiasts. The goal is to automatically detect negative movie reviews using labeled IMDB review data, enabling efficient filtering and categorization of user-generated content.

The project evaluates multiple text classification approaches and compares their performance using a strict quality threshold.

# Objective

To test the following hypothesis:

Movie review sentiment can be accurately classified using machine learning models, achieving an F1 score of at least 0.85 on the test dataset.

# 🛠️ Technologies Used

Python: Pandas, NumPy, Scikit-learn

NLP Tools: TF-IDF, tokenization, text preprocessing

Machine Learning Models: Logistic Regression, Gradient Boosting (and others)

Jupyter Notebook: Interactive environment for analysis and modeling

# Key Steps
# Data Description

Loaded and examined the IMDB movie review dataset.

Identified the target variable (pos) and dataset partitions (training and test).

Reviewed class balance and dataset structure.

# Exploratory Data Analysis

Analyzed class distribution to assess potential imbalance.

Examined text length and word frequency patterns.

Drew conclusions regarding dataset suitability for classification tasks.

# Text Preprocessing

Cleaned and normalized review text.

Applied tokenization and vectorization techniques (e.g., TF-IDF).

Prepared text features for model training.

# Model Development

Trained at least three different classification models, including:

Logistic regression-based classifiers

Gradient boosting-based classifiers

Additional baseline or experimental models

Tuned hyperparameters to improve F1 score.

# Model Evaluation

Evaluated all models on the test dataset using the F1 score.

Compared model performance and identified strengths and weaknesses.

Tested models on custom-written reviews to analyze real-world behavior.

# Model Comparison and Interpretation

Analyzed discrepancies between test set results and manual review predictions.

Explained differences in model behavior based on algorithmic characteristics and feature representation.

# Results

The analysis demonstrates that:

Machine learning models can reliably classify movie review sentiment.

Text preprocessing and feature engineering play a crucial role in model performance.

The best-performing model achieved an F1 score exceeding 0.85.

Different models exhibit varying sensitivity to language patterns and review length.

These results confirm that automated sentiment analysis can effectively support content moderation and categorization for Film Junky Union.
