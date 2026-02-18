Book Market Intelligence System: Web Scraping & Data Analysis
--------------------------------------------------------------

Project Overview
This project demonstrates an end-to-end data science workflow using web scraping and exploratory data analysis.

The objective was to extract raw book data from a multi-page website and convert it into a structured dataset for analysis and business insights.


Problem Statement
Web data is typically unstructured and stored in HTML format.

The goal of this project was to:
- Extract structured information from a website
- Clean and preprocess the collected data
- Perform exploratory data analysis
- Generate meaningful insights


Data Collected
- Book Title
- Price
- Rating
- Availability

Approximately 1000 records were collected using multi-page scraping.


Technologies Used
- Python
- requests
- BeautifulSoup
- pandas
- matplotlib


Project Workflow
1. Website Inspection
   Identified relevant HTML tags and classes for data extraction.

2. Multi-Page Scraping
   Implemented pagination logic to scrape data from 50 pages.

3. Data Cleaning
   - Removed currency symbol from price column
   - Converted price to float
   - Converted categorical ratings (One, Two, etc.) into numerical values

4. Exploratory Data Analysis
   - Calculated average price
   - Analyzed rating distribution
   - Identified highest priced books

5. Visualization
   - Rating distribution bar chart
   - Price distribution histogram


Key Insights
- Identified rating distribution pattern
- Observed pricing trends
- Detected premium-priced books
- Analyzed relationship between rating and price


Outcome
This project demonstrates how unstructured HTML data can be transformed into a structured dataset and analyzed to extract insights.

It highlights skills in web scraping, data cleaning, feature engineering, and exploratory data analysis.


Future Improvements
- Store data in a database
- Automate scraping process
- Build dashboard using Streamlit
- Apply machine learning for price prediction
