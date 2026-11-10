# IMDb Top 250 Scraper

Scrapes the IMDb Top 250 movies (rank, title, year, rating) using Selenium and saves them to a CSV.

## Setup
pip install -r requirements.txt

## Run
python imdb_scraper.py

Output: `imdb_top250.csv`

## Notes
- Requires Google Chrome installed.
- IMDb may change its page layout, which can break the selectors.
