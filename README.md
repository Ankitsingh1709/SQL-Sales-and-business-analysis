# PARCH & POSEY Paper Company Sales Analysis

## Table of Contents

- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)
- [SQL Queries](#SQL-Queries)

## Introduction

This GitHub repository contains an analysis of sales data for the PARCH & POSEY paper company. The analysis aims to provide insights into the company's sales performance, revenue channels, and sales representatives' achievements.

## Dataset Overview

The dataset consists of several tables:

### `Orders` Table

| Column              | Description                              |
|---------------------|------------------------------------------|
| id                  | Unique identifier for each order.        |
| account_id          | Account identifier associated with the order. |
| occurred_at         | Date and time of the order.              |
| standard_qty        | Quantity of standard paper sold.         |
| gloss_qty           | Quantity of glossy paper sold.           |
| poster_qty          | Quantity of poster paper sold.           |
| total               | Total quantity of paper products sold.   |
| standard_amt_usd    | Total amount (USD) for standard paper.    |
| gloss_amt_usd       | Total amount (USD) for glossy paper.      |
| poster_amt_usd      | Total amount (USD) for poster paper.      |
| total_amt_usd       | Total amount (USD) for the order.        |

### `Region` Table

| Column  | Description                      |
|---------|----------------------------------|
| id      | Unique identifier for each region. |
| name    | Name of the region.              |

### `Sales_Reps` Table

| Column      | Description                              |
|-------------|------------------------------------------|
| id          | Unique identifier for each sales representative. |
| name        | Name of the sales representative.         |
| region_id   | Identifier of the region to which the sales representative belongs. |

### `Web_Events` Table

| Column       | Description                              |
|--------------|------------------------------------------|
| id           | Unique identifier for each web event.    |
| account_id   | Account identifier associated with the web event. |
| occurred_at  | Date and time of the web event.          |
| channel      | Advertising channel used for the web event. |

### Some Key Information About the Data:

- The company sells three types of paper: regular, poster, and glossy.
- Clients primarily include large companies (e.g., 100 companies).
- Advertising is done on Google, Facebook, and Twitter to attract clients.

### Some Key Information About the Data:

- The company sells three types of paper: regular, poster, and glossy.
- Clients primarily include large companies (e.g., 100 companies).
- Advertising is done on Google, Facebook, and Twitter to attract clients.

## SQL Queries

We have analyzed the dataset using SQL queries to derive valuable insights. Here are some of the key queries and their purposes:

1. **Main Revenue Channels and Amount Sold**: Identifies the primary revenue channels and the amount sold through each channel.

2. **Region with the Most Sales**: Determines the region with the highest sales and provides insights into regional performance.

3. **Highest Sales Representative**: Identifies the highest-performing sales representative based on total sales.

4. **Highest Sales Representative by Region**: Uses Common Table Expressions (CTEs) to find the top sales representatives in each region.

5. **Account Spending on Paper and Channels**: Determines which account spent the most on paper and the corresponding channel used.

6. **Yearly Sales Analysis**: Analyzes sales trends over the years, identifying the years with the most sales and exploring monthly sales within specific years.

7. **Additional Queries**: Includes queries to find paper products with the highest revenue, the most sold paper products, and calculations for retention ratios of salespeople and customers.

## Usage

To use these SQL queries and explore the dataset:

1. Clone or download the repository to your local machine.
2. Set up your database environment if necessary.
3. Run the queries using your preferred SQL database management tool.
4. Analyze the results to gain insights from the dataset.
