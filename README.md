# News Classification Comparison

This project aims to classify news articles as either real or fake using various machine learning algorithms and a Long Short-Term Memory (LSTM) neural network model.

## Dataset

The dataset used in this project contains news articles along with their headlines, bodies, and labels indicating whether they are real or fake. The dataset was preprocessed by combining the headlines and bodies, filtering out samples with empty text, and encoding the labels.

## Models and Results

1. **LSTM Model:**
   - Accuracy: 98.37%
   - The LSTM model achieved an accuracy of 98.37% on the test data after training for 5 epochs.

2. **Random Forest:**
   - Accuracy: 91.10%
   - Random forest classifier achieved an accuracy of 91.10% on the test data.

3. **Support Vector Machine (SVM):**
   - Accuracy: 74.81%
   - SVM classifier achieved an accuracy of 74.81% on the test data.

4. **Naive Bayes:**
   - Accuracy: 62.66%
   - Naive Bayes classifier achieved an accuracy of 62.66% on the test data.

5. **Gradient Boosting:**
   - Accuracy: 90.10%
   - Gradient boosting classifier achieved an accuracy of 90.10% on the test data.

## Conclusion

The LSTM model outperformed the traditional machine learning algorithms, achieving the highest accuracy of 98.37%. This suggests that deep learning models, such as LSTM, can be effective for text classification tasks like news classification. However, it's essential to consider factors such as model complexity, training time, and interpretability when choosing the appropriate model for a given task.

## Author

- Nimra Waqar

## Data Source

The dataset used in this project can be found at [link](https://data.europa.eu/data/datasets/gender-equality-index?locale=en).
