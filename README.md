# Relationships Between Presidents Twitter and Political Issues

Twitter is one of the most popular social media in the U.S. and used by influential politicians
including US presidents. Twitter has been proven to be a tool to predict the real world. There
are many kinds of research on the relationship between Twitter and the stock market. The most famous
study is Twitter mood predicts the stock market by J Bollen which has been cited more than
3000 times. In this project, we sought to answer a question: Do politicians’ tweets match to their
real-life behaviors? With the answer to this question, we can forecast the changes in political
concerns by analyzing tweets.

# Introduction
The purpose of the project is analyzing the Twitter behaviors of Donald Trump and Barack Obama
and comparing their Twitter behaviors to what they do in the government. Exploring their
tweets by a Natural Language Processing approch, and find out their characteristics. Eomparing their tweets to find the changes of political concerns.

# Data Source
I used the 2014-2017 twitter data that provided by [Political Twitter Archive](http://www.trumptwitterarchive.com/)

# Analysis

I briefly explored the usage of the twitter of both presidents and processed content of tweets with NLTK to explore aggregate text statistics of the speeches and visualize some of their properties. Also, I analyzed the relationships between the properties of the tweets. Lastly, I used Latent Dirichlet allocation model to find the political concerns change between the President Obama’s last 10 Months of the presidency and President Trump’s first 10 months of the presidency in twitter in order to match to the actual changes of political concerns between two presidents in the real world. Please see the [analysis report](https://github.com/jimxx1995/PresidentsTwitterPoliticalIssues/blob/master/report.pdf) for more details.

# Interactive Visualization of Political Concerns of Presidents in Twitter
- [President Obama Political Concerns Visualization](https://cdn.rawgit.com/jimxx1995/PresidentsTwitterPoliticalIssues/9b318aa7/fig/ldaobama.html)
- [President Trump Political Concerns Visualization](https://cdn.rawgit.com/jimxx1995/PresidentsTwitterPoliticalIssues/9b318aa7/fig/ldatrump.html)

# Declaration
This project is an updated version of a project that I've done in UC Berkeley. This project only contains my part of work. I also updated with a data analysis report.

# Package Requirement
The package need to be installed are Wordcloud and pyLDAvis, I recommend using `pip` install
```
pip install wordcloud
pip install pyLDAvis
```
# LICENSE
In an effort to enable reproducible, collaborative research this project is subject to the MIT License.
