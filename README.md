# World Population Data Scraper

This project scrapes population data for all countries from [Worldometers](https://www.worldometers.info/population/), and stores the data in individual `.csv` files for each country.

## Features
- Extracts a list of all countries from the population page.
- Scrapes historical population data per country (Year, Population, Yearly_%_Change , Migrants_net , Median Age).
- Saves each country's data in a separate CSV file inside the `Folder files` directory.
- Lets the user select and read a specific country’s data.

## Technologies Used

- Python
- `requests` for fetching web pages
- `BeautifulSoup` for HTML parsing
- `pandas` for reading CSV files (if used later)
