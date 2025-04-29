# pandas-and-matplotlib
# Pandas and Matplotlib: Iris Dataset Visualization

This project demonstrates data analysis and visualization using the **Iris dataset** with **Pandas**, **Matplotlib**, and **Seaborn**. It includes data preprocessing, statistical analysis, and various types of visualizations to explore the dataset.

## Features

1. **Data Loading and Preprocessing**:
   - Load the Iris dataset using `sklearn.datasets`.
   - Convert the dataset into a Pandas DataFrame.
   - Map numeric target values to species names.
   - Handle missing values (if any).

2. **Statistical Analysis**:
   - Display basic statistics using `df.describe()`.
   - Group data by species and compute mean values.

3. **Visualizations**:
   - **Line Chart**: Simulates a trend of sepal length over the dataset index.
   - **Bar Chart**: Displays average petal length by species.
   - **Histogram**: Shows the distribution of sepal width.
   - **Scatter Plot**: Visualizes the relationship between sepal length and petal length, categorized by species.

## Requirements

- Python 3.7 or higher
- Libraries:
  - `pandas`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

Install the required libraries using pip:

```bash
pip install pandas matplotlib seaborn scikit-learn
```

## How to Run

1. Clone this repository or download the script.
2. Run the Python script:

```bash
python "python script.py file"
```

3. The script will:
   - Load and preprocess the Iris dataset.
   - Display basic statistics and grouped means.
   - Generate and display visualizations.

## Example Outputs

### Line Chart
- **Sepal Length Trend Over Index**

### Bar Chart
- **Average Petal Length by Species**

### Histogram
- **Distribution of Sepal Width**

### Scatter Plot
- **Sepal Length vs Petal Length**

## Observations

1. **Line Chart**:
   - The sepal length varies across the dataset index, with distinct trends for each species.
   - Setosa has consistently lower sepal lengths compared to Versicolor and Virginica.

2. **Bar Chart**:
   - Virginica has the highest average petal length, followed by Versicolor and Setosa.
   - The differences in petal length are significant between species.

3. **Histogram**:
   - The sepal width distribution is approximately normal, with most values concentrated around 3 cm.
   - Setosa tends to have slightly higher sepal widths compared to the other species.

4. **Scatter Plot**:
   - There is a positive correlation between sepal length and petal length.
   - The species are well-separated in the scatter plot, with Setosa forming a distinct cluster.

## Notes

- The warning about `edgecolor` in the scatter plot is a known issue with Matplotlib and Seaborn. It does not affect the functionality of the script.
- The dataset used is the classic Iris dataset, which is widely used for machine learning and data visualization.

## Acknowledgments

- **Scikit-learn** for providing the Iris dataset.
- **Pandas**, **Matplotlib**, and **Seaborn** for data analysis and visualization tools.

![alt text](image.png)
![alt text](image.png)
![alt text](image.png)
![alt text](image.png)

