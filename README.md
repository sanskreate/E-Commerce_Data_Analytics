# Data Analyst Project: E-commerce Behavior Analysis

## Overview
This project analyzes e-commerce user behavior data from a multi-category online store. The dataset contains millions of user interactions, including product views, cart additions, purchases, and more, collected during October 2019.

## Data Source
- **Kaggle Dataset:** [Ecommerce behavior data from multi-category store](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store?select=2019-Oct.csv)
- **File Used:** `2019-Oct.csv`

## Project Structure
- `2019-Oct.csv`: Raw data file downloaded from Kaggle.
- `combined_data_oct.parquet`: Combined and processed data in Parquet format.
- `cleaned_data_oct.parquet/`: Directory containing partitioned cleaned data files in Parquet format.
- `DataAnalystTask-Sanskriti Rai.ipynb`: Jupyter notebook with analysis, data cleaning, and insights.

## Getting Started
1. **Download the dataset** from Kaggle and place `2019-Oct.csv` in the project folder.
2. **Run the Jupyter notebook** (`DataAnalystTask-Sanskriti Rai.ipynb`) to see the data cleaning, exploration, and analysis steps.
3. **Processed data** is saved in Parquet format for efficient storage and analysis.

## Requirements
- Python 3.x
- Jupyter Notebook
- pandas
- dask.dataframe
- matplotlib.pyplot


## Analysis Goals
- Clean and preprocess raw e-commerce behavior data.
- Explore user interactions and purchasing patterns.
- Generate insights for business and marketing strategies.

## Usage
- Open the notebook and follow the step-by-step analysis.
- Use the cleaned and processed data for further analytics or machine learning tasks.

## Author
Sanskriti Rai

## License
This project is for educational and research purposes. Please refer to the Kaggle dataset license for data usage terms.
