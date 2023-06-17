
# Radon Monitoring for Earthquake Surveillance Using Machine Learning Methods
Major natural disasters like earthquakes have the potential to seriously affect both human life and property. One way to predict earthquakes is through soil radon monitoring. By considering the parameters that affect radon concentration in soil, various machine learning algorithms (Leverberg-Marquardt,Genetic Algorithm,Random Forest,Gradient Boost,ANN and LSTM) are used to predict the anamolous behavior of radon in soil,before and after the occurrence of seismic events.

## Overview
 A model is built to predict
the concentration of radon in the soil based on various parameters such as the radon emanation
coefficient, leak rate, decay constant, and diffusion coefficient. The model can be trained on
datasets to identify patterns and relationships and make predictions using the results. Soil
radon monitoring is an efficient technique for predicting earthquakes, and machine learning
can increase its usefulness by providing more accurate predictions.
## Motivation
Earthquakes are a major natural disaster that can cause significant harm to human life and property. Soil radon monitoring is one of the methods used in earthquake prediction, as increased
radon levels can indicate an upcoming seismic event. Uranium and radium, which are elements
that can be found in rocks, soils, and groundwater, undergo radioactive decay to produce radon.
Variations in radon concentration preceding earthquakes might indicate changes to the Earth’s
crust. Mathematical modelling of radon transport can help to understand geophysical processes.
Machine learning methods are being used to predict radon behaviour.


## Working Methodology

![Workflow](https://imgtr.ee/images/2023/06/17/YQp4B.png)


## Insights About Data
The data for finding space radon concentration is collected in an excel file where,
- C - Pore space radon concentration at a given time
- t -  Time at which measurement is taken 
- C0 - Minimum pore radon concentration
- C∞ - Maximum pore radon concentration
- 𝝀 - Radon decay constant (𝝀=𝟎.𝟐𝟏"x " 〖𝟏𝟎〗^(−𝟓) 𝒔^(−𝟏))

## Files 
- `Pso.py` : Operating cost for the usage of energy resources for each day is computed using PSO
- `bat.py`: Operating cost for the usage of energy resources for each day is computed using bat algorithm
- `Cost_Calculation.ipnb` :The estimated operating cost, power load and the day profile costs per unit of distributed generators (PV and WT) without MT
- `PLOT_codes.ipnb`: Contains various plots for comparing the results in the presence or absence of certain energy resources
- `MG_Hourly_data.csv`: Data from micro grid components collected every hour during the day

## Algorithm Used
- Levenberg Marquardt
- Genetic Algorithm
- Random Forest
- ANN
- Gradient Boost
- LSTM

## Packages Used
- Pandas 
- Numpy
- Matplotlib 


## Results

This study compares the performance of six models in predicting radon time series data.The LSTM model performed best with 97% accuracy, followed by random forest and gradient boosting models. 
Unknown parameters in the exponential equation were estimated, adding value to the analysis. Evaluation metrics provide a comprehensive picture of each model's performance. The LSTM model is the most suitable for predicting radon time series data, but other models may still have value depending on specific requirements.The study contributes valuable insights into radon transport mechanisms and modelling techniques.


## Documentation

[Documentation](https://drive.google.com/file/d/1X_JsPsaGT-veQuL-OcJa1fbk9YaPYZym/view?usp=sharing)

