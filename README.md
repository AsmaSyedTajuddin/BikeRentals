# BikeRentals

Dataset uploaded


BackGround:
Bike sharing systems are new generation of traditional bike rentals where whole process from membership, rental and return back has become automatic. Through these systems, user is able to easily rent a bike from a particular position and return back at another position. Currently, there are about over 500 bike-sharing programs around the world which is composed of over 500 thousands bicycles. Today, there exists great interest in these systems due to their important role in traffic, environmental and health issues.
About the Data Set
Bike-sharing rental process is highly correlated to the environmental and seasonal settings. For instance, weather conditions,precipitation, day of week, season, hour of the day, etc. can affect the rental behaviors. The core data set is related to the two-year historical log corresponding to years 2011 and 2012 from Capital Bikeshare system, Washington D.C., USA which is publicly available in http://capitalbikeshare.com/system-data. We aggregated the data on two hourly and daily basis and then extracted and added the corresponding weather and seasonal information. Weather information are extracted from http://www.freemeteo.com.
The objective of this Case is to Predication of bike rental count on daily based on the environmental and seasonal settings.

prediction using AutoML: H2O

H2O is a fully open-source, distributed in-memory machine learning platform with linear scalability. H2O supports the most widely used statistical & machine learning algorithms, including gradient boosted machines, generalized linear models, deep learning, and many more.

Results:
Model Details
=============
H2OStackedEnsembleEstimator :  Stacked Ensemble
Model Key:  StackedEnsemble_AllModels_1_AutoML_1_20220714_212327

No model summary for this model

ModelMetricsRegressionGLM: stackedensemble
** Reported on train data. **

MSE: 36681.301670885114
RMSE: 191.52363214727606
MAE: 141.10215315033258
RMSLE: 0.17391017703012834
R^2: 0.9902312800310261
Mean Residual Deviance: 36681.301670885114
Null degrees of freedom: 574
Residual degrees of freedom: 570
Null deviance: 2159110766.584347
Residual deviance: 21091748.46075894
AIC: 7687.042200632402

ModelMetricsRegressionGLM: stackedensemble
** Reported on cross-validation data. **

MSE: 408436.2114235596
RMSE: 639.0901434254479
MAE: 443.86727195278274
RMSLE: 0.3047770875949318
R^2: 0.8912279882981298
Mean Residual Deviance: 408436.2114235596
Null degrees of freedom: 574
Residual degrees of freedom: 571
Null deviance: 2159869623.8187118
Residual deviance: 234850821.56854674
AIC: 9070.831654229665
