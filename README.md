# Spam Email Classifier
This project is a spam email classifier. The same classifier is built using two different algorithms to compare the performance metrics of the algorithms on the dataset. The highlights of both the algorithms are listed below, along with the details of the dataset. 

## LOGISTIC REGRESSION:
1. TF-IDF vectorization is used for numerical vectorization of the emails.
2. Binary classification is used to classify the 'spam' and 'ham' emails.
3. Dataset is shuffled and assigned appropriate labels for better training. 

## LSTM:
1. A Recurrent Neural Network (RNN) is implemented using LSTM layers. 
2. Tensorflow is used to implement the LSTM model.
3. Emails are tokenized and preprocessed using appropriate labels. 
4. Sequence padding is used to ensure uniform input size.
5. EarlyStopping is used as a callback to prevent overfitting.

## Evaluation Metrics:
1.Average statistics of the model are given here.
  1. Accuracy: 98.067%
  2. Precision: 94.076%
  3. F1 Score: 0.96424
  4. Recall: 0.9890
2. Confusion Matrix has been plotted to visualize the performance of the models.

Dataset: **Source[Enron Email dataset](https://www.kaggle.com/datasets/wanderfj/enron-spam)

## Installation

```bash
git clone https://github.com/JambavanAbhiram/spam-email-classifier.git
cd spam-email-classifier
pip install -r requirements.txt
