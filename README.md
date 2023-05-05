# Supermarket Orders Dataset Analysis using K-means Clustering and PCA

This project aims to explore the Supermarket Orders 2023 dataset by applying K-means Clustering and Principal Component Analysis (PCA) techniques. (https://www.kaggle.com/datasets/hunter0007/ecommerce-dataset-for-predictive-marketing-2023)

## Dataset

The dataset can be found [here]. It consists of a single CSV file with 12 columns. The columns represent:

-   order_id – (A unique number to identity the order)
-   user_id - (A unique number to identify the user)
-   order_number – (Number of the order)
-   order_dow – (Day of the Week the order was made)
-   order_hour_of_day – (Time of the order)
-   days_since_prior_order - (History of the order)
-   product_id – (Id of the product)
-   add_to_cart_order – (Number of items added to cart)
-   reordered – (If the reorder took place)
-   department_id - (Unique number allocated to each department)
-   department – (Names of the departments)
-   product_name – (Name of the products)

## Prerequisites

Before running the code, the following Python packages need to be installed:

-   pandas
-   numpy
-   sklearn
-   matplotlib
-   seaborn

You can install them by running the following command:

Copy code

`pip install pandas numpy sklearn matplotlib seaborn` 

## Approach

The project has been divided into two parts:

1.  Data Preprocessing and EDA
2.  Analysis using K-means Clustering and PCA

### Data Preprocessing

The first step in any data analysis project is to preprocess the data. In this project, we have performed the following steps:

1.  Reading the dataset
2.  Removing unnecessary columns
3.  Handling missing values
4.  Handling categorical variables
5.  Scaling the data
6. Answer basic analysis questions

### Analysis using K-means Clustering and PCA

The second part of the project involves applying K-means Clustering and PCA techniques to the preprocessed data. The goal is to identify patterns in the data that can help in better understanding the customers' behavior.

1.  **K-means Clustering:** K-means clustering is a popular unsupervised machine learning technique used for clustering similar data points.
    
2.  **Principal Component Analysis (PCA):** PCA is a statistical technique used to reduce the dimensionality of the data. In this project, we will use PCA to identify the most important features that contribute to the customers' behavior. We will then visualize the data using these features to better understand the relationships between the different variables.
    

## Results

The results of the analysis are presented in the Jupyter notebook that can be found [here](https://www.kaggle.com/markstent/supermarket-data-eda-kmeans/edit). The notebook includes the following:

1.  Data preprocessing steps
2.  K-means clustering analysis
3.  PCA analysis
4.  Visualization of results using plots

![KMeans PCA Pairplot](https://github.com/markstent/supermarket_clustering_PCA/blob/main/customer_pca.png)

## Conclusion

In this project, we explored the Supermarket Orders 2023 dataset using K-means clustering and PCA techniques. We identified patterns in the data that can help in better understanding the customers' behavior. The results of the analysis can be used to develop marketing strategies that target specific customer segments.
