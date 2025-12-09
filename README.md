# FoodHub Order Analytics: 
## Objective: This project analyzes customer orders from FoodHub, an online food delivery app, to uncover patterns in restaurant popularity, cuisine preferences, delivery time, and customer ratings.

## Context
The number of restaurants in New York is increasing day by day. Lots of students and busy professionals rely on those restaurants due to their hectic lifestyles. Online food delivery service is a great option for them. It provides them with good food from their favorite restaurants. A food aggregator company FoodHub offers access to multiple restaurants through a single smartphone app.
The app allows restaurants to receive a direct online order from a customer. The app assigns a delivery person from the company to pick up the order after it is confirmed by the restaurant. The delivery person then uses the map to reach the restaurant and waits for the food package. Once the food package is handed over to the delivery person, he/she confirms the pick-up in the app and travels to the customer's location to deliver the food. The delivery person confirms the drop-off in the app after delivering the food package to the customer. The customer can rate the order in the app. The food aggregator earns money by collecting a fixed margin of the delivery order from the restaurants.

## Data Description
The data includes various information related to a food order. A detailed data dictionary is provided below.

## Data Dictionary
order_id: Unique ID of the order
customer_id: ID of the customer who ordered the food
restaurant_name: Name of the restaurant
cuisine_type: Cuisine ordered by the customer
cost_of_the_order: Cost of the order
day_of_the_week: Indicates whether the order is placed on a weekday or weekend (The weekday is from Monday to Friday and the weekend is Saturday and Sunday)
rating: Rating given by the customer out of 5
food_preparation_time: Time (in minutes) taken by the restaurant to prepare the food. This is calculated by taking the difference between the timestamps of the restaurant's order confirmation and the delivery person's pick-up confirmation.
delivery_time: Time (in minutes) taken by the delivery person to deliver the food package. This is calculated by taking the difference between the timestamps of the delivery person's pick-up confirmation and drop-off information

## Key Highlights
* Cleaned and explored food delivery records
* Visualized trends using Python (Pandas, Seaborn, Matplotlib)
* Created custom plotting functions for easy reuse
* Analyzed food preparation and delivery time distributions
* Identified top cuisines and restaurants
* Suggested ways to enhance delivery and customer experience

## Conclusion
* A majority of orders (70%) are priced at or below $20, suggesting most customers prefer budget-friendly options.
* Only a small portion of customers order frequently, indicating that a large number of users may be one-time buyers.
* Many restaurants (50) have only received one order, suggesting that customer preferences are concentrated on a few popular restaurants.
* American cuisine is the most popular and also the most profitable, generating the highest revenue.
* Most orders are placed on weekends, suggesting peak usage aligns with customer free time.
* Average food preparation time is around 27 minutes, and delivery time is around 24 minutes, indicating relatively efficient service.
* A notable portion of ratings are marked as “Not given,” which may limit insights into customer satisfaction. Filling these gaps or encouraging more ratings could enhance future analysis.
* There is no strong correlation between order cost and restaurant ratings. High-rated restaurants exist across all price ranges, indicating that cost alone doesn’t guarantee a better rating.
* The company generated $6,166.30 in revenue from commission charges, with higher-priced orders contributing more.

## Technical Stack
Programming: Python
Libraries: Pandas (Data manipulation)
Visualization: Matplotlib & Seaborn
Concepts: Exploratory Data Analysis (EDA), Data Cleaning, Data Visualization
