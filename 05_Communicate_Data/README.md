# Communicate Data findings Project 
This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In the first part, we will use Python visualization libraries to systematically explore a selected dataset(*Ford GoBike System Data Flights*), starting from plots of single variables and building up to plots of multiple variables. In the second part, we will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. 

## Ford GoBike System Data Flights Dataset  
This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.  This data is provided according to the [Bay Wheels License Agreement](https://baywheels-assets.s3.amazonaws.com/data-license-agreement.html).  
We use the data of all the year 2018. 
Each trip is ananymized and includes:  
- Trip Duration (seconds) : duration of each trip
- Start Time and Date : Date and time in which the trip starts
- End Time and Date : Date and time in which the trip ended
- Start Station ID : unique identificative number of the station where the trip starts  
- Start Station Name : Name of the station where the trip starts
- Start Station Latitude : Latitude of the station where the trip starts
- Start Station Longitude : Longitude of the station where the trip starts
- End Station ID : Unique identificative number of the station where the trip ends
- End Station Name : Name of the station where the trip ends(Could be the same as the starting station)  
- End Station Latitude : Latitude of the station where the trip ends
- End Station Longitude : Longitude of the station where the trip ends
- Bike ID : unique identificative number of the bike used for the trip
- User Type (Subscriber or Customer – “Subscriber” = Member or “Customer” = Casual)  
- Member Year of Birth : Year of birth of the the user
- Member Gender : Gender of the user(Male, Female or Other)
- Bike Share For All : New option that the member can use (Yes or No to know if the option is being used)    

## Main findings  
- There are Subcribers than Customers even if the longest trip is made by a customer  
- Male have more trip than Female 
- Very few people use the new option Bike Share for all Trip  
- The average rider is about 35 years old, even if there are people around 90 years riding. The peak is around 30 years old.  
- In general all the trip are brief around 15mn, but there is one trip of 24h
- Subscribers tend to have more trips between may and october with the peak at october, during the weekday and between 7-9am and 5-7pm  
- Customers tend to have more trips between may and october with the peak at july, during the weekends and between 11am to 6pm  
- Customers tend to have trips with more duration(more than 1h) than subscribers  

## Resources    
Main resource : **Head First python** by *Paul Barry* 2nd edtion 

