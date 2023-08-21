# Amazon Product Scraper

A Python script to scrape product information from Amazon.in.


## Table of Contents

- [About](#about)
- [Features](#features)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## About

This project is a Python-based web scraper designed to collect product information from Amazon.in. It provides a convenient way to gather details such as product names, prices, ratings, and more.

## Features

- Scrapes product URLs, names, prices, ratings, and review counts.
- Collects additional information like product descriptions, ASIN, and manufacturer.
- Exports data to a CSV file for analysis and further processing.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/amazon-product-scraper.git
   ```

2. Install dependencies:
   ```bash
   pip install requests beautifulsoup4
   ```

3. Run the script:
   ```bash
   python amazon_scraper.py
   ```

## Usage

1. Adjust the `base_url` in `amazon_scraper.py` to customize the scraping target.
2. Set the `pages_to_scrape` variable to control the number of pages to scrape.
3. Run the script and find the scraped data in `amazon_products.csv`.


## Contributing

Contributions are welcome! Feel free to open issues and submit pull requests.

1. Fork the repository.
2. Create a new branch for your feature/fix: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
```
