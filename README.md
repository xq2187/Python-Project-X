<div align="center">
  <img src="https://www.longfordleader.ie/resizer/750/563/true/1475831179315.jpg--longford.jpg?1475831180000"><br><br>
</div>

# Python-Project-X (section 2)
Tools for Analytics Project (section 2)
# Predicting the Airbnb House Price

Our project is making a reasonable and sensible prediction for Airbnb houses price. In general, there are many features of a property that may affect its price. We are interested in how these features affect the pricing on the Airbnb property. The origin dataset we obtained on the Internet include information on number of people it can accommodate, number of bedrooms and bathrooms, etc. We first analyze the data by doing data preprocessing, where we categorize the data and deal with missing values. Then we conduct statistical analysis on the data and plot corresponding plots and curves. After that, we split our original dataset into test (80%) and train (20%). Finally we use machine learning models including LightGBM, CatBoost, RandomForest and XGBoost to regress and predict the test dataset’s house price and compare the MSE of these models. 


## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisites

What things you need to install the software and how to install them

```
Give examples
```

### Installation Instructions

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

End with an example of getting some data out of the system or using it for a little demo


## Run Instructions
1. Download data.csv and Project_FinalVersion.ipynb.

2. Change path variable to the absolute path of data.csv file.

3. Run Project_FinalVersion.ipynb file and get the anticipated result.


## Authors

Yashi Huang (yh3068) # data preprocessing part, commitment shown as "hys19960"

Yuhui Gao (yg2606) # RandomForest and XGBoost part,commitment shown as "GMundell2"

Xuchen Qiu (xq2187) # LightGBM and CatBoost part, commitment shown as "Your Name" and "xq2187" 

Yusang Liu (yl3600) # statistical analysis and plotting part, commitment shown as "lys7901"

