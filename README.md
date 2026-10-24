# iPhone Sales Data Analysis

Exploratory data analysis of iPhone listings (price, discount, ratings, reviews) with interactive Plotly charts.

## Dataset

`Phone_Sales.csv` with these columns: Product Name, Product URL, Brand, Sale Price, MRP, Discount Percentage, Number Of Ratings, Number Of Reviews, UPC, Star Rating, RAM.

> The CSV is not included in this repo. Place it next to the notebook before running.

## What the notebook does

1. **Data check** — missing values and summary statistics
2. **Top-rated phones** — the 10 highest-rated iPhone models
3. **Ratings and reviews** — number of ratings and reviews for the top models
4. **Price vs. ratings** — how sale price relates to number of ratings
5. **Discounts** — how discount percentage relates to ratings

## Tools

Python · pandas · NumPy · Plotly

## Run it

```bash
git clone https://github.com/QosainBukhari/Iphone_Sales-Data_Analysis.git
cd Iphone_Sales-Data_Analysis
pip install pandas numpy plotly statsmodels jupyter
jupyter notebook Phone_Sales.ipynb
```
