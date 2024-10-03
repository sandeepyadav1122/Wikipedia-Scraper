# Web Scraping Wikipedia - Rajneesh (Osho) Biography

![osho](https://github.com/user-attachments/assets/0232f665-3611-47a3-910c-dba77c1ff89e)

## Project Overview

This project demonstrates how to scrape a Wikipedia page using Python. Specifically, we scrape the biography of **Rajneesh (Osho)** from his Wikipedia page. The project utilizes the `requests` library to fetch the HTML content of the page and `BeautifulSoup` from the `bs4` package to parse and extract the biography section in clean text format.

### Features:
- Sends an HTTP request to Wikipedia and fetches the page content.
- Parses the HTML and extracts human-readable text from the biography section.
- Demonstrates essential web scraping techniques such as:
  - Making GET requests using the `requests` library.
  - Parsing HTML using `BeautifulSoup` from the `bs4` package.

## Prerequisites

To run this project, you’ll need the following:
- Python 3.x installed
- Required Python libraries:
  - `requests` (for making HTTP requests)
  - `BeautifulSoup4` (for parsing HTML)

### Installing Dependencies

You can install the necessary libraries using `pip`:

```bash
pip install requests
pip install beautifulsoup4
