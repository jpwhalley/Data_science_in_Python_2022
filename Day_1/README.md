# Data Science in Python
## Day 1: Collecting disparate data online by web scraping using Selenium and BeautifulSoup

Ideally the data we wish to work on can be downloaded in an easy to use format. Otherwise when we want only a small subset of a very big dataset, or the data is being constantly updated, hopefully the owner will provide an application programming interface (API) to automate the collection of the relevant data. However quite often the data cannot be downloaded and there is no API, but the data is publicly available, just dispersed across a website. When it would be too tedious and time consuming to navigate page by page to collect the data manually; we can use Selenium Webdriver and Beautiful Soup to automate navigating across the website and collecting of the relevant data. In this code clinic, I will go through the best practices (and what not to do!) when web scraping; using Selenium Webdriver to navigate around a website and then using Beautiful Soup to extract the data from the HTML.

Prerequisites
-------------

For this session, you will need:

*   I will talk about version control, specifically using Github. If you have an account, you may want to install [Github Desktop](https://desktop.github.com/).

*   Python3, I will be sharing a Python Notebook for everyone to work through with me (as discussed in the course [To do before the start](https://canvas.ox.ac.uk/courses/112935/pages/to-do-before-start "To do before start")).
*   Selenium: [https://selenium-python.readthedocs.io/](https://selenium-python.readthedocs.io/)I usually use pip or conda to install packages: 
    *   pip install selenium
        

or

*   *   conda install -c anaconda selenium
        

*   Beautiful Soup: [https://www.crummy.com/software/BeautifulSoup/bs4/doc/](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
    *   pip install beautifulsoup4
        

or

*   *   conda install -c anaconda beautifulsoup4
        

*   Gecko drivers for my web browser [https://selenium-python.readthedocs.io/installation.html#drivers](https://selenium-python.readthedocs.io/installation.html)
    *   You have to put the geckodriverbinary in a path Python can see, if my case I have it in ~/anaconda3/bin/ . If this does not work, I have found that putting it in your working directory (the same as the python notebook), should work.

*   Once you have done that, hopefully running the following code snippet:

from selenium import webdriver  
browser = webdriver.Firefox() # Or which ever web browser you are using  
browser.get("[https://www.literaryclock.com](https://www.literaryclock.com/)/“)

you should get a pop-up window of the [Literary Clock website](http://www.literaryclock.com/).

Recommended tutorial and reading
--------------------------------

*   A good example of scientific work based on web scraping can be found here: [Soft Drinks Industry Levy paper.](https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1003025)
*   Another good example of web scraping is the COVID-19 cumulative trackers, for example [Jon Hopkins COVID-19 Dashboard](https://www.arcgis.com/apps/dashboards/bda7594740fd40299423467b48e9ecf6), as published [here](https://www.thelancet.com/journals/laninf/article/PIIS1473-3099(20)30120-1/fulltext), with [Github repository.](https://github.com/CSSEGISandData/COVID-19)
