# CS411_Project
.
1. Travel Plan Web Application: 

Design a web application for users to select preferences of different categories (attractions, restaurants, hotels) and users can receive a travel plan. The APIs we can use are Google, Yelp, Amadeus place APIs to get the data sets of attractions, restaurants, and hotels. The travel plan is generated by the recommendation system based on users' preferences, ratings, and locations (lat, lon).
  APIs/Datasets:
   > https://developers.google.com/maps/documentation/places/web-service/overview - Google place APIs
   > https://www.yelp.com/developers/documentation/v3/get_started - Yelp APIs
   > https://developers.amadeus.com/self-service/category/covid-19-and-travel-safety/api-doc/safe-place/api-reference - Amadeus place APIs

2. Boston Delivery Management System Web Application: 

Design a drone & robot delivery management system. We have a few bases in Boston to send out drone & robot to delivery package. Users can type their name pickup address, recevier's name and delivery address to create order in the order interface. The recommendation system generate delivery plans based on users' inputs in the plan interface. Users can also register for an account and login/logout to review their delivery status. Use Google Geolocation API or Pubnub to visualize the delivery status on the Google Map.
  APIs/Datasets: Google API(text search)/Pakage delivery time/Google Geolocation API
> https://kilthub.cmu.edu/articles/dataset/Data_Collected_with_Package_Delivery_Quadcopter_Drone/12683453?file=26405936 -- info on drone deliveries
> https://data.boston.gov/dataset/traffic-related-data -- info on boston traffic, for contrast w/ drone services


3. Util:

Many people, myself included, have issues tracking recurring payments. Some of the largest of these payments are utility bills, such as monthly AC, electric, or water bills. This app will help users track their bills: when they recur, how much they pay, and how their payments stack up versus nearby payments/providers. Users can register for accounts for a streamlined dashboard, where their bills pop up in the order they're due.
   > https://data.boston.gov/dataset/city-of-boston-utility-data 
   > https://utilityapi.com/
   

4. Solar:

This app will allow citizens to see how much they could save, monetarily & energy-wise, by switching to solar power. Users can sign up for accounts and input details about their household: number of residents, avg utility costs, energy output(?), etc. They can then see how much cheaper their bills would be if they opted for greener solutions(solar panels, renewable energy, etc).
  APIs/Datasets:
   > https://data.boston.gov/dataset/city-of-boston-utility-data 
   > https://utilityapi.com/
   > https://www.causeweb.org/cause/resources/library/r1086
   > https://developer.nrel.gov/docs/solar/solar-resource-v1/ -- gives exact metrics for solar energy production via long/lat
   > Can visualize solar savings with formulas (national average electricity rate as of October 2021 ($0.1411 per kWh) vs solar kWh)
