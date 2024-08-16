# Complete-EDA-FE-on-House-Prices-Dataset
In this repository I performed complete Exploratory Data Analysis, Feature Engineering and Feature Selection on House Price Prediction Dataset which is publically available on kaggle: https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data

## Dataset Description
### File descriptions
train.csv - the training set <br/>
test.csv - the test set
### Data Fields
These are the features and its descriptions present in the dataset<br/>

SalePrice - the property's sale price in dollars. This is the target variable that you're trying to predict.<br/>
MSSubClass: The building class<br/>
MSZoning: The general zoning classification<br/>
LotFrontage: Linear feet of street connected to property<br/>
LotArea: Lot size in square feet<br/>
Street: Type of road access<br/>
Alley: Type of alley access<br/>
LotShape: General shape of property<br/>
LandContour: Flatness of the property<br/>
Utilities: Type of utilities available<br/>
LotConfig: Lot configuration<br/>
LandSlope: Slope of property<br/>
Neighborhood: Physical locations within Ames city limits<br/>
Condition1: Proximity to main road or railroad<br/>
Condition2: Proximity to main road or railroad (if a second is present)<br/>
BldgType: Type of dwelling<br/>
HouseStyle: Style of dwelling<br/>
OverallQual: Overall material and finish quality<br/>
OverallCond: Overall condition rating<br/>
YearBuilt: Original construction date<br/>
YearRemodAdd: Remodel date<br/>
RoofStyle: Type of roof<br/>
RoofMatl: Roof material<br/>
Exterior1st: Exterior covering on house<br/>
Exterior2nd: Exterior covering on house (if more than one material)<br/>
MasVnrType: Masonry veneer type<br/>
MasVnrArea: Masonry veneer area in square feet<br/>
ExterQual: Exterior material quality<br/>
ExterCond: Present condition of the material on the exterior<br/>
Foundation: Type of foundation<br/>
BsmtQual: Height of the basement<br/>
BsmtCond: General condition of the basement<br/>
BsmtExposure: Walkout or garden level basement walls<br/>
BsmtFinType1: Quality of basement finished area<br/>
BsmtFinSF1: Type 1 finished square feet<br/>
BsmtFinType2: Quality of second finished area (if present)<br/>
BsmtFinSF2: Type 2 finished square feet<br/>
BsmtUnfSF: Unfinished square feet of basement area<br/>
TotalBsmtSF: Total square feet of basement area<br/>
Heating: Type of heating<br/>
HeatingQC: Heating quality and condition<br/>
CentralAir: Central air conditioning<br/>
Electrical: Electrical system<br/>
1stFlrSF: First Floor square feet<br/>
2ndFlrSF: Second floor square feet<br/>
LowQualFinSF: Low quality finished square feet (all floors)<br/>
GrLivArea: Above grade (ground) living area square feet<br/>
BsmtFullBath: Basement full bathrooms<br/>
BsmtHalfBath: Basement half bathrooms<br/>
FullBath: Full bathrooms above grade<br/>
HalfBath: Half baths above grade<br/>
Bedroom: Number of bedrooms above basement level<br/>
Kitchen: Number of kitchens<br/>
KitchenQual: Kitchen quality<br/>
TotRmsAbvGrd: Total rooms above grade (does not include bathrooms)<br/>
Functional: Home functionality rating<br/>
Fireplaces: Number of fireplaces<br/>
FireplaceQu: Fireplace quality<br/>
GarageType: Garage location<br/>
GarageYrBlt: Year garage was built<br/>
GarageFinish: Interior finish of the garage<br/>
GarageCars: Size of garage in car capacity<br/>
GarageArea: Size of garage in square feet<br/>
GarageQual: Garage quality<br/>
GarageCond: Garage condition<br/>
PavedDrive: Paved driveway<br/>
WoodDeckSF: Wood deck area in square feet<br/>
OpenPorchSF: Open porch area in square feet<br/>
EnclosedPorch: Enclosed porch area in square feet<br/>
3SsnPorch: Three season porch area in square feet<br/>
ScreenPorch: Screen porch area in square feet<br/>
PoolArea: Pool area in square feet<br/>
PoolQC: Pool quality<br/>
Fence: Fence quality<br/>
MiscFeature: Miscellaneous feature not covered in other categories<br/>
MiscVal: $Value of miscellaneous feature<br/>
MoSold: Month Sold<br/>
YrSold: Year Sold<br/>
SaleType: Type of sale<br/>
SaleCondition: Condition of sale<br/>

## Steps I Followed:<br/>
-- Performing Exploratory Data Analysis on the train dataset(train.csv) to get meaningful insights of the data <br/>
-- Performing Feature Engineering on both datasets(train.csv and test.csv) to handle features of dataset and normalizing the numerical variables and encoding categorical variables. <br/>
-- Performing Feature selection using Lasso and SelectfromModel and selecting 21 most important features that are most important to predict the dependent variable <br/>
-- Saving the final datframes in the .csv files in same folder(X_train.csv and X_test.csv) <br/>

### By performing these steps I got a final dataset which we can use for model training
