# Exploratory data analysis for fine-tuned-BERT-Model-for-Multi-Class-Tweets-Classification
How to fine-tune BERT model for binary and multi-class classification on 3 twitter text classification tasks(irony prediction, sentiment analysis and emotions detection.)

# Table of Contents
1. [Introduction](#Introduction)
2. [Data](#OurData)
3. [How to use](#HowToUse)


***
# Introduction
This is the repository for the Fine-tune-BERT-Model-for-Multi-Class-andMulti-Task-Tweets-Classification project. It consists of three tasks in Twitter.

# Our Data

These are the three datasets for this project, with its corresponding labels (more details about the format in the [datasets](https://github.com/cardiffnlp/tweeteval/tree/main/datasets) directory):

- **Emotion Recognition**: [SemEval 2018 (Emotion Recognition)](https://www.aclweb.org/anthology/S18-1001/) - 4 labels: `anger`, `joy`,`sadness`, `optimism`

- **Irony Detection**, [SemEval 2018 (Irony Detection)](https://www.aclweb.org/anthology/S18-1005.pdf) - 2 labels: `irony`, `not irony`

- **Sentiment Analysis***, [SemEval 2017 (Sentiment Analysis in Twitter)](https://www.aclweb.org/anthology/S17-2088/) - 3 labels: `positive`, `neutral`, `negative`

***
You can skip through preprocessing by feeding in our already pre-processed data into the model for a faster classification. Subsequently, you can use the train_text data and train_label data available in the data folder of each individual task.

### How to use

This code was created in Google Colab, and by default it should run smoothly on any program. 
Before use, we advise you change the file path to the path your file is stored. 


(this script would output the evaluation analysis only, and not an actual classification task.)
