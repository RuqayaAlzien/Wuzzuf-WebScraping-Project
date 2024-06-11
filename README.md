# Web Scraping Project: Wuzzuf Job Listings

## Overview

This project focuses on scraping job listings from [Wuzzuf](https://wuzzuf.net/), a popular job search platform in Egypt. The goal is to extract job titles, company names, and job types from the website using Python's web scraping libraries (`requests` and `BeautifulSoup`) and then save the data into a CSV file. 

## Features

- **Scraping Job Listings**: The `scrape_wuzzuf.py` script scrapes job listings from Wuzzuf.
- **Data Extraction**: It extracts job titles, company names, and job types from the website.
- **Saving Data**: The extracted data is saved into a CSV file named `wuzzuf_jobs.csv`.
- **Jupyter Notebook Integration**: The project also includes a Jupyter notebook (`Wuzzuf_Job_Scraping.ipynb`) that demonstrates how to run the scraping script and view the scraped data in a DataFrame within the notebook environment.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repository.git
    ```

2. Install the required Python libraries:

    ```bash
    pip install requests beautifulsoup4 pandas
    ```

## Usage

1. Run the `scrape_wuzzuf.py` script to scrape job listings from Wuzzuf:

    ```bash
    python scrape_wuzzuf.py
    ```

2. The script will save the job data into a CSV file named `wuzzuf_jobs.csv`.

3. Optionally, you can explore the data and visualize it using the provided Jupyter notebook (`Wuzzuf_Job_Scraping.ipynb`).

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request if you have any suggestions or improvements.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
