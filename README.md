# Car Evaluation Dataset
This dataset comprises 1,728 records, each representing a car evaluation. Each evaluation includes 7 attributes, with 6 describing car characteristics such as buying price, maintenance cost, number of doors, passenger capacity, luggage boot size, and estimated safety rating. The seventh attribute indicates the overall evaluation of the car, categorized as unacceptable, acceptable, good, or very good.

**Handling Ordinal Inputs**

In addressing this problem, various methods were tested to handle features that are both numeric and considered ordinal due to their inherent meaning. A comparison was made between treating ordinal variables as numeric or categorical, each with its own set of advantages and disadvantages. Model performances were compared using both approaches to determine the most effective strategy.

**Applied Models**

Several models were applied to the dataset, including Decision Tree, K-Nearest Neighbor, Logistic Regression, Naive Bayes, and Support Vector Machine (SVM). Nested cross-validation was utilized with different hyperparameters for each model, such as maxdepth in Decision Tree, k value in kNN, and c value in Logistic Regression. The goal was to identify optimal hyperparameters that maximize performance on the training data while avoiding overfitting by comparing results on a validation dataset. Additionally, the robustness of the models was assessed using cross-validation to ensure effectiveness on unseen data.

**Exploration**

Analysis of the models consistently revealed that numerical inputs tend to outperform categorical ones across various performance metrics and model classes. This underscores the efficiency and effectiveness of using numerical inputs for car evaluation tasks. Furthermore, deeper examination of the classification task highlighted Decision Tree and SVM models as particularly adept, demonstrating superior classification performance tailored to this specific application.
