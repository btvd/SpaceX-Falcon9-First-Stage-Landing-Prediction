## SpaceX-Falcon9-First-Stage-Landing-Prediction

<p align="left">
  <img width="500" height="300" src="https://images.squarespace-cdn.com/content/v1/59122c863a0411116f0625a6/1555095344123-3JKAX5M17W0C3YYJQ2GL/giphy+%2874%29.gif?format=500w">
</p>

## Introduction

In this project we will collect and transform data about SpaceX Falcon 9 rocket launches to use it for building predictive model of first stage landing success.

We will follow the Data Science methodology involving [data collection](https://github.com/btvd/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/master/SpaceX_data-collection-api.ipynb), [data wrangling](https://github.com/btvd/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/master/SpaceX_Data%20wrangling.ipynb), [exploratory data analysis](https://github.com/btvd/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/master/SpaceX_eda_sqllite.ipynb), [data visualization](https://github.com/btvd/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/master/SpaceX_eda-dataviz.ipynb), [model development](https://github.com/btvd/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/master/SpaceX_Machine%20Learning%20Prediction.ipynb), [model evaluation](https://github.com/btvd/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/master/SpaceX_Machine%20Learning%20Prediction.ipynb), and [reporting]([PASTW link](https://github.com/btvd/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/master/RB_ds_capstone-presentation.pdf) results to stakeholders.

## Business Problem

Current price of SpaceX Falcon 9 rocket launch is 67 million dollars. Other providers give price like 165 million dollars each. The big difference in prices comes from the ability of SpaceX to reuse their first stage capacities. Therefore, if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if SpaceX competitor wants to bid against SpaceX for a rocket launch.

## Objective

- To apply data science toolkit and machine learning in order to accurately predict the likelihood of the first stage rocket landing successfully, and thus determine the cost of a launch.
- Explore the data in order to obtain more insight from the data.

## Business metric
Classification accuracy - number of correct prediction divided by the total number of prediction defined as:
$$Accuracy = \frac{TP+TN}{TP+FP+TN+FN}$$

![Confusion matrix](https://github.com/btvd/SpaceX-Falcon9-First-Stage-Landing-Prediction/blob/master/plots/Confusion%20matrix.PNG)

## Deliverables
- Accurate predictive algorithms
- Business case report to stakeholders
