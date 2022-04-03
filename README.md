# EP-Predictor
CS3110 - Introduction to Machine Learning | Lab 02 - Regression | Electrical Energy Output Predictor

This will be conducted as a Kaggle competition.

Competition URL: https://www.kaggle.com/t/a093d1c5510d474e97a6367da4ec69af

Please use your index number as the username in the following format when creating your Kaggle account. Please use the same account for this lab and the Mini Project that was launch earlier.

                   UOM_IndexNo (E.g.: UOM_190001X)
Dataset

The training dataset contains 8500 data points collected from a power station over several years. You should build a model to forecast the net hourly electrical energy output (EP) of the power station.

The recorded attributes in the dataset include the following hourly average variables:

    Temperature (AT)
    Ambient Pressure (AP)
    Relative Humidity (RH)
    Exhaust Vacuum (V)

This power station has gas turbines (GT), steam turbines (ST) and heat recovery steam generators. Here, the electricity is generated by gas and steam turbines, which are combined in one cycle, and is transferred from one turbine to another. While the Vacuum is collected from and has effect on the Steam Turbine, the other three of the ambient variables affect the GT performance.

Task

    Design a machine learning model to predict the electrical energy output (EP), given the attributes AT, AP, RH and V. Use your model to predict the EP for the test dataset.
    Calculate the necessary evaluation metrics to show how good your model is.

Evaluation Metric

The evaluation metric for this competition is Mean Absolute Error. 
Evaluation Criteria

    Final accuracy [30 points]
    Trying out 2 different approaches [30 points]
    Calculating various evaluation metrics [20 points]
    Short discussion on the evaluation metrics calculated along with the comparison of the results obtained from the two different approaches. [20 points] - This should be submitted here (Moodle submission). Should not be more than one page long.

