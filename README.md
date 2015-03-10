# twister
a web app to test the twitter API.

- Briefly describe your team’s project

```
  We will work on a Web app that will use the Twitter API. The app will allow users to
  create and edit goups of users to follow while providing a vote for tweets, so the proper
  tweet(s) will appear for each user. Wee need an API that does not require Authentication.
```

- Q2 and Q3 | Research and compile a list of APIs that might be useful for your project, and For each API, briefly describe how its functionality might be used in your project

```
 There are tons of API that we can use in out project, but due to the Twitter policy change
 in Jun 2013, almost all of APIs need OAuth. Which means, we can not use them without
 authentication in out app.

	- Twitter Custom PHP API: This API is very useful since it provides 2 options to search
	for. One is using the keyword search, and the other one is using a username.
	Link: https://github.com/robinbonnes/Custom-Twitter-PHP-API

	- Twitter REST API: This API needs authentication.
	Link: https://dev.twitter.com/rest/public

	- Twitcher API: Twitcher API seems to be the best match for the project since it does not
	need authentication.
	Link: http://twitcher.steer.me

	- anyorigin: Which basically converts the url to a JSON method. Useful but needs purchase.
	Link: http://anyorigin.com
  ```

- Choose one API from your list and create an example web page using jQuery AJAX to call the API and display the returned results

See the screenshots. Used Twitcher API.
	![alt tag](https://raw.github.com/mehrdadrafiee/twister/master/1.png)

- Describe why you chose that particular API and provide a link to its documentation

```
  Twitcher API: This API does not require authentication, however you have to sing in
  with your twitter account to use the API.
```

- Discuss any potential issues that you can foresee with using this API in your project

```
  Developers who wants to use twitcher need to sign in with their tweeter account, then
  twitcher will assign a key value to him/her. It might not be safe/secure, because it can
  access the developer's twitter information.
```

- Evaluate your experience creating the example web page and make a recommendation of whether your team should use this API or keep looking for better options

 ```
  I tried to use other mentioned options but the implementation was not easy at all.
  Twitcher is so easy to use, however, they have not provided a good documentation.
 ```

- Describe how the example you wrote might be expanded to use additional functionality provided by the API

  ```
  It can be expanded if we can look hashtags then find and introduce the users who has
  the same type of interests, who live in a area (or close by).
  ```