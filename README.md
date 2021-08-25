# West Nile Virus Outbreak Prediction in Chicago, Illinois
_Blaine Murphy, July 2021_

## Data
This project is based on the Kaggle Competition: https://www.kaggle.com/c/predict-west-nile-virus
The `input` folder contains the following datasets:
1. `train.csv` -- Training data of mosquito samples from traps around the city
1. `test.csv` -- Test data for Kaggle competition
1. `weather.csv` -- Daily weather data from 2 weather stations at two Chicago airports
1. `spray.csv` -- Data on city pesticide spraying efforts to reduce mosquito populations

## Notebooks
The following notebooks are in the `working` folder and they contain my work for this project.
1. `West Nile Data Wrangling.ipynb` -- Importing and basic cleaning of the WNV data sets from Kaggle
1. `WNV EDA.ipynb` -- Exploratory Data Analysis and creation of new features
1. `WNV Preprocessing.ipynb` -- Preparing data for modelling
1. `WNV Modelling.ipynb` -- Predictive modelling and evaluation of results

## Final Model
The best performing model on this data set is an XG Boost classifier.  The model is in the `working` folder in the file `XGBoost_final_classifier.pkl`. The file `XGBoost Model Metrics.txt` file contains details on the inputs of the model and its performance.  

## Documentation 
1. `WNV Problem Statement.pptx` -- Explicitly defining the problem and the scope of the project
1. `West Nile Virus Project Proposal.docx` -- Project proposal detailing the problem and how I will solve it
1. `Capstone 2 WNV.pptx` -- Presentation meant for the Chicago Department of Public Health detailing the project and final predictive model
1. `Capstone 2 Final Report.docx` -- Report documenting the entire project, final model, and model performance
1. `West Nile Virus Project Proposal.pdf` -- Same as above but in pdf format



