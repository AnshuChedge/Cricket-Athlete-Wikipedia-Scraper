# Cricket-Athlete-Wikipedia-Scraper
PROJECT OVERVIEW

This project is a Python-based web scraping application that automatically collects detailed information about top Indian cricket players from Wikipedia. Instead of manually visiting each player's Wikipedia page and copying data, this script does it automatically in minutes and saves everything into a clean, structured CSV file ready for analysis.

OBJECTIVE

The main goal of this project is to build a custom sports dataset by extracting real data from public web pages using Python libraries — which directly satisfies the Web Scraping task requirement of collecting relevant datasets from public websites and creating custom datasets tailored to specific analysis needs.

TASK ALIGHMENT

This project is built as part of the Web Scraping Task which requires:

Using Python libraries like BeautifulSoup to extract data from websites
Identifying and collecting relevant datasets from public web pages
Handling HTML structure and web navigation to gather accurate data
Creating custom datasets tailored to specific analysis needs.

HOW IT WORKS

1.A list of 10 player names is defined as the starting point

2.The script calls Wikipedia's official API to fetch raw wikitext for each player

3.Regular expressions parse the infobox template to extract profile details

4.The rendered HTML version is fetched and pandas reads the career statistics table

5.All extracted text is cleaned by removing Wikipedia markup, citation numbers, and extra whitespace

6.All player data is combined into a single DataFrame and saved as a CSV file

ETHICAL SCRAPING PRACTICE FOLLOWS

- Uses Wikipedia's official REST API instead of direct HTML scraping.

- Adds a 1.5 second delay between each request to avoid overloading servers.

- Sets a proper User-Agent header to identify the bot transparently.

- Scrapes only publicly available data — no login or authentication required.

- No data is sold or used for commercial purposes.
