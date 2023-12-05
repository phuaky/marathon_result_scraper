Fetch Marathon Data

## Description

Fetch Marathon Data is a Python script designed to fetch and parse marathon race data from a specified range of pages on the sportsplits.com website. It extracts details such as the position, name, net time, representing country, overall position, category, and gun position, then exports this data into an Excel sheet for further analysis, such as pivot table creation and data comparison.

## Features

- Fetch race data across multiple pages
- Parse HTML to extract relevant table data
- Save data to Excel for easy manipulation and analysis

## Requirements

This script requires Python 3.x and the following Python libraries:

- requests
- BeautifulSoup4
- pandas

To install these dependencies, run the following command:

```bash
pip install requests beautifulsoup4 pandas openpyxl
```

## Usage

To run the script, simply execute it from the command line:

```bash
python fetch_marathon_data.py
```

Ensure you are in the correct directory where the script is located or provide the full path to the script.

## Output

The script will generate an Excel file named marathon_data.xlsx in the current working directory. This file will contain the extracted data in tabular form, separated into columns as per the script's configuration.

## Contributing

Contributions to Fetch Marathon Data are welcome! If you have suggestions for improvements or encounter any issues, please open an issue or submit a pull request.

## Acknowledgments

Thanks to sportsplits.com for providing the data.
This project is for educational purposes only.
