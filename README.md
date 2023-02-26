# Prediction-using-unsupervised-ML

Unsupervised learning is a type of machine learning in which the model learns to find patterns and relationships in the data without being explicitly told what those patterns might be. Clustering is a common technique in unsupervised learning that involves grouping similar data points together into clusters based on some similarity metric.

Here I have done some steps: 

1. Importing Required Libraries.
2. Mount the google drive (for loading data/ can be load locally or by URL as well).
3. Reading the data using pandas (pd.read_csv).
4. After checking the data set, then dropping Id column as it looks like it is not needed and it is repeated in the dataset.
5. Checking for null values and duplicates.
6. Dropping the duplicate rows. (earlier it was 150 after dropping it was 147).
7. After that checking the outliers in the numeric data.
8. Outlier's definition:  In data analysis, outliers are data points that differ significantly from other data points in the dataset. Outliers may be caused by measurement errors, data processing errors, or they may represent legitimate but rare observations in the dataset. Outliers can have a significant impact on statistical analyses because they can bias the results or make them less reliable. For example, outliers can cause skewed distributions, inflate standard deviation, or distort regression lines. Therefore, identifying and handling outliers is an important step in data analysis. Outliers can be detected using various statistical methods, such as Z-score, modified Z-score, box plots, or kernel density estimation. Once identified, outliers can be removed, corrected, or imputed using appropriate techniques depending on the nature of the data and the research question at hand.

![outliers](https://user-images.githubusercontent.com/118778677/221422681-67a6aa91-26b4-4972-928c-0cb80a0c3c96.jpg)

9. Treating outliers present in the coulmn detected.

![outliers1](https://user-images.githubusercontent.com/118778677/221422737-158ac82d-76d3-446a-a653-dbd680b2bb02.jpg)

10. After that plotting the column using boxplot.
11. After plotting, Understanding the data, then distributing the features by species.
12. After that checking the correlation matrix and plotting using heatmap.
13. Now applying K-means clustering, and determining the optimal value of K using Elbow Method and Plotting the graph.
14. Predicted cluster for sepal length and width.
15. used lamda function to find the mean of the iris-setosa and iris-versicolor.
16. Print the classification report.
17. Representing that report into heatmap.

Thanks
