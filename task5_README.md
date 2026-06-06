# synent-task5-salesanalysis-yourname

## Problem Statement

A retail business needs to know which products are making money, which months see the most sales, and where profits are being lost. The goal was to analyze the Superstore dataset and answer these questions using data.

## Dataset Details

- Dataset: Superstore Sales Dataset
- Source: Kaggle
- Contains order-level transaction data with columns like order date, product category, sales, quantity, discount, and profit across different regions of the US.
- Format: CSV

## Approach

I first converted the order date column to datetime and extracted the month and year. Monthly revenue was plotted using a line chart to spot any seasonal patterns. Then I grouped the data by sub-category to find the top sellers by revenue and the most and least profitable products. I also looked at how discount rates affect profit by plotting discount percentage against profit margin.

## Results

- Sales peak in November and December every year
- Technology is the highest revenue category while office supplies have the most orders
- Tables and bookcases consistently run at a loss mainly because of high discounts
- Discounts above 30 percent almost always result in negative profit
- The West region is the most profitable overall
