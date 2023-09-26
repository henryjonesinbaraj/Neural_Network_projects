# Neural_Network_projects

In this analysis, I conducted an exploration of the dataset related to Algerian forest fires, followed by preprocessing and modeling tasks. My primary objective was to predict the Fire Weather Index (FWI) based on various environmental features.

Data Preparation and Cleaning I began by loading and exploring the dataset, checking for missing values and gaining an initial understanding of the data.

I cleaned the 'Classes' column, which represents fire occurrence, by stripping spaces and converting class labels to numerical values (0 for no fire and 1 for fire).

I also dropped redundant columns such as 'day,' 'month,' and 'year' since they didn't significantly contribute to the analysis.

Model Building and Evaluation I developed a Linear Regression model to predict the Fire Weather Index (FWI) based on the remaining environmental features.

After splitting the dataset into training and testing sets, I standardized the features using StandardScaler.

Subsequently, I trained and evaluated the model using metrics such as Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared (R2) on the test data.

The model's performance on the test data demonstrated promising results, with metrics indicating how well it fits the data.

Recommendation:

Logistic regression cannot be applied because our target variable is not categorical

Ridge regression is a solution to handle multicolinearity by reducing coefficent of correlated features. since our dataset has some multincolinearity. ridge regression might rpoduce a better model.

Lasso will address both multicolinearity and feature selection problem.

My recommedation would be ridge regression for this data set to give a better model.
