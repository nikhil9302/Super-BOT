# twitter-bot-NodeJS
1. First use the Twitter API from https://developer.twitter.com/ and authenticate to recieve the relevant API keys and Access Tokens which would be added in the config.js file.
2. For Searching hashtags and liking those tweets, Run this on your terminal:-
   ```  
   node app.js
   ```
   This gives us all the links of liked tweets of the specified Hashtag or if the tweet is already liked, then it is logged saying ```[ { code: 139, message: 'You have already favorited this status.' } ]```
3. For tweeting from NodeJS from your autheticated account, modify the tweet.status property in the tweet.js file and Run this on your terminal:-
   ```
   node tweet.js
   ```
4. Enjoy the bot in action    

   
