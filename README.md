# Twitter-users-analysis
A Twitter data analytics project 

![Screenshot 2022-03-13 131245](https://user-images.githubusercontent.com/77558802/158046098-99873a2c-d37b-4546-a2ca-d5f015b4152d.png)


# Resources Used
IDE : Google Colab <br />
Website : http://www.twitterholic.com/top200/followers/ <br />
Website 2 : https://en.wikipedia.org/wiki/List_of_most-followed_Twitter_accounts <br />
Python : Pandas, Numpy, Twint, NLTK(with Wordnet), Wordcloud <br />
SQL : Sqlite3<br />
Data visualization : Power BI

# Summary
I scraped data from http://www.twitterholic.com/top200/followers/ but the website is outdated. I took only names from this website and do data cleaning and verify them on Twitter using Twint. I obtain another 50 accounts information from wikipedia because top100 website seems not working. All of the data are inserted into sqlite3 database.<br />

I also categorized names by keywords by finding keywords in their bio and wikipedia pages. <br />
Visualized words by category using wordcloud : <br />
![download (2)](https://user-images.githubusercontent.com/77558802/154855092-146a0b77-f5e4-4442-9d30-83926f888981.png)
