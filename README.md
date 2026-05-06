# Practical-Application-2---Used-Car-Dealerships
Berkeley ML-AI Course, Practical Application Week 11, May 6, 2026, by Timothy Vermette

# What Drives Used Car Prices? Case Study for Used Car Dealerships

## Link to Jupyter Notebook on GitHub
https://github.com/t-vermette/Practical-Application-2---Used-Car-Dealerships/blob/main/Practical%20Application%202.ipynb

## Overview
Our objective here is to determine the factors that impact used car prices in order to make business recommendations to clients that own used car dealerships. 


## Methods
- Utilize CRISP-DM Framwork to obtain understanding of used car dealership business, understand and prepare dataset, create models and evaluate.
- One Hot Encoding to convert categorical variables into binary indicators for modeling.
- Utilize Linear Regression, Ridge Regression, K Fold Cross Validation, Lasso.
- Compare RMSE.
- Create plots to visualize key findings.
- Report findings to client.

## Key Findings and Business Recommendations
For the luxury focused dealers interested in supplying exotic and high ticket vehicles, we know that manufacturer is king. Imported brands such as Ferrari will command the highest prices. Keep in mind, the condition of the vehicle should be new, good, or like new, and the lower the odometer reading, the greater the value. Look for high end luxury and exotic cars to have mileage <25k for the highest prices. For cars with 25k- 50k miles, you can expect about a 20% decrease in price. There is a steady trend, that for every 20k miles, there is a decrease of $10k in price, on average.

For dealerships focused on mainstream vehicles, with average clientele, similar rules apply. Vehicle brand is the most significant driver of price, followed by fuel type, age of vehicle, mileage and condition. Depending on your location, if you supply customers in rural and high agriculture infrastructure areas, diesel Rams are trucks that you want in your inventory, as these remain popular, in demand, and maintain high value as used vehicles. For the urban dealerships, you will want to streamline your inventory with electric, gas, and hybrid vehicles. Higher end EV’s such as Teslas remain in demand and will yield higher prices. Again, condition, age, and mileage are critical to the price. Aim for vehicles with fewer than 100k miles, that are less than 10 years old.

If you’re dealing in classic cars, you’ll want to focus on vehicles from the 1950’s and 1960’s. Lower odometer readings for these cars will significantly increase price.

Unless this is your dealership’s area of focus, it would be worthwhile to avoid vehicles with salvage titles, or vehicles in fair condition. These will yield the lowest prices, and stocking these in your inventory can negatively impact reputation. However, there is a space for these in the marketplace. If you plan to deal vehicles that meet these criteria, it would be advisable to design your business around providing affordable cars to clients that are seeking high mileage, salvage titles, or vehicles in lower conditions.
  
## Tools Used
- Jupyter Notebook
- Python
- pandas
- seaborn
- matplotlib
- sklearn
- numpy
