## Logistic Regression with Predictive Modelling

In our project we have developed a logistic regression model with 46 Subterranious samples, 43 Multiplex
samples and the 199 Unknown samples.Initially we have done formatting and cleaning of our given data
set which were subdivided into three csv files and then we did some common exploratory data analysis like
pairs plot, scatterplot, boxplot, density plot, correlation analysis between numeric variables etc. From our
exploratory data analysis, we have drawn several conclusions about the symmetry, skewness and distribution
of our 3 separate data set of Multiplex, subterranious and unknown species. After that, we Prepared a
two preliminary models with two and three variables using generalized linear regression model. From our
generalized linear model, We can see that the coefficients of Vole Skull Height (Scale of 0.01 mm) and Vole
Skull Weight (Scale of 0.01 mm) are significant (p < 0.05), while the coefficient of Vole Skull Length (Scale
of 0.01 mm) is non-significant considering three variables. Our model with 2 variables has AIC of 60.4188
and model with three variables has the smallest AIC(56.87). So based on AIC, we have selected the model
with the lowest AIC. Using the p-value in the ANOVA output, we rejected the null hypothesis as the p-value
was less than the significance level and concluded that at least two of the species parameters are different
from each other. Also we have done QQ plotting of our regression model and saw that the the data was
normally distributed for our model except some outliers like 24,241 and 271.After moidelling we have done
cross-validation for the models and checked model accuracy. Our cross validation showed that the full model
and the model based of width and height are effectively the same for the LOOCV. Furthermore, the model
with just Vole Skull Width and Vole Skull Height (“WH”) is better than the models with Vole Skull Length
in the model. Lastly, we have predicted for the unknown species. out of 197 unknown samples, there are 82
multiplex data and 115 subterranious data. The error rate of our model is 58.37%. .
