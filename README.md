# Mars Data Web Scraping and Analysis

## Overview
This repository contains two deliverables as part of a web scraping and data analysis challenge. It demonstrates web scraping skills, data analysis, and data visualization techniques in the context of Mars-related data.

## Table of Contents
1. [Deliverable 1: Scrape Titles and Preview Text from Mars News](#deliverable-1-scrape-titles-and-preview-text-from-mars-news)
2. [Deliverable 2: Scrape and Analyze Mars Weather Data](#deliverable-2-scrape-and-analyze-mars-weather-data)
3. [Conclusions](#conclusions)

## Deliverable 1: Scrape Titles and Preview Text from Mars News
In this part of the challenge, web scraping techniques were utilized to extract titles and preview text from a Mars news website. The process involved:

- Automated browsing to visit the Mars news website.
- Inspection of the webpage to identify elements for scraping.
- Creation of a Beautiful Soup object to extract relevant text elements.
- Extraction of titles and preview text from news articles.
- Storage of the scraping results in Python dictionaries.
- Compilation of all dictionaries into a Python list.
- Exportation of data to a JSON file for future reference.

## Deliverable 2: Scrape and Analyze Mars Weather Data
In this part, the focus was on scraping and analyzing Mars weather data from a table on a website. The steps involved were as follows:

- Automated browsing to visit the Mars Temperature Data Site.
- Inspection of the webpage to identify elements for scraping.
- Creation of a Beautiful Soup object to extract data from the HTML table.
- Assembly of the scraped data into a Pandas DataFrame with appropriate column headings.
- Conversion of data types in the DataFrame for analysis.
- Analysis of the dataset to answer specific questions about Martian weather, including the number of months on Mars, Martian days' worth of data, coldest and warmest months, and atmospheric pressure.
- Visualization of the analysis results using Matplotlib.
- Export of the DataFrame to a CSV file for future reference.

## Conclusions
Here are some key findings from the analysis of Mars-related data:

- Mars weather data was analyzed, yielding the following insights:
  - There are 12 months on Mars.
  - The dataset contains 1867 Martian days' worth of data.
  - The coldest month on Mars, on average, is March, while the warmest month is September.
  - The lowest atmospheric pressure is in June, and the highest is in September.
  - A Martian year is approximately 675 Earth days, with temperature patterns suggesting a year length of around 700 days.
