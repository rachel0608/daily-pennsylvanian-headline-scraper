# Daily Pennsylvanian Headline Scraper

This Python script scrapes the headline from the Crime section of The Daily Pennsylvanian website and saves it to a JSON file that tracks headlines over time. It scrapes once a day at 8PM.

## Description

The scraper uses BeautifulSoup to parse the HTML content of The Daily Pennsylvanian website's Crime section. It searches for the headline within the <h3> element with the class "standard-link". If found, the headline is extracted and logged. The script then saves the headline to a JSON file using the daily_event_monitor module, which tracks headlines over time.

## Acknowledgments

This scraper is based on the template provided by jlumbroso/basic-git-scraper-template.