## Zakariya Shafi 596

## Simple Data Warehouse in Python

This project demonstrates how to create a simple data warehouse using Python, SQLite, and Pandas.
It includes functionality for data storage, retrieval, basic analysis, and visualization.

## Features

Create and connect to an SQLite database

Execute SQL queries and fetch results

Convert Pandas DataFrames into SQL tables

Perform basic data analysis (summary statistics, missing values check, info)

Visualize data with Seaborn and Matplotlib (bar, line, scatter plots)

## Technologies Used

Python 3.x

Pandas – for data manipulation

SQLite3 – for database storage

Matplotlib & Seaborn – for visualization

NumPy – for numerical operations

## Project Structure
.
├── data_warehouse.db      # SQLite database (auto-created on run)
├── main.py                # Main script with all functions
└── README.md              # Documentation

## How It Works

Create Database Connection

Uses sqlite3.connect() to establish a connection.

Store Data

A sample employee dataset is converted into an SQL table (employees).

Fetch Data

Run SQL queries to retrieve rows from the database.

Analyze Data

Display head, info, descriptive statistics, and missing values.

Visualize Data

Plot employee salaries against names (bar chart).

## Usage
1. Clone the repository
git clone https://github.com/your-username/simple-data-warehouse.git
cd simple-data-warehouse

2. Install dependencies
pip install pandas matplotlib seaborn numpy

3. Run the script
python main.py

## Example Output

Console:

Connected database message

Fetched rows from employees

Data analysis results (head, info, describe, nulls)

Visualization:

A bar plot of employee salaries

## Future Improvements

Load data from CSV/Excel instead of hardcoded dictionary

Add support for multiple related tables (fact & dimension tables)

Implement aggregation queries (SUM, AVG, COUNT, GROUP BY)

Build a simple dashboard with Streamlit or Dash
