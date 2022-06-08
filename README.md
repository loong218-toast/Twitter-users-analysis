# Twitter-users-analysis
A Twitter data analytics project 

![Screenshot 2022-03-13 131245](https://user-images.githubusercontent.com/77558802/158046098-99873a2c-d37b-4546-a2ca-d5f015b4152d.png)

Categories are defined by certain keywords. one category can be an interest, topic, and occupation. <br />
Samples are the top accounts (with most followers) from the population. <br />
People are interested in US media as most users are US-based (73% of accounts). We can see that media plays a big role in social media. People are also interested in music and film. A lot of Twitter users are also writers, which can mean that those followers read books. We have other categorized accounts, but 30.7% of accounts remain uncategorized as sometimes users don't provide enough information with their accounts.

A lot of accounts started around the time of 2009, and these accounts are top accounts and they are existed for at least 7 years. <br />

We can also see that producing more tweets doesn't mean more followers. Someone tweeted 1.5 million times but his followers are still below average. <br />

The relationship between following and followers doesn't tell us a lot. Generally, The lesson is that you don't need to follow a lot of people to have many followers.


# Summary
The objective is to find out the interests of users on Twitter. I scraped data from http://www.twitterholic.com/top200/followers/ but the website is outdated. I took only names from this website and do data cleaning and verify them on Twitter using Twint. I obtain another 50 accounts information from Wikipedia because the top100 website seems not working. All of the data are also inserted into sqlite3 database.<br />

I also categorized names by keywords by finding keywords on their bio and wikipedia pages. <br />
Visualized words by category using wordcloud : <br />
![download (2)](https://user-images.githubusercontent.com/77558802/154855092-146a0b77-f5e4-4442-9d30-83926f888981.png)


# Resources Used
IDE : Google Colab <br />
Website : http://www.twitterholic.com/top200/followers/ <br />
Website 2 : https://en.wikipedia.org/wiki/List_of_most-followed_Twitter_accounts <br />
Python : Pandas, Numpy, Twint, NLTK(with Wordnet), Wordcloud <br />
SQL : Sqlite3<br />
Data visualization : Power BI


