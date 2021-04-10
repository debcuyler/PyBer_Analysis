# PyBer Ride-Sharing Analysis

# Overview
V. Isualize, CEO of PyBer has asked me to complete a summary of ride-sharing data by city type. I used Pandas and Matplotlib to create DataFrames and graph the information requested.

# Results
 - The summary DataFrame was completed and shows Total Rides, Total Drivers, Average Fare per Ride and Average Fare per Driver for each city type.
	- There are 2405 drivers and 1625 total rides for Urban cities. The average fare per ride was $24.53 and the average fare per driver was $16.57. 
	- There are 490 drivers and 625 total rides for Suburban cities. The average fare per ride was $30.97 and the average fare per driver was $39.50.
	- There are 78 drivers and 125 total rides for Rural cities. The average fare per ride was $34.62 and the average fare per driver was $55.49.
	
- A multiple line plot was created that shows the total weekly fares for each type of city from Jan 1, 2019 through April 29, 2019.
	- Weekly fares were fairly consistent for all city types throughout the period with all city types seeing a slight spike in fare the third week of February. As shown in the summary DataFrame, the Urban cities had more fares, with the Suburban cites coming next and the Rural cities had the lowest total fares.
	
# Summary
- Business Recommendations
	- Decrease the number of urban city drivers as the total number of drivers are higher than the total number of rides. Likely, this is what is skewing the data to make is seem that urban drivers are making much less money per fare. The total fares were divided by the total drivers and there were more drivers than rides. 
	- The average fare per ride for urban city rides was less than both suburban cities and rural cities. The distance of the ride could account for the difference but a slight fare increase may bring all city types closer to the same average fare per ride.
	- Increase the number of drivers in the rural cities to bring the average fare per driver down so that all city types are closer to the same average. Rural drivers may have longer rides, which may account for the highest average fare per ride, but it is pretty consistent with the Suburban fare per ride.