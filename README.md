# FUTSA_final_project

In this project, we have tried to predict the blasting time in a coal field of Coal India Singrauli. We have tried to arrive at various conclusions using the data of the pollutants at variuos timestamps provided. We have tried to do some operations on the data and tried to take out meaningfull results from it.

Firstly we have tried some basic methods that is resampling the data to an hourly basis. Also we have plotted the data of the pollutants with the original timeframe and also with the hourly timeframe, that is basically smoothing the data. We have also plotted histogram plot of PM 10 to get better insights. It tells us that the maximum frequency of the pollutants is around the frequency which is higher than national average.

Then we have done the seasonal decomposition of the time series. Here, we have done the seasonal decomposition of PM 10, but we have not arrived at any conclusive results as there is no particular trend being followed. There is a seasonality, but that is expected as mining is a daily process.

Then we have found the average values of the pollutants at every hour over the given timeperiod. That is we found the average values of the pollutants at different hours of the day. We have also found the average values of the pollutants at 2 hrs before the given blasting time(13:45-14:45) and 2hrs after that too. This has given us some good insights which are explained in the notebook itself alongside the graphs obtained.

We have obtained a single timeseries of the pollutants by assigning weights using the standard deviation observed in the values of the pollutants throught the day. We came to this by thinking that in a coal mine, if due to any activity some pollutants will be getting affected while other will be not. So more weight should be given to those pollutants which have a higher standard deviation. While we have assigned a lower weight to those pollutants which have a lower standard deviation.

We have also calculated the AQI values at different hours and have also tried to predict the results using it. We have arrived at different conclusion and all of those are mentioned in the notebook itself along with the relevant graphs.

# Work Distribution
The work distribution was toatlly equal and everybody had contributed equally. Vatsaankit and Rohit had contributed towards the parts including plotting the relevant graphs, 24 hour average of the pollutants and the single time series part. Trijal contributed towards the AQI part and all of its parts. Anya and Arin had contributed towards the probability of the blasting time part and all the related parts. 
