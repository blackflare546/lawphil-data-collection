# LawPhil Web Scraper & Crawler

A Python-based web scraping and crawling application for collecting legal information from [LawPhil](https://lawphil.net/). This tool uses the `requests` and `BeautifulSoup` libraries to extract content efficiently and handle crawling operations. It is optimized to gather structured legal data, ensuring proper compliance with the site's terms of use.

## Features

- **Efficient Crawling**: The app systematically visits and extracts legal data from various sections of LawPhil.
- **Customizable Scraping**: Easily adjust the scraping targets and customize extraction rules for different types of content.
- **Data Export**: Save collected data in CSV formats

## Installation

Follow these steps to set up the project:

1. **Setup a Python Virtual Environment**

#### Create a virtual environment:

```bash
python -m venv venv
```

#### Activate the virtual environment:

On Windows:

```bash
venv\Scripts\activate
```

On Mac:

```bash
source venv/bin/activate
```

2. **Install Depedencies**

```bash
pip install -r requirements.txt
```

## Usage

```bash
jupyter notebook
```

## Contributing

Pull requests are welcome. For major changes, please open an issue first
to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License

[MIT](https://choosealicense.com/licenses/mit/)
