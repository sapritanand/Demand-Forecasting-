<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
  
</head>
<body>

<h1>Demand Forecasting Using SARIMAX</h1>

<p><strong>Project Overview:</strong></p>
<p>This project demonstrates demand forecasting using historical demand and inventory data. The forecasting model is built using the SARIMA (Seasonal Autoregressive Integrated Moving Average) model to predict future product demand, helping businesses optimize their inventory management strategies.</p>

<h2>Key Features</h2>
<ul>
    <li>Time Series Analysis with SARIMAX model</li>
    <li>Optimal Order Quantity Calculation</li>
    <li>Reorder Point and Safety Stock Calculation</li>
    <li>Total Cost Estimation for Inventory</li>
</ul>

<h2>Dataset</h2>
<p>The dataset contains the following columns:</p>
<ul>
    <li><strong>Date:</strong> Date of demand and inventory observation</li>
    <li><strong>Product_ID:</strong> Unique identifier for the product</li>
    <li><strong>Demand:</strong> Quantity demanded on that date</li>
    <li><strong>Inventory:</strong> Inventory level on that date</li>
</ul>

<h2>Installation and Setup</h2>
<p>Clone the repository and install the required packages:</p>
<pre><code>git clone https://github.com/sapritanand/Demand-Forecasting-.git
pip install -r requirements.txt</code></pre>

<p>Run the demand forecasting script:</p>
<pre><code>python forecast.py</code></pre>

<h2>Forecasting Process</h2>
<p>The SARIMA model is used for forecasting future demand, with the following steps:</p>
<ol>
    <li>Data pre-processing and differencing to make the series stationary</li>
    <li>ACF and PACF plots to determine the AR and MA terms</li>
    <li>Fitting the SARIMAX model and predicting future demand</li>
</ol>

<h2>Optimal Order Quantity and Inventory Management</h2>
<p>Based on the forecasted demand, the optimal order quantity, reorder point, safety stock, and total inventory cost (holding and stockout costs) are calculated to assist with efficient inventory planning.</p>

<h2>Visualization</h2>
<ul>
    <li>Line plot of <strong>Demand Over Time</strong></li>
    <li>Line plot of <strong>Inventory Over Time</strong></li>
    <li>Autocorrelation and Partial Autocorrelation plots for time series analysis</li>
</ul>

<h2>Model Predictions</h2>
<p>The model predicts future demand over 10 days, providing insights into the necessary reorder point, safety stock, and optimal order quantity for inventory management.</p>

<h2>Conclusion</h2>
<p>This project provides an end-to-end solution for demand forecasting, helping businesses maintain optimal inventory levels and reduce costs through effective forecasting techniques.</p>

</body>
</html>
