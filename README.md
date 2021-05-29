# Sentiment-Analysis
The following repository is about sentiment analysis on Twitter data. <br>

<h3>Introduction</h3>
Sentiment analysis (or opinion mining) is a <b>Natural Language Processing</b> technique used to determine whether data is positive, negative or neutral. Sentiment analysis is often performed on textual data to help businesses monitor brand and product sentiment in customer feedback, and understand customer needs.<br>

<h3>What you will learn?</h3>
Learn to perform basic sentiment analysis on real time data using Natural Language Processing libraries of Python. Also, get to know about WordCloud library to visualise the data and work on Twitter API.<br>
You can read more about these libraries in the documentation.<br>Click here to read more
<a href="https://docs.tweepy.org/en/latest/index.html">Tweepy</a>, <a href = "https://textblob.readthedocs.io/en/dev/">TextBlob</a>, <a href ="https://pypi.org/project/wordcloud/">WordCloud</a> <br>                                                           


<h3>How to perform the Analysis?</h3>
In this project, I am using tweepy, TextBlob and WordCloud libraries of Python to perform the analysis. Our task is to analyse the data in terms of subjectivity and plolarity. <br>
The <i>sentiment</i> funtion of TextBlob returns these two properties, subjectivity and polarity.<br><b>Polarity</b> is float which lies in the range of [-1,1] where 1 means positive statement and -1 means a negative statement. Subjective sentences generally refer to personal opinion, emotion or judgment whereas objective refers to factual information. Subjectivity is also a float which lies in the range of [0,1].<br>
1. Create Twitter API keys - for this, create developer account at <a href = "developer.twitter.com">developer.twitter.com</a>. Standard Twitter account will let you log in. Apply for the developer access by answering few question about why you need it.<br>
2. After getting keys - create a csv file and store ConsumerKey, ConsumerSecretKey, AccessToken and AccessTokenSecret. <br>
3. Upload the file as given in code <br>
4. Start writing code and perfrom the analysis.
