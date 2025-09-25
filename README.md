# Python-intership-task3
# News Headlines Web Scraper

This project contains a Python script that scrapes the top news headlines from a news website and saves them in a `.txt` file. The script uses the `requests` library to fetch the HTML of a webpage and `BeautifulSoup` from `bs4` to parse the HTML and extract the headlines.

## Prerequisites

Before running the script, make sure you have the following Python libraries installed:

- `requests`: To send HTTP requests to fetch HTML content from the website.
- `beautifulsoup4`: To parse the HTML content and extract headlines.

You can install the required libraries using the following command:

```bash
pip install requests beautifulsoup4
```

## How It Works

Send an HTTP Request: The script first uses the requests library to fetch the HTML content of the news website.
Parse the HTML Content: The script uses BeautifulSoup to parse the HTML and extract the headlines. It searches for <h1>, <h2>, and <h3> tags that typically contain the headlines.
Save Headlines: The extracted headlines are saved in a file called headlines.txt.
Error Handling: If the request fails or the HTML parsing doesn't work as expected, the script handles errors gracefully, allowing you to debug issues.
