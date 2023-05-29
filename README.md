# 👥 **Team**
- [Yuhan Liu](https://github.com/Yuhan1224). 
- [Lena Umphprn](https://github.com/lenaumphprn). 
- [Jiaming Zhang](https://github.com/knzz716). 
- [Nikolai Semikhatov](https://github.com/Sevnhutsjr).

# Work Contribution
| **People** | **Data Collection** | **Data Cleaning** | **Code Quality Check**  | **Data Summary and Visualization** | **Report** |
|:-----------|:-------------------:|:-----------------:|:-----------------------:|:----------------------------------:|:----------:|
| Lena |      10%          |      20%        |      25%              |      30%                         |   25%    |
| Kevin |      30%          |      20%        |      25%              |      10%                         |   25%    |
| Kathy |      50%          |      40%        |      25%              |      30%                         |   25%    |
| Nikolai |      10%          |      20%        |      25%              |      30%                         |   25%    |

# Step 1: Data Collection and Preliminary Cleaning

The first step in our project involves data collection and preliminary data cleaning. We use two notebooks for this process, both located in the **Data&Outlier_Analysis** folder.

1. [dep&ret_tickets_data.ipynb](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/blob/main/Code/dep%26ret_tickets_data.ipynb): This notebook is used for weekly data collection. It gathers data on both departure and return flight tickets. After the data is collected, we perform an initial cleaning process. This involves selecting the necessary columns and ensuring that the data frames for each city are coherent. This cleaned data provides a comprehensive view of the flight details, including both departure and return flights.[dep&ret_tickets_data](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/tree/main/dep%26ret_flights): Here is the data collected.

2. [dep_tickets_data_and_clean.ipynb](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/blob/main/Code/dep_tickets_data_and_clean.ipynb): This notebook is specifically used to collect data on departure tickets. The purpose of this separate data collection is to analyze the relationship between departure airports and ticket prices without the influence of return tickets. This data provides a focused view on departure flight details and allows us to isolate the impact of departure airport on ticket prices.[dep&ret_tickets_data](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/tree/main/dep_flights): Here is the data collected.

These notebooks form the foundation of our data collection process, providing us with clean, organized data that is ready for further analysis.

# Step 2: Having An Initial Sense of Data distribution and Outlier Analysis:

To understand how the data looks like, we had plotted the data distribution for each city and done some outlier analysis, which proviede by this notebook [Data_distribution&Outlier_analysis.ipynb](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/blob/main/Code/Data_distribution%26Outlier_analysis.ipynb)

**We've decided to use the median for our visualizations because the presence of outliers can skew the mean, making it less representative of our data. In such cases, the median provides a more stable measure of central tendency, and so we opt to use it for further visualizations.**

# Step 3: Visualisaztion

In order to find out factors affects weekend flight price, we carried out several analysis:

1.Departure Time Analysis：[flight_time_analysis.ipynb](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/blob/main/Visualisations/flight_time_analysis.ipynb). This notebook contains the code for graphs showing how, for each city analysed, the price varies for each departure time throughout the day. We decide to visualise the median on the basis of understanding whether the departure time is relevant for flyers trying to minimise travel costs.

2.Departure Airport Analysis：[dep_airport_analysis.ipynb](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/blob/main/Visualisations/dep_airport_analysis.ipynb). This set of analyses plots the median and minimum price per month to fly to each city, with each line on each graph comparing how these prices differ between each departure airport. By making these visualisations, we are able to analyse the change in prices and differences in available airports for each city. The median allows us to grasp the expected price perceived by flyers, whereas the minimum price provides a more relevant picture for budget travellers choosing to optimise their cost within each flight date.

3.Carrier Provider and Price Analysis：[price_analysis.ipynb](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/blob/main/Visualisations/price_analysis.ipynb). Here we analyse the price to each destination for each airline overall. We use the mean to see what your expected flight price is, median to understand the price range and the minimum to see what the cheapest airline and destination is. There is a “mixed” line which represents chosing a different outbound and return airline to your destination and is only interesting in regards to the minimum price, as it shows what the cheapest price could be. 

4.Booking time window analysis:[Booking_time_window.ipynb](https://github.com/Sevnhutsjr/LSE-DS105-Wandermetrics/blob/main/Visualisations/Booking_time_window.ipynb). This notebook is about the visualisations for booking time window analysis, and we generated the dynamic graphs to show how the price distributions for each city changed over time and used the Wasserstein distance to evaluate hoe similar of the two price distributions for each consecutive dates.



















