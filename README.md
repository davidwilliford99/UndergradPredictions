# Predictive Analysis on College Graduates' Salaries

This Jupyter Notebook is a course project for Big Data Analitycs, utilizing Apache Spark, Pandas, scikit-learn, and Matplotlib to perform predictive analysis on the impact of college characteristics to graduates' futures. The analysis is based on a dataset from Kaggle titled "Where it Pays to Attend College".

## Project Overview

The project aims to understand how different factors related to educational institutions (like school type and region) affect the earning potential of graduates. It employs a linear regression model to predict future salaries based on these factors.

## Installation

### Prerequisites
- Python 3.8 or higher
- Apache Spark 3.5.1
- Jupyter Notebook

### Dependencies
To install the required Python libraries, run the following commands in your Jupyter Notebook or Python environment:

```bash
pip install pandas scikit-learn matplotlib pyspark
```

## Files
- `data/`: Folder containing CSV files with the data used for analysis.
  - `degrees-that-pay-back.csv`
  - `salaries-by-college-type.csv`
  - `salaries-by-region.csv`
- `Predictive_Analysis.ipynb`: Jupyter Notebook containing the complete analysis pipeline.

## Usage
Open the Jupyter Notebook in your preferred environment that supports `.ipynb` files (like JupyterLab or VSCode) and execute the cells sequentially to see the analysis and predictions.

## Features
- Data preprocessing and cleaning with Spark DataFrame operations.
- Feature engineering using one-hot encoding and vector assembly.
- Training a linear regression model with Spark MLlib.
- Evaluation of model performance with RMSE.
- Predictions of future salaries based on school type.

## Contributing
Contributions to this project are welcome! Please fork the repository and submit a pull request with your enhancements. For major changes, please open an issue first to discuss what you would like to change.

### Original Contributors
- [David Williford](https://github.com/davidwilliford99)
- [Matt Miranda](https://github.com/mattmiranda55)
- [Francisco Maldonado](https://github.com/fmaldon)

