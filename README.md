# Hotel_Booking_Cancellation

## Introduction
This project aims to analyze the hotel bookings dataset, focusing on the cancellation rates and other significant trends. The dataset contains detailed information about hotel reservations, including booking details, customer demographics, and reservation statuses. The analysis will provide insights into the factors affecting cancellation rates and other key performance metrics.

### Project Steps

#### Data Loading and Preprocessing
Import necessary libraries and load the dataset.
Check the initial structure of the dataset.
Handle missing values by dropping columns with excessive missing data and filling or dropping rows with minor missing values.
Convert necessary columns to appropriate data types.

#### Exploratory Data Analysis (EDA)
Understand the distribution and unique values of categorical features.
Visualize the data to identify patterns and trends.
Analyze the distribution of is_canceled to understand the proportion of canceled vs. non-canceled bookings.

#### Data Cleaning
Drop irrelevant columns that have a high percentage of missing values or do not contribute to the analysis (agent and company).
Remove outliers in the adr column to ensure accurate analysis.

#### Visualization
Use bar plots and count plots to visualize the cancellation status across different hotels and other relevant features.
Analyze the distribution of adr and other numerical features.

#### Analysis of Cancellation Rates
Calculate the percentage of canceled bookings.
Visualize the cancellation rates across different categories.


### Conclusion

#### Key Results
**Cancellation Rates:** The dataset revealed that approximately **37.13%** of the bookings were canceled, while **62.87%** were not canceled.
**Hotel-wise Analysis:** Resort Hotels have a lower cancellation rate (**27.98%**) compared to City Hotels (**41.71%**).The average daily rate (ADR) for Resort Hotels tends to be slightly higher compared to City Hotels over time.
**Customer Preferences:** ADR trends show fluctuations over time, with both City and Resort Hotels experiencing periods of increase and decrease.
Monthly reservation data indicates seasonal trends in booking volumes and cancellations..

#### Performance Metrics
**Proportion of Cancellations:** The dataset has been analyzed to calculate the proportion of cancellations, which is a key metric for understanding booking trends.

**Average Daily Rate (ADR):** By analyzing the adr column, we can determine the typical revenue per available room, adjusted for outliers.
