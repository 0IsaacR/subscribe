# subscribe
In this project, we looked closely at the marketing data from UCI Bank Marketing dataset. We needed to create a model that can classify if someone will be subscribing to a banks term deposit.

Overall the dataset is clean. The main issue was encoding the dataset. This dataset had a lot of object type features making the encoded dataset pretty big column wise. 

Next we established a baseline model and ran an accuracy test. With no adjustments and defualt settings the model achived close to 90% accuracy. After running a gridsearch and PCA, I found the accuracy to improve very slightly. The gridsearch took approximately 10 minutes, this can be an issue for much larger datasets.

Finaly, I determined logistic regression was the way to go. I ran a classification report and displayed a ROC curve.
