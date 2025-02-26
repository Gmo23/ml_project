# ml_project

Standard classification project on generated data for the purpose of practice and application of techniques. Specific focus is put on investigating how model performance varies for dimensionally reduced vs full dimensional data. 

Begins with exploratory data analysis to check shape, normality and multicolinearity of the data which reveals data is good.

PCA is performed, importance of certain features is checked and it is found that a large number are needed to explain most of the variance of the data.

To be stringent initial model uses # of PC's as a hyperparamter and it is confirmed that all are needed (i.e. full dimension)

Final model is a logistic regression using polynomial features (to combat a lack of linear seperability) with grid search cross-validation. Achieving a test score of 94%. 


