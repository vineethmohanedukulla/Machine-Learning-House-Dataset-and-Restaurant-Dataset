# ICP-6

#### Complete the following:
```
Name: Edukulla Vineeth Mohan
Email: vekfd@umsystem.edu
```
---
```
Partner Name: Mahesh Badrapu
Partner Email:mbfb6@umsystem.edu
Partner ICP-Link: https://github.com/UMKC-APL-PythonDeepLearing/icp-6-Maheswarrao1
```
### SUBMIT PYTHON NOTEBOOK FILE (ipynb file)

```
Video Link:  https://github.com/UMKC-APL-PythonDeepLearing/icp-6-vekfd/raw/master/Video%20Explanation/video%20explanation.mp4
```
<br/>
 
Write brief explanation here:
##  In this lesson we will review regression techniques
Regression techniques
a. Linear Regression
b. Multiple Regression
c. Clustering
d. PCA

### **Question 1**
Regression Assignment:
1. For question 1 use the same dataset used in the source code (House Prices).
    Delete all the outlier data for the GarageArea field (for the same data set in the use case: House Prices).
    for this task you need to plot GaurageArea field and SalePrice in scatter plot, then check which numbers are anomalies.
2. Evaluate the model using MAE, MSE, RMSE and R2 score.
3. Using simple regression select one feature that is   positively correlated with ‘SalePrice’ create a regression model and Plot the regression line between the two features.
4. For questions 2 and 3 use the Restaurant Revenue Prediction dataset “rest_data.csv” described here: https://www.kaggle.com/c/restaurant-revenue-prediction/data o Id : 

5. Restaurant id. o City Group: Type of the city. Big cities, or Other. o Type: Type of the restaurant. FC: Food Court, IL: Inline, DT: Drive Thru, MB: Mobile o P1, P2 - P37: There are three categories of these obfuscated data. Demographic data are gathered from third party providers with GIS systems. These include population in any given area, age and gender distribution, development scales. 

6. Real estate data mainly relate to the m2 of the location, front facade of the location, car park availability. 

7. Commercial data mainly include the existence of points of interest including schools, banks, other QSR operators. o Revenue: The revenue column indicates a (transformed) revenue of the restaurant and is the target of predictive analysis. Please note that the values are transformed so they don't mean real dollar values.
2. Create Multiple Regression for the “Restaurant Revenue Prediction” dataset.
(bonus) 3. Find top 5 most correlated features to the target label(revenue) and then build a model on top of those 5 features. Evaluate the model using MAE, MSE, RMSE and R2 score and then compare the result with the RMSE and R2 you achieved in question 2. 
### **Question 2**    
K-means & PCA Assignment:
1. Apply K means clustering to credit card dataset: CC.csv
• Remove any null values by the mean.
• Use the elbow method to find a good number of clusters with the K-Means algorithm
• Calculate the silhouette score for the above clustering.
2. Try feature scaling and then apply K-Means on the scaled features. Did that improve the Silhouette score?
*** Bonus points
2. Visualize the clustering of first question.
3. Apply PCA on the same dataset. Apply K-Means algorithm on the PCA result and report your observation if the silhouette score improved or not?


## Softwares Required :
1. Python 3
2. Github Desktop
3. pycharm

## Implementation:
1. Assignment was provided with steps for titanic dataset.
2. We need to run the preprocessing_EDA file to preprocess the data before sending it to the model for input
3. preprocessing_EDA provides test_preprocessed and train_preprocessed as ouput and this is used for training and testing the model.
4. Glass dataset requires no preprocessing, hence we split the data into training and testing data and send it to the model.


## Tasks Performed
### **Question 1: Code Development**

# 
Step 1: We need to run preprocessing_EDA(Question1).ipynb to get the preprocessed data.

Step 2: test_preprocessed and train_preprocessed are in the git folder

Step 3: Run the Naive(Question1).ipynb file to train and test the model.

Comments, Inferences, results are written with full explanations within jupyter notebook.

Below are the outputs:

![Outpu2](https://user-images.githubusercontent.com/78897209/136877488-24c077a7-72ef-49ff-8bd7-c3aa633ede90.png)
![Output3](https://user-images.githubusercontent.com/78897209/136877493-a1844653-ac59-466f-9b12-24a111147b96.png)
![Output4](https://user-images.githubusercontent.com/78897209/136877495-12754c71-15ff-41e5-953f-ba4345ad9a27.png)
![Output5](https://user-images.githubusercontent.com/78897209/136877496-42e32183-04ca-4a8b-a734-4286de32aefa.png)
![Output6](https://user-images.githubusercontent.com/78897209/136877497-0230cfa9-ee54-4834-a28f-6c04dbd33f73.png)
![Output7](https://user-images.githubusercontent.com/78897209/136877499-f5ff4e57-6be5-48b7-9568-fded69122f48.png)
![Output8](https://user-images.githubusercontent.com/78897209/136877500-0e664755-1f28-4676-84b6-55bb4fc453fa.png)





### **Question 2: Code Development**


Below are the outputs:
![Output9](https://user-images.githubusercontent.com/78897209/136877501-3b834873-7760-4508-81c5-48ca7fbb0490.png)
![Output10](https://user-images.githubusercontent.com/78897209/136877503-7131e431-b778-4f5d-a74f-58497254a068.png)
![Output11](https://user-images.githubusercontent.com/78897209/136877504-1f714d39-0353-463e-aa45-c421cce9baba.png)
![Output12](https://user-images.githubusercontent.com/78897209/136877505-dd88f95c-791e-4800-ae8a-37b78fc1859f.png)





**Note:** 
Before executing the python notebook, keep the code and the python dataset in same folder.

Explanation Video:

https://github.com/UMKC-APL-PythonDeepLearing/icp-6-vekfd/raw/master/Video%20Explanation/video%20explanation.mp4
