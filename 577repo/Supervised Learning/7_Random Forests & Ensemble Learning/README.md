Ensemble Methods







1) Bootstrapping. This resampling technique is random sampling with replacement from the training data. When one does this many times over, we get bagging. Bagging (bootstrap aggregating) involves training the same base learning algorithm on multiple subsets of the data. From that, we take the combined predictions (aggregation) and use it as a single prediction. This is barely better than random guessing, and honestly how I feel in my higher level math classes sometimes. The key idea is that it reduces the variance of a model by aggregating all of the individual subsets.


2) Random Forests. This ensemble method combines multiple decision trees, where each one is a subset of the training data and inputs. Similar to bagging, individual predictions are aggregated together to produce a final result. 


3) Boosting