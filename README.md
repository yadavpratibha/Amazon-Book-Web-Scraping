# 📚 Amazon Book Info Scraper

This Python script scrapes the Titl and Price of specific books from Amazon.in using `requests` and `BeautifulSoup`.

## 🛠 Features

- Extracts book **title** and **price** from Amazon product pages.
- Uses a custom `User-Agent` header to mimic a browser and avoid being blocked.
- Introduces a delay between requests using `time.sleep()` to reduce load on Amazon's servers.
- Gracefully handles missing data.

## 📦 Requirements

- Python 3.x
- Libraries:
  - `requests`
  - `beautifulsoup4`

Install required packages using pip:

```bash
pip install requests beautifulsoup4
