![Fig_05](img/fig_05.png)

# <font size="8"><b>PREDICTING ARRIVAL DELAYS FOR MAJOR US AIRLINES</b></font>

# INTRODUCTION AND PROBLEM STATEMENT
The Capstone project is the cornerstone project that is the essence of the Data Science Immersive program at General Assembly. The aviation industry is of great importance for a globally connected economy. Customer satisfaction with airlines and airport performance is considerably influenced by how much flights are delayed.
I am very passionate about the airline industry decided to do my project with a dataset that is composed of domestic flights within the United States with data from January of 2019 to December of 2020. I wanted to make sure the dataset covered the pre-Covid 19 period as well as the year 2020. I will use the aggregate data for the years 2019 and 2020 to make some comparison on how the COVID-19 has impacted the airline industry and use the data from 2019 to run my machine learning algorithms to predict flight delays at arrivals. I have chosen the 20 busiest airports within the united states as well as four main airlines namely American, Delta, United and Southwest airlines.

According to data from the United States Bureau of Transportation Statistics (BTS), almost 20% of flights within the U.S were delayed at arrival in 2019, which resulted in a severe economic impact equivalent to circa 41 billion US$ (A delayed flight is a flight that is delayed 15 minutes or more).


# DATA

Overview of the data set

My dataset has been taken from the United States government agency website that provides the air traffic delay statistics in the U.S.
The U.S. Department of Transportation's (DOT) Bureau of Transportation Statistics performance of domestic flights operated by large air carriers. BTS compiles daily data for the benefit of the customers or for data practitioner like myself. The dataset is comprised of 2019, 2020 and the first 2 months of 2021 reporting on time performance.
I have included the following column headers: Year, Quarter, Month, DayofMonth, DayofWeek, flight date, Reporting_Airline, DOT_ID_Reporting_Airline, IATA_CODE_Reporting_Airline, Tail_Number, OriginAirportID, OriginAirportSeqID, OriginCityMarketID, Origin, OriginCityName, OriginState, OriginStateName, OriginWac, DestAirportID, DestAirportSeqID, DestCityMarketID, Dest, DestCityName, DestState, DestWac, CRSDepTime, DepTime, DepDelay, DepDelayMinutes, DepDel15,DepTimeBlk,CRSArrTime, ArrTime, ArrDelay, ArrDelayMinutes, ArrDel15, Cancelled, Flights and Distance.

Data Exploration

Data cleaning is the critical initial step in evaluating the dataset for final analysis. With the enormous amount of data available, databases are prone to have noisy, missing and inconsistent data. 
From all flights in the dataset, less than 0.005 percent were cancelled thus the vast majority of flight were not. I decided not to use the canceled flights column for my analysis.
Also I did not take into account the folllowing delays for my analysis: Carrier Delay, Weather delay, security dealy and late aircraft delay because 88.97 percent of the data was missing.
The BTS website does not allow dowloading the dataset all at once. I had to do it on a monthly basis for the years 2019 and 2020. After the data was downloaded as CSV files onto my computer, I did some cleaning and create 2 separates dataframes for 2019 and 2020 and also a combined dataframe for 2019-2020 (6,112,240 rows × 24 columns).











# CONCLUSIONS AND FUTURE WORK






# BIBLIOGRAPHY
