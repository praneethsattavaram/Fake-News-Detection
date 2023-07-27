# Fake-News-Detection
# Fake News Detector Web App

This is a web application built using Streamlit to detect whether a given news article is fake or real. The fake news detection model is based on a logistic regression algorithm trained on a dataset of news articles with corresponding labels (fake or real).

## Installation

Before running the application, ensure you have the required libraries installed. You can install the dependencies using the following command:

```bash
pip install streamlit numpy pandas nltk scikit-learn
```

## Dataset

The model is trained on a dataset named `train.csv`, which should be present in the same directory as this script. If you don't have the dataset, you can obtain a similar labeled dataset of news articles and corresponding labels.

## Stemming and Vectorization

The content of each news article is preprocessed using stemming and vectorization. Stemming is performed to convert words to their base or root form, and stopwords (commonly occurring words like "and," "the," etc.) are removed from the content to improve the model's performance. The vectorization step converts the preprocessed text data into numerical form for machine learning algorithms.

## Running the Web App

To run the application, execute the following command:

```bash
streamlit run app.py
```

A web page will open in your default browser, where you can enter a news article. The model will then predict whether the news is fake or real.

## Note

Please note that the accuracy of the model is based on the quality and size of the training dataset. The provided implementation serves as a basic example of how to build a simple fake news detection web app using Streamlit and scikit-learn. Further improvements and fine-tuning may be required for real-world deployment.

Feel free to modify the code and experiment with different models or datasets to improve the performance of the fake news detection. Enjoy exploring the world of natural language processing and machine learning with this Fake News Detector!
