# nyt-mongo-scraper
## NYT-SCRAPER

### About
This app scrape technology news from NY times website. It allows users to view and write notes on the latest news articles.

### Instructions

![Image of concert](./images/scrape.png)

1. Whenever a user clicks on the scrape button, the app scrapes stories from the NY Times technology section and displays them for the user. Each scraped article will be saved to the application database. The app scrapes and display the following information for each article:

* Headline - the title of the article

* Summary - a short summary of the article

* URL - the url to the original article

![Image of concert](./images/scrape1.png)

2. Users are also be able to leave notes on the articles displayed and revisit them later. The comments are saved to the database as well and associated with their articles. Users are also able to delete comments left on articles. All stored comments are visible to every user.