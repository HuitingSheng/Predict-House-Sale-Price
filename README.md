# House Sale Price Prediction

When people are buying or selling a house, the biggest thing they care about is the sales price. Buyers usually have their dream house checklist including: number of bedrooms/bathrooms, house age, kitchen finishes, and the quality of the schools and surronding neighborhood. Sellers want to know what factors impact the sales price the most. An example of this is whether doing a last minute remodel or staging the house correctly can increase the value of their housel
I got my dataset from Kaggle, it has 79 explanatory variables describing (almost) every aspect of residential homes in Ames, Iowa. The goal of this project is to build a model to predict the final house sale price of each home using Python. Additionally I wanted try to find out the features that have the biggest influcene on the final price.

This project is using Python langugage. The package I'm using are pandas, numpy,matplotlib, seaborn, sklearn scipy.stats etc. These package are very powerful when doing anaysis and building models.

There are 1460 instances of training data and 1460 of test data. Total number of attributes equals 81, of which 36 is quantitative, 43 categorical + Id and SalePrice.

Quantitative: 1stFlrSF, 2ndFlrSF, 3SsnPorch, BedroomAbvGr, BsmtFinSF1, BsmtFinSF2, BsmtFullBath, BsmtHalfBath, BsmtUnfSF, EnclosedPorch, Fireplaces, FullBath, GarageArea, GarageCars, GarageYrBlt, GrLivArea, HalfBath, KitchenAbvGr, LotArea, LotFrontage, LowQualFinSF, MSSubClass, MasVnrArea, MiscVal, MoSold, OpenPorchSF, OverallCond, OverallQual, PoolArea, ScreenPorch, TotRmsAbvGrd, TotalBsmtSF, WoodDeckSF, YearBuilt, YearRemodAdd, YrSold

Qualitative: Alley, BldgType, BsmtCond, BsmtExposure, BsmtFinType1, BsmtFinType2, BsmtQual, CentralAir, Condition1, Condition2, Electrical, ExterCond, ExterQual, Exterior1st, Exterior2nd, Fence, FireplaceQu, Foundation, Functional, GarageCond, GarageFinish, GarageQual, GarageType, Heating, HeatingQC, HouseStyle, KitchenQual, LandContour, LandSlope, LotConfig, LotShape, MSZoning, MasVnrType, MiscFeature, Neighborhood, PavedDrive, PoolQC, RoofMatl, RoofStyle, SaleCondition, SaleType, Street, Utilities.

Our target variable is SalePrice. It is numerical, so regression algorithms are proper candidates.
The Overall project will including data cleaning, data preprocessing, building and validating models.

The data description is in the data_descritpion.txt file

Whole Project:

https://huitingsheng.github.io/Predict-House-Sale-Price/House_Sale_Price_Prediction.html


