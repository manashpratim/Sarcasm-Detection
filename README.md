# Sarcasm-Detection
Can sarcastic sentences be identified?
# Description
In this project, I have implemented a Convolutional Neural Network (CNN) using Tensorflow and Keras to detect sarcasm in News Headlines. The dataset that I have used in this project is available for download at  https://www.kaggle.com/rmisra/news-headlines-dataset-for-sarcasm-detection. The dataset contains headlines of news articles, link to the articles and the labels (1: Sarcastic,0: Not Sarcastic). I have used only the headlines to detect sarcasm due to resource constraints. However, I have provided the code to extract the articles from the links, in the notebook. The datset has 26709 headlines. I have split the data into 90:10 training (24038) and test (2671) sets. I have obtained an accuracy of over 95% in the training set and over 81% in the test set.
The accuracies can be further improved by using the articles to detect sarcasm.
