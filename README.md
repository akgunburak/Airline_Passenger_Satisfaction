# Predicting the Satisfaction of Passengers of an Airline Company
&nbsp; In this project, I built a model to predict the satisfaction of passengers of an airline company. I compared the performances of  Logistic Regression, Random Forest, XGBoost and, Multi-Layer Perceptron with K-Fold Cross-Validation. I also investigated whether dimension reduction boosts the performance or does not. In this specific problem, after trying to reduce the dataset to different dimensions using Principal Component Analysis, I concluded that it does not enhance the performance. Among the four algorithms, XGBoost yielded the highest accuracy score. Project is available [**here**](https://akgunburak.github.io/Airline_Passenger_Satisfaction/)

&nbsp;

## Technologies Used
- **Language and version:** Python - 3.8.8
- **Packages:** Pandas, Numpy, Matplotlib, Seaborn, Scikit-Learn, Xgboost

&nbsp;

## Dataset
Dataset was obtained from Kaggle. Original dataset with variables and descriptions can be found from: https://www.kaggle.com/teejmahal20/airline-passenger-satisfaction

&nbsp;

## Steps
**1- Loading the Data**  
**2- Exploratory Data Analysis**  
**3- Splitting Dataset Into Train and Test Sets**  
**4- Preprocessing**  
**5- Comparing the Performances of Algorithms**  
**6- Comparing the Performances of Algorithms After Applying PCA**  
**7- Hyper-parameter Optimization**  
**8- Evaluating the Model Performance on Test Set**

&nbsp;

## Results
* Performances Without PCA
![alt text](https://github.com/akgunburak/Airline_Passenger_Satisfaction/blob/master/without_pca.png)

&nbsp;

* Performances With PCA
![alt text](https://github.com/akgunburak/Airline_Passenger_Satisfaction/blob/master/with_pca.png)
