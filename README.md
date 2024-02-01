# Fake News Detection Project

## Data Description

The dataset used for this project is named `news_data.csv`. It contains the following columns:

1. `URLs`: The URLs of the news articles.
2. `Headline`: The headline or title of the news articles.
3. `Body`: The body text or content of the news articles.
4. `Label`: The label indicating whether the news articles are real or fake. The labels are represented numerically: 0 for real news and 1 for fake news.

The dataset is preprocessed by removing any rows with missing values and converting the text labels to numerical labels.

## Evaluation Technique

The evaluation technique used for assessing the performance of the fake news detection model is binary classification evaluation metrics. Since this is a binary classification problem (real vs. fake news), the following evaluation metrics are used:

1. **Accuracy**: The proportion of correctly classified news articles out of the total articles.
2. **Precision**: The proportion of correctly classified fake news articles out of all articles classified as fake.
3. **Recall**: The proportion of correctly classified fake news articles out of all actual fake news articles.
4. **F1-Score**: The harmonic mean of precision and recall, providing a balanced measure between them.
5. **ROC-AUC Score**: The area under the Receiver Operating Characteristic curve, which measures the model's ability to distinguish between real and fake news across various thresholds.

These metrics provide insights into the performance of the fake news detection model and help assess its effectiveness in correctly identifying fake news articles while minimizing false positives and false negatives.
