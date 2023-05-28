
# A Practical Workflow for Our Projects


# 👥 **Team**
- [Karina Moura](https://github.com/kvmoura). _A stellar project manager!_
- [Natalia Del Coco](https://github.com/NataliaDelCoco). _She is taking her van to the mountains for a while._
- [Sara Luxmoore](https://github.com/SaraLuxmoore). _She can be seen doing cool research-related stuff in Italy these days._

# Step 1: Data Collection and Preliminary Cleaning

The first step in our project involves data collection and preliminary data cleaning. We use two notebooks for this process, both located in the **Data&Outlier_Analysis** folder.

1. [dep&ret_tickets_data.ipynb](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/blob/main/Code/dep%26ret_tickets_data.ipynb): This notebook is used for weekly data collection. It gathers data on both departure and return flight tickets. After the data is collected, we perform an initial cleaning process. This involves selecting the necessary columns and ensuring that the data frames for each city are coherent. This cleaned data provides a comprehensive view of the flight details, including both departure and return flights.[dep&ret_tickets_data](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/tree/main/dep%26ret_flights): Here is the data collected.

2. [dep_tickets_data_and_clean.ipynb](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/blob/main/Code/dep_tickets_data_and_clean.ipynb): This notebook is specifically used to collect data on departure tickets. The purpose of this separate data collection is to analyze the relationship between departure airports and ticket prices without the influence of return tickets. This data provides a focused view on departure flight details and allows us to isolate the impact of departure airport on ticket prices.[dep&ret_tickets_data](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/tree/main/dep_flights): Here is the data collected.

These notebooks form the foundation of our data collection process, providing us with clean, organized data that is ready for further analysis.

# Step 2: Having an initial sense of Data distribution and some Outlier Analysis:

To understand how the data looks like, we had plotted the data distribution for each city and done some outlier analysis, which proviede by this notebook [Data_distribution&Outlier_analysis.ipynb](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/blob/main/Code/Data_distribution%26Outlier_analysis.ipynb)

# Step 3: Visualisaztion

In order to find out factors affects weekend flight price, we carried out several analysis:

1.Departure Time Analysis：

2.Departure Airport Analysis：

3.Carrier Provider Analysis：

4.Booking time window analysis:[Booking_time_window.ipynb](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/blob/main/Visualisations/Booking_time_window.ipynb). This notebook is about the visualisations for booking time window analysis, and we generated the dynamic graphs to show how the price distributions for each city changed over time and used the Wasserstein distance to evaluate hoe similar of the two price distributions for each consecutive dates.



















