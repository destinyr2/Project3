# Estimating Prediction Model Performance on A New Target Population: A Transportability Analysis
This project includes a transportability anysis where a logistic regression model was developed on the source population Framingham study
data to predict the probability of experiencing the outcome of cardiovascular disease and evaluated in a new target population (NHANES 
data). The NHANES data sample did not include the observed outcome variable for cardiovascular disease. The Framingham study data was split 
into a training set for model development and a test set to validate the model, or measure how the model performs on unseen data. The Brier
score was then used to measure the accuracy of predicted probabilities. The model performance was estimated in the new target population by
creating an outcome indicator variable "S" where,  S=1 indicates the probability of being in the Framingham study data and S=0 indicated the
probability of being in the NHANES data. The inverse-odds weights were used to calculated the estimate for the Brier risk. The target 
population data was simulated using individual level data from the NHANES survey and the model's performance evaluated from the estimator for the Brier risk.
