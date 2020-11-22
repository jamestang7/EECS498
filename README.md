# EECS498
EECS498 project 2 

AIS data interpolation
***

**Please download the code and put it under the directory with AIS dataset for testing and modification.**

# [AIS dataset](https://marinecadastre.gov/ais/)

The Automated Identification System (AIS) is an automated system for identifying and tracking marine vessels’ locations. AIS is composed of a transponder attached to each ship along with coastal and satellite-based receivers, providing useful data for the EPA. AIS is used for numerous functions such as Vessel Traffic Services (VTS), Commercial Fishing Monitoring, and Maritime Security. The NVFEL utilizes the AIS research to model marine emissions and incorporates the data into overall emissions and air quality models for the US territory. However, the AIS dataset is inherently noisy and incomplete, and there is an overwhelming amount of data.
Our long-term goal is to develop models and use data science techniques to handle these sparse and high dimensional datasets. We aim to efficiently impute missing data to track vessels moving within the US coastal waters properly. The better we can model these datasets, the better we can model emissions. We plan to achieve these goals through two specific aims:

## Aim 1 
– To properly handle anomalies and missing data. In other words, we want to try and clean the dataset so that we can effectively use it for interpolation in our second aim. We plan to use angle-based outlier detection and autoencoders to detect anomalies. To handle missing data, we plan to use several techniques, such as regression and stochastic imputations. We hypothesize that autoencoders and stochastic imputations will best clean the data for interpolation.

## Aim 2 
– To determine the optimal interpolation method for given emissions data among a myriad of parametric curve-fitting techniques, including but not limited to: Non-linear Least Squares, B-Splines, Bézier curves, and Bézier splines. We hypothesize that a Bézier spline will perform the best, yielding the lowest test error rate estimation.

# Acknoledgement
I want to express my sincere gratitude to Arav, Hannah for their relentless collaboration and creativity, to Jonathan for his patiance and guidance on this project.
