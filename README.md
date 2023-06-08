# CarEmissionClassification
Machine Learning Project for class

The class project was meant to be done in Rapidminer but instead, I adapted it to use Python; Pandas, Numpy and AutoML by H2O.

The context is that the EPA has set a new target: 40 MPG Fuel Efficiency Average For 2026. Can machine learning models classify cars whether it passes the EPA target based on data of its features and specifications.

Dataset was retrieved from the Official US Govt EPA website : https://www.fueleconomy.gov/feg/download.shtml

The test performance resulted in 40/42 "Yes" labels predicted as 'No'. Essentially, the model was inclined to predicted false negatives. This can be attributed to the class imbalance (which I have not shown in the code) but also the possibility of the lack of features such as weight of the car. 
