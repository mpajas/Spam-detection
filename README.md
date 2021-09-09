# Spam detection

## Data
Data used for the purposes of this project is [SMS Spam Collection](https://www.kaggle.com/uciml/sms-spam-collection-dataset/code?datasetId=483&sortBy=voteCount) dataset on Kaggle. Data features 5574 SMS messages written in English, tagged using labels spam and ham accordingly. Each line contains one message and belonging label (ham or spam).

In this project I consider a few naive indicators like message length and word count in order to classify the messages. I compare them with a more advanced strategy and observe how it acts on different machine learning models.
