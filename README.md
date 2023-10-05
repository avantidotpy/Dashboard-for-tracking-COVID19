<b> Holistic Analysis of Corona Virus using Statastical modelling and Machine Learning</b><br>
Visualize and Predict spread of CoronaVirus
Since the pilot out-break in Wuhan,Huebei COVID-19 has infected almost 50,000+ people in 28 countries. This project aims at visualizing changes happening on a global scale by incorporating rapid mapping of live datasets. A pilot model build upon ARIMA and Exponential Curve fitting helps to predict future outbreaks by analysing the current data pool.

<b>Getting Started</b><br>
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

<b>Prerequisites</b><br>
<ol>
  <li>Python >=3.5</li>
<li>Numpy</li>
<li>Pandas</li>
<li>Statsmodels</li>
  <li>Dash</li>
<li>Amira</li>
<li>SCIPY</li>
<li>Seaborn</li>
<li>Matplotlib</li>
</ol>

Installing
A step by step series of examples that tell you how to get a development env running
<ol>
  <h3>Developing a Flask application</h3>
  <li>Fetch the CSV from this GITHUB repository:https://github.com/Perishleaf/data-visualisation-scripts<br> Data can also be imported from the repository (mapping wont be live)</li>
  <li>Create a Flask Server<br> How to set up a flash server:https://www.twilio.com/docs/usage/tutorials/how-to-set-up-your-python-and-flask-development-environment</li>
  <li>Select the plots you want to plot using the dataset<br>Guide: https://www.freecodecamp.org/news/how-to-build-a-web-application-using-flask-and-deploy-it-to-the-cloud-3551c985e492/</li>
  <li>Render the elements and the visualise the changes</li>
  <li>You can also use hello.py</li>
</ol>

<h3>TimeSeries Forecasting</h3>
<p> These models are used to forecast/predict time-series data. As our data highly depends upon timestamps it's highly advisable to use this</p>
 <ol>
  <li>It's beautifully explained how to implement any timeseries forecasting model in this link: <br>https://machinelearningmastery.com/arima-for-time-series-forecasting-with-python/</li>
  <li>Note: Make sure to use the dataset to generate the predictive model<br>If you need our model drop us a mail at <mailto>vivek.bhanushali16@siesgst.ac.in</mailto></li>
  <li> We achieved an accuracy of 97.8% with the limited dataset.</li>
  </ol>
  <p>The model uses diffrential equations to generalise results, the better the diffrential equation the higher accuracy the model yields</p>

<h3>Predicting fatality - Curve fitting using Exponential Equations</h3>
<p> Fetches data in real time and processes numerical attributes to forecast potential deaths and infections</p>
<ol>
  <li>Import the dataset from the affomentioned github repository</li>
  <li>Visualise the infected and death rates</li>
  <li>Refinment of the dataset</li>
  <li>Visualising new infections/deaths per day</li>
  <li>Use exponential equation: <b>n(t) = c(t-t0)^p+a0</b> Where <br> n = function of no. of days <br>p = exponential factor <br> t = time </li>
  <li> We achieved an accuracy of 95%</li>
  <li>For Queries drop a mail to: avantilaingam@gmail.com</li>
</ol>

<b>Computing risk factor</b>
<p>To visualise which country is most vulnerable we computed risk factor using epidemiologic analysis<p>
<p>Refer page: https://www.cdc.gov/csels/dsepd/ss1978/lesson3/section5.html</p>
<p>Risk factor =function([age,health facilities,population,standard of living, travel ration],country)</p>

Version (1.0.0)
Includes
<ol>
  <li>Visualising changes</li>
  <li>Predictive analysis</li>
  <li>Risk Factor association</li>
</ol>

Authors
Apurva Mhatre - Time Series Forecasting.<br>
Avantika Mahalingam - Curve fitting and predictions.<br>
Aaditya Gurav - Flask server implementation.

License
This project is opensource.

