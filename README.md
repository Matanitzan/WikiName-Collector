
# WikiName Collector

## Project Overview
The **WikiName Collector** is a Python project designed to scrape and organize first names and surnames from Wikipedia. This project uses web scraping and data manipulation techniques to generate structured datasets suitable for applications such as machine learning, linguistic studies, or name-based analysis.

## Features
- **Data Collection**: Retrieves first names and surnames from Wikipedia using BeautifulSoup.
- **Data Organization**: Saves the scraped data into structured CSV files (`names.csv` and `surname.csv`) for further use.
- **Customizable**: Modular code allows easy adaptation for similar scraping tasks.

## Project Structure
- **`Wikipedia_Name_Collector.ipynb`**: Jupyter Notebook containing code for data scraping and processing.
- **`names.csv`**: CSV file containing the collected first names.
- **`surname.csv`**: CSV file containing the collected surnames.

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `pandas`: For data manipulation and storage.
  - `BeautifulSoup`: For web scraping.
  - `requests`: For making HTTP requests.

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/Matanitzan/WikiName-Collector.git
   ```
2. Install the required Python libraries:
   ```bash
   pip install pandas beautifulsoup4 requests
   ```
3. Open and run the Jupyter Notebook (`Wikipedia_Name_Collector.ipynb`) to start scraping data.

## Future Directions
- Expand scraping to include additional name-related data such as origins or popularity.
- Integrate multilingual support to collect names from non-English Wikipedia pages.
- Create an API for easy access to the collected datasets.

## Acknowledgments
This project is a part of exploratory data scraping and organization efforts, leveraging the power of Python libraries for efficient data collection and storage.

---
