
# WebsiteScarper

WebsiteScarper is a Python-based utility that **automatically crawls dynamic websites** (including those that load content with JavaScript) and saves the entire content into a formatted Word (.docx) document, preserving site structure for easy offline review, sharing, or analysis.

## Table of Contents
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features
- Crawls **static and dynamic websites** using Selenium (supports infinite scroll & Ajax-loaded data)
- Exports collected data as a **Word (.docx)** file, maintaining layout & heading hierarchy
- Designed for **pythonic extensibility**: easy to customize crawl depth, user interactions, or post-processing
- Handles authentication, delays, and can be integrated with other automation workflows

## Installation

1. **Clone the repository**:
    ```
    git clone https://github.com/tanishqkaul/WebsiteScarper.git
    cd WebsiteScarper
    ```
2. **Install dependencies**:
    ```
    pip install -r requirements.txt
    ```
   Ensure you have Python 3.7+ and an appropriate browser driver (e.g., `chromedriver` for Chrome).

## Usage

**Basic Example**:
```
python main.py 
```


## Configuration

- Crawl delay/timeout
- Custom user-agent
- Inclusion/exclusion URL patterns
- Selenium browser options



## Contributing

Contributions are welcome! Feel free to open issues, submit feature requests, or create pull requests. Please review and follow the [CONTRIBUTING.md](CONTRIBUTING.md) guidelines.

## License

This repository is licensed under the MIT License — see [`LICENSE`](LICENSE) for details.

## Acknowledgments

- Inspired by automation challenges around data preservation and SharePoint integration.
- Utilizes open-source packages such as Selenium and python-docx.

---


