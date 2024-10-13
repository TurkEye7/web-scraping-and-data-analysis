# web-scraping-and-data-analysis

# Mars News and Weather Data Scraping

## Overview
This project consists of two main tasks:

1. **Scraping Titles and Preview Text from Mars News**: Using Splinter and BeautifulSoup to extract the latest Mars news titles and previews from a provided URL.
2. **Scraping and Analyzing Mars Weather Data**: Scraping Mars weather data from a table and analyzing the data to answer questions related to Martian months, temperatures, atmospheric pressure, and the length of a Martian year.

## Deliverables

### 1. Mars News Scraping
- Used automated browsing to visit the Mars News site.
- Scraped titles and preview text from the articles.
- Stored the data in a list of dictionaries with keys for `title` and `preview`.
- Printed the scraped data for confirmation.

### 2. Mars Weather Data Scraping and Analysis
- Scraped the HTML table from the Mars weather site using BeautifulSoup.
- Converted the data into a Pandas DataFrame with the appropriate columns and data types.
- Analyzed the data to determine:
  - How many months exist on Mars.
  - How many Martian (sol) days worth of data were available.
  - The coldest and warmest months based on average minimum temperature.
  - The months with the lowest and highest atmospheric pressure.
  - Estimated how many terrestrial (Earth) days exist in a Martian year.
- Visualized the results using bar charts.
- Exported the final DataFrame to a CSV file.

## Acknowledgements
This project was completed with assistance from OpenAI language models such as **ChatGPT**.
