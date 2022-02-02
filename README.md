# COVID-19 Factors Project

### Analysis of socioeconomic and environmental factors leading to the spread of COVID-19

The goal of this project was to explore the effect of several covariates on COVID-19 cases and deaths across 50 U.S. states in 2020. We used a dataset collected by the authors of the following paper:

    Roy, Satyaki, and Preetam Ghosh. “Factors affecting COVID-19 infected and death rates inform
      lockdown-related policymaking.” PloS one vol. 15,10 e0241165. 23 Oct. 2020,
      doi:10.1371/journal.pone.0241165
      
For the project, we did the following:

1) Performed a Mann-Whitney U hypothesis test to determine if there is a statistically significant difference between COVID-19 cases and/or deaths between densely and sparsely populated states.

2) Used ridge regression to determine which of several covariates contributed the most to COVID-19 cases/deaths.

3) Clustered the states based on shared characteristics.
    - We used principal component analysis to reduce the dimensionality of the data
    - We used the silhouette method to determine the optimal number of clusters present in the rotated data
    - We used k-means clustering to cluster the states
    
Code for the project can be found in [COVID-19_Factors.ipynb](COVID-19_Factors.ipynb). The final project report can be viewed in [COVID-19_Factors_Report.pdf](COVID-19_Factors_Report.pdf).
