# Notebook

## 1. Preprocessing.ipynb
This notebook focuses on cleaning and preparing the dataset for analysis. Key steps include:
- **Handling Missing Data**: Calculating the number of null values in each column and removing rows containing null values where necessary.
- **Feature Engineering**: Dropping irrelevant columns and parsing important fields (e.g., date-time, location).
- **Data Filtering**: After exploring the dataset, we found that the majority of severe accidents occurred in the Eastern Time Zone. As a result, we filtered the dataset to include only data from the eastern part of the US.
- **Saving Processed Data**: The filtered data was saved as a new CSV file to be used for further analysis.

A scatterplot showed the concentration of accidents in the Eastern region, helping inform the decision to focus on this region for more relevant predictions.

## 2. Visualization_and_ML_Models.ipynb
This notebook covers both data visualization and the implementation of machine learning models.

**Visualization**: Various plots such as bar plots, scatterplots, heat maps, Plotly box plots, Folium heat maps, and pie charts were used to extract insights and understand the dataset better.
**Machine Learning Models**: Three machine learning models were applied to predict accident severity:
1. **Logistic Regression:** A simple and interpretable model.
2. **Random Forest Classifier:** A powerful ensemble model that handles non-linearity well.
3. **K-Nearest Neighbors (KNN) Classifier:** This model provided the best performance with an accuracy score of 94.05%.
The KNN Classifier performed the best in predicting accident severity, outperforming Logistic Regression and Random Forest.

# Result
1. Visualizations provided deeper insights into accident distribution and correlations.
2. The focus on the Eastern Time Zone improved model performance due to the concentration of severe accidents in this region.
3. The KNN Classifier achieved the highest accuracy: 94.05%.
