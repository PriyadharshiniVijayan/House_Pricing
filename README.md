# House Pricing
>  Building a regression model to predict the actual value of the prospective properties and decide whether to invest in them or not.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)


## General Information
-  Surprise Housing has decided to enter the Australian market
- Planning to purchase houses at a lower price and flip them on at a higher price
- The company wants to know:
    - Which variables are significant in predicting the price of a house, and
    - How well those variables describe the price of a house.


## Conclusions
- Assumptions derived from the model
    - Best variables to define Sale price of a property are **['LotArea', 'Street', 'OverallQual',
       'OverallCond', 'MasVnrArea', 'ExterQual', 'BsmtQual',
       'BsmtExposure', '2ndFlrSF', 'GrLivArea', 'BsmtFullBath',
       'FullBath', 'KitchenQual',
       'TotRmsAbvGrd', 'Functional', 'GarageCars', 'GarageQual', '3SsnPorch',
       'ScreenPorch', 'Neighborhood_Crawfor',
       'Neighborhood_NoRidge', 'Neighborhood_NridgHt', 'Neighborhood_StoneBr',
       'Neighborhood_Veenker', 'BldgType_Townhouse',
       'HouseStyle_1Story', 'GarageType_NoGarage']**
    - SalePrice increases with increase in squarefeet(GrlivArea)
    - Good or Best quality fetches great SalePrice.Increased value in OverallQual, BsmtQual,KitchenQual,GarageQual would have a good SalePrice
    - Property around  Neighbourhood like NoRidge, NridgHt, StoneBr has good SalePrice
    - Houses having many number of rooms have high demand.
    - Properties with amenities like LotArea, Garage, Fireplace has higher price
    -  BsmtFinSF1,TotalBsmtSF,1stFlrSF,2ndFlrSF,GrLivArea has a linear relation with SalePrice(target variable)
    - Houses with full bath has higher SalePrice
    - Quality and Condition of the prpoerty plays important role in SalePrice


## Technologies Used
- numpy - 1.24.3
- python - 3.11.4
- seaborn - 0.13.0
- pandas - 1.5.3
- plotly - 5.17.0
- matplotlib - 3.7.1


## Acknowledgements
- This project was based on "Surprise Housing by upgrad"


## Contact
Created by [@PriyadharshiniVijayan] - feel free to contact me!

