
# UmojaHack Algeria : Yassir ETA Prediction

Ride-hailing apps like Uber and Yassir rely on real-time data and machine learning algorithms to automate their services. Accurately predicting the estimated time of arrival (ETA) for Yassir trips will make Yassir’s services more reliable and attractive; this will have a direct and indirect impact on both customers and business partners. The solution would help the company save money and allocate more resources to other parts of the business.

The objective of this hackathon was to predict the estimated time of arrival at the dropoff point for a single Yassir journey.

# About Yassir 
Established in 2017, Yassir is the leading ride-hailing company in Algeria. It covers all major Algerian cities and is expanding its services to Tunisia, Morocco and France. Besides ride-hailing services, Yassir is making customers’ lives easier by providing diversified services such as goods and food delivery as well as telemedicine.

<img src="yassir_logo.png" alt="alt text" width="200" height="250">






# What I did in short

My solution **(ranked 5th on LB)** was actually straightforward, it consists of training a LightGBM regressor on the data after various feature engineering (date features , geospacial coordinates clustering and the like), data cleaning to obtain over 30 features. 

One of the techniques that boosted my score was the Box-cox transform that was applied on the target variable. 

the model scored 149.72 seconds on the LB, which means it's 2 min and 49 seconds off on average. 

# aknowlegments

I would like to warmly thank the all the organizers  and Yassir company that went through this for making this exsiting hackathon.
