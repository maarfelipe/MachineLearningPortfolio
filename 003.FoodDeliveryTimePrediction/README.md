# Food Delivery Time Prediction

Food Delivery services like **Zomato** and **Swiggy** need to show the accurate time it will take to deliver your order to keep transparency with their customers. These companies use **Machine Learning** algorithms to predict the food delivery time based on how much time the delivery partners took for the same distance in the past.

To predict the food delivery time in real-time, we need to calculate the distance between the food preparation point and the point of food consumption. After finding the distance between the restaurant and the delivery locations, we need to find relationships between the time taken by delivery partners to deliver the food in the past for the same distance.

# Project Details

In this project, various Python libraries were used to analyze and visualize the Food Delivery Time dataset. The Pandas library was used to read and manipulate the dataset, including checking for null values and creating a new feature based on latitude and longitude points. The NumPy library was used for numerical calculations, such as converting degrees to radians in the haversine formula for calculating distances. The Plotly Express library was used for creating visualizations, such as scatter plots and box plots, to explore relationships between the features.

Additionally, the geopy library was used to calculate the distance between two points using the Haversine formula. This library simplifies the calculation process by providing a built-in distance function to calculate the distance between two points on a globe.
