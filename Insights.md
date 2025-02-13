## The swiggy dataset consists of following columns: 
* ID – A unique identifier for each restaurant.
* Area – The specific locality or neighborhood where the restaurant is located.
* City – The city where the restaurant operates.
* Restaurant – The name of the restaurant.
* Price – The average cost for two people at the restaurant (in ₹).
* Avg ratings – The average customer rating of the restaurant (out of 5).
* Total ratings – The total number of ratings/reviews the restaurant has received.
* Food type – The type of cuisine(s) served by the restaurant (e.g., Chinese, Indian, Italian).
* Address – The specific street address of the restaurant.
* Delivery time – The estimated delivery time (in minutes) for online food orders from the restaurant.

## Insights:
1. Number of Restaurants: 7,865
2. Highest Restaurant Price: ₹2,500
3. Average Rating of All Restaurants: 3.66
4. Total Ratings Across All Restaurants: 1,359,590
5. Number of Different Food Types: 3,734

## Insights:
1. Top 3 Cities by Restaurant Count:
    - Kolkata: 1,346 restaurants
    - Mumbai: 1,277 restaurants
    - Chennai: 1,106 restaurants
2. Average Price of Restaurants for Each Food Type (Top 8):
    - <u>Food Type</u> --------------------------------------------------------- <u>Avg. Price</u>
    - Japanese,Korean,Barbecue ---------------------------------------- 2500.0
    - North Indian,Mughlai,Biryani,Grill,Seafood,Kebabs,Desserts ---- 2500.0
    - Asian,Continental -------------------------------------------------- 2000.0
    - Healthy Food,Salads,Pizzas ---------------------------------------- 1900.0
    - Chinese  Pan-Asian  Tibetan  Oriental  Mongolian ------------------ 1800.0
    - Goan,Portuguese -------------------------------------------------- 1800.0
    - Italian,Continental,North Indian,Mughlai,Pizzas,Bakery ----------- 1800.0
    - North Indian,Chinese,Biryani,Continental,Mughlai --------------- 1700.0

3. Rating Distribution: The histogram of restaurant ratings shows that most restaurants have ratings clustered around 3 to 4, with fewer restaurants rated below 2 or above 4.5. This suggests that while most restaurants are moderately rated, very high or very low ratings are less common. The distribution is slightly right-skewed, meaning a small number of restaurants achieve excellent ratings.
4. Average Delivery Time for Restaurants with Rating Above 4: 51.99 minutes
5. Top 5 Rated Restaurants and Their Food Types:
    - Diamond Market Pizza Jp (Italian) with rating 5.0
    - Get In My Belly (Indian) with rating 5.0
    - The Asian Pavilion (Asian, Chinese) with rating 5.0
    - Cafe Kokomo (Beverages, Snacks, Desserts, Bakery) with rating 5.0
    - Papacream (Ice Cream) with rating 5.0

## Insights:
1. Price vs. Ratings Correlation:
    - Weak positive correlation (r = 0.11), meaning higher prices don't strongly indicate better ratings.
2. Delivery Time Outliers:
    - Some restaurants have extremely high delivery times, possibly due to long distances or operational delays.
3. Price vs. Ratings Box Plot:
    - Higher-rated restaurants tend to have slightly higher prices, but pricing varies widely across all rating categories.
4. City-Wise Analysis:
    - Mumbai has the highest average restaurant price, while Bangalore has the highest average rating. Surat has the lowest prices. 
