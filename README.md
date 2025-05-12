# Zomato Restaurant Exploratory Data Analysis

This repository contains a Jupyter Notebook for conducting Exploratory Data Analysis (EDA) on a Zomato restaurant dataset. The analysis explores various aspects of restaurants, including ratings, cuisines, location, and cost, to derive meaningful insights.

## Data Source

The data is sourced from a [CSV file](zomato.csv)

## Libraries Used

The following Python libraries are used in this analysis:

* **pandas**: For data manipulation and analysis.
* **numpy**: For numerical operations.
* **matplotlib**: For creating static visualizations.
* **seaborn**: For enhanced statistical data visualizations.

## Data Cleaning

The data cleaning process involves the following steps:

* Loading the CSV file into a pandas DataFrame.
* Handling missing values (e.g., identifying and dealing with NaNs).
* Checking and correcting data types where necessary.
* (Any other specific cleaning steps you performed, e.g., removing duplicates)

## Data Analysis and Visualization

The analysis includes visualizing and exploring the following:

* **Distribution of Restaurant Ratings:** To understand the general rating scenario.
* **Top Cuisines:** Identifying the most common cuisines.
* **Restaurant Count by City:** Showing the distribution of restaurants across different cities.
* **Average Cost for Two by City:** Analyzing the cost variations in different areas.
* **Relationship between Average Cost and Aggregate Rating:** Exploring if higher cost correlates with better ratings.
* (Any other specific visualizations you created)

## Observations

The analysis yielded the following key observations:

* Most restaurants have an aggregate rating above 3.
* North Indian cuisine is the most frequently listed cuisine.
* The number of restaurants varies across different cities.
* The average cost for two people varies across cities.
* A higher average cost for two people does not always indicate a higher aggregate rating.
* New Delhi has a significant representation in the dataset regarding the number of restaurants.
* A notable proportion of restaurants offer table booking services.
* Online delivery service adoption varies among restaurants.

## How to Use

1.  Clone this repository to your local machine:

    ```bash
    git clone <repository_url>
    ```

    (Replace `<repository_url>` with the actual URL of your repository)

2.  Navigate to the repository directory:

    ```bash
    cd EDA-on-Zomato
    ```

3.  Ensure you have the required libraries installed. You can install them using pip:

    ```bash
    pip install pandas numpy matplotlib seaborn
    ```

4.  Open and run the `EDA-on-Zomato.ipynb` Jupyter Notebook to reproduce the analysis and visualizations.

## Contributions

Contributions to this project are welcome. Please feel free to fork the repository and submit pull requests.
