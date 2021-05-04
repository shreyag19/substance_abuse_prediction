# Substance Abuse Analysis & Predictions
Database contains records for 1885 respondents.​Our dataset had 12 different features, 5 of them were general information on a person and the other 7 were personality scores that described that person. The general information features were age, gender, level of education, ethnicity, and country of residence; while the 7 personality scores were, neuroticism, extraversion, openness to experience, agreeableness, conscientiousness, impulsivity, and sensation seeking.

Drug, Wikipedia URL: https://en.wikipedia.org/wiki/Drug

## Results:
The data set contains seven categories of drug uses: ‘Never used’, ‘Used over a decade ago’, ‘Used in last decade’, ‘Used in last year’, ‘Used in last month’, and ‘Used in last week’. We form four problems based on four dichotomies of these classes: the decade-, year-, month-, and week-based user/non-user separations. We identified the relationship between personality profiles (NEO-FFI-R) and drug consumption for the decade-, year-, month-, and week-based classification problems. We evaluated the risk of drug consumption for each individual according to their personality profiles. This evaluation was performed separately for each drug for thedecade-based user/non-user separation. We also analyzed interrelations between the individual drug consumption risks for different drugs.

In conclusion, the best classification methods we found when running against the dataset were Decision Trees, kNN, Support vector machine, and AdaBoost. Our very
best classifier was Decision trees, even though it did not have the highest accuracy, its f1 score was high. When running against individual drugs we saw much higher accuracies for a handful of drugs, regardless of the classification method used. This is because the drugs were either very commonly used or not very common at all. So if the usage for a particular drug was on either extreme we found that the algorithms usually had a much higher accuracy.
