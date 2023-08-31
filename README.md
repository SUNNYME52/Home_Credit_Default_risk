# Home_Credit_Risk_Prediction
Home Credit risk prediction is the process of using data and machine learning to assess the likelihood that a borrower will default on their home credit loan. This is crucial for making informed lending decisions and reducing financial losses.

## About Home Credit
Home Credit Group is an international consumer finance provider which was founded in 1997 and has operations in 9 countries. Our responsible lending model empowers underserved customers with little or no credit history by enabling them to borrow easily and safely, both online and offline. 
Home Credit offers easy, simple and fast loans for a range of Home Appliances, Mobile Phones, Laptops, Two Wheeler's , and varied personal needs.
Dataset link: https://www.kaggle.com/c/home-credit-default-risk/data
##Exploratoy Data Analysis
Data Exploration is an open-ended process where we calculate statistics and make figures to find trends, anomalies, patterns, or relationships within the data. The goal of Data Exploration is to learn what our data can tell us. It generally starts out with a high level overview, then narrows in to specific areas as we find intriguing areas of the data.

## Data preprocessing
 It is a crucial step in conducting a home credit risk analysis. It involves cleaning and preparing the data to ensure it's suitable for accurate analysis and modeling.It includes handling missing data,handling 
 outliers,One hot encdoding,label encoding etc.
 
 ## Supervised Learning Techniques
 Algorithms used:
Logistic regression
Random Forest
Extreme Gradient Boost
We have created base models without balancing the target class and then We have used  Random OverSampler methods to balance the data. XGBoost model balanced using Random OverSampler method gave better accuracy and ROC AUC score.

## Built with
- Pandas - Pandas is used for data cleaning and analysis. Its features were used for exploring, cleaning, transforming and visualizing the data. Also Pandas is an open-source python package built on top of Numpy.
- Numpy - Numpy adds support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these arrays.
- Matplotlib - Matplotlib work like MATLAB that helps in data visualization to makes some change to a figure: e.g., creates a figure, creates a plotting area in a figure, plots some lines in a plotting area, decorates the plot with labels, etc.
- Seaborn - Seaborn is also used for data visualization and it is based on matplotlib. It provides a high-level interface for attractive and informative statistical graphics.

- Imblearn- imbalanced-learn is a python package offering a number of re-sampling techniques.
- Sklearn - Scikit-learn is a free machine learning library for the Python. It features various classification algorithms including Logistic regression, Random forest and XGBoost which were used in this project. It also helps in calculating the metrics such as classification report, accuracy score, f1 score, roc auc score and confusion matrix.

## Conclusion
In conclusion, our home credit risk prediction model offers a reliable way to assess applicants seeking home loans. By analyzing factors like income, credit history, and employment stability, the model helps lenders make informed decisions. It performs well with high accuracy and provides insights into the most important factors influencing credit risk. By using this model responsibly and continuously refining it, lenders can offer better-tailored loan terms and contribute to a fairer lending process.


