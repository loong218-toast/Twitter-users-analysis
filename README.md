# Twitter-users-analysis
A Twitter data analytics project 

https://app.powerbi.com/reportEmbed?reportId=ca1ea38c-f891-4ca6-828d-f830fb65abcf&autoAuth=true&ctid=cb2d37ae-1db9-4ac5-8be5-c2d9ceb1508b&config=eyJjbHVzdGVyVXJsIjoiaHR0cHM6Ly93YWJpLXdlc3QtdXMtYi1wcmltYXJ5LXJlZGlyZWN0LmFuYWx5c2lzLndpbmRvd3MubmV0LyJ9

![image](https://user-images.githubusercontent.com/77558802/154854826-a8db1309-807c-46df-b308-184bf4ebc224.png)

# Resources Used
Website : http://www.twitterholic.com/top200/followers/ <br />
Website 2 : https://en.wikipedia.org/wiki/List_of_most-followed_Twitter_accounts <br />
Python : pandas, numpy, twint, nltk(with wordnet), wordcloud <br />
SQL : Sqlite3<br />
Data visualization : Power BI

# Summary
I scraped data from http://www.twitterholic.com/top200/followers/ but the website is outdated. I took only names from this website and do data cleaning and verify them on Twitter using Twint. I obtain another 50 accounts information from wikipedia because top100 website seems not working. All of the data are inserted into sqlite3 database.<br />

I also categorized names by keywords by finding keywords at their bio and wikipedia pages. <br />
Visualized words by category using wordcloud : <br />
![download (2)](https://user-images.githubusercontent.com/77558802/154855092-146a0b77-f5e4-4442-9d30-83926f888981.png)
