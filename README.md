# CarPricePredictor

## Our goal is to create models and present the data in a way that allows us to predict the expected value of a given vehicle based on the dataset.
# Languages and Libraries:
## Python
## Scikit-Learn
## Tensor Flow 
## Keras

## US Cars' data was scraped from AUCTION EXPORT.com. This dataset included information about 28 brands of clean and used vehicles for sale in the US. Twelve features were assembled for each car in the dataset.


Attributes
1. Price - The sale price of the vehicle in the ad
2. Years - The vehicle’s registration year
3. Brand - The car brand
4. Model - The model of the vehicle
5. Color - The color of the car
6. State - The location where the car is available for purchase
7. Mileage - Miles traveled by the vehicle
8. VIN- Vehicle Identification Number (17 characters of digits and capital letters)
9. Title Status - Clean Title Vehicles or Salvage Insurance vehicles
10. Lot - Identification number assigned to a particular quantity or lot of material from a
single manufacturer.For cars, a lot number is combined with a serial number to form the
Vehicle Identification Number
11. Condition - time
12. Country - Country where the car is available for purchase



# Task Analysis
This is a supervised task and the dataset we chose is labeled. Additionally, since we are required to predict a value, it is also a regression task. Further, because we used various factors such as year, model, and brand to predict a singular value (price), it is a multiple regression problem as well as a univariate regression problem. A plain batch learning is required as the dataset is not online and is not continuous.
After extensive research and testing different models, we discovered that Linear Regression was the perfect model for our specific data.
