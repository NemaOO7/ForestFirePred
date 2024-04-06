# Wildfire Prediction with Machine Learning

In light of escalating global temperatures and the consequential increase in wildfire incidents, this repository presents a novel approach to wildfire prediction using machine learning techniques. Our focus centers on harnessing the power of live fuel moisture content (LFMC) data obtained through advanced microwave remote sensing technology.

## Introduction

As the world grapples with the consequences of rising temperatures, the threat of wildfires looms larger than ever. Over recent decades, we've witnessed a surge in the frequency and intensity of these natural disasters. Early prediction of wildfires is paramount to effective risk management strategies.

Key to our predictive model is the utilization of live fuel moisture content (LFMC) data. LFMC measures the mass of water per unit dry biomass in vegetation, providing invaluable insights into fire susceptibility. This data, acquired through state-of-the-art microwave remote sensing techniques, is then processed and visualized as detailed maps.

### Problem Statement

Given an extensive image dataset, our objective is to forecast the likelihood of wildfire occurrence within predefined 8km x 8km grid cells over the next 15 days.

## Data Collection and Methodology

Our predictive model leverages LFMC maps obtained via the Google Earth Engine API, combined with ground truth wildfire data sourced from fire.ca.gov. We employ robust machine learning algorithms, including Support Vector Machines (SVM) and Random Forest, to analyze and predict wildfire occurrence within the specified grid cells.

![LFMC Map](https://github.com/manvendra-nema/LFMC_WildFire_Pred/assets/53614640/5662ab02-edbc-4e8b-bf9e-f5b9433e5397)

## Results and Insights

Through rigorous experimentation and analysis, our model achieved the following accuracies:

- Random Forest: 91.69%
- SVM: 80%

These results underscore the effectiveness of Random Forest in wildfire prediction tasks, providing valuable insights for future risk mitigation efforts.

## Dependencies

Ensure you have the following dependencies installed:

- Python 3.x
- scikit-learn
- pandas
- numpy
- matplotlib
- geopandas
- rasterio
- pyproj
- pycrs
- ray
- earthengine-api

Please make sure all dependencies are properly installed and up-to-date to replicate the results accurately.
