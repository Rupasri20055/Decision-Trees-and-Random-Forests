# Decision-Trees-and-Random-Forests
Task 5: Decision Trees and Random Forests

About this Task:
Hey! In this task, I worked on the Titanic dataset again, but this time to explore tree-based models like Decision Trees and Random Forests for classification problems. The goal was to predict passenger survival using these models and see how tree-based algorithms work.

 What I did in this task:
 
1️ Imported the Titanic dataset using Pandas.

2️ Checked for missing values and handled them — filled Age with median and Embarked with mode.

3️ Encoded categorical features like Sex and Embarked into numbers.

4️ Selected important features (Pclass, Sex, Age, Fare) and set Survived as the target.

5️ Split the dataset into training and test sets (80-20 split).

6️ Trained a Decision Tree Classifier using sklearn.tree.DecisionTreeClassifier().

7️ Visualized the Decision Tree using plot_tree() to understand the splits and rules.

8️ Controlled overfitting by setting max_depth=3 and checked how it impacted accuracy.

9️ Trained a Random Forest Classifier and compared its accuracy with the Decision Tree.

10 Checked feature importances using feature_importances_ from Random Forest and plotted a bar graph.

11 Evaluated the models using cross-validation with 5 folds for Random Forest to get a reliable accuracy estimate.


