# Web Scraping Top Asian Countries by Area from Wikipedia

## Overview

This repository contains a Python script that performs web scraping to extract a list of Asian countries by area from a Wikipedia page. The script retrieves the data, cleans and formats it, and presents the top countries in a user-friendly format.

## Project Goals

*   Scrape data of Asian countries area from the Wikipedia page.
*   Clean and process the extracted data.
*   Present the data in a clear and organized manner.

## Code Description

The Python script `Web-Scraping-Using-Python.ipynb` uses the following libraries:

*   **requests:** To send HTTP requests to the Wikipedia page.
*   **Beautiful Soup:** To parse the HTML content and extract the table data.
*   **Pandas:** To create and manipulate dataframes for cleaning and analysis.

## Methodology

1.  **Send Request:** The script sends an HTTP request to the specified Wikipedia page URL.
2.  **Parse HTML:** Beautiful Soup is used to parse the HTML content of the page.
3.  **Extract Table:** The script locates the table containing the list of Asian countries by area.
4.  **Create DataFrame:** The extracted table data is converted into a Pandas DataFrame.
5.  **Data Cleaning:** The data is cleaned by removing unwanted characters, handling missing values, and converting data types.
6.  **Display Results:** The cleaned and processed data is displayed in a tabular format.

## Usage

1.  Make sure you have Python installed.
2.  Install the required libraries:

    ```
    pip install requests beautifulsoup4 pandas
    ```

3.  Run the script:

    ```
    jupyter notebook Web-Scraping-Using-Python.ipynb
    ```

4.  Follow the instructions in the Jupyter Notebook to execute the code and view the results.

## Sample Output

The script outputs a list of country names by area present in asia


## Skills Demonstrated

*   Web Scraping
*   Data Extraction
*   HTML Parsing
*   Data Cleaning
*   Pandas
*   Python Programming
