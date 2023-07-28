# Customer-Satisfaction-Analysis
Overview
This project aims to analyze customer satisfaction data from an airline company. The dataset contains various features related to customer experiences, flight details, and satisfaction levels. The primary goal is to explore the data, visualize key insights, and gain a better understanding of the factors that influence customer satisfaction.

Data
The dataset used for this analysis is stored in the file "satisfaction.csv". It includes the following columns:

"Satisfaction": The target variable indicating whether the customer was satisfied or dissatisfied.
"Customer Type": Type of customer (e.g., loyal, disloyal).
"Age": Age of the customer.
"Flight Distance": Distance of the flight in miles.
"Type of Travel": Purpose of travel (e.g., business, personal).
"Class": Class of the flight (e.g., Business, Eco).
"Seat Comfort": Customer's rating of seat comfort.
"Gender": Gender of the customer.
"Departure Delay in Minutes": Delay in minutes at departure.
"Arrival Delay in Minutes": Delay in minutes at arrival.
Libraries Used
pandas: For data manipulation and analysis.
numpy: For numerical computing.
matplotlib: For creating visualizations.
seaborn: For enhanced data visualization.
Data Exploration and Preprocessing
The initial phase of the project involves exploring the dataset to understand its structure and identifying missing values. The dataset is then preprocessed to prepare it for analysis. Notable preprocessing steps include dropping the "Online support" column, filling missing values in "Arrival Delay in Minutes" with "Departure Delay in Minutes", and renaming the column "satisfaction_v2" to "Satisfaction" for clarity.

Exploratory Data Analysis (EDA) and Visualizations
The EDA phase focuses on understanding the data through visualizations and gaining insights into the dataset. Some of the visualizations include:

Distribution of Satisfaction Levels: A bar chart displaying the count of satisfied and dissatisfied customers.
Count of Passengers by Customer Type: A bar chart representing the distribution of customers based on their type (e.g., loyal, disloyal).
Distribution of Ages: A histogram showcasing the distribution of customer ages.
Distribution of Flight Distances: A histogram displaying the distribution of flight distances.
Proportion of Types of Travel: A pie chart depicting the proportion of different types of travel.
Proportion of Classes: A pie chart showing the proportion of customers in different classes (e.g., Business, Eco).
Proportion of Customer Types: A pie chart representing the proportion of loyal and disloyal customers.
Distribution of Seat Comfort by Gender: Boxplots comparing the seat comfort ratings between male and female passengers.
Distribution of Seat Comfort by Class: Boxplots comparing seat comfort ratings in different classes.
Trend of Departure Delay Over Time: A line plot depicting the trend of departure delays over time.
Conclusion
The analysis and visualizations in this project provide valuable insights into customer satisfaction in the airline industry. By understanding the factors that influence customer satisfaction, the airline company can make informed decisions to enhance the overall customer experience and improve their services.

Note
This readme file provides an overview of the project, including the dataset, libraries used, data exploration, and visualizations. For detailed code and analysis, please refer to the Jupyter Notebook or Python script used to execute the project.
