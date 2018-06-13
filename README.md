# Mongo

## The New York Time Scraper

* Overview

The New York Time (NYT) Scraper is a scraper app which captures the title, summary and image of articles of The New York Times. In this app, users are able to save their preferred articles, add notes and edit notes to one or multiple articles. 

In this repository, you can see source code of NYT Scraper. For experiencing, please go to Heroku:

https:.herokuapp.com/

Key Dependencies
request: enables cheerio to get access to front-end code of https://www.nytimes.com/section/world

* cheerio: scrapes front-end code from https://www.nytimes.com/section/world

* mongoose: be in charge of database of NYT Scraper

* express: builds server-side routes and functions

* morgan: logs server-side requests, helping debugging

* express-handlebars: a powerful front-end builder without requiring multiple html pages