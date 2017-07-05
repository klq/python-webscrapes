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

* [Extra Credit: Scraping the unscrapable - Selenium](notebooks/06.Extra-Credit-Scraping-the-unscrapable.ipynb)   
  I wonder if top grossing movies also have the best reviews (it sounds obvious but is it really?). Let's do some interactive web scraping with Selenium.

* [Lab: HackerNews Trends Project](notebooks/Lab-Scrape-HackerNews.ipynb)  
  Let's work on a Scrapping project to extract HackerNews trends to practice what we learnt.


## Aditional resources

* [Introduction to HTML](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/Introduction
)
* [Discover Devtools](http://discover-devtools.codeschool.com/): a free interactive intro to using Chrome's developer tools
* [httpbin](http://httpbin.org/) lets you easily test a lot of HTTP functionality. (And it's [written](https://github.com/Runscope/httpbin) in Python; check it out!)
* [Web Scraping with Beautiful Soup](http://web.stanford.edu/~zlotnick/TextAsData/Web_Scraping_with_Beautiful_Soup.html) from some Stanford class
* [4 Best Practices of Web Scraping](http://scraping.pro/basic-web-scraping-principles/): not bad advice
* The [BeautifulSoup documentation](http://www.crummy.com/software/BeautifulSoup/bs4/doc/) is very good. There are all sorts of methods and they're all described here!
* [Newspaper](http://newspaper.readthedocs.org/), a Python library that might be helpful when you want to extract an article from a web site
* [Here is an introduction to regular expressions](http://www.diveintopython.net/regular_expressions/)
* [Web Scraping 101 with Python by Greg Reda (beautifulsoup)](http://www.gregreda.com/2013/03/03/web-scraping-101-with-python/)
* [Scrapy](http://scrapy.org/)  
An open source and collaborative framework for extracting the data you need from websites.  In a fast, simple, yet extensible way.  
* [Scrapy Tutorial](http://doc.scrapy.org/en/latest/intro/tutorial.html)
* The Selenium docs for [Locating Elements](http://selenium-python.readthedocs.org/locating-elements.html)
* You can use this [XPATH selector tutorial](http://zvon.org/comp/r/tut-XPath_1.html) when you need to construct an xpath selector. You can also check out the [w3schools XPath syntax](http://www.w3schools.com/xpath/xpath_syntax.asp) guide.
* [The 30 CSS Selectors you Must Memorize](http://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048)

