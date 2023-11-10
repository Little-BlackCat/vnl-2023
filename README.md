# VNL 2023 Matches Project

The VNL 2023 Matches project involves web scraping using Python to gather data related to all volleyball matches in the VNL 2023 (Volleyball Nations League). The collected data is then manipulated and stored in a structured format using the Pandas library. This project is implemented in a Jupyter Notebook (`ipynb`).

## Features

- **Web Scraping**: Utilizes the BeautifulSoup library to scrape data from web pages containing information about VNL 2023 volleyball matches.

- **Data Extraction**: Extracts relevant information such as match details, teams, scores, and dates.

- **Data Manipulation**: Uses Pandas for data manipulation to structure the extracted information into a more organized and readable format.

## Technologies Used

- **BeautifulSoup**: A Python library for pulling data out of HTML and XML files.

- **Requests**: A Python library for making HTTP requests.

- **Pandas**: A fast, powerful, and flexible open-source data analysis and manipulation library for Python.

## How to Use

1. Clone the project repository:

   ```bash
   git clone git@github.com:Little-BlackCat/vnl-2023.git
   ```

2. Open the Jupyter Notebook:

   ```bash
   jupyter notebook VNL_2023.ipynb
   ```

3. Run the notebook cells to execute the web scraping, data extraction, and manipulation processes.

4. View the results and structured data within the notebook.

## Dependencies

Ensure you have the following Python libraries installed:

- `beautifulsoup4`
- `requests`
- `pandas`

You can install these dependencies using:

```bash
pip install beautifulsoup4 requests pandas
```

## Notes

- This project may require updates if the structure of the web pages containing match information changes.

- Always consider web scraping ethics and adhere to the terms of service of the websites being scraped.

