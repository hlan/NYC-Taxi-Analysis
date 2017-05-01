# NYC Taxi Analysis

![alt tag](https://github.com/NYU-CS6313-Fall16/NYC-Taxi-10/blob/master/files/NYCtaxi.png)

#### Authors
Hai Lan([hlan](https://github.com/hlan)), Heejong Kim([heej0ng](https://github.com/heej0ng)), Himanshu Kumawat([hk1953](https://github.com/hk1953)), Aayushi([aayushia](https://github.com/aayushia))

# Description

### Problem

Where the taxi drivers in New York City can easily find the “target spots” to pick passengers?
 
Taxi drivers, especially in crowded city like New York, are facing intense competition every day. Every taxi drivers are hoping to minimize the empty-load time during their work hours and also, get more money earned. Fortunately, NYC Taxi and Limousine Commission (TLC) provide records of all historical taxi data in past few years. With those data, taxi drivers no longer need to find passengers in blind. However, simply show those data to taxi drivers directly is not a wise way because those data is complex to analyze and it is difficult for drivers to find their interested information from those data directly.
 
Therefore, developing an effective visual analytic tool to interactively mine and visualize those data to those taxi drivers with their own needs will be helpful for them to work more efficiency. On the other hand, it can also optimize passengers’ satisfactory as well because no passenger prefer to wait a super long time until get a taxi.

### The driving analytical questions this Visualization can easily answer:

Since our project aims to help taxi drivers in NYC to find the target spots, we want to answer the questions that taxi drivers might have. 

##### Where is the highest taxi demanding area in Manhattan in different time intervals?
Taxi demanding will change at different place at different time. For example in rush hour, it is possible that more potential passengers may take taxi from residence places to their working places.

#### Where and when to find the places those passengers prefer to pay highest tips?
Taxi drivers usually want to earn more for each trip. However, tips amount are not always affected by total amount. By calculating the average tip percentage of total amount and mapping results to map can help drivers find out in which area and time, people prefer to pay higher tips.

#### Where and when is the place that passengers usually pay with cash rather than credit cards?
Sometimes, drivers prefer to get cash directly to avoid withdraw from ATM again. Sometimes, they just prefer to get money with credit cards for some safety reasons. By analyzing the credit card/cash ratio in spatio­temporal can help to find the place that fit for those drivers’ need.
 
#### Is there relationship between higher demanding areas and tips (or cash/credit ratio)? 
In addition to finding the best place for taxi demands, tips or cash, we want to find the relationship between taxi demands and other attributes.

### Video: https://vimeo.com/196902125

### Live Demo: http://54.174.39.79/

### Final Document: [Final Report](https://github.com/NYU-CS6313-Fall16/NYC-Taxi-10/blob/master/files/Final_Project_Report.pdf)

# Data Source

[NYC Taxi Data](http://www.nyc.gov/html/tlc/html/about/trip_record_data.shtml)

# Install Instructions

Run a localhost.

You can use SimpleHttpServer (Requires Python Installed 2.x)

Open a terminal, navigate to the folder where you cloned the repository and type in: python -m SimpleHTTPServer 8000

Open browser and navigate to URL: localhost:8000
