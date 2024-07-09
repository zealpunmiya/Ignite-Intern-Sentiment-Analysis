## Ignite Intern Sentiment Analysis

### Introduction
This project aims to build a sentiment analysis model to classify text data as positive or negative sentiment. The model uses techniques like TF-IDF vectorization and logistic regression to achieve high accuracy in classifying sentiments.

### Dataset
The dataset used in this project consists of customer reviews. The data was sourced from the Kaggle "Sentiment140" dataset, which contains 1.6 million tweets labeled for sentiment analysis.

### Project Structure
```
.
├── data
│   ├── sentiment140.csv          # Dataset file
├── notebooks
│   ├── Ignite_intern_sentiment_analysis.ipynb  # Jupyter notebook with the project code
├── images
│   ├── wordcloud_positive.png    # Word cloud for positive reviews
│   ├── wordcloud_negative.png    # Word cloud for negative reviews
│   ├── confusion_matrix.png      # Confusion matrix visualization
│   ├── roc_curve.png             # ROC curve visualization
│   ├── precision_recall_curve.png# Precision-Recall curve visualization
├── README.md                     # README file
└── requirements.txt              # Dependencies
```

### Model Description
- **Preprocessing**: The text data was cleaned and vectorized using TF-IDF.
- **Model**: A Logistic Regression model was trained to classify the text as positive or negative sentiment.
- **Evaluation**: The model achieved an accuracy of 89% on the test set.

### Evaluation
- **Accuracy**: 0.89
- **Precision**: 0.89
- **Recall**: 0.89
- **F1 Score**: 0.89

