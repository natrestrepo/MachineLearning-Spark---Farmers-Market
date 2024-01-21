# MachineLearning-Spark---Farmers-Market
Using the Spark ML pipeline to build a model to classify a Farmers Markets dataset and to predict the price of a diamond based on the available features.

Assigment completed for Big Data course at University of Waterloo. The published notebook can be found using the following link: https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/2076258431253745/1790176459232697/8071911021850060/latest.html


### Learning Outcomes
- Use ML piplenes
- Improve a Random Forest model
- Perform Hyperparameter tuning

### Question 1:
In our learning from this module, we have identified a fairly significant link by leveraging the ML pipeline, a more sophisticated model, and better hyperparameter tuning. However these results are still a bit disappointing. With that being said, we're working with very few features and we've likely made some assumptions that just aren't quite valid (like zip code shortening). Also, just because a rich zip code exists doesn't mean that the farmer's market would be held in that zip code too. In fact we might want to start looking at neighboring zip codes or doing some sort of distance measure to predict whether or not there exists a farmer's market in a certain mile radius from a wealthy zip code.

With that being said, we've got a lot of other potential features and plenty of other parameters to tune on our random forest so play around with the above pipeline and see if you can improve it further! Note: adding a feaure for the distance measure is just an example and not a mandatory change to improve the model's performance. We also aren't concerned about if the model's perforamnce is actually improved! We simply want to see if changes have been made to the code for possible improvements.

Learn mode about the Farmers Markets dataset, here: https://catalog.data.gov/dataset/farmers-markets-directory-and-geographic-data


#### Question 2
Using the Apache Spark ML pipeline, build a model to predict the price of a diamond based on the available features.
