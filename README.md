# Feedback Extraction from Product Reviews

<b>Project Introduction:</b> This project aims to identify and extract tangible feedback from product reviews posted on Amazon. This is accomplished in two stages: in the first stage a sentiment analysis is utilized to ascertain whether product reviews are positive or negative. In the second stage, reviews identified as "negative sentiment" are analyzed to assess if we can determine any themes or common topics emerging.

<b>What is sentiment analysis?</b> Sentiment analysis is a growing genre of text analysis that aims to assess the tone or emotion, a.k.a sentiment, associated with text. It gained a lot of mainstream attention in 2020, when stock analysts were especially interested in mining posts from popular subreddits such as r/wallstreetbets to try ascertain the retail investor sentiments about meme stocks via their posts, as thus, predict their potential trading actions. While main state of the art packages exist for sentiment analysis today, this project is a means to gain experience in more traditional sklearn based techniques and so more complex libraries are not explored here. Two vectorizers - CountVectorizer and TfidfVectorizer and three sklearn models - multinomial naivebaiyes, logistic regression and random forest classifiers, are explored. Gridsearch based parameter tuning is performed to determine the optimal number of features and other parameters for the vectorizers and each of the models.

<b>What is topic modeling?</b> Topic modeling aims to create coherent groupings of words to glean common themes ("topics") from the text corpus. Non-negative Matrix Factorization and Latent Dirichlet Allocation are utilized to explored project reviews for a subset of the products (in particular, Apple iphones).

<b>Dataset and Technology:</b> 

The dataset is an extract of ~400K reviews of various various products (predominantely electronics) from Amazon. This project is executed in Python, using predominantly the nltk/spacy and sklearn libraries. 

<b>Key Findings:</b>  PLACEHOLDER

###
#### Development Timeline
|Phase|Timeline| Decription |
|:---:|:---:|:---|
|P1 |Jul 2024|Initial Version: Focus is sentiment analysis using standard machine learning classification techniques|
|P2|Aug - Sept 2024|Topic modeling for negative reviews on a subset of products using Non Negative Matrix Factorization and Latent Dirichlet Allocation|
