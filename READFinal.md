Project Task:
You will only be forecasting for Pakistan only in this project.
1)	Load and process the concerned data, you will use time_series_covid_19_confirmed
2)	Identify 5 most related countries that have a similar trend of infection as Pakistan. While comparing trends please keep in mind the 27th May restriction on data.
3)	Use the data of these countries to predict the spread of Coronavirus in Pakistan. Your prediction must start from 10th May and until 27th June so you will also be predicting trend for one month into the future (31 days into future).
Hint: While comparing trends and predicting, use number of days versus amount of cases as a measure of spread, instead of date against amount of cases
4)	Your expected output will be a list of numbers where each next individual element refers to the total new cases reported on that day.
5)	Use the prediction from 10th May until 27th May and report how well the model performed.
6)	Now use Pakistan time series and predict future cases until 27th June (one month into the future)
7)	Plot the original time series and predicted time series and compare their difference/similarities explain any peculiarities if found. Also explain briefly how different countries predict different trends for Pakistan and what do you think is the best one. 

Important Guidelines:
1)	There are a plenty of forecasting models you can use. We have studies a few of these namely:
a.	Autoregression
b.	Moving Average
c.	ARIMA
d.	RNN/LSTM
You should try as many as you like and go with what works best for you. You can also introduce more complex ideas into your models. Sometimes implementing ideas based on intuition goes a long way. 
You can also use other models beyond the ones listed above, however you must implement all models yourself. Plagiarism will not be tolerated.
2)	You are restricted to Pytorch and Scikit-Learn for implementation of your models.
3)	You are restricted to the dataset mentioned above, you can utilize all the files in it however you please, using any other data source other than specified is not allowed.
4)	You cannot use any third-party libraries and tools other than the one mentioned. You can however use Rapid Miner for your own personal experimentation.




