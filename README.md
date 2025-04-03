# CrimeCheck

The Project aims to present predictive models on the likelihood of arrest in a crime incident using some key factors that would influence arrest outcomes based on historic crimes and inspects the predictive power of key features: Primary Type, Location Description, Year, for determining the probability of the Arrest and No Arrest outcomes in crime incidents.

Logistic Regression posted a moderate accuracy of 53%, with high precision for No Arrest but really poor for Arrest, accompanied by low F1-scores and precision. In contrast, it had the best recall for Arrest, though with a lot of misclassifications.

Random Forest showed considerable improvement and reached an accuracy of 88% with balanced precision, recall, and F1-scores for both Arrest and No Arrest. However, slightly lower recall for Arrest (0.61) suggests occasional missed cases.

The analysis explains Random Forest and strength of machine learning models to uncover nonlinear associations. Knowledge gained from the best insights of this present analysis

In the Next Notebook we will cover the Neural Network Model to understand different metrics for Arrest and No Arrest by including two new spatial features from the dataset.
