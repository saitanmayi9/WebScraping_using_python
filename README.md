Web Scraping Project – Wikipedia Data Extraction

This project demonstrates web scraping with Python. The target page is Wikipedia’s Human Body Weight article. Using the requests library, the HTML content is fetched, and BeautifulSoup is used to parse and extract structured data (tables with class "wikitable").

Key Steps :

Fetch webpage with requests (using custom headers to mimic a browser).

Parse HTML with BeautifulSoup.

Locate and extract data tables (<table class="wikitable">).

Convert extracted tables into structured format (string/clean data).

Tech Used:

Python

requests, BeautifulSoup

 Use Case:
This project can be extended to scrape tabular data from Wikipedia and other websites for analysis, automation, and research.
