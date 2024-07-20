# FUTSA_final_project

In this project, I have tried to predict the blasting time in a coal field of Coal India Singrauli. I have tried to arrive at various conclusions using the data of the pollutants at variuos timestamps provided. I have tried to do some operations on the data and tried to take out meaningfull results from it.

Firstly I have tried some basic methods that is resampling the data to an hourly basis. Also we have plotted the data of the pollutants with the original timeframe and also with the hourly timeframe, that is basically smoothing the data. We have also plotted histogram plot of PM 10 to get better insights. It tells us that the maximum frequency of the pollutants is around the frequency which is higher than national average.

Then I have done the seasonal decomposition of the time series. Here, I have done the seasonal decomposition of PM 10, but I have not arrived at any conclusive results as there is no particular trend being followed. There is a seasonality, but that is expected as mining is a daily process.

Then I have found the average values of the pollutants at every hour over the given timeperiod. That is how I found the average values of the pollutants at different hours of the day. I have also found the average values of the pollutants at 2 hrs before the given blasting time(13:45-14:45) and 2hrs after that too. This has given me some good insights which are explained in the notebook itself alongside the graphs obtained.

I have obtained a single timeseries of the pollutants by assigning weights using the standard deviation observed in the values of the pollutants throught the day. I came to this by thinking that in a coal mine, if due to any activity some pollutants will be getting affected while other will be not. So more weight should be given to those pollutants which have a higher standard deviation. While I have assigned a lower weight to those pollutants which have a lower standard deviation.

I have also calculated the AQI values at different hours and have also tried to predict the results using it. I have arrived at different conclusion and all of those are mentioned in the notebook itself along with the relevant graphs.

