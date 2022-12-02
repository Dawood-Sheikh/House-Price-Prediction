# Introduction:

The housing market reflects the economy, and housing price ranges are of great interest to buyers and sellers. The purpose of this project is to predict house prices 
using explanatory variables covering many aspects of residential housing. This project aims to build a regression model that will estimate the house price accurately 
based on its features.

For that we've to form a regression model that's able to accurately estimate the value of the house given the options and to reduce the distinction between expected 
and actual rating (RMSE). Almost all aspects of residential homes in Ames, Iowa, USA areexplained by 79 variables (features).

## User Requirements
* Hardware requirements:
  1. Operating system- Windows 7,8,10
  2. Processor- Dual core 2.4 GHz (i5 or i7 series Intel processor or equivalent AMD)
  3. RAM - 4GB
* Software Requirements:
  1. Python 3.8
  2. PyCharm
  3. PIP
  4. Jupyter Notebook
  5. Anaconda
  6. Chrome
  7. Cloud Environment to Deploy Model

## Unresolved Issues:

Due to lack of technical requirements we will be assuming the ideal parameters of the XGBoost
Regressor.

## Analysis of Work Done and Design
### Goals:
* To develop an efficient and effective model which predict the sale price for each
house.
* To achieve good accuracy by minimizing the difference between predicted and actual
rating (RMSE/MSE)

## Data & Attributes:
We have used a data set uploaded by Dean De Cock on Kaggle for a competition. You can download the data set from this link https://www.kaggle.com/competitions/house-prices-advanced-regression-techniques/data
It consists of four files, namely as:

* data_desription.txt
* sample_submission.csv
* test.csv
* train.csv

The dataset contains **2919 records (rows)** and **80 features (columns) (including ‘SalePrice’ column of the train dataset)**. **data_description.txt** consists of 
the information about all the features listed in the train and test csv files. These features are:

FEATURE | DESCRIPTION
--------|-------------
MSSubClass | The type of the house involved in the sale of the property
MSZoning | The general zoning classification of the sale of the property
LotFrontage | Linear feet ofstreet connected to the house
LotArea | Lot size in square feet
Street | Type of road access to the house
Alley | Type of alley access to the house
LotShape | General shape of the house
LandContour | House flatness
Utilities | Type of utilities available
LotConfig | Lot configuration
LandSlope | House Slope
Neighborhood | Locations within Ames city limits
Condition1 | Proximity to various conditions
Condition2 | Proximity to various conditions (if there is more than one)
BldgType | House type
HouseStyle | House style
OverallQual | Overall quality of material and finish of the house
OverallCond | Overall condition of the house
YearBuilt | Construction year
YearRemodAdd | Remodel year (if no remodeling nor addition, same as YearBuilt)
RoofStyle | Roof type
RoofMatl | Roof material
Exterior1st | Exterior covering on house
Exterior2nd | Exterior covering on house (if there is more than one material)
MasVnrType | Type of masonry veneer
MasVnrArea | Masonry veneer area in square feet
ExterQual | Quality of the material on the exterior
ExterCond | Condition of the material on the exterior
Foundation | Foundation type
BsmtQual | Basement height
BsmtCond | Basement Condition
BsmtExposure | Refers to walkout or garden level walls of the property
BsmtFinType1 | Rating of basement finished area
BsmtFinSF1 | Type 1 finished square feet
BsmtFinType2 | Rating of basement finished area (if there are multiple types)
BsmtFinSF2 | Type 2 finished square feet
BsmtUnfSF | Unfinished basement area in square feet
TotalBsmtSF | Total basement area in square feet
Heating | Heating type
HeatingQC | Heating quality and condition
CentralAir | Central air conditioning
Electrical | Electrical system type
1stFlrSF | First floor area in square feet
2ndFlrSF | Second floor area in square feet
LowQualFinSF | Low quality finished square feet in all floors
GrLivArea | Above-ground living area in square feet
BsmtFullBath | Basement full bathrooms
BsmtHalfBath | Basement half bathrooms
FullBath | Full bathrooms above ground
HalfBath | Half bathrooms above ground
Bedroom | Bedrooms above ground
Kitchen | Kitchens above ground
KitchenQual | Kitchen quality
TotRmsAbvGrd | Total rooms above ground (excluding bathrooms)
Functional | Home functionality
Fireplaces | Number of fireplaces
FireplaceQu | Fireplace quality
GarageType | Garage location
GarageYrBlt | Year garage was built in
GarageFinish | Interior finish of the garage
GarageCars | Size of garage (in car capacity)
GarageArea | Garage size in square feet
GarageQual | Garage quality
GarageCond | Garage condition
PavedDrive | How driveway is paved
WoodDeckSF | Wood deck area in square feet
OpenPorchSF | Open porch area in square feet
EnclosedPorch | Enclosed porch area in square feet
3SsnPorch | Three season porch construction space in sq. feet
ScreenPorch | Screen porch area in square feet
PoolArea | Pool area in square feet
PoolQC | Pool quality
Fence | Fence quality
MiscFeature | Miscellaneous feature
MiscVal | Value of miscellaneous feature
MoSold | Sale month
YrSold | Sale year
SaleType | Sale type
SaleCondition | Sale condition

# Code is uploaded and accessible for knowledge purpose!

# Conclusions:
With the increase in the demand for the houses and lack of proper evaluation of the prices of those housed, the demand for automated prediction models is increased. 
The House Price Prediction system which effectively determines the worthiness of the house using a variety of features is useful not only for real-estate companies
but also for individual buyers who are on the lookout for their dream home. The proposed system will help to determine the near-accurate price of the houses.

# Bibliography:
* Kaggle - https://www.kaggle.com/
* Google - https://www.google.com/
* Matplotlib - https://matplotlib.org/
* Seaborn - https://seaborn.pydata.org/
* Scikit-learn - https://scikit-learn.org/stable/
* Analytics Vidya - https://www.analyticsvidhya.com/blog/2020/12/improve-predictive-model-scorestacking-regressor/
