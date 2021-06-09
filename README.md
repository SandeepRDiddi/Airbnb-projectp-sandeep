Project overview:-
The purpose of this project is to investigate host listings on Airbnb data proovided on Udacity Nandegree program and build predictive models on listing price based on key factors and variables.


Resources Used
Python Version: 3
Packages: pandas, numpy, sklearn, matplotlib, seaborn,os


Data

1.listing.csv
2.calendar.csv
3.reviews.csv

Acknowledgements for data : -https://www.kaggle.com/airbnb/boston

Summary
This project follows CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology. Steps followed in this project:

Business Understanding: 

From looking at the listing data we could possibly point to the price of each listing which tells us about the Airbnb business in Boston. And the entire analysise will be done on this as the back bone

We can see that we have all the main information about the listing, such as host information, property information, house rules, amenities, listing price, location of the listing, number of beds, bathrooms, bedrooms, and how many people can be accommodated in each property.

With the data in hand here are some high level questions to answer 

What are the price distributions for each type of room?
What are the features that highly correlate to price?
What are the most expensive zip codes in Boston?


Data Understanding

I have used below features for the data Analysis 

reviews_per_month: The number of reviews the listing has per month
host_acceptance_rate: The rate of booking acceptance
accommodates: The number of guests that can be accommodated in the property
bathrooms: The number of bathrooms in the property
bedrooms: The number of bedrooms in the property
beds: The number of beds in the property
price: The price per night for the booking
host_response_rate: The responsiveness of the host, in hours or days
zipcode: The zip code where the property is located
property_type: The property type (House, apartment, etc)
room_type: The room type (private room, entire house/apartment, shared room)
neighbourhood_cleansed: The neighborhood where the property is located
minimum_nights: The minimum nights that needed to complete the booking


Prepare Data

The data is engineered in such a fashion that the required variables are picked and the least co-related variables are not considered for the study 


Data Modeling

Regression modesl has been picked up for this study. I will compare Both OLS method and also the SKlearn method and will provide appropriate comments on the code in Jypyter notebook 

Evaluate the Results

The Results will be evaluated with how close are the Predicted and actual outcomes will be on the regression method. To evaluate the results i will also choose right variables based on several Profelling and co-relation study of the variables. 


Analyze the price
How we can predict
Discuss how price can contribute to neighborhood
Factors that influence prices
Applied certain data engineering (Clearning and Wranggling) techniques
Best methods of handled missing data and impute them if required where ever necassary



Acknowledgements
Kaggle
Stackoverflow
Youtube
Github
Google
