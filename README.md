# Car-Evaluation-Prediction
This dataset has 1728 records, each record representing a car evaluation. Each car evaluation is described with 7 attributes. 6 of the attributes represent car characteristics, such as buying price, price of the maintenance, number of doors, capacity in terms of persons to carry, the size of luggage boot, and estimated safety of the car. The seventh variable represents the evaluation of the car (unacceptable, acceptable, good, very good).

Handling Ordinal Inputs
In this problem, I also tested different methods to handle the features, which are currently reppresented as numeric features however, it is also considered as ordinal due to underlying meaning.
Numeric vs. Categorical Approach: Discuss the advantages and disadvantages of treating ordinal variables as either numeric or categorical. Compare the performances of models using both approaches to determine which was more effective.

Model Applied
Decision Tree
K-Nearest Neighbor
Logistic Regression
Naive Bayes
Support Vector Machine (SVM)
Nested cross-validation
With different hyperparameter: maxdepth in decision tree, k value in the kNN model, and c value in Logistic regression, kernel and C in SVM then finalized the optimal hyperparameter to get highest performance on traning data but ensure not commmit overfitting by comparing with performance on validation dataset. After that, I would like to check the robust of the model by using cross-validation to check whether my model work well on the unseen data.

Exploration
The comprehensive analysis of our models indicates a consistent trend: numerical inputs generally outperform categorical ones in performance metrics across most models and various classes. This trend underscores the greater efficiency and effectiveness of numerical inputs for car evaluation purposes. Furthermore, a deeper dive into the classification task reveals that Decision Tree and SVM models exhibit superior classification prowess, distinguishing themselves as particularly effective for this specific application.
