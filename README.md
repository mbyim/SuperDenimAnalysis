# SuperDenimAnalysis
Webscraped &amp; Explored Superfuture's Superdenim forum


I scraped superfuture.com's superdenim forum, a forum dedicated to denim enthusiests, to see if I could make some interesting insights from the data encompassing the entire history of the forum board.

**SuperdenimScrape.ipynb** -- I first attempted to scrape using Beatifulsoup, and I encountered errors due to Beatifulsoup not recognizing tags that existed. Wanting to avoid missing values, I decided to try and learn Scrapy and see if I could scrape without issue.

**denimspider.py** -- I wrote this scraper using the Scrapy webscraping framework. It ended up still having issues with grabbing all the values that existed, but I figured I would just work around it for the moment.

**CleaningandAnalysis.ipynb** -- Here, I cleaned the raw json data that the denimspider crawler had collected, and then began to analyze it (although I never fully exploited the data due to other priorities taking hold).

What I did learn so far:

I learned that the forum board had already peaked by post activity around roughly 2011 and had been on a serious decline ever since. (see graph in CleaningandAnalysis.ipynb) My follow up would be - why? What happened in 2011?

I confirmed my (obvious) hunch that the "replies" on a thread is highly predictive of how many "views" it had.
