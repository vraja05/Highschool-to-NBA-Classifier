# Amazon Discount Impact Analysis

## Project Overview
This project aims to analyze the impact of discount percentage on the sales volume of products listed on Amazon. 
We use the number of ratings as a proxy for sales volume to understand how varying levels of discounts influence customer engagement and purchase behavior. 
The core of our analysis is built around a linear regression model that quantifies the relationship between discount percentage and sales volume.

## Dataset Description
The dataset used in this project contains various details about products sold on Amazon, including product names, categories, pricing, discounts, customer ratings, and more. 
For this analysis, we primarily focus on the `discount_percentage` and `rating_count` fields.

### Prerequisites
- Python 3.8 or higher
- pip (Python package installer)

### Libraries
This project depends on several Python libraries listed below:
- pandas
- numpy
- matplotlib
- scikit-learn

You can install these packages via pip using the following command:
```bash
pip install pandas numpy matplotlib scikit-learn
