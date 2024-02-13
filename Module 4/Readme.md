# Module 4 - Web Scraping Essentials Project

### Description

This project contains the Python script that, when executed, detects any mentions of a particular keyword on Mastodon, Twitter, Gab, Parler, Truth Social, Telegram, or MeWe, or similar, and stores these to a report.

In this project, Selenium is utilized to access the "Craigslist - New York" website("https://newyork.craigslist.org/") . The functionalities of Selenium, BeautifulSoup, and Chrome WebDriver are used to locate appropriate titles/posts related to the keyword "jobs." The results, an available list of job categories found on the site, are generated as a CSV file named "job_catagories_list.csv". 

### Prerequisites

[selenium · PyPI](https://pypi.org/project/selenium/)
[ChromeDriver - WebDriver for Chrome - Downloads (chromium.org)](https://chromedriver.chromium.org/downloads)
 Beautiful Soup ( pip install beautifulsoup4)

### References

Scrapping Site -> "https://newyork.craigslist.org/"
[Beautiful Soup: Build a Web Scraper With Python – Real Python](https://realpython.com/beautiful-soup-web-scraper-python/)
[Combine Web Scraping, API Requests & Visualizations | by Techletters | Python Point | Medium](https://medium.com/python-point/combining-web-scraping-api-requests-visualizations-6b7a4cfacdd2)
[ChatGPT (openai.com)](https://chat.openai.com/) (for troubleshooting errors)
https://stackoverflow.com/questions/77515424/issues-downloading-chrome-driver-for-selenium-2023 (for troubleshooting errors)
