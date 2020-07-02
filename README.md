# Demand-Order-Forecasting
A forecasting project using ARIMA and SARIMA model to predict future demand.

About
-------
I make this project to explore and study time series forecasting using ARIMA and SARIMA model. 
The <a href="https://www.kaggle.com/felixzhao/productdemandforecasting">dataset</a> contains historical product demand for a manufacturing company. The company has 4 main warehouses.
The company provides thousands of products within dozens of product categories.

Exploration & Visualization
-------
Here are explorations I've done with the data :

<ul>
  <li>Annual Average Order Demand</li>
  <p align="center">
    <img src="https://github.com/farizdar/Demand-Order-Forecasting/blob/master/image/eda%201.PNG" width="1000" height="600" >
  </p>
  
  <li>Total Orders per Warehose</li>
  <p align = 'center'>
     <img src = 'https://github.com/farizdar/Demand-Order-Forecasting/blob/master/image/eda%202.PNG' width = '600' height = '550'>
  </p>
  
  <li>Order Demand per Category</li>
  <p align = 'center'>
     <img src = 'https://github.com/farizdar/Demand-Order-Forecasting/blob/master/image/eda.PNG' width = '800' height = '600'>
  </p>
</ul>

Model
-------
I did monthly sequence resampling with the data, stationarity check, time-shifting data (monthly and yearly) and deseasoned data. Lastly, I built 2 models, ARIMA and SARIMA, for each model I did model validation by plotting and calculate its Mean Absolute Percentage Error (MAPE) value.
For the full code, you can see in my <a href = 'https://github.com/farizdar/Demand-Order-Forecasting/blob/master/Demand%20Order%20Forecasting.ipynb'>notebook.</a> <br>
Herewith is some of the visualization from the model :
<ul>
  <li>Original Monthly Average Order Demand</li>
  <p align="center">
    <img src="https://github.com/farizdar/Demand-Order-Forecasting/blob/master/image/1.PNG" width="1000" height="400" >
  </p>
  
  <li>ARIMA Model Validation</li>
  <p align="center">
    <img src="https://github.com/farizdar/Demand-Order-Forecasting/blob/master/image/arima.PNG" width="1000" height="400" >
  </p>
  
  <li>SARIMA Model Validation</li>
  <p align="center">
    <img src="https://github.com/farizdar/Demand-Order-Forecasting/blob/master/image/sarima.PNG" width="1000" height="400" >
  </p>
  
  <li>Observed-Forecast Average Order Demand</li>
  <p align="center">
    <img src="https://github.com/farizdar/Demand-Order-Forecasting/blob/master/image/2.PNG" width="1000" height="400" >
  </p>
</ul>

Conclusion
-------
From this project, I can draw these conclusions :
<ul>
    <li>We have sucessfully built 2 models for forecasting product order demand by using ARIMA and SARIMA model.</li>
    <li>SARIMA model is the better model with better residual behaviors and Accuracy around 99%.</li>
    <li>For future demand, Company has to strategize something to make their product's demand increase, either better marketing strategy or launch a new product.</li>
</ul>
  
### Thank you for reading until the end!

#### Fariz Darmawan 
#### Email : darmawanfariz@gmail.com | [LinkedIn](https://www.linkedin.com/in/fariz-darmawan-a28600b3//) | [GitHub](https://github.com/farizdar/) 
