# Project-2__Web-scraping
Web scraping for the "Books to Scrape" website

We use the "Books to Scrape" website (http://books.toscrape.com/) for web scraping. In Section 1 of the Jupyter notebook we use web scraping to retrieve the title, rating, price, link and book cover for a list of 20 books. In section 2 of the Jupyter notebook we constructed interactive tools for the users. The users can provide the title of a book as input, and they will receive the rating, link, price and book cover as the output. 

In addition to the standard libraries (e.g., numpy, pandas), we also use the following libraries: 

import requests
from bs4 import BeautifulSoup
from IPython.display import Image
from IPython.core.display import HTML 
from ipywidgets import interact
import ipywidgets as widgets
