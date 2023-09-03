# PARCH & POSEY Paper Company Sales Analysis

## Table of Contents

- [Introduction](#introduction)
- [Dataset Overview](#dataset-overview)

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


## SQL Queries


[Optional: Add badges, links to your website, social media, or any other relevant information here.]

For any questions or issues related to this repository, please create an [issue](#) or contact [your email address].
