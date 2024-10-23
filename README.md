Business Problem:
The dataset contains multiple features related to customers, all of which are to be used to determine whether a customer will subscribe and pay to the provided service or not.

Descriptive and Inferential Statistics:
Based on the data, about 89% of the entries said no to the subscription while 11% of the entries said yes. There were no missing values within the dataset. 

Findings:
Based on the results, either the KNearestNeighbors model or the Decision Tree model would be the most optimal model for determining a customer's subscription. While all the models had very similar test scores,
KNN and Decision Tree models had the shortest fit times with only a 0.03 second difference between them (0.04 and 0.07 seconds respectively). Logistic Regression required about half a second while SVC required 5.5 seconds.

Next Steps and Recommendations:
With a select number of features being used to train the models, a next step would be to observe any common features among customers that subscribe and gain further confirmation of whether these specific
features increase the likelihood of subscription.
