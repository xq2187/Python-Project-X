<div align="center">
  <img src="https://www.longfordleader.ie/resizer/750/563/true/1475831179315.jpg--longford.jpg?1475831180000"><br><br>
</div>

## Python-Project-X (section 2)

Tools for Analytics Project (section 2)


## Predicting the Airbnb House Price

Our project is to make a reasonable and sensitive prediction for Airbnb houses price. In general, there are many features of a property that may affect its price. We are interested in how these features affect the price of the Airbnb property. The original dataset we obtained on the Internet includes information of number of people it can accommodate, number of bedrooms and bathrooms, etc. We first analyze the data by doing data preprocessing, where we categorize the data and deal with missing values. Then we conduct statistical analysis on the data and draw corresponding plots and curves. After that, we split our original dataset into train set(80%) and test set(20%). Finally we use machine learning algorithms including LightGBM, CatBoost, RandomForest and XGBoost to fit the model and predict the test dataset’s house price and compare the mean absolute error and mean squared error of these models. 


## Installation Instructions

Environment: Python 3.6

To install the Scikit-learn library:

```
!pip install sklearn
```

To install the LightGBM library:

```
!pip install lightgbm
```

To install the CatBoost library:

```
!pip install catboost
```

To install the XGBoost library:
```
!pip install xgboost
```


## Run Instructions

1. Clone this repository: 'git@github.com:xq2187/Python-Project-X.git'.

2. pip install necessary libraries.

3. Assign path variable with the absolute path of data.csv that downloaded in your computer.

4. Open Project_FinalVersion.ipynb file and follow the instructions inside to get the anticipated result.


## Authors

Yashi Huang (yh3068) # data preprocessing part, commitment shown as "hys19960"

Yuhui Gao (yg2606) # RandomForest and XGBoost part,commitment shown as "GMundell2"

Xuchen Qiu (xq2187) # LightGBM and CatBoost part, commitment shown as "Your Name" and "xq2187" 

Yusang Liu (yl3600) # statistical analysis and plotting part, commitment shown as "lys7901"

