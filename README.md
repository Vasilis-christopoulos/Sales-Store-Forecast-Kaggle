# Sales-Store-Forecast-Kaggle
This is getting started Kaggle competition which I completed using different technics and using other published notebooks. 
The purpose of this project is getting familiar with TimeSeries and future forecasting. 
I used the Darts library to complete the task, which assisted with dealing with the TimeSeries. 
Regarding the modeling process, I followed an ensemble strategy using LightGBM firstly in a general scope and then in a more specified scope.
In more detail I used a single LightGBM with access to all data and then I created 3 different versions of model parameters which I used to train 33 LightGBM for the 54 stores.
Basically, I created one model for each product family for every version of the model parameters.
I concluded my submission by adding the results of the general model with those of the specified models and taking the average.
This method gave me a fairly good position in the competition and can be optimized further. However, I mainly did for learning puproses and I'm planning to come back to it soon.
