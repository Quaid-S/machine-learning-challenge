# machine-learning-challenge

Findings:

For this project, I tested a number of selection models including: logistic regression, random forest, decision tree, knn, and svm. The testing scores of which are as follows:

logistic regression: 0.653
random forest: 0.912
decision tree: 0.872
knn (k=15): 0.661
svm: N/A

Based on these results, we can confidently say the random forest classifier produces the highest degree of accuracy in regards to this data set and the parameters set. For the SVM model, I was unable to create any set of parameters and features that either produced a reasonable test score or didn't take multiple days to process. In hindsight, It seems that the SVM model is rather limited by size, but with an appropriate set of data and parameters, may produce satisfying results.

Tuning: I tuned both the tree classifiers in order to perform optimal feature selection, and used those features for the other models as well, however for the SVM I did have to reduce the number of features further for the sake of time. 

Scaling: I also scaled the data, but found that the model accuracy for several classifiers was slightly reduced by this.
