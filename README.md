# Crawler
Some crawlers that crawl PTT pages, Instagram, and Facebook
## PTT
Requests + BeautifulSoup
* Posts information in the past 3 days on PTT studyabroad
    * Likes
    * Topic
    * Date
    * Link
## IG
Selenium chromedriver + BeautifulSoup
* All the Saved Posts information from 1 account 
    * Link
    * Picture label
* Saved Posts Transfer
    * Failed because of HTTP ERROR 429 (Too Many Requests)
## FB
Selenium chromedriver + BeautifulSoup
* New posts information in a group(清交二手大拍賣XD)
    * Failed to crawl its link because of anti-crawl
### Note
* Change to YOUR_ACCOUNT and YOUR_PASSWORD in the codes before use
* Install Python, Selenium, Chromedriver, BeautifulSoup, and maybe Pandas
