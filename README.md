# Exploratory-Analysis-of-Geolocational-Data
## Objective: 
This project involves the use of K-Means Clustering to find the best accommodation for students in a city by classifying accommodation for incoming students on the basis of their preferences on amenities, budget and proximity to the location.

## Context:
Imagine a scenario where a person has newly moved into a new location. They already
have certain preferences, certain tastes. It would save both the student and the food
providers a lot of hassle if the student lived close to their preferred outlets. Convenience
means better sales, and saved time for the customer.

Food delivery apps aside, managers of restaurant chains and hotels can also leverage this
information. For example, if a manager of a restaurant already knows the demographic of
his current customers, they’d ideally want to open at a location where this demographic is
at its highest concentration, ensuring short commute times to the location and more
customers served.If potential hotel locations are being evaluated, a site that caters to a wide
variety of tastes would be ideal, since one would want every guest to have something to
their liking.

## High-Level Approach:
1. Fetch Datasets from the relevant locations (Data Collection)
2. Clean the Datasets to prepare them for analysis. (Data Cleaning via Pandas)
3. Visualise the data using boxplots. (Using Matplotlib /Seaborn /Pandas)
4. Fetch Geolocational Data from the Foursquare API. (REST APIs)
5. Use K-Means Clustering to cluster the locations (Using ScikitLearn)
6. Present findings on a map. (Using Folium/Seaborn)
