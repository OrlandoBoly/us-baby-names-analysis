    US Baby Names Data Analysis
This project explores historical trends in United States baby naming conventions using the Pandas library in Python. The analysis focuses on data ingestion, filtering for specific demographics, and identifying the most popular names across historical records.

     Project Overview
The primary goal of this repository is to demonstrate data manipulation techniques on a large-scale dataset containing over 1.8 million records. By leveraging Python's data science ecosystem, the project extracts meaningful insights from raw CSV data.

        Features

* **Data Ingestion:** Efficient loading of the `us_baby_names.csv` dataset into a Pandas DataFrame.
* **Data Filtering:** Implementation of boolean indexing to isolate specific subsets of data (e.g., filtering for male births).
* **Statistical Sorting:** Ranking names based on their historical frequency to identify peak popularity years.
* **Positional Indexing:** Using `.iloc` for precise data retrieval and visualization of top-tier results.

## Dataset Description

The analysis is performed on a dataset containing the following features:

| Column | Description |
| :--- | :--- |
| **Id** | Unique identifier for each record. |
| **Name** | The name given to the baby. |
| **Year** | The year of birth (ranging from 1880 to 2014). |
| **Gender** | "M" for Male, "F" for Female. |
| **Count** | Total number of occurrences for that name/year/gender combination. |

## Technical Implementation

The notebook follows a logical data science workflow:

1.  **Exploration:** Initial review of the first 1,825,433 rows of the dataset.
2.  **Filtering:** Created a specialized subset, `us_babies_Male`, specifically targeting male birth records.
3.  **Ranking:** Sorted the data in descending order by `Count`.
4.  **Top-Tier Analysis:** Identified that **James** (1947) and **Michael** (1957) hold some of the highest single-year counts in US history, with over 90,000 births each.

## Requirements

To run this notebook, you will need:
* Python 3.x
* Pandas
* Jupyter Notebook or JupyterLab






       Author
Emmanuel Harrison Pratt
