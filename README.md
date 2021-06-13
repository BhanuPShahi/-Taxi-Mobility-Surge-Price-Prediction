# Taxi-Mobility-Surge-Price-Prediction

Data provided by an Indian cab aggregator service Sigma Cabs. Their customers can download their app on smartphones and book a cab from anywhere in the cities they operate in. They, in turn, search for cabs from various service providers and provide the best option to their clients across available options. They have been in operation for a little less than a year now. During this period, they have captured surge pricing types from the service providers.

In Taxi Mobility Surge Price Prediction our main objective is to build a predictive model, which could help in predicting the surge pricing type proactively.

---
Attributes 

● Trip_ID: ID for TRIP

● Trip_Distance: The distance for the trip requested by the customer

● TypeofCab: Category of the cab requested by the customer

● CustomerSinceMonths: Customer using cab services since n months; 0 month means the current month

● LifeStyleIndex: Proprietary index created by Sigma Cabs showing the lifestyle of the customer based on their behaviour

● ConfidenceLifeStyle_Index: Category showing confidence on the index mentioned above

● Destination_Type: Sigma Cabs divides any destination into one of the 14 categories.

● Customer_Rating: Average of lifetime ratings of the customer till date

● CancellationLast1Month: Number of trips cancelled by the customer in last 1 month

● Var1, Var2 and Var3: Continuous variables masked by the company. Can be used for

modelling purposes

● Gender: Gender of the customer

● SurgePricingType: Target (can be of 3 types) - DV

How Surge pricing works

● Demand for rides increases There are times when so many people are requesting rides that there aren’t enough cars on the road to help take them all. Bad weather, rush hour, and special events, for instance, may cause unusually large numbers of people to want to request a ride with Sigma all at the same time.

● Prices go up In these cases of very high demand, prices may increase to help ensure that those who need a ride can get one. This system is called surge pricing, and it lets the app continue to be a reliable choice.

● Riders pay more or wait Whenever rates are raised due to surge pricing, the app lets riders know. Some riders will choose to pay, while some will choose to wait a few minutes to see if the rates go back down.

---
# Conclusion
Started with loading the data so far we have done EDA , null values treatment, encoding of categorical columns, feature selection and then model building.

So far I have modelled on

* Logistic Classifier
* SVM Classifier
* Random Forest Classifier
* XGBoost classifier

In all of these models accuracy revolves in the range of 70 to 73%.
And there is no such improvement in accuracy score even after hyperparameter tuning.

So the accuracy of best model is 73% which can be said to be good for this large dataset.

