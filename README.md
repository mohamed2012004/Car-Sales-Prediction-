# Car Sales Prdiction

This project analyzes a dataset containing car sales transactions and predict sales of it. The dataset includes detailed information about customers, cars, and dealerships. The goal is to understand purchasing behavior, regional sales trends, and the influence of various attributes (such as car model, price, and customer demographics) on sales.

## Dataset Metadata

The dataset includes the following columns:

1. **Car_id**: A unique identifier for each car in the dataset.  
   _Example: C001, C002, C003, etc._

2. **Date**: The date when the car was sold or the transaction took place.  
   _Example: 2023-07-15_

3. **Customer Name**: The name of the customer who purchased or inquired about the car.  
   _Example: John Doe, Jane Smith_

4. **Gender**: The gender of the customer, which might be useful for analyzing purchasing trends by gender.  
   _Example: Male, Female_

5. **Annual Income**: The annual income of the customer, which could be used to analyze the purchasing power or predict the likelihood of buying specific car models.  
   _Example: 50000, 80000, 120000_

6. **Dealer_Name**: The name of the car dealership where the transaction occurred.  
   _Example: ABC Motors, XYZ Autos_

7. **Company**: The car manufacturing company (e.g., Toyota, Ford, etc.).  
   _Example: Toyota, Ford, BMW_

8. **Model**: The specific car model purchased or inquired about.  
   _Example: Corolla, Mustang, X5_

9. **Engine**: Details about the car's engine (e.g., engine size, type, etc.), which can be useful for analyzing the type of cars being sold.  
   _Example: 2.0L, 3.5L V6, Electric_

10. **Transmission**: Information about whether the car has an automatic or manual transmission, which is an important feature for many customers.  
   _Example: Automatic, Manual_

11. **Color**: The color of the car, which can sometimes be a deciding factor in the purchasing decision.  
   _Example: Red, Blue, Black_

12. **Price ($)**: The price of the car, which is an important variable for understanding customer purchasing behavior and dealer pricing strategies.  
   _Example: 25000, 30000, 45000_

13. **Dealer_No**: A unique identifier for the car dealership. This could be useful for analyzing sales performance across different dealers.  
   _Example: D001, D002, D003_

14. **Body Style**: The style or type of the car body (e.g., sedan, SUV, coupe). This helps to categorize cars and can be useful for understanding customer preferences.  
   _Example: Sedan, SUV, Coupe_

15. **Phone**: The customer's phone number, which may be useful for follow-up or targeted marketing.  
   _Example: (555) 123-4567_

16. **Dealer_Region**: The geographic region where the dealership is located, which can help in understanding regional sales trends and preferences.  
   _Example: North, South, East, West_

## Goals of the Analysis

- **Customer Demographics**: Analyze purchasing trends based on customer gender and income.
- **Sales Performance by Dealer**: Compare the sales performance across different dealerships.
- **Regional Analysis**: Investigate sales patterns by geographic region.
- **Price Trends**: Identify trends in car prices based on model, company, and body style.
- **Transmission Preferences**: Examine customer preferences for manual versus automatic transmissions.
- **Body Style and Model Preferences**: Understand customer preferences for different body styles and car models.
- **Sales Prediction**: The analysis also attempts to predict car sales, addressing the challenge of overfitting, which was encountered during the project. Various algorithms were tested, although the results were not ideal.

## Analysis

1.**Gender Analysis**

![Screenshot 2024-11-12 061053](https://github.com/user-attachments/assets/decde912-9eb0-4d99-9b4f-f17a18e638a6)


2.**Company and Model Analysis**
![Screenshot 2024-11-12 064043](https://github.com/user-attachments/assets/60d8d779-a657-462b-88cf-71f699d4e980)
![Screenshot 2024-11-12 065319](https://github.com/user-attachments/assets/f7e79112-9fa3-4e1b-befb-05f7c4ac1818)

3.**Time Analysis**
![Screenshot 2024-11-12 074738](https://github.com/user-attachments/assets/72e7e4b1-1b59-44d9-a447-0dd5007e80b0)


## Data Visualizations

The project includes the following types of visualizations:
- **Bar charts**: To show the number of cars sold by region and dealer.
- **Pie charts**: To visualize the distribution of car body styles and customer gender.
- **Line graphs**: To analyze sales trends over time.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/car-sales-analysis.git
