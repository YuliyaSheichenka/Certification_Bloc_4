# <p align="center">AT&T Spam Detector</p>

<p align="center"> <img src="https://full-stack-assets.s3.eu-west-3.amazonaws.com/M08-deep-learning/AT%26T_logo_2016.svg" alt="AT&T LOGO" width="50%" />

## Video presentation

[Bloc 4: AT&T Spam Detector](xxx)

## Contact

You can write me at **sheichenkojuly@gmail.com**

## Context 

AT&T Inc. is an American multinational telecommunications holding company headquartered at Whitacre Tower in Downtown Dallas, Texas. One of the major problems that AT&T users are facing are spam sms messages.

AT&T has been able to manually flag spam messages for a time, but now they are looking for a way to detect them automatically in order to protect their users.

See **References** for more information on the dataset.

The dataset (.csv file) is included in the **data** folder. 

## Goal of the project
Build a spam detector that can automatically flag spam messages based on the sms' content only.

## Project files

The project includes two notebooks:
- *att_spam_detector_lstm.ipynb* describes building of a model from scratch using LSTM layers;
- *att_spam_detector_transfer_learning_bert.ipynb* describes transfer learning using Bert for sequence classification.

## References

- [Dataset on Kaggle](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset)
- [Classification using Pre-trained Bert Model (Transfer Learning)](https://medium.com/@yashvardhanvs/classification-using-pre-trained-bert-model-transfer-learning-2d50f404ed4c) (Medium article with code examples for using BERT with TensofFlow for supervised text classification)
- [Python for NLP: Multi-label Text Classification with Keras](https://stackabuse.com/python-for-nlp-multi-label-text-classification-with-keras/)