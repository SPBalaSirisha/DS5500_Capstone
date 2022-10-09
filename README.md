# Text Summarization

With the abundance of social media and cellphones in modern society, the influence of information on any field is frequently evaluated within a very less span of time. In this digital era, data is generated every second and the amount of data one can process is growing exponentially. This emphasizes the value of using autonomous models to gather and compile relevant data so that the articles would be limited to the screen space available on mobiles or devices like smart watches. Text Summarization is one such technique used in NLP to shorten long pieces of text into summaries from resources like books, news articles, web pages, conference papers etc.  In a nutshell, summarization is finding a subset of data which contains the “details'' of the entire set. 

Text Summarization is used to generate a summary that focuses on the details of the whole large text. There are basically two types of Text Summarization -
Extractive-based Summarization, which extracts the most important words in the text and generates a summary, and
Abstractive-based Summarization, which paraphrases the important information from text to generate a shorter document. 
For an Extractive summarization model, the approaches can be either supervised or unsupervised. All extraction based summarizers perform three relatively independent tasks:
(a) capturing key aspects of text and storing it using an intermediate representation
(b) scoring sentences in the text based on that representation
(c) and composing a summary by selecting several sentences.

In this project we aim to implement extraction-based Summarization using various approaches using BERT sentence embedding.

## Dataset Description

The dataset used in this Project is the Cornell Newsroom dataset Created by Grusky et al. at 2018, which contains 1.3 million articles and summaries written by authors and editors in the newsrooms of 38 major publications. The summaries are obtained from search and social metadata between 1998 and 2017., in English language. Containing 1.3M in JSON file format.  We have used the dataset with articles filtered for extractive summaries and truncated to 5,000 articles representing over 166,000 sentences.




