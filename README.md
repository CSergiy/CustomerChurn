# Customer Churn Analysis

## Table of Contents
- [About](#about)
    - [Information About The Dataset](#information-about-the-dataset)
- [Prerequisites](#prerequisites)
- [Results](#results)
- [Contact](#contact)

## About
This project employs advanced data analytics techniques to analyze customer churn. The objective of this project is to identify the factors contributing to customer churn and develop predictive models to identify customers at risk of churning. 

The analysis is done in the notebook `Customer_Churn.ipynb`, which analyzes customer churn and develops a predictive model.

### Information About The Dataset
The project makes use of the **Telco Customer Churn dataset** available at [IBM Business Analytics Community](https://accelerator.ca.analytics.ibm.com/bi/?perspective=authoring&pathRef=.public_folders%2FIBM%2BAccelerator%2BCatalog%2FContent%2FDAT00148&id=i9710CF25EF75468D95FFFC7D57D45204&objRef=i9710CF25EF75468D95FFFC7D57D45204&action=run&format=HTML&cmPropStr=%7B%22id%22%3A%22i9710CF25EF75468D95FFFC7D57D45204%22%2C%22type%22%3A%22reportView%22%2C%22defaultName%22%3A%22DAT00148%22%2C%22permissions%22%3A%5B%22execute%22%2C%22read%22%2C%22traverse%22%5D%7D). The [data dictionary](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113) provides a detailed description of each field in the dataset.

## Prerequisites
To run this project, the following packages need to be installed. You can install them using pip:

```sh
pip install pandas matplotlib seaborn numpy scikit-learn statsmodels imbalanced-learn
```

## Results
This project leveraged machine learning techniques to predict customer churn at a telecom company. We performed feature selection, balanced our dataset, and tuned our hyperparameters to build two models: Logistic Regression and Random Forest Classifier.

Our business objective was to identify customers at risk of churning, thus our model evaluations were focused on recall. Both models performed well, but our Logistic Regression model demonstrated a higher recall score, making it our preferred model.

The Logistic Regression model was instantiated with the best hyperparameters found during Grid Search and fitted on the resampled training data. This model had an accuracy score of 95.03% with a recall score for the positive class (churn) of 90%.

The Random Forest Classifier model was similarly instantiated and fitted. It achieved an accuracy score of 95.39%, with a recall score for the positive class (churn) of 87%.

Our results indicate that the Logistic Regression model is better suited to our business objective, as it's more effective at identifying customers likely to churn. With this model, the telecom company can take proactive measures, like offering incentives, personalizing communication, or improving services to engage customers and prevent churn.

By employing machine learning techniques, businesses in the telecom industry can enhance customer loyalty and retention, leading to sustained revenue. 

Going forward, this model could be refined with more data and explore the impact of various customer engagment and retention strategies on the churn rate after the individual being flagged as expected to churn. 

Detailed code and analysis are available in the Customer_Churn.ipynb notebook. Please refer to it for a comprehensive walkthrough of the project.

## Future Steps

Add executive report that allows more digestible way of getting key insights.

## Contact
For any queries, please feel free to reach out to me at sergiy12422@gmail.com or connect with me on [LinkedIn](https://www.linkedin.com/in/sergiy-chepiga/).
