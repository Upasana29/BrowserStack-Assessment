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

  Implementation Details
## Web Scraping
Target Website: El País

Steps:

Navigate to the Opinion section.

Scrape the first five articles for:

Titles

Content

Cover images (saved locally in article_images/).

Translation
Uses an external API to translate article headlines from Spanish to English.

Text Analysis
Counts the occurrences of words across translated titles.

Identifies words repeated more than twice.

Cross-Browser Testing with BrowserStack
Tests the script across different browsers and devices.

Runs 5 parallel threads to improve execution time.

## PDF Report
The BrowserStack Test Report (PDF) contains the results of cross-browser testing.

It documents test cases, execution logs, and screenshots.

[Public Link of Test Report] (https://automate.browserstack.com/dashboard/v2/public-build/V04xejVEYUpzZmc1YVB4VkFFa3FwZjd4SVJLbXhLOS80UlNTbFlmM2Ywcm1qWmR2Um11UGx4UFZwRExDTzZ0TjFnQTBJa1pMbDFFSGV2cDl6NVA5eFE9PS0tSmF2ZXQ0ei94QnN2M2o2VUd5OStqUT09--40646db6c26241a78b3a40faa9659434a8658849)
