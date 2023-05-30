# Kickstarter_CMPE-257

### About Kickstarter
Kickstarter, founded in 2009, is an online platform connecting "creators" with funding to pursue their projects by allowing them to pitch their ideas to potential backers who can pledge money to support the project.

### About the project
This project focuses on developing a classifier to predict the success or failure of Kickstarter campaigns in achieving their fundraising goals. We will use a dataset that contains information on Kickstarter campaigns, perform exploratory data analysis (EDA), and clean the data. The dataset includes features such as funding goals, backers, and project categories. The project will also determine if any features need to be dropped to optimize the classifier's performance. We have used various clasifiers such as Decision Tree, Ensemble techniques like Bagging, Adaboost, XGBoost and Random Forest, MLP, SVM, Naive Bayes and KNN. Ultimately, the goal is to develop a reliable classifier that can assist in predicting the success or failure of Kickstarter campaigns, providing valuable insights to both creators and backers.

### About the dataset
We have used two datasets "kickstarter_dataset_full.csv" and "kickstarter_data_with_features.csv". There are minor differences between both the datasets like few columns are not present in "kickstarter_data_with_features.csv" which could give us valuable information and are present in "kickstarter_dataset_full.csv". However, we did not eliminate the dataset and continued performing our experiments on both.

### Result
From our experiments, we see that XGBoost algorithm gives the best accuracy score of 99.37%
