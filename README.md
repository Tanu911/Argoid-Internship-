# Argoid-Internship-
Here I am to summarize my Assignment.

I have used K-Means Clustering as my model for prediction of items.
Since we had to suggest two items to a person with every purchase, based on the previous purchases of a huge customer base, we could use the features given in the data.
So, I first analyzed the data and then I made my own model from the very scratch as the data was very huge for any in-built function. Because they form matrix within of that size, which was an issue with this massive data!!!!

I used TransactionId and ItemCode in my model. So first to access them, I built two dictionaries to simplify their values. Where I gave ascending numbers to the unique values (Total unique ItemCode = 3407; total unique TransactionId = 25900).
Then I plotted these two values.

Then I assigned 3407 centers to start with. Then I built my model and started with those centers and only stored the value of the latest centers. 
Then I plotted the new centers with the old ones for comparison.
Then I built two functions: Predict and Itemname.


And then stored my solutions in Predictions.csv.


The overall model is based on the pattern of choices made by the customers while buying things.
