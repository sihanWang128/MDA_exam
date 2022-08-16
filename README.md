# Obama speech NLP Analysis

## About the project

All files related to this project are listed in MDA_exam repository

## code
For this project, there are 4 python files (recommend reading order)
1. MDA_project_crawler.ipynb
2. MDA_project_preprocessing.ipynb
3. MDA_project_TopicModeling.ipynb
4. MDA_Sentiment_analysis.ipynb

First the crawler file extracts all the information of speeches and same the values into obama_speech.csv

Then pre-processing file reads obama_speech.csv, clean and transform the data then save the data into obama_clean.csv

Next topic modelling file uses obama_clean.csv to train the model, generates NMF_topic.csv and gensim_topic_classifier.csv

Finally Sentiment analysis file reads gensim_topic_classifier.csv and NMF_topic.csv to perform the result

## report
The report is named as Obama_speech_report

## PowerPoint
There are two version of PowerPoint, one is pdf and another is ppt, both are named as Obama_presentation


