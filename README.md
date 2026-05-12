## Overview
An exploratory data analysis of the Iris flower dataset to understand the relationships between flower features and species classification. This project covers data visualization, statistical analysis, and basic classification insights using Python.

## Dataset
- *iris.csv*: The Iris flower dataset with 150 samples and 5 columns.
- *iris.ipynb*: Jupyter notebook containing the complete EDA workflow.

### *Features*
| Column | Description |
| --- | --- |
| SepalLengthCm | Length of the sepal in cm |
| SepalWidthCm | Width of the sepal in cm |
| PetalLengthCm | Length of the petal in cm |
| PetalWidthCm | Width of the petal in cm |
| Species | Flower species: Setosa, Versicolor, Virginica |

## Key Analysis Steps
1. *Data Loading & Overview*: Load dataset and check structure, data types, and missing values.
2. *Descriptive Statistics*: Mean, median, standard deviation for each feature grouped by species.
3. *Data Visualization*:
   - Pairplot to visualize relationships between all features
   - Boxplots to compare feature distribution across species
   - Scatter plots to identify separable clusters
4. *Correlation Analysis*: Heatmap showing correlation between numerical features.
5. *Species Distribution*: Count plot showing the balance of each flower species in the dataset.

## Tools & Libraries
- *Python 3.10+*
- *Pandas* - Data manipulation
- *NumPy* - Numerical computations  
- *Matplotlib & Seaborn* - Data visualization
- *Jupyter Notebook* - Interactive analysis
## Key Insights
- *Setosa* species is linearly separable from Versicolor and Virginica based on petal measurements.
- *PetalLength* and *PetalWidth* have the strongest correlation and are best for distinguishing species.
- *SepalWidth* shows the most overlap across all three species.
## Use Case
The Iris dataset is widely used for teaching classification algorithms and data visualization techniques. It serves as a foundation for understanding multi-class classification problems.

## Future Improvements
- Train a Machine Learning model like KNN or SVM for species classification
- Add PCA for dimensionality reduction and 2D visualization
- Deploy as a simple web app using Streamlit
