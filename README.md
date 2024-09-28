**NYC Taxi Tipping Prediction Using Random Forest & XGBoost**

**Project Overview**

This project, contracted by the New York City Taxi & Limousine Commission (TLC), aims to predict whether a taxi rider will be a generous tipper (tip ≥ 20%). The objective is to balance the interests of both taxi drivers and passengers by helping drivers anticipate generous tipping. The Random Forest model provided the best predictive performance with an F1 score of 0.7235.

**Business Understanding**

The New York City TLC sought to build a machine learning model to predict tipping behavior, focusing on generous tippers. Initially, predicting non-tippers was considered but was rejected due to ethical concerns. This prediction can help drivers better serve passengers and optimize earnings.

_**Stakeholders:**_

NYC Taxi & Limousine Commission

Taxi Drivers in New York City

The goal is to help drivers anticipate high tippers and enhance passenger-driver relationships.

**Data Understanding**

The dataset included various factors such as:

Trip itinerary

Predicted fare amount

Time of day

These factors were hypothesized to have a significant relationship with tip amount, and indeed, the model demonstrated strong predictive power for tipping behavior.

**Data Limitations:**

The data lacked granular user and driver-level details, such as past tipping behavior.

**Modeling and Evaluation**

We compared two models—Random Forest and XGBoost. Both models performed well, but Random Forest outperformed slightly in terms of accuracy and F1 score.

**Model Results:**

Random Forest F1 Score: 0.7235

The model can reasonably predict which riders are likely to tip generously, based on factors like fare and time of day.

**Conclusion**

The model shows promise for predicting generous tippers and can help optimize taxi drivers' earnings strategies. However, further improvements are possible with more detailed data.

**Next Steps:**

Beta Test: Implement the model in a real-world setting to gather feedback from taxi drivers.

Data Enrichment: Collect more granular data, such as past tipping behavior and user-specific insights.

Cluster Analysis: Use K-means clustering to derive deeper insights from the dataset.
