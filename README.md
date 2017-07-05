# Tutorial: Web Scraping with Python

This repo contains materials of my tutorial at PyData Seattle 2017


## Environment and Installs

This tutorial requires you have an updated version of Python and Jupyter Notebook. I recommend Anaconda, which is a Python distribution. It's free and open source. You can download Anaconda from [here](https://www.continuum.io/downloads)

The notebooks contained in this tutorial is tested on Python 3, but should be mostly compatible with Python 2.x as well.

* Download drivers if you use Selenium

# Table of Contents

* [Chapter 0: Setup Instructions](notebooks/00.Check-Environment.ipynb)

* [Chapter 1: HTTP, GET requests, HTML](notebooks/01.HTML-Refresher.ipynb)

  Here let's do a quick HTML

* [Chapter 2: Study the site, and get a list of movies](notebooks/02.Parse-HTML-with-BeautifulSoup-Top-Movies.ipynb)

  Before we scrape the top movies, we have to find a list of them. We can do that in one request . This is really easy as long as there are some consistent patterns to the page.

* [Chapter 3: Let's get details about one movie](notebooks/03.BeautifulSoup-with-all-the-Details.ipynb)

  I want to see how much money the top 100 movie made

* [Chapter 4: Let's put all the code together, add loop magic](notebooks/04.Putting-it-all-together-Scraping-all-relevant-movies.ipynb)

  Now we have all 100 movies. Hooray!

* [Chapter 5: Scraping best practices](notebooks/05.Web-Scraping-Best-Practices.ipynb)

* [Extra Credit: Scraping the unscrapable - Selenium]()

  I wonder if top grossing movies also have the best reviews (it sounds obvious but is it really?). Let's do some interactive web scraping with Selenium.

* [Lab: HackerNews Trends Project](notebooks/Lab-Scrape-HackerNews.ipynb)

  Let's work on a Scrapping project to extract HackerNews trends to practice what we learnt.


## Aditional resources

Check out these really cool links and get inspired!


