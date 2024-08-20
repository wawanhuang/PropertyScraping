# Real Estate Data Scraping in Samarinda

## Overview

This project involves scraping real estate data from a property website for the city of Samarinda, Indonesia. The data collection process is automated using Selenium for browser automation and BeautifulSoup for parsing the HTML content. The scraped data is then organized into a structured format for further analysis.

## Project Structure

- **Notebook:** `data_scrap_samarinda.ipynb`
  - The Jupyter notebook contains the code and steps for scraping data from the targeted website.
  - It includes sections for importing necessary libraries, setting up the web driver, and extracting relevant data.

## Contents

1. **Import Libraries:**

   - The notebook starts with importing essential libraries including Selenium, BeautifulSoup, Pandas, and time.

2. **Web Driver Initialization:**

   - The Selenium web driver is initialized to automate the browser and navigate to the target URL.

3. **URL Setup:**

   - The target URL is set up to scrape property listings in Samarinda.

4. **Data Extraction:**

   - Using BeautifulSoup, the HTML content of the website is parsed to extract information such as property details, prices, and locations.

5. **Data Storage:**
   - The extracted data is stored in a Pandas DataFrame, which can then be exported to a CSV file for further analysis.

## Requirements

- **Python 3.12.3**
- **Selenium==3.14.1**
- **BeautifulSoup4==4.12.3**
- **Pandas==2.2.1**
- **Chromedriver**

## Setup Instructions

1. **Clone the repository:**

   ```bash
   git clone https://github.com/wawanhuang/PropertyScraping
   ```

2. **Install the required libraries:**

   ```bash
   pip install -r requirements.txt
   ```

3. **Download the Chrome WebDriver:**

   - Ensure that the Chrome WebDriver is compatible with your version of Chrome and place it in the appropriate path.

4. **Run the Notebook:**
   - Open the Jupyter Notebook and run the cells to start the scraping process.

## Usage

- After running the notebook, the scraped data will be stored in a DataFrame which can be exported to a CSV file for further analysis.
- You can modify the target URL or the scraping logic to adjust for different search criteria or locations.
