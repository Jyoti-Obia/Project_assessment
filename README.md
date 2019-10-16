# Project_assessment

This analysis is based on the full data analysis. To avoid the data size constraint, data storage and analysis was done using Google drive tools


# The Taxi_data_analysis.ipny file has four components-
## 1.	Data cleaning and preprocessing

a.	Columns names in both the files had leading spaces which was removed. 

b.	Missing data checks was done. Coulmn “store_and_fwd_flag” had around 50% missing values, hence dropped the column.

c.	Also,  columns “dropoff_longitude” and “dropoff_loatitude” has 146 missing records and were removed.

d.	The merged file had 122 duplicate records which were removed.

e.	The two files provided were merged on the common  four columns to create a single master file.

f.	trip_distance  was found to be zero in around 1 lakh trips, hence for those computations which involved trip_distance as denominator these trips were excluded.

g.	8871 trip records have tip amount greater than fare were removed from the dataset

## 2.	EDA using Visualisation

Matplotlib and Seaborn libraries used.

a.	Distribution plot for Continuous variable

b.	Histograms for discrete variable

c.	Correlation matrix for variable relationship

## 3.	Basic Questions 

a.	What is the distribution of number of passengers per trip? 

b.	What is the distribution of payment_type? 

c.	What is the distribution of fare amount? 

d.	What is the distribution of tip amount? 

e.	What is the distribution of total amount? 

f.	What are top 5 busiest hours of the day?

g.	What are the top 10 busiest locations of the city? 

h.	Which trip has the highest standard deviation of travel time? 

i.	Which trip has most consistent fares? 

## 4.	Open Questions 

a.	In what trips can you confidently use respective means as measures of central tendency to estimate fare, time taken, etc.

b.	Can we build a model to predict fare and tip amount given pick up and drop off coordinates, time of day and week?

c.	If you were a taxi owner, how would you maximize your earnings in a day? 

d.	If you were a taxi owner, how would you minimize your work time while retaining the average wages earned by a typical taxi in the dataset? 

e.	If you run a taxi company with 10 taxis, how would you maximize your earnings? 

### The Taxi_analysis.ppt answers the Basic and Open question. 
### In appendix, some visualisation is depicted to understand the data and distribution.
