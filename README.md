# Brain-Injury
Four Classification Algorithms' Accuracy in Predicting Clinically Important Brain Injury
Data Science Tools 2 Course (Fall 2022)

Purpose: Understand the performance of four algorithms in predicting whether someone will have any acute brain findng revealed on CT, given their symptoms and risk factors. 
Scope of Work:
- Data Preparation: Preprocessing data and splitting/partitioning them into training and test sets.
- Data Analysis: Exploratory data analysis (EDA); model building, selection, and evaluation of four classification algorithms (Random Forest Classifier, K-Nearest Neighbors Classifier, Naïves Bayes, and Logisitic Regression).
- Data Visualization: Countplots and correlation heatmap for EDA; a table of accuracy, recall and precision scores for all tuned and untuned models.

As the lead and sole person working on the project, I completed all work.
All code was written in Python via Jupyter Notebook.


#### More Details

Description of Dataset:
  - The dataset, called “headInjury”, is one of the standard R datasets that can be pulled in R Studio. I’ve downloaded a csv file from GitHub (see Appendix A for documentation and general website). There are 3121 rows and 11 columns, and the data were simulated according to a simple logistic regression model to match roughly the clinical characteristics of a sample of individuals who suffered minor head injuries. The output variable is clinically important brain injury (“clinically.important.brain.injury”), and it is binary (e.g., 0 = not present, 1 = present). All ten input variables are categorical and binary; they include: age.65, amnesia.before (amnesia before impact), basal.skull.fracture, GCS.decrease (Glasgow Coma Scale decrease), GCS.13 (initial Glasgow Coma Scale), GCS.15.2hours (Glasgow Coma Scale after 2 hours), high.risk (assessed by clinician as high risk for neurological intervention), loss.of.consciousness, open.skull.fracture, and vomiting.

Conclusion:
  - The best algorithms for predicting the clinically important brain injury based on the accuracy metrics are the tuned Random Forest Classifier and untuned Logistic Regression models with the accuracy rate of 92%. However, the worst accuracy rate of all algorithms was 91.04%, which means that there is very little difference among the algorithms for accuracy. Based on the recall metrics, the Bernoulli Naïve Bayes is the best algorithm. However, I would use a bit of caution since it happens to have the worst precision metrics of all algorithms.
