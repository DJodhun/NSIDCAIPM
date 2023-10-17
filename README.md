# NSIDC Arctic Ice Prediction Model

## Background
Machine Learning models can be used to predict the decrease in the amount of Arctic ice extent. According to the WWF, 13% of the Arctic sea ice is being lost per decade, and by their estimates there will be no ice by the year 2040. 

The aim of this project is to model the current (as of January 2023) extent of Arctic sea ice using Supervised Learning models and data from the National Snow and Ice Data Centre (NSIDC). The models used include linear and polynomial regression and an artificial neural network, which can be used to predict the Arctic ice extent for a given year, and determine the first year when the Arctic will be ice-free. The features used are the year, $CO_{2}$ concentration (using NASA data) and global average temperature. 

The models were created without the assistance of the standard suite of ML libraries in Python, meaning that each model was created from scratch, using the base mathematical principles that underpin them. 

## Results
The best model performance came from the linear regression model, with the best MSE and $R^{2}$ scores compared with the other two models. This model predicted that the year the Arctic will be ice-free is, optimistically, 2221. 

## Future Work
- A wider range of features would create a better model.
- Modelling the Arctic ice by season.
- Expand the number of SL models to include Support \/ector Machines, Decision Trees and the Random Forest. These might be tricky to implement from scratch, if keeping with the spirit of the original project. 

## What This Repository Contains

The main code file is final_project.ipynb, which contains everything needed to train and test the models, and the relevant figures. The .csv files are the required data files used as the dataset, where each file is a different feature as described above.
