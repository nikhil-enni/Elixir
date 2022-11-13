# Elixir

Elixir twitter bot:
This twitter bot which is a python script, scrapes the data utilising Twitter API. The bot essentially extracts the Tweets related to Diseases, Drugs and Hospitals, this also stores the user information like user name, user handle, twitter joining date, followers count etc. associated with the Tweets that were extracted. Additional feature of this bot is to store the tags used by the users to Tweet in Twitter. One important functionality is to add a sentiment score to all the tweets, by this it would be possible to know the user's opinion on the medicines and hospitals. Extraction is done on the basis of the details stored in the Diseases, Drugs and Hospitals table. All the extracted details are committed in the Database used using a python script. Below are the details that are being scrapped from Twitter.

Tweet Details:
Tweet ID
Twitter Handle 
Tweet
Tweet creation date
Retweet count
Likes count 

User Details:
User ID
User Name
User Handle
User Profile Picture link
Followers Count

Tag Details:
Tag Name

Sentiment score:
Sentiment score of all the tweets are calculated
score>0 implies positive opinion
score<0 implies negative opinion 
score=0 implies neutral opinion

Steps to be followed:
1. Execute the given python file.
2. Use the given database to store the extracted details using Twitter API 
3. Run the SQL queries given in the document

Please refer to the document in the repository for more details 
Note: Twitter scraping bot file is present in the repository
Database file is also attached
