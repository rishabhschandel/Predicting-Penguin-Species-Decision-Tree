# Predicting-Penguin-Species-Decision-Tree

1. Trained a decision tree model on penguin dataset(from kaggle) to predict the species of penguin. 
2. Did exploratory data analysis(EDA) to understand data using feature distrubtions and deduced relationship between features and species using correlation, heatmap, pairplots.Determined predictors from pairplot that would be best able to classify species
3. Did Data preprocessing by filling in in missing values, using grouby statistics and values of other features.Dropped rows which had more than 3 missing values. Converted categorical features into numerical features using onehotencoding.
4. Acheived an accuracy of 97% on test set using default parameters. Achecived good precision and recall.
5. Tried pruning the tree to check whether the tree has overfitted. Utilized max_depth,max_leaf_node hyperparameters.
6. Tried both Gini Impurity and Entropy as criterion.
7. Used Random Forest to improve accuracy, acheived an accuracy of 98%. 
