# Twitter-users-analysis
A Twitter data analytics project 

https://app.powerbi.com/reportEmbed?reportId=ca1ea38c-f891-4ca6-828d-f830fb65abcf&autoAuth=true&ctid=cb2d37ae-1db9-4ac5-8be5-c2d9ceb1508b&config=eyJjbHVzdGVyVXJsIjoiaHR0cHM6Ly93YWJpLXdlc3QtdXMtYi1wcmltYXJ5LXJlZGlyZWN0LmFuYWx5c2lzLndpbmRvd3MubmV0LyJ9

![image](https://user-images.githubusercontent.com/77558802/154852491-f4e5369e-507e-4f5c-ab87-b3fefcc2421e.png)

# Resources Used
Website : http://www.twitterholic.com/top200/followers/ <br />
Website 2 : https://en.wikipedia.org/wiki/List_of_most-followed_Twitter_accounts <br />
Python : pandas, numpy, twint, nltk(with wordnet), wordcloud <br />
SQL : Sqlite3<br />
Data visualization : Power BI

# Explanation
I scraped data from http://www.twitterholic.com/top200/followers/ but the website is outdated. I took only names from this website and do data cleaning and verify them on Twitter using Twint. I obtain another 50 accounts information from wikipedia because top100 website seems not working. All of the data are inserted into sqlite3 database.<br />

I also categorized names by keywords by finding keywords at their bio and wikipedia pages. I then visualized words with their bio and wikipedia page using wordcloud.
