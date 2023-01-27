# CarPricePredictor

The goal of this project is to create a model and present the data in a way that allows us to predict the expected value of a given vehicle based on the dataset.

## Languages and Libraries:

1. Python
2. Scikit_learn
3. Keras
4. Tensor Flow
5. 
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

US Cars' data was scraped from AUCTION EXPORT.com. This dataset included information about 28 brands of clean and used vehicles for sale in the US. Twelve features were assembled for each car in the dataset.


## Task Analysis
This is a supervised task and the dataset we chose is labeled. Additionally, since we are required to predict a value, it is also a regression task. Further, because we used various factors such as year, model, and brand to predict a singular value (price), it is a multiple regression problem as well as a univariate regression problem. A plain batch learning is required as the dataset is not online and is not continuous.
After extensive research and testing different models, we discovered that Linear Regression was the perfect model for our specific data.


Below is an example of the actual price of a vehicle vs the estimated price of the vehicle in Dollar.

<img width="326" alt="Screenshot 2023-01-27 at 3 16 52 PM" src="https://user-images.githubusercontent.com/122697805/215190184-c7879bd8-cb54-469f-8a0a-081e46f19434.png">
