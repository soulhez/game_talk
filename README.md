UCDD2 Final Project: Game Talk
==============================
##Team Infamous Blue Kittens##
**Members:**

* Olivia Abrant
* Erik Eakins
* Andrea Sassu

##About##

**Overview:** Create a website that, given the name of a recent video game, pulls news, reviews, and tweets about the game for market feedback purposes.

**APIs:**

* [GamesRadar API](http://api-portal.anypoint.mulesoft.com/future/api/gamesradar-developer-api/docs/reference): To grab reviews and news on specific games
* [Twitter API](https://dev.twitter.com/overview/api): To figure out what social media is saying about specific games
* STRETCH GOAL: [Alchemy API](http://www.alchemyapi.com/): To be used with the Twitter api to do a sentiment analysis to determine a positive or negative view about a game

**Learning Goals:** 

We want to learn how to get information from multiple APIs and display it in an easily readble fashion, even though the type of information varies. Overall, our focus is on rendering 15 pieces of information regarding the searched game on the website: 5 articles/news sources, 5 reviews, and 5 tweets. Pulling this information and laying it out in a easily readable and understandable manner for the user is our primary focus.

Additionally, we are planning for this to be a one-page website: it will look a bit like the google home page to start with just a search box, and when a game name is typed in, it will render all of the information on the same page.

**Stretch Goals:** Filter more relevent articles/reviews, sentiment analysis, having multiple/extra pages of information that we feel is relevent regarding the game.

**Responsibilities:**

* Olivia Abrant - Working with OAuth and Twitter
* Erik Eakins - Working with OAuth and GamesRadar
* Andrea Sassu - Building the front end (layout, CSS)

##Milestones##

**Stage One:**

* Very basic website layout with searching functionality
* Implement GamesRadar api to pull reviews for specific games from the search
* (Possible use: node.js or jquery)

**Stage Two:**

* Implement GamesRadar api to pull news for upcoming games
* Figure out what we want to render on the page with reviews and news results 
  (probably: top 5 results of each)

**Stage Three:**

* Implement Twitter information gathering, figure out what information we want to render 
  (probably: top 5 results - rank by number of retweets?)
* Display Twitter information alongside GamesRadar information

**Stage Four:**

* Make website more sophisticated looking: update graphics, polish interface
* STRETCH GOAL: use sentiment analysis (Alchemy API) on Twitter results