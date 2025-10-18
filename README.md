_**Task 1: Top Cuisines**__

**Objective:**

* Determine the top three most common cuisines in the dataset.

* Calculate the percentage of restaurants that serve each of these cuisines.

**Approach:**

1. Load dataset using pandas.

2. Explore the Cuisines column.

3. Count occurrences of each cuisine.

4. Identify top 3 cuisines.

5. Calculate their percentage relative to total restaurants.

6. Visualize using a bar chart.

**Insights:**

* Helps understand which cuisines dominate the restaurant market.

* Useful for targeting popular cuisine trends in business decisions.


_**Task 2: City Analysis**_

**Objective:**

* Identify the city with the highest number of restaurants.

* Calculate the average rating for restaurants in each city.

* Determine the city with the highest average rating.

**Approach:**

1. Group dataset by City and count restaurants.

2. Calculate average Aggregate rating for each city.

3. Visualize using bar charts or horizontal bar charts for readability.

**Insights:**

* Shows cities with high restaurant density.

* Highlights cities with better-rated restaurants, helpful for expansion planning.


_**Task 3: Price Range Distribution**_

**Objective:**

* Visualize the distribution of price ranges among restaurants.

* Calculate the percentage of restaurants in each price range.

**Approach:**

1. Use Price range column.

2. Count restaurants in each price category.

3. Visualize using a histogram or bar chart.

**Insights:**

* Understand the pricing structure of restaurants in the dataset.

* Helps target different customer segments based on pricing.


_**Task 4: Online Delivery**_

**Objective:**

* Determine the percentage of restaurants offering online delivery.

* Compare the average ratings of restaurants with and without online delivery.

**Approach:**

1. Convert Has Online delivery to numeric (0/1).

2. Calculate percentage for restaurants offering online delivery.

3. Compare average Aggregate rating for delivery vs non-delivery.

4. Visualize using bar charts or pie charts.

**Insights:**

* Shows the adoption of online delivery across restaurants.

* Helps correlate service availability with customer satisfaction.


_**Task 5: Restaurant Ratings**_

**Objective:**

* Analyze the distribution of aggregate ratings.

* Determine the most common rating range.

* Calculate the average number of votes received.

**Approach:**

1. Use Aggregate rating and Votes columns.

2. Visualize rating distribution using histograms.

3. Calculate average votes using mean().

**Insights:**

* Highlights general restaurant performance.

* Helps identify how ratings relate to popularity (votes).
  

_**Task 6: Cuisine Combination**_

**Objective:**

* Identify the most common combinations of cuisines.

* Determine if certain combinations tend to have higher ratings.

**Approach:**

1. Split Cuisines column for restaurants with multiple cuisines.

2. Count the frequency of combinations.

3. Group by combination and calculate average rating.

4. Visualize top combinations with ratings.

**Insights:**

* Helps understand which cuisine combinations are popular.

* Identifies combinations linked with higher customer satisfaction.


_**Task 7: Geographic Analysis**_

**Objective:**

* Plot the locations of restaurants using longitude and latitude.

* Identify clusters of restaurants in specific areas.

**Approach:**

1. Use Longitude and Latitude columns.

2. Plot using matplotlib scatter plot.

3. Observe clustering patterns by city or locality.

**Insights:**

* Shows high-density areas for restaurants.

* Useful for location-based business strategy.


_**Task 8: Restaurant Chains**_

**Objective:**

* Identify restaurant chains in the dataset.

* Analyze ratings and popularity of different chains.

**Approach:**

1. Check for restaurants with the same Restaurant Name across multiple locations.

2. Group by name to calculate average rating and total votes.

3. Visualize using bar charts or scatter plots.

**Insights:**

* Helps find the most popular chains and their performance.

* Useful for marketing and expansion planning.


_**Task 9: Restaurant Reviews (adapted for rating text)**_

**Objective:**

* Identify distribution of positive, neutral, and negative reviews using Rating text.

* Compare average Aggregate rating for positive and negative ratings.

**Approach:**

1. Categorize Rating text as Positive (Excellent, Very Good), Negative (Poor, Average), Neutral (others).

2. Count each category and calculate percentages.

3. Visualize using bar charts or pie charts.

4. Compare average ratings per category.

**Insights:**

* Shows sentiment distribution without text reviews.

* Helps identify the quality trend of restaurants based on customer ratings.



_**Task 10: Votes Analysis**_

**Objective:**

* Identify restaurants with the highest and lowest number of votes.

* Check correlation between votes and ratings.

**Approach:**

1. Use Votes and Aggregate rating columns.

2. Find restaurants with max and min votes.

3. Visualize vote distribution with histogram.

4. Plot scatterplot of Votes vs Ratings and calculate correlation.

**Insights:**

* Highlights popular and less popular restaurants.

* Helps understand if more votes indicate better ratings.


_**Task 11: Price Range vs Online Delivery & Table Booking**_

**Objective:**

* Analyze relationship between Price range and availability of online delivery and table booking.

* Determine if higher-priced restaurants are more likely to offer these services.

**Approach:**

1. Convert Has Online delivery and Has Table booking to numeric (1/0).

2. Group by Price range and calculate percentage offering each service.

3. Visualize using bar charts with percentage labels.

4. Draw insights by comparing price ranges.

**Insights:**

* Shows how service offerings vary by price.

* Helps identify trends in customer convenience features in higher-priced restaurants.

