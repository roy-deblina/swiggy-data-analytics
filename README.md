# swiggy-data-analytics

# Restaurant Data Analysis Project

## Introduction

This case study project revolves around analyzing a Swiggy dataset containing information about various restaurants. The dataset includes columns such as `restaurant_no`, `restaurant_name`, `city`, `address`, `rating`, `cost_per_person`, `cuisine`, `restaurant_link`, `menu_category`, `item`, `price`, and `veg_or_nonveg`. Each column provides valuable insights into different aspects of the restaurant industry, from location and menu offerings to pricing and customer ratings.

## Column Description

- `restaurant_no` (INTEGER, NOT NULL): A unique identifier for each restaurant.
- `restaurant_name` (VARCHAR(50), NOT NULL): Name of the restaurant.
- `city` (VARCHAR(9), NOT NULL): City where the restaurant is located.
- `address` (VARCHAR(204)): Address of the restaurant.
- `rating` (NUMERIC(3,1), NOT NULL): Rating of the restaurant.
- `cost_per_person` (INTEGER): Approximate cost per person for dining.
- `cuisine` (VARCHAR(49), NOT NULL): Type of cuisine offered.
- `restaurant_link` (VARCHAR(136), NOT NULL): Link to the restaurant's online profile.
- `menu_category` (VARCHAR(66)): Category of items in the menu.
- `item` (VARCHAR(188)): Name or description of a menu item.
- `price` (VARCHAR(12), NOT NULL): Price of a menu item or range of prices.
- `veg_or_nonveg` (VARCHAR(7)): Indicates if a menu item is vegetarian or non-vegetarian.

## Key Performance Indicators (KPIs)

1. Rating Distribution: Analyzing customer satisfaction across restaurants.
2. Cuisine Diversity: Identifying popular and niche food preferences.
3. Price Range Analysis: Determining affordability and luxury offerings.
4. Vegetarian vs. Non-Vegetarian Options: Assessing dietary preferences.
5. City-wise Analysis: Uncovering trends and preferences in different regions.

## Questions And Insights Generated Based on the Data

- HOW MANY RESTAURANTS HAVE A RATING GREATER THAN 4.5?
- WHICH IS THE TOP 1 CITY WITH THE HIGHEST NUMBER OF RESTAURANTS?
- HOW MANY RESTAURANTS SELL( HAVE WORD "PIZZA" IN THEIR NAME)?
- WHAT IS THE MOST COMMON CUISINE AMONG THE RESTAURANTS IN THE DATASET?
- WHAT IS THE AVERAGE RATING OF RESTAURANTS IN EACH CITY?
- WHAT IS THE HIGHEST PRICE OF ITEM UNDER THE 'RECOMMENDED' MENU CATEGORY FOR EACH RESTAURANT?
- FIND THE TOP 5 MOST EXPENSIVE RESTAURANTS THAT OFFER CUISINE OTHER THAN INDIAN CUISINE. 
- FIND THE RESTAURANTS THAT HAVE AN AVERAGE COST WHICH IS HIGHER THAN THE TOTAL AVERAGE COST OF ALL    
   RESTAURANTS TOGETHER.
- RETRIEVE THE DETAILS OF RESTAURANTS THAT HAVE THE SAME NAME BUT ARE LOCATED IN DIFFERENT CITIES.
- WHICH RESTAURANT OFFERS THE MOST NUMBER OF ITEMS IN THE 'MAIN COURSE' CATEGORY?
- LIST THE NAMES OF RESTAURANTS THAT ARE 100% VEGEATARIAN IN ALPHABETICAL ORDER OF RESTAURANT NAME
- WHICH IS THE RESTAURANT PROVIDING THE LOWEST AVERAGE PRICE FOR ALL ITEMS?
- WHICH TOP 5 RESTAURANT OFFERS HIGHEST NUMBER OF CATEGORIES?
- WHICH RESTAURANT PROVIDES THE HIGHEST PERCENTAGE OF NON-VEGEATARIAN FOOD?
- Determine the Most Expensive and Least Expensive Cities for Dining:
- Calculate the Rating Rank for Each Restaurant Within Its City
- What is the distribution of ratings across restaurants?
- Which cuisines are most popular among customers?
- What is the average cost per person for dining?
- How does the price range vary for different menu categories?
- What proportion of menu items are vegetarian vs. non-vegetarian?
- Are there any trends in customer preferences based on city locations?

## Conclusion

-The analysis of restaurant data has provided valuable insights into customer satisfaction and market trends. High ratings across establishments indicate a strong level of satisfaction, particularly in popular dishes like pizza, which can inform targeted marketing strategies and menu optimizations.

-Understanding city-wise preferences allows for tailored approaches in different regions, while the diversity in cuisines and pricing strategies presents opportunities to attract a wide range of customers.

-This data-driven approach serves as a roadmap for restaurant owners and managers, guiding strategic decisions to enhance customer experiences, improve profitability, and foster sustainable growth in a competitive industry landscape.
