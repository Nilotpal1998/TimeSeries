<h2><b>Forecasting NO<sub>2</sub> emission Rate with <i>SARIMA</i> and predicting the autocorrelation with State-wise GDP</b></h2>
<h3>What is Seasonality?</h3>
<p>Seasonality is a characteristic of a time series in which the data experiences regular and predictable changes that recur every calendar year. Any predictable fluctuation or pattern that recurs or repeats over a one-year period is said to be seasonal.Seasonal effects are different from cyclical effects, as seasonal cycles are observed within one calendar year, while cyclical effects, such as boosted sales due to low unemployment rates, can span time periods shorter or longer than one calendar year.</p>
<p align="center">
  <img width="568" height="288" src="https://s3-eu-west-1.amazonaws.com/ppreviews-plos-725668748/1713638/preview.jpg" >
</p>
<h3>Let's look at our Data</h3>
<p>We have have the monthly NO<sub>2</sub> emission rate data from January, 2005 to December ,2019  of 29 Indian states and below is the sample from Karnataka State . </p>
<p align="center">
  <img width="568" height="288" src="https://github.com/Nilotpal1998/TimeSeries/blob/main/Karnataka/Original_Karnataka.png" >
</p>
<p>As we can see , there is a prominent seasonality in the data and it is expected as NO<sub>2</sub> emission is mainly caused by chemical industries and that can fluctuate between months. So we are expecting a periodicity of 12 months or 1 year. Now , we are going to see a detailed description of our analysis and methodology for Karnataka state only, as we have taken the similar measures for other states also except some parameter tuning. Later we shall look at the detailed results for all the states.</p>
