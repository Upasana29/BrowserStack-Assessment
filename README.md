# BrowserStack-Assessment
BrowserStack el-pais site scraping task.

# ElpaisArticleScraping

## Selenium Web Scraper for El País Opinion Section

This project is a **Python-based web scraper** that uses **Selenium** to fetch articles, cover images, and content from the **Opinion** section of [El País](https://elpais.com/). It also translates article headlines from Spanish to English and identifies repeated words in the headlines.

## Features

- **Web Scraping**: Extracts article headlines, content, and cover images.
- **Automatic Cookie Handling**: Accepts cookies and navigates to the Opinion section.
- **Translation API Integration**: Translates headlines from Spanish to English.
- **Text Analysis**: Identifies repeated words across translated headlines.
- **Cross-Browser Testing**: Runs tests on **BrowserStack** across multiple browsers and devices.

---

## Prerequisites

Before running the script, ensure you have:

- **Python 3.8+**
- **Google Chrome**
- **ChromeDriver** (compatible with your Chrome version)
- **BrowserStack account** (for cross-browser testing)
- **API Key** for the translation service (e.g., Google Translate API)
- **Required Python libraries** (install using `requirements.txt`):
  ```plaintext
  selenium
  requests
  googletrans==4.0.0-rc1  # Example for Google Translate

