<!-- This is the markdown template for the final project of the Building AI course, 
created by Reaktor Innovations and University of Helsinki. 
Copy the template, paste it to your GitHub README and edit! -->

# Determinants of well-being in the world and economic development

Building AI course project

## Summary
 
The pursuit of happiness is one of the most important human needs around the world. This is a complex problem, depending on socio-political and economic decisions in a given country. The aim of the study is to determine what factors influence the level of well-being and to compare and select the regression algorithm that allows for the best prediction of its changes.

Building AI course project

## Background

The pursuit of happiness is one of the most important human needs around the world. This is a complex problem, depending on socio-political and economic decisions in a given country. The aim of the study is to determine what factors influence the level of well-being and to compare and select the regression algorithm that allows for the best prediction of its changes.

## How is it used?

The work uses open data source from Kaggle, and originally from a Gallup survey, the results of which concern the assessment of the quality of life. The regression modeling study was performed using R and the tidymodels package, comparing 23 different models. People feel the greatest level of well-being when they can live a long, healthy life and have their material needs met. The model with the xgboost algorithm and appropriately selected parameters turned out to be the best in predicting well-being.

Data Set Feature Descriptive Analysis:
![Data Features](/w16.png)

World Happiness Ranking by Country:
![World Happiness Ranking](/w19.png)

Regression Models Ranking by RMSE metric (the lower the better one):
![Regression Models Ranking](/w23.png)
Here, the boosted tree regression model with tuned hyperparameters was the best one.

## Data sources and AI methods

For this empirical research, the World Happiness Report 2021 was used to get data set from the Kaggle data sets, owned by Mathurin Aché. [Kaggle dataset](https://www.kaggle.com/mathurinache/world-happiness-report-2021) - the data file used in this research study was obtained on October 3, 2021. These data were only obtained by Mathurin Aché from the original dataset from the World Happiness Report 2020 (Helliwell et al., 2020). The downloaded dataset from Kaggle contains 1949 rows of data.

## Challenges

This was my first AI project for purpose of university studies.
This is a common generic model, not separated by country due to not having a large enough dataset, so more developed countries may impact the results for the less one.

## What next?

The research conducted in this study also allowed for the identification of opportunities for further research. Adding an auxiliary variable "continent" could help capture cultural differences between groups of countries. Ideas for future research also include examining trends over time - separately for each country - by creating separate models for each country (this requires obtaining more data from a given country).

## Acknowledgments

* The Kaggle data sets, owned by Mathurin Aché
* Authors of World Happiness Report
