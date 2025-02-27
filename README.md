Web Scraping Data Extraction Project

[Python](https://img.shields.io/badge/Python-3.x-blue.svg)
[BeautifulSoup](https://img.shields.io/badge/BeautifulSoup-4.x-orange.svg)

This project extracts structured data from an HTML page using Python and saves the results into CSV and JSON files. It addresses six tasks, including text extraction, table parsing, product information scraping, form details extraction, multimedia link collection, and a scraping challenge for featured products.


Table of Contents
- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Configuration](#configuration)
- [Usage](#usage)
- [File Structure](#file-structure)
- [Contributing](#contributing)
- [License](#license)

---

Features

1. Text Data Extraction
   Extract headings, paragraphs, and list items into `Extract_Text_Data.csv`.

2. Table Data Extraction  
   Scrape product names, prices, and stock status from tables into `Extract_Table_Data.csv`.

3. Product Information
   Capture book card details (title, price, availability) into `Product_Information.json`.

4. Form Details
   Extract form field names, input types, and default values into `Form_Details.json`.

5. Links and Multimedia
   Collect hyperlinks, video URLs, and metadata into `Links_and_Multimedia.json`.

6. Featured Products Challenge
   Scrape hidden product details (price, colors, ID) into `Featured_Products.json`.

---
 Technologies

- Language: Python 3.x
- Libraries:
  - `BeautifulSoup` (HTML parsing)
  - `requests` (HTTP requests)
  - `csv` (CSV file handling)
  - `json` (JSON file handling)

Installation

1. Clone the repository:
   bash
   git clone https://github.com/your-username/web-scraping-project.git
   cd web-scraping-project


