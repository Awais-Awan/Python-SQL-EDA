# CSV to MySQL Integration and Exploratory Data Analysis using Python

## Overview

This project showcases how to integrate CSV data into a MySQL database using Python and perform exploratory data analysis (EDA) on the imported data. It consists of two main Jupyter notebooks:

1. **`csv-to-mysql.ipynb`**: Automates the process of importing CSV files into MySQL, handling data type mapping, table creation, and data insertion.
2. **`SQL-Python-EDA.ipynb`**: Performs EDA on the MySQL data using SQL queries and Python libraries such as Pandas, Matplotlib, and Seaborn.

## Project Structure

- **`csv-to-mysql.ipynb`**: 
  - Connects to a MySQL database.
  - Reads multiple CSV files from a specified directory.
  - Creates corresponding MySQL tables and inserts data.
  - Handles data type conversions and missing values.

- **`SQL-Python-EDA.ipynb`**:
  - Connects to the MySQL database containing the imported data.
  - Executes basic and complex SQL queries to extract insights.
  - Utilizes Python's data analysis libraries for visualization and deeper insights.

## Setup Instructions

### Prerequisites

- Python 3.x
- MySQL server installed and running
- MySQL Connector/Python (`mysql-connector-python`)
- Pandas, Numpy, Matplotlib, Seaborn

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/repository-name.git

**For DataSet please visit**: https://www.kaggle.com/datasets/devarajv88/target-dataset?select=products.csv
