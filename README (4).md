# E-commerce Purchases Data Analysis

## Project Overview

This project explores an e-commerce purchases dataset using Python and
Pandas. It focuses on understanding customer purchase information and
answering practical data-analysis questions through filtering,
aggregation, string operations, and basic data exploration.

## Dataset

-   **Dataset:** [Ecommerce Purchases --
    Kaggle](https://www.kaggle.com/datasets/utkarsharya/ecommerce-purchases)
-   **File used:** `Ecommerce Purchases.csv`
-   **Records:** 10,000
-   **Columns:** 14

### Dataset Columns

The dataset contains the following fields:

-   `Address`
-   `Lot`
-   `AM or PM`
-   `Browser Info`
-   `Company`
-   `Credit Card`
-   `CC Exp Date`
-   `CC Security Code`
-   `CC Provider`
-   `Email`
-   `Job`
-   `IP Address`
-   `Language`
-   `Purchase Price`

## Questions Explored

The notebook works through the following questions:

1.  Display the first and last 10 records.
2.  Inspect data types, columns, dataset dimensions, and missing values.
3.  Find the minimum and maximum purchase prices.
4.  Calculate the average purchase price.
5.  Count customers whose language is French (`fr`).
6.  Find customers whose job title contains the word `engineer`, without
    case sensitivity.
7.  Retrieve the email address associated with a specified IP address.
8.  Count customers who use Mastercard and made a purchase above 50.
9.  Retrieve the email address associated with a specified credit card
    number.
10. Count purchases made during AM and PM.
11. Count credit cards that expire in 2020.
12. Identify the five most common email providers.

## Tools and Libraries

-   **Python**
-   **Pandas**
-   **Jupyter Notebook**

## Concepts Practised

-   Loading CSV data with `pandas.read_csv()`
-   Exploring data with `head()`, `tail()`, `info()`, `dtypes`,
    `columns`, and `shape`-related checks
-   Checking missing values with `isnull()` and `isnull().sum()`
-   Descriptive statistics using `min()`, `max()`, and `mean()`
-   Filtering rows with Boolean conditions
-   Combining conditions using `&`
-   Case-insensitive text matching with `str.contains()`
-   Selecting specific columns
-   Counting records with `len()` and `count()`
-   Counting categories with `value_counts()`
-   Extracting text using `split()` and string slicing
-   Applying custom logic using `apply()` and lambda functions
-   Iterating through a column using a `for` loop

## How to Run the Project

1.  Clone or download this repository.

2.  Download the dataset from the Kaggle link above.

3.  Place `Ecommerce Purchases.csv` in the same folder as the notebook.

4.  Install the required library:

    ``` bash
    pip install pandas jupyter
    ```

5.  Open Jupyter Notebook:

    ``` bash
    jupyter notebook
    ```

6.  Open `Ecommerce (1).ipynb` and run the cells.

## Project Structure

``` text
Ecommerce-Purchases-Analysis/
│
├── Ecommerce (1).ipynb
├── Ecommerce Purchases.csv
└── README.md
```

## Note

The notebook uses a local CSV filename, `Ecommerce Purchases.csv`. Make
sure the dataset is downloaded and placed in the correct folder before
running the notebook.

The dataset contains fields such as email addresses, IP addresses, and
payment-card information. Use it for learning and analysis only; do not
expose or misuse personal or payment-related data.

## Learning Outcome

This project provides hands-on practice with Pandas and exploratory data
analysis by answering real-world-style questions from a structured
e-commerce dataset.
