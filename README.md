# Data Analytics Project
This repository contains the folders of the Data Analytics Project. Our topic for the project is "Data Analytics and Forecasting of COVID-19 Pandemic"

## Introduction
The outbreak of COVID-19 has affected over 218 countries around the world. The number of infected and deceased patients have been increasing at an alarming rate. It has therefore become necessary for the inculcation of forecasting techniques to develop better strategies and taking preventive decisions. In this study, we focus on in-depth analysis and forecasting techniques to predict the number of cases in the foreseeable future. These predictions might help to prepare against possible threats and consequences.

## Exploratory Data Analysis
For EDA, please refer to [DA_Visualizations2(Phase_1)](https://github.com/sreesh2411/DA_Project/blob/main/Notebooks%20%2B%20Data/DA_Visualizations2(Phase_1).ipynb).

## Visualizations
The Visualizations are done in [DA_Visualizations(Phase_1)](https://github.com/sreesh2411/DA_Project/blob/main/Notebooks%20%2B%20Data/DA_Visualizations(Phase_1).ipynb). There are some animations present in the notebooks of EDA and Visualizations too have animations present in them. Hence, viewing them in a notebook viewer (Jupyter/Google Colab) would be optimal.<br>
Some [Visualizations](https://github.com/sreesh2411/DA_Project/tree/main/Visualizations) are already taken out from the notebook:
* [Bar Plots](https://github.com/sreesh2411/DA_Project/tree/main/Visualizations/Bar%20Plots) 
* [Bubble Charts](https://github.com/sreesh2411/DA_Project/tree/main/Visualizations/Bubble%20Charts)
  * [Continent-Wise](https://github.com/sreesh2411/DA_Project/tree/main/Visualizations/Bubble%20Charts/Continent%20Wise)
  * [Country-Wise](https://github.com/sreesh2411/DA_Project/tree/main/Visualizations/Bubble%20Charts/Country%20Wise)
* [Geo Plots](https://github.com/sreesh2411/DA_Project/tree/main/Visualizations/Geo%20Plots) 
* [Advanced Visualiaztions](https://github.com/sreesh2411/DA_Project/tree/main/Visualizations/Advanced%20Viz) 
  * [USA](https://github.com/sreesh2411/DA_Project/tree/main/Visualizations/Advanced%20Viz/USA)
  * [India](https://github.com/sreesh2411/DA_Project/tree/main/Visualizations/Advanced%20Viz/India)
* [Word Cloud](https://github.com/sreesh2411/DA_Project/tree/main/Visualizations/Word%20Cloud) 

## Sources for Data
Data was majorly compiled from:
* https://github.com/CSSEGISandData/COVID-19 : John Hopkins Dataset
* https://ourworldindata.org/coronavirus-data : Our World in Data Dataset

## Modeling/Forecasting
The forecasting of the cases were done with two compartmental model : SIR (Susceptible, Infectious, Recovered) and SEIHRD (Susceptible, Exposed, Infectious, Hospitalized, Recovered, Dead).
![SIR Model](https://www.lewuathe.com/assets/img/posts/2020-03-11-covid-19-dynamics-with-sir-model/sir.png)

## For Execution
All notebooks are present in the ```Notebooks + Data``` Folder with the datasets.<br>
For Phase 1 (EDA/Visualizations):<br>
* [DA_Visualizations(Phase_1)](https://github.com/sreesh2411/DA_Project/blob/main/Notebooks%20%2B%20Data/DA_Visualizations(Phase_1).ipynb)
* [DA_Visualizations2(Phase_1)](https://github.com/sreesh2411/DA_Project/blob/main/Notebooks%20%2B%20Data/DA_Visualizations2(Phase_1).ipynb)

For Phase 2 (Modeling/Forecasting):<br>
* [DA_Model+Forecasting(Phase_2)](https://github.com/sreesh2411/DA_Project/blob/main/Notebooks%20%2B%20Data/DA_Model%2BForecasting(Phase_2).ipynb) (Modeling using China Data)
* [DA_Model+Forecasting2(Phase_2)](https://github.com/sreesh2411/DA_Project/blob/main/Notebooks%20%2B%20Data/DA_Model%2BForecasting2(Phase_2).ipynb) (Forecast using SIR and SEIHRD)





