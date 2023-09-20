# Business Analysis Across Continents and Categories

This project provides a Python script that analyzes a dataset containing information about businesses, their founding years, countries, and categories. The datasets used are `businesses.csv`, `countries.csv`, `new_businesses.csv`, and `categories.csv`, all of which are expected to be located in a `datasets` directory.

## Features

- Load and inspect the business data.
- Sort businesses based on their founding year.
- Merge business data with country data.
- Filter businesses based on their continent.
- Analyze the oldest businesses per continent.
- Handle missing data and identify countries without business data.
- Incorporate new business data.
- Merge business data with category data.
- Analyze the oldest businesses in specific categories.
- Comprehensive analysis of businesses across continents and categories.

## Requirements

- Python 3.x
- pandas library

## Usage

1. Ensure you have the required library installed:

   ```bash
   pip install pandas
   ```

2. Place the datasets (`businesses.csv`, `countries.csv`, `new_businesses.csv`, and `categories.csv`) in a directory named `datasets`.

3. Run the script:

   ```bash
   python <script_name>.py
   ```

## Dataset Columns

### businesses.csv
- `country_code`: Code representing the country of the business.
- `business`: Name of the business.
- `year_founded`: Year the business was founded.
- `category_code`: Code representing the category of the business.

### countries.csv
- `country_code`: Code representing the country.
- `country`: Name of the country.
- `continent`: Continent of the country.

### new_businesses.csv
- Contains similar columns to `businesses.csv` but represents newer data.

### categories.csv
- `category_code`: Code representing the category.
- `category`: Name of the category.

## Notes

- The project handles missing data and identifies countries without business data.
- The analysis includes merging multiple datasets to provide comprehensive insights.
- The project provides insights into the oldest businesses across different continents and categories.

## License

This project is open-source and available to everyone. Please make sure to reference this repository if you use it in your work or research.

---

For any issues or suggestions, please open an issue on the project's GitHub page.
