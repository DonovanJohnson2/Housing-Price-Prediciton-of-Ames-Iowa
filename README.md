# Personal-Projects
This dataset is a collection of residential real estate sales from 2006 to 2010 collected by
the Ames, Iowa Assessor Office. The dataset has a total of 2,930 observations and 80 variables. Out of
the 80 variables, 20 are continuous, 14 are discrete, 23 are nominal, and 23 are ordinal. For the class
final project, the objective was to determine which factors, qualitative or quantitative, are important
features for the prediction of home sale prices. Furthermore, the team developed statistical models to
predict home sale prices, specifically for homes in Ames, Iowa. Prior to analysis, exploratory data
analysis was conducted to explore the data and discover patterns, spot anomalies, and present
graphical representation that is beyond the formal modeling methods. Additionally, the dataset was
cleaned and transformed for prediction. One of the challenges of working with this dataset, oddly, was
also one of its strengths. The dataset has an extensive record of each sale. The large number of
variables in the dataset (80) are quality and quantity attributes of each property. While this was a
great problem to have, the main challenge was to reduce the number of variables necessary for
predicting house sales without compromising prediction power or violating model assumptions. For
analysis, the team utilized forward stepwise regression and random forest regression. Lastly, the team
selected the final predictive model and compared the predicted home sale price with the actual sale
price of each property. Ultimately, the best predictive model had six variables, which are: overall
material finish and quality, above ground living area (measured by square feet), neighborhood, total
basement square feet, year remodeled date, and year built. The most important predictor of sale price
was above ground living area, and the second most important factor was the overall material finish
and quality of the home. The root mean square error of the final model was 0.05681 (on a log10 scale)
and mean absolute error was $17,948.90 (on actual dollar scale).
