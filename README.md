# Regression
Includes: Linear, Logistic, Multinomial, Decision Tree, Ridge, Lasso, Elastic Net, SVM, Ordinal, Poisson, Bayesian, Negative Binomial

## EDA
In this section, I performed an exploratory data analysis (EDA) on the Abalone dataset to get a deeper understanding of the data and its distributions. The steps included:
- Data loading and cleaning: The dataset was loaded, and basic cleaning steps were taken, such as converting the "Sex" variable from character to factor.
- Descriptive statistics: Basic summary statistics were generated for all variables to provide an overview of the distribution of the data.
- Skewness and kurtosis check: I analyzed the skewness and kurtosis of the numerical variables to assess their symmetry and the presence of outliers.
- Visualizations: Histograms and boxplots were created for key variables like the abalone's longest shell, diameter, height, and weight, to visualize their distributions and outliers.
- Correlation analysis: I used a correlation matrix and plotted it to examine relationships between variables, particularly focusing on the relationship between different weight measures and the number of rings.
## Linear
In the linear regression section, I built models to predict the diameter of the abalone based on the number of rings and other factors.
- Basic linear model: A simple linear regression model was constructed to predict the abalone’s diameter using the number of rings as a predictor. The model explained about 33% of the variability in the diameter.
- Adding sex as a predictor: I expanded the model by adding "Sex" as an additional predictor, increasing the model's explanatory power to about 45%.
- Interaction terms: I introduced interaction terms between "Rings" and "Sex" to see if the relationship between rings and diameter varied by sex. This improved the model further, accounting for 49% of the variance.
- Outlier detection: Using Cook’s distance and other metrics, I identified and removed influential points that were potentially skewing the results. After cleaning the dataset, the final model explained 56% of the variance in abalone diameter.

Each model was evaluated through standard diagnostic plots to ensure that the assumptions of linear regression were met.
