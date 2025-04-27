![Banner](https://github.com/thetechleila/Housing-Prices-Predictor/blob/main/images/Housing%20Prices%20Predictor_Banner.png)

# Housing Prices Predictor 

___

## **Project Overview**

This project contains the process of creating machine learning models that use advanced regression techniques to predict the costs of individual homes in Ames, Iowa (USA) through the transformation of 79 features available in the [Ames Housing Dataset](https://www.kaggle.com/datasets/shashanknecrothapa/ames-housing-dataset).

The project will be broken down into 4 phases, each housed in its own Jupyter notebook:


### *Phase 1:* Exploratory Data Analysis (EDA)

Implementation of univariate, bivariate, and multivariate exploratory analyses and creation of relevant visualizations/graphs that inspect possible relationships between the several predictor features.


### *Phase 2:* Data Transformation 
### *(Data Cleaning, Data Wrangling/Pre-Processing)* 

Techniques utilized include, but are not limited to:

* Removing features with strong colinearity
* Dropping null values
* Removing unnecessary columns
* Potentially fixing incorrectly formatted data
* Removing outliers


### *Phase 3:* Data Model Creation, Hyper-parameter Search, and Model Evaluation
* Create train-test-splits
* Implement a classifier(s) such as Random Forest or Gradient Boosting
* Hyper-parameter tuning via Randomized Search
* Re-training of models after hyper-parameter tuning
* Determination of accuracy scores and selection of model with the best performance


###  *Phase 4:* Predictions

Application of the trained machine learning algorithm(s) on the pre-existing test housing data set to caluclate the costs of each home.
___

## **Tools**

* Python
* TensorFlow
* Jupyter Notebooks
* NumPy for mathematical & statistical operations
* Pandas for data manipulation
* Matplotlib & Seaborn for data visualization
* Scikit-learn for machine learning and data processing
* Statsmodels for statistical data exploration

___

## **Data Overview**

___
### *Numeric Features*

	**SalePrice:** The property's sale price in dollars. This is the target variable that this project aims to predict.

* **MSSubClass**: The building class
* **LotFrontage**: Linear feet of street connected to property
* **LotArea**: Lot size in square feet
* **Street**: Type of road access
* **OverallQual**: Overall material and finish quality
* **OverallCond**: Overall condition rating
* **YearBuilt**: Original construction date
* **YearRemodAdd**: Remodel date
* **MasVnrArea**: Masonry veneer area in square feet
* **BsmtFinSF1**: Type 1 finished square feet
* **BsmtFinSF2**: Type 2 finished square feet
* **BsmtUnfSF**: Unfinished square feet of basement area
* **TotalBsmtSF**: Total square feet of basement area
* **1stFlrSF**: First Floor square feet
* **2ndFlrSF**: Second floor square feet
* **LowQualFinSF**: Low quality finished square feet (all floors)
* **GrLivArea**: Above grade (ground) living area square feet
* **BsmtFullBath**: Basement full bathrooms
* **BsmtHalfBath**: Basement half bathrooms
* **FullBath**: Full bathrooms above grade
* **HalfBath**: Half baths above grade
* **Bedroom**: Number of bedrooms above basement level
* **Kitchen**: Number of kitchens
* **TotRmsAbvGrd**: Total rooms above grade (does not include bathrooms)
* **Fireplaces**: Number of fireplaces
* **GarageYrBlt**: Year garage was built
* **GarageFinish**: Interior finish of the garage
* **GarageCars**: Size of garage in car capacity
* **GarageArea**: Size of garage in square feet
* **WoodDeckSF**: Wood deck area in square feet
* **OpenPorchSF**: Open porch area in square feet
* **EnclosedPorch**: Enclosed porch area in square feet
* **3SsnPorch**: Three season porch area in square feet
* **ScreenPorch**: Screen porch area in square feet
* **PoolArea**: Pool area in square feet
* **MiscVal**: Value of miscellaneous feature
* **MoSold**: Month Sold
* **YrSold**: Year Sold


### *Categorical Features*

* **MSZoning**: The general zoning classification
* **Alley**: Type of alley access
* **LotShape**: General shape of property
* **LandContour**: Flatness of the property
* **Utilities**: Type of utilities available
* **LotConfig**: Lot configuration
* **LandSlope**: Slope of property
* **Neighborhood**: Physical locations within Ames city limits
* **Condition1**: Proximity to main road or railroad
* **Condition2**: Proximity to main road or railroad (if a second is present)
* **BldgType**: Type of dwelling
* **HouseStyle**: Style of dwelling
* **RoofStyle**: Type of roof
* **RoofMatl**: Roof material
* **Exterior1st**: Exterior covering on house
* **Exterior2nd**: Exterior covering on house (if more than one material)
* **MasVnrType**: Masonry veneer type
* **ExterQual**: Exterior material quality
* **ExterCond**: Present condition of the material on the exterior
* **Foundation**: Type of foundation
* **BsmtQual**: Height of the basement
* **BsmtCond**: General condition of the basement
* **BsmtExposure**: Walkout or garden level basement walls
* **BsmtFinType1**: Quality of basement finished area
* **BsmtFinType2**: Quality of second finished area (if present)
* **Heating**: Type of heating
* **HeatingQC**: Heating quality and condition
* **CentralAir**: Central air conditioning
* **Electrical**: Electrical system
* **KitchenQual**: Kitchen quality
* **FireplaceQu**: Fireplace quality
* **Functional**: Home functionality rating
* **GarageType**: Garage location
* **GarageQual**: Garage quality
* **GarageCond**: Garage condition
* **PavedDrive**: Paved driveway
* **PoolQC**: Pool quality
* **Fence**: Fence quality
* **MiscFeature**: Miscellaneous feature not covered in other categories
* **SaleType**: Type of sale
* **SaleCondition**: Condition of sale