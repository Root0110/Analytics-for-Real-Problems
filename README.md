# Unsupervised Stoll Sample Analysis in Hepatic Encephalopathy
### Background
In this project, I will study relative abundance data for microbes in stool samples collected from two sets of patients: 
those with cirrhosis but not HE (HE0 population), and those with cirrhosis who have developed HE (HE1 populations).
Microbes with significantly altered abundance levels would be identified between both populations and the ways in which these abundance levels change. 
Although such results will not directly answer the question of how HE develops in cirrhosis patients, they can help scientists and doctors to better direct their experimentation on how to map out the gut-brain axis.

### Data Science Algorithms:
1. __Bayesian Network__: 
To determine the quality of the analyzed stool samples given data on the Storage Temperature, 
Collection Method, and Lab Time Before Processing.
2. __Kolmogorov–Smirnov (KS) Test__: To find the p-calue of a two-sample KS test across HE0 samples v.s. HE1 samples.
3. __Dimensionality Reduction and Clustering__: 
Applying PCA to project the data onto a lower-dimensional subspace, and apply K-Means to identify subpopulations based on samples’ microbe abundance profiles.
