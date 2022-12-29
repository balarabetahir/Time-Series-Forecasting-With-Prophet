# Time-Series-Forecasting-With-Prophet
In this project, we will use the Prophet open source library to predict the power consumption for next year. Prophet is designed to automatically find a good set of hyperparameters for the model with skilful forecasts and data with trends and seasonal structure by default.

I recently had the opportunity to work on a guided project using Time Series Forecasting with Prophet, a powerful open-source tool for predicting time-series data developed by Facebook. For this project, I used Python as my programming language of choice.

Time series forecasting is a common task in data science, as it allows us to predict future values of a series based on its past values. This can be particularly useful in fields such as finance, marketing, and logistics, where the ability to accurately forecast demand or trends can have a significant impact on a company's bottom line.

To get started, I first had to install the Prophet library in my Python environment. This was relatively straightforward, as the library can be easily installed using pip install fbprophet.

Next, I imported the necessary libraries and data into my Python script. Prophet requires a specific format for the input data, with two columns: a timestamp column and a value column. I made sure to pre-process my data accordingly before feeding it into the model.

Once my data was in the correct format, I was ready to start building my model. The first step was to initialize a Prophet object and specify any desired model hyperparameters. Prophet offers a wide range of customization options, including the ability to specify custom growth trends, seasonality, and holiday effects.

Next, I fit my model to the data using the .fit() method, and then used the .predict() method to generate forecasts for the desired time horizon. Prophet also provides useful visualization tools, such as the .plot() method, which allows us to visualize the model's fit and forecasted values.
To train and fit the time series forecasting model. Here we are using the model Prophet for forecasting time series data based on an additive model where non-linear trends are fit with yearly, weekly, and daily seasonality along with holiday effects. It is also a robust way to handle missing data and shifts in the trend as well as handling outliers in the data. It works best with time series that have strong seasonal effects (Seasonality).


MAE (Mean Absolute Error). Absolute error refers to the magnitude of difference between the prediction of an observation and the true value of that observation. It is thus an arithmetic average of the absolute errors  

  where  y{i} is the prediction and x{i} the true value. Note that alternative formulations may include relative frequencies as weight factors. The mean absolute error uses the same scale as the data being measured. This is known as a scale-dependent accuracy measure and therefore cannot be used to make comparisons between series using different scales.


Overall, working with Prophet was a smooth and enjoyable experience. The library is well-documented and user-friendly, making it easy for even beginner data scientists like myself to get up and running quickly. I'm looking forward to using it on more time series forecasting projects in the future!

Did you have a chance to work with Time Series Forecasting with Prophet? Share your experiences in the comments below!
