# PyBer_Analysis
Creating visualizations of rideshare data for PyBer to help improve access to ride-sharing services and determine affordability for underserved neighborhoods.

## Overview of the analysis
PyBer, is a ride-sharing app company valued at $2.3 billion. We have to create visualizations to show the relationship between the number of drivers, number of rides,  sum of fares , average fare per ride, average fare per driver by the type of city based on the data gathered from Jan 2019 to early May 2019 on the ride share app stored as [city_data.csv](https://github.com/sucharita1/PyBer_Analysis/blob/1d878529192f25064dd45d2a5dfb6bcb3b20cd00/Resources/city_data.csv) and [ride_data.csv](https://github.com/sucharita1/PyBer_Analysis/blob/1d878529192f25064dd45d2a5dfb6bcb3b20cd00/Resources/ride_data.csv).

The results of the analysis and visualizations are present in the [PyBer_Challenge.ipnyb](https://github.com/sucharita1/PyBer_Analysis/blob/1d878529192f25064dd45d2a5dfb6bcb3b20cd00/PyBer_Challenge.ipynb) . This will help PyBer improve access to ride-sharing services and determine affordability for underserved neghbourhoods.

## Resources
* Data Source: city_data.csv, ride_data.csv
* Software: Python 3.7.10, Jupyter notebook 6.3.0

## Results:

* Total are total 120 cities where Pyber operated from 2019-01-01 through 2019-04-28.
1. 18 cities of type Rural.
2. 36 cities of type Suburban.
3. 66 cities of type Urban.

![type_of_city](https://github.com/sucharita1/PyBer_Analysis/blob/1d878529192f25064dd45d2a5dfb6bcb3b20cd00/analysis/type_of_city.png?raw=true)

* The total number of rides for each type of city from 2019-01-01 through 2019-04-28 is:
1. 125 Rides for Rural cities.
2. 625 Rides for Suburban cities.
3. 1,625 Rides for Urban cities.

* The total number of drivers for each type of city from 2019-01-01 through 2019-04-28 is:
1. 78 drivers for Rural cities.
2. 490 drivers for Suburban cities.
3. 2,405 drivers for Urban cities.

* The sum of fares for each type of city from 2019-01-01 through 2019-04-28 is:
1. $4,327.93 for Rural cities.
2. $19356.33 for Suburban cities.
3. $39,854.38 for Urban cities.

* The average fare per ride for each type of city from 2019-01-01 through 2019-04-28 is:
1. $34.62 for Rural cities.
2. $30.97 for Suburban cities.
3. $24.53 for Urban cities.

* The average fare per driver for each type of city from 2019-01-01 through 2019-04-28 is:
1. $55.49 for Rural cities.
2. $39.50 for Suburban cities.
3. $16.57 for Urban cities.

The above results are summarized in the Pyber Summary Dataframe below:
![pyber_summary_df](https://github.com/sucharita1/PyBer_Analysis/blob/1d878529192f25064dd45d2a5dfb6bcb3b20cd00/analysis/pyber_summary_df.png?raw=true)

## Summary:
#### We can see from the data from 2019-01-01 through 2019-04-28 that Urban cities are the workhorses that generate most of the revenue while rural cities do not generate enough. During peak season urban cities generate close to 2,500$ per week but the rural cities rarely make upto 500$. Urban cities maintain close to 2,000$ per week revenue. While rural cities don't even maintain a 200$ per week. This gap needs to be bridged in order for Pyber to become the most preffered ride share app. 
![PyBer_fare_summary](https://github.com/sucharita1/PyBer_Analysis/blob/1d878529192f25064dd45d2a5dfb6bcb3b20cd00/analysis/PyBer_fare_summary.png?raw=true)

The disparity between the fares vs driver count and number of rides are discussed below. Alongwith some suggestions to generate more revenue from the underserved rural cities.

* Pyber needs more visibility in rural areas. 

Pyber operates in 120 cities out of which 66 cities are  Urban and 36 cities are suburban, and 18 cities are rural. So Pyber has a strong presence in urban cities i.e. (55%) but almost equal presence in suburban/rural cities that is (45%). But the number of rides in rural areas was 125 while the numer of rides for suburban areas was 625 and urban areas was 1650. Likewise almost 63% of the revenue comes from urban cities while rural cities which comprise 15% of the cities bring only 7% revenue approx. We need to advertise Pyber's ride share model in rural cities to tap the highly underserved rural market. 

![type_of_city_by_fare](https://github.com/sucharita1/PyBer_Analysis/blob/1d878529192f25064dd45d2a5dfb6bcb3b20cd00/analysis/type_of_city_by_fare.png?raw=true)
 
* Pyber needs to make fares in rural areas more afforable.

The average fare for rides in the rural cities is about $34.62. But for urban cities was $24.53 and $30.97 in suburban cities, respectively. The rides in rural area cost 11$ and 5$ more than urban and suburban cities. No wonder the number of rides in rural areas is just 7% of that of urban areas. The population in rural areas is less but so is the connectivity by buses/trains within the city or to/from urban cities. By advertising on bus stops/train stations about the PyBer_Rideshare and sending discount coupons to existing customer on sharing rides will generate more rides and bring down average fare for rides. Increase in affordability will increase the revenue manyfolds.
![Average_Fare](https://github.com/sucharita1/PyBer_Analysis/blob/1d878529192f25064dd45d2a5dfb6bcb3b20cd00/analysis/Average_Fare.png?raw=true)

* Pyber needs more drivers in rural area.

 The fare per driver is $55.49 in rural areas while it is $39.50 for suburban and $16.57 for urban areas. Only 2.6% drivers cater to rural citites while 80.9% cater to Urban cities. Thus, the average number of drivers in rural cities is nine to four times less per city than in urban and suburban cities, respectively. This creates higher demand and leads to higher fares per driver. Rural areas have high population of seasonal workers as many of them are farmers or work in tourism sector as many rural areas also serve as tourist places. If these people can be roped in as part time drivers then the driver shortage can be addressed.
 
![Total_drivers](https://github.com/sucharita1/PyBer_Analysis/blob/1d878529192f25064dd45d2a5dfb6bcb3b20cd00/analysis/Total_Drivers.png?raw=true)

