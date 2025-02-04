# GLOBUS FOOD DELIVERY PERFORMANCE ANALYSIS FORT THE YEAR 2022
---
The "Globus Food Delivery Performance Analysis" project provides a comprehensive evaluation of key metrics impacting food delivery services. The analysis is based on various factors, including weather conditions, traffic levels, vehicle types, delivery distance, and order types. 
# BUSINESS PROBLEM
---
The food delivery industry faces multiple challenges, including fluctuating delivery times due to external factors like traffic congestion, weather conditions, and delivery personnel efficiency. Ensuring timely deliveries is crucial for customer satisfaction and operational efficiency. This analysis aims to:


1.Identify the key factors influencing delivery time.


2.Provide insights into optimizing delivery routes, vehicle usage, and workforce efficiency.


3.Offer recommendations to minimize delays and improve overall delivery performance.


<img width="788" alt="food delivery dashboard" src="https://github.com/user-attachments/assets/3a20f91e-abe7-40bf-9678-3c35d6907aec" />

# METHODOLOGY
--
Excel (Data cleaning), Tableau (Data visualization

# DATA SOURCE
---
The data used for the analysis was sourced from kaggle

# DATA CLEANING 
---

-Checked for duplicate values

-Trimmed the "Delivery person id" column using the "trim function"

-Removed blanke ,using find and replace and "special" to remove blanks

-Converted the delivery person age into group using the "ifs function"

-Handling missing values with find and replace


# Key Performance Indicators (KPIs)
---

-Total Delivery Time by Delivery Person: 43,100 minutes


-Total Number of Delivery Persons: 9,040


-Average Delivery Time by Traffic Level: 172 minutes


-Overall Average Delivery Time: 38 minutes

# INSIGHTS
---

### Weather Impact:

-Delivery times are highest during scattered clouds (43.55 mins) and smoke (41.64 mins), suggesting that adverse weather conditions negatively impact delivery efficiency.


-Broken clouds and haze result in relatively lower delivery times (~35-37 mins), indicating that weather stability plays a role in efficient delivery.


### Traffic Level Influence:

-Very high traffic significantly increases delivery time to 62.26 minutes, whereas very low traffic allows for much faster deliveries (13.89 mins).


-Effective route planning and delivery timing adjustments are crucial to reducing delays in high-traffic conditions.


### Vehicle Type & Distance Impact:

-Motorcycles cover the longest distances and have the highest delivery times.


-Electric scooters and bicycles have shorter delivery distances and correspondingly lower delivery times.


-Strategic allocation of vehicle types based on order distance could improve efficiency.


### Order Type Variations:

-Drink orders have the longest delivery times (43.13 mins), while meals (33.90 mins) have the shortest.


-The difference in delivery times may be attributed to order preparation time, packaging, and storage requirements.


### Delivery Personnel Efficiency:

-The younger age group (15-20 years) has the fastest average delivery times (37.42 mins), while the 21-30 and 31-40 age groups take longer (~53-55 mins).



-Experience may lead to cautious driving, or older drivers may be handling more complex routes.

### Top average delivery time by delivery perrsonel id

-CHENRES14DEL02 : 44.09mins
-CHENRES01DEL02 : 36.55mins
-JAPRES12DEL02 : 36.09mins
-COIMBRES12DEL02: 35.74mins
-COIMBRESO3DEL02: 35.38mins
-SURRESI6DEL01 : 33.04mins
-COIMBRES06DEL01 :31.25mins 
-RANCHIRES18DEL01 : 29.38mins

# RECOMMENDATION
---

### Optimize Route Planning:

Implement AI-driven route optimization tools to navigate high-traffic areas more efficiently.


Encourage deliveries during low-traffic hours to reduce delays.


### Improve Vehicle Allocation:

Assign electric scooters and bicycles for shorter distances to improve efficiency.


Utilize motorcycles for long-distance deliveries to reduce overall delivery time.


### Weather Adaptation Strategies:

Provide weather-based route planning to avoid congested or unsafe areas.


Equip delivery personnel with appropriate gear to ensure safety and efficiency in adverse conditions.


### Enhance Workforce Training:

Train delivery personnel on time management and efficient navigation techniques.


Offer incentives for timely deliveries to encourage higher performance.


### Order Handling Improvements:

Streamline meal preparation processes to minimize waiting times.


Prioritize quick packaging techniques for drinks and snacks to reduce handling delays.

### Improve Individual Delivery Performance:

Analyze high delivery time cases (e.g., CHENRES14DEL02) to identify specific causes such as traffic congestion, vehicle type, or order type.


Provide additional training and support to slower delivery personnel.


# CONCLUSION
---

This analysis highlights key factors influencing delivery times, including weather conditions, traffic congestion, order types, and workforce efficiency. By implementing strategic route planning, optimizing vehicle usage, and improving workforce training, Globus Food Delivery can significantly enhance its delivery performance. The recommendations provided aim to reduce delays, improve customer satisfaction, and optimize operational efficiency, ensuring a smoother and more reliable delivery service for the future.




