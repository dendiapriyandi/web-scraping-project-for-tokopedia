# Web Scraping Project for Tokopedia (Example: Seblak Search)
This project involves scraping data from Tokopedia using Python libraries such as BeautifulSoup and Selenium. The goal is to extract product-related information, such as names, prices, sellers, and more, from multiple pages of search results.



## Authors

This project was developed by [Dendi Apriyandi](https://www.linkedin.com/in/dendiapriyandi), an entry level data scientist and data engineer.
## Libraries

- BeautifulSoup: For parsing the HTML content of web pages.
- Selenium: To automate interactions with the web browser.
- Pandas: For organizing and manipulating the scraped data into a structured format (like CSV or Excel).
## Project Overview

This project involves scraping data from Tokopedia using Python libraries such as BeautifulSoup and Selenium. The goal is to extract product-related information, such as names, prices, sellers, and more, from multiple pages of search results.
## Prerequisites

Before running the project, ensure you have the following installed:

- Python 3.x
- BeautifulSoup (bs4): Install via pip install beautifulsoup4
- Selenium: Install via pip install selenium
- Pandas: Install via pip install pandas
- ChromeDriver: Make sure ChromeDriver is installed and available in your PATH.
## Key Sections

1. Data Loading and Cleaning

- The initial part of the notebook involves loading the dataset and performing necessary data cleaning steps, such as handling missing values and standardizing the data format.

2. Exploratory Data Analysis (EDA)

- Various statistical metrics such as mean, standard deviation, and skewness are computed to understand the distribution of data.
- Visualizations like histograms and bar charts are used to explore relationships between price, region, and customer behavior.

3. Statistical Hypothesis Testing

- Confidence intervals are calculated for the product pricing to determine the price range that is most likely to attract customers. For example, the lower and upper bounds for the price of Seblak are calculated as 20,631 and 23,471, respectively, based on a 95% confidence level.
- Hypothesis testing is performed to compare the sales patterns between different regions, particularly Jabodetabek (Jakarta and surrounding cities) versus non-Jabodetabek regions.

4. Price Optimization

- The analysis highlights an optimal price range for Seblak based on customer purchasing data. Insights are drawn on the pricing strategy, suggesting not to overprice or underprice the product to remain competitive in the market.

5. Actionable Insights

- Based on the skewness of the product ratings and sales, recommendations are made to focus promotional efforts on high-selling products and improve lower-rated products to enhance brand reputation.

6. Business Recommendations

The notebook concludes with strategic business recommendations such as pricing optimization, promotional focus, and product improvement areas to enhance sales and customer satisfaction.
## Future Improvements

- More Advanced Scraping Features: Extend the scraper to capture additional product details like reviews or product descriptions.
- Headless Scraping: To improve efficiency and avoid detection, configure the scraper to run in headless mode (without launching a visible browser window).
- Improved Error Handling: Add comprehensive error handling for scenarios such as page load failures or dynamic content loading issues.
