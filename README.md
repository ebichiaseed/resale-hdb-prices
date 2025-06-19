# resale-hdb-prices
# Resale HDB Prices Analysis (Singapore)

This project explores and analyzes public resale flat transactions in Singapore using structured data analytics and visualization. It aims to uncover pricing patterns, lease trends, and spatial dynamics across towns and flat types, enabling better understanding of the housing landscape.

## 📊 Features

- **Data Cleaning & Preprocessing**
  - Parsing of remaining lease strings into numerical years.
  - Handling of missing values and standardization of column types.

- **Exploratory Data Analysis (EDA)**
  - Distribution of resale prices, floor areas, and remaining leases.
  - Boxplots and scatter plots to compare flat types and towns.
  - Lease trends visualized by planning area.

- **Aggregated Statistics**
  - Average resale price and floor area by town and flat type.
  - Remaining lease (mean and median) analysis.
  - Computation of average price per square meter.
  - Flat type availability mapping per town.

## 🏙 Dataset

The dataset used is from **data.gov.sg**, called using an OpenAPI query

> The dataset includes multiple years of resale transactions across all HDB towns.


> To view interactive plots: https://nbviewer.org/github/ebichiaseed/resale-hdb-prices/blob/main/resale_hdb_prices.ipynb
