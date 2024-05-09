#This is a test
Introduction
This is a mini javascript project collection. Both of them were coded with HTML, CSS and Javascript.
Project detail
Text to speech converter
Description: This is a web tool can let you input the text data and then, it will speak the text for you. You can choose the language that you want to listen
Language programming: HTML, CSS and Javascript
Guide: First, you need to type the text into the box. After that, you choose the language in the tray below and then you just need press the Speak button to listen the voice

# **Project in colab (for presenting)**
[Model RoBerta _ Colab](https://colab.research.google.com/github/DangHuuPhuocVinh/data_science_application/blob/main/tweet_sentiment_extraction_2.ipynb)
# **Project in kaggle (for running)**
[Tweet Sentiment Extraction](https://www.kaggle.com/code/danghuuphuocvinh/report/edit/run/102204871)
# **Work plan**
 [Work plan of group](https://docs.google.com/spreadsheets/d/10moa8xnprmD-MkfVzvn73UQyaCyHGVSmkDy8GRSXU4Y/edit#gid=0)
# **Competition**
 [Tweet Sentiment Extraction](https://www.kaggle.com/competitions/tweet-sentiment-extraction) organized by [Kaggle](https://www.kaggle.com/)
## **Prize**
 **15000 USD**
## **Link solution** 
 https://www.kaggle.com/code/minhtamlenguyen/tensorflow-roberta-0-705
 <br>
 https://www.kaggle.com/code/jerifate/tweet-sentiment-blue-visualization-with-bert
 <br>
 [Google Colab](https://colab.research.google.com/github/lnmtam1999/BigData/blob/main/Amazon_Craw_Bertl.ipynb)
## Description
  E.g: "My ridiculous dog is amazing." [sentiment: positive]

  With all of the tweets circulating every second it is hard to tell whether the sentiment behind a specific tweet will impact a company, or a person's, brand for being viral (positive), or devastate profit because it strikes a negative tone. Capturing sentiment in language is important in these times where decisions and reactions are created and updated in seconds. But, which words actually lead to the sentiment description? In this competition you will need to pick out the part of the tweet (word or phrase) that reflects the sentiment.

  In this competition we've extracted support phrases from [Figure Eight's Data for Everyone platform](https://appen.com/datasets-resource-center/). The dataset is titled Sentiment Analysis: Emotion in Text tweets with existing sentiment labels, used here under creative commons attribution 4.0. international licence. Your objective in this competition is to construct a model that can do the same - look at the labeled sentiment for a given tweet and figure out what word or phrase best supports it.
  
  - Input: textID, text and sentiment
  - Output: selected_text
 
## **Columns**
 -  textID - unique ID for each piece of text
 -  text - the text of the tweet
 -  sentiment - the general sentiment of the tweet
 -  selected_text - [train only] the text that supports the tweet's sentiment
