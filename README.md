# Fake News Detection using LSTM

## Overview
This project aims to build a fake news detection model using LSTM (Long Short-Term Memory) neural networks. The model will analyze headlines and body text of news articles to classify them as either real or fake.

## Data Description
The dataset used for this project is stored in a CSV file named `news_data.csv`. It contains the following columns:

- URLs: URLs of the news articles
- Headline: Headlines of the news articles
- Body: Body text of the news articles
- Label: Labels indicating whether the news articles are real or fake (1 for fake, 0 for real)

## Data Preprocessing
- The data is loaded from the CSV file using pandas.
- Rows with missing values are dropped.
- Text labels are converted to numerical labels.
- The text data is tokenized and padded to ensure uniform length for LSTM input.

## Model Architecture
- The LSTM model consists of an embedding layer, an LSTM layer, and a dense output layer with sigmoid activation.
- Adam optimizer is used with binary crossentropy loss function.
- The model is compiled and ready for training.

## Training the Model
- The data is split into training and testing sets using a 80-20 split.
- The model is trained on the training set for 10 epochs with a batch size of 64.

## Model Evaluation
- The trained model is evaluated on the testing set to measure its performance.
- Evaluation metrics include loss and accuracy.

## Running the Code
1. Make sure you have the necessary libraries installed (`pandas`, `keras`, `scikit-learn`).
2. Place the `news_data.csv` file in the same directory as the code.
3. Run the code snippets provided in the sections above.

## Conclusion
This README provides an overview of the fake news detection project, including data description, model architecture, training process, and evaluation technique used. The LSTM model shows promising results in classifying news articles as real or fake based on their content. Further improvements can be made by optimizing hyperparameters and exploring advanced NLP techniques.

Feel free to reach out for any further inquiries or assistance.

---

This README provides a comprehensive guide to understanding and running the code for the fake news detection project. You can customize it further based on your project's specific requirements and additional details.
