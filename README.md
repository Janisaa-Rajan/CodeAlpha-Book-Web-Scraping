# CodeAlpha – Web Scraping and Exploratory Data Analysis of Books

## Project Overview

This project was completed as part of the **CodeAlpha Data Analytics Internship**.

The project focuses on collecting book data from the **Books to Scrape** website using Python and web scraping techniques. The collected data is cleaned, structured, analyzed using Exploratory Data Analysis (EDA), and visualized to identify useful patterns and relationships.

## Objectives

- Scrape book information from multiple webpages.
- Collect and organize book titles, prices, ratings, availability, and URLs.
- Clean and validate the collected dataset.
- Perform Exploratory Data Analysis (EDA).
- Analyze the relationship between book price and rating.
- Create meaningful data visualizations.
- Generate a structured dataset for further analysis.

## Technologies Used

- Python
- Requests
- BeautifulSoup
- Pandas
- Matplotlib
- Google Colab
- GitHub

## Data Collection

The project collects the following information for each book:

- **Title**
- **Price**
- **Rating**
- **Availability**
- **URL**

Data is collected from multiple pages of the Books to Scrape website and combined into a single Pandas DataFrame.

The final dataset contains **100 books** and **5 attributes**.

## Data Cleaning and Validation

The collected data was cleaned and validated before analysis.

The following checks were performed:

- Converted book prices into numerical values.
- Converted ratings from text values into numerical ratings from 1 to 5.
- Checked for missing values.
- Checked for duplicate records.
- Verified appropriate data types.

The final dataset contains no missing values or duplicate rows.

## Exploratory Data Analysis

The dataset was analyzed to understand:

- Distribution of book ratings.
- Distribution of book prices.
- Average price for each rating.
- Relationship between price and rating.
- Number of books across different price ranges.
- Highest and lowest priced books.

### Key Findings

- The average book price is approximately **£34.56**.
- The average rating is approximately **2.93 out of 5**.
- The cheapest book in the dataset is **Patience**, priced at **£10.16**.
- The most expensive book is **The Death of Humanity: and the Case for Life**, priced at **£58.11**.
- The correlation between price and rating is approximately **-0.12**, indicating a very weak negative relationship.
- Books are distributed across all five rating categories.
- The **£0–20** price range contains the highest number of books.

## Visualizations

The project includes the following visualizations:

1. Distribution of Book Ratings
2. Distribution of Book Prices
3. Average Book Price by Rating
4. Book Price vs Rating
5. Number of Books by Price Range

These visualizations help communicate the patterns identified during the analysis.

## Project Files

- `CodeAlpha_Book_Web_Scraping.ipynb` – Complete Python notebook containing the web scraping, data cleaning, EDA, and visualizations.
- `CodeAlpha_Book_Web_Scraping.csv` – Final structured dataset containing the scraped book information.

## Conclusion

This project demonstrates a complete data analytics workflow, starting from web data collection and progressing through data cleaning, validation, exploratory analysis, and visualization.

The analysis shows that book price does not have a strong relationship with rating in the collected dataset. The project also demonstrates how web scraping and data analysis techniques can be combined to transform publicly available web data into meaningful insights.

## Internship

**CodeAlpha Data Analytics Internship**

Project: **Web Scraping and Exploratory Data Analysis of Books**
