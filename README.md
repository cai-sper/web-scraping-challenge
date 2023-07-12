# Web Scraping Challenge

In part one of this challenge, Splinter was used to automate browser access to a website containing news about Mars. The article titles and previews were scraped from the website using Beautiful Soup, then saved in a Python dictionary by using a for loop to pull the text from specific HTML classes. This data was then exported to JSON to ease sharing the data with others.<br/>

In part two, Splinter was again used to automate webpage access to Martian temperature data. Beautiful Soup was then used to scrape tabular data off of the website which was then extracted from the HTML code by using a for loop. The results of the for loop were then turned into a Pandas DataFrame, which was cleaned by changing the data types and removing duplicate rows. It was then analyzed using Pandas aggregate functions and plotted using Matplotlib.
