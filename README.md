# Customer_Churn_Prediction
Python-based project to predict customer churn for an energy provider, leveraging machine learning techniques to analyze customer behavior and identify key factors influencing retention

The data preprocessing and visualization works were saved in Data_Preprocessing_Visualization file, and model application and predictions were saved in Modeling file. 


## Background
Leveraged a random forest model to predict the customer churn based on a set of variables including customer demographic, consumption trend and prediction, and price fluctuation. More importantly, figure out if price is the factor of customer churning. 


## Steps
(1) Descriptive Statistics: Assessed the data dimensions and examined the overall distribution to understand key characteristics.
(2) Visualization:  Visualized churn rates across various customer segments, such as sales channel and consumption history, while also examining distributions for skewness and potential outliers
(3) Feature engineering: Developed features to capture price fluctuations over different time periods which can not directly reflected by existing features, and applied techniques like one-hot encoding and transformations to address imbalances in the data
(3) Correlation analysis: Generated a correlation matrix to explore relationships between features
(4) Modeling and prediction: Built a Random Forest model using training data and evaluated its performance with a separate test dataset


