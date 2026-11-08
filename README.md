# Beauty-Products-Data-Warehouse
A data warehousing project using scraped beauty and cosmetics product data.
# Beauty Products Data Warehouse

## 1. Project Overview

This project focuses on the design and implementation of a Beauty Products Data Warehouse using data collected from an online beauty and cosmetics website.

The project will involve web scraping to collect information about different beauty products, followed by data cleaning, transformation, and storage in a structured data warehouse.

The purpose is to organize beauty product information in a way that makes it easier to analyze products, brands, categories, prices, and customer ratings.

## 2. Project Objectives

The main objectives of this project are:

- To collect beauty and cosmetics product information through web scraping.
- To extract product names, prices, brands, categories, ratings, and reviews,size.
- To clean and transform the collected data.
- To design a data warehouse using a Star Schema.
- To create fact and dimension tables.
- To analyze beauty product information and identify useful patterns.

## 3. Data Source

The proposed data source is Sephora, an online beauty retailer that provides information about different beauty and skincare products.

Website: https://www.sephora.com/

The collected data will depend on the information publicly accessible on the selected website.

## 4. Data to Be Collected

The project will focus on collecting the following attributes:

- Product ID
- Product Name
- Brand
- Category
- Price
- Customer Rating
- Number of Reviews
- Product Link

## 5. Proposed Data Warehouse Design

The data warehouse will use a Star Schema structure.

### Dimension Tables

- Dim_Product: Stores product information.
- Dim_Brand: Stores brand information.
- Dim_Category: Stores product categories.
- Dim_Date: Stores dates, months, and years.
- Dim_Retailer: Stores information about the online retailer.

### Fact Table

- Fact_Product_Sales_Analysis: Stores measurable product information such as price, rating, review count, and product records captured on different dates.

## 6. Tools and Technologies

The following technologies will be used:

- Python – Data extraction and processing.
- BeautifulSoup – Web scraping.
- Pandas – Data cleaning and transformation.
- SQL Server – Data warehouse storage.
- Power BI – Data visualization and reporting.
- GitHub – Project documentation and version control.

## 7. Expected Results

At the end of this project, a structured Beauty Products Data Warehouse will be developed. The warehouse will make it possible to analyze beauty products, compare brands, examine product prices, and explore customer ratings and reviews.
