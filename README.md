# Weather-Prediction


The main aim of the project is to correctly classify rainfall in the country of Singapore. To do that, I have obtained data from the Singapore Government weather website. The original data is available in the form of individual files spanning the months from the years of 1983 to 2020 and they amount to more than 450 csv files that have been concatenated into one. I chose these weather records because of their ease of availability and their detailed documentation throughout the years. The weather records are available from the years of 1983-2020. The files are mostly clean save for a few missing values for some columns. The dataset is one of the few detailed, multi-year ones that are available freely through the public domain Through Exploratory Data Analysis, Anomaly Detection using Cluster-based Local Outlier Factor (CBLOF), Histogram-base Outlier Detection (HBOS), Isolation Forest and K Nearest Neighbors (KNN), more insight in the data can be gained. Different classification models such as Logistic Regression, XGBoost and Neural networks have been trained on the dataset to perform predictive modeling. Kfold Cross-Validation & Grid Search is used to generalize the model better on the data it has not seen and tune the hyperparameters to get the best prediction

To run the project and load the dataset, follow the below instructions -

•	Download the data from - http://www.weather.gov.sg/climate-historical-daily/

•	Keep all the files provided and the downloaded dataset in either the current working directory, or change the working directory to any path you like in the Jupyter Notebook.

•	Open ‘FinalProject’ and run it.

•	You will find all the steps from importing the libraries, image  preprocessing, network architecture etc for the classification there 

