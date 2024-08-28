<PLACHOLDER> # Sentiment Analysis and Topic Modeling Product Reviews

<b>Project Introduction:</b> This project aims to build a basic sentiment analysis functionality to ascertain whether product reviews are positive or negative. Time permitting, this project also has a secondary goal: to analyze the negative reviews for a subset of the products (in particular, Apple iphones) to assess if we can determine any themes or common topics emerging.

<b>What is sentiment analysis?</b> Sentiment analysis is a growing genre of text analysis that aims to assess the tone or emotion, a.k.a sentiment, associated with text. It gained a lot of mainstream attention in 2020, when stock analysts were especially interested in mining posts from popular subreddits such as r/wallstreetbets to try ascertain the retail investor sentiments about meme stocks via their posts, as thus, predict their potential trading actions. While main state of the art packages exist for sentiment analysis today, this project is meant to serve only as an intro to this field.

<b>What is topic modeling?</b> Topic modeling aims to create coherent groupings of words to glean common themes ("topics") from the text corpus.

<b>Project Details:</b> 


The dataset is an extract of ~400K reviews of various various products (predominantely electronics) from Amazon. This project is executed in Python, using predominantly the nltk/spacy and sklearn libraries. 


Dataset and Technology

###
#### Development Timeline
|Phase|Timeline| Decription |
|:---:|:---:|:---|
|P1 |Jul 2024|Initial Version: Focus is sentiment analysis using standard machine learning classification techniques. Two vectorizers - CountVectorizer and TfidfVectorizer and three sklearn models - multinomial naivebaiyes, logistic regression and random forest classifiers, are explored. Gridsearch based parameter tuning is performed to determine the optimal number of features and other parameters for the vectorizers and each of the models.|
|P2|Aug 2024|Expanding sentiment analysis functionality using ...|
|P3|Aug 2024|Topic modeling for negative reviews on a subset of products|
