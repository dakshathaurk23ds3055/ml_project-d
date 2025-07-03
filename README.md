#  Web Crawler Tool with Parameter Extraction

This is a Python-based command-line tool designed to crawl a website and extract all URLs along with their GET parameters. It is useful for web application analysis, penetration testing, and automated inspection.


## Features

- Crawl internal links starting from a base URL
- Extract GET parameters from URLs (e.g., `?id=1&user=abc`)
- Save results to a `.txt` or `.csv` file
- Command-line interface for ease of use
- Lightweight and easy to extend


##  Requirements

- Python 3.6+
- Install required libraries using pip:

```bash
pip install requests beautifulsoup4
