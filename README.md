# Practical-Application-III

Problem 11: Improving the Model

For banks attempting to use ML model to classify whether customers will sign up for long-term subscriptions and deposit money, I evaluate the consequence of false positive and false negatives.

1. False Positive - model predicts that a customer will deposit money, but in reality, they do not. The consequence is that the bank may spend resources on customers who ultimately do not subscribe, and this leads to wasted resources and potential opportunity costs.

2. False Negative - model predicts that a customer will not deposit money, but in reality, they do. The consequence is that the bank misses out great opportunities to follow up with potential customers who would have subscribed. This could result in lost revenuse and sales opportunities.

3. False negative is more detirmental in this situation, if bank fails to realize potential customers, the bank will miss out significant revenue opportunites. Although false positives lead to wasted resources, they do not directly result in lost sales, just inefficiency.

4. Avoiding false negatives is crucial because missing out on potential deposits (subscribing customers) can have a larger impact on the bank's profitability.

5. Recall is the metric to use, since it measure the proportion of actual positives (customers who subscribed) that were correctly identified by the model. Maximizing recall ensures that most potential subscribers are correctly identified, reducing the chances of missing out on revenue.

Summary: 
For my KNN modeling, the recall for "yes" is only 0.36. It is recommmended for further feature engineering and transformations, hyperparameters tuning to further improve this value, which ultimately could provide better prediction and insight on how to follow up with potential customers.
