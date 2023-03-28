<h1>Bitcoin Historical Data</h1>

<h2>Description</h2>
This Project is on Bitcoin which is the longest running and most well known cryptocurrency. The dataset contains select bitcoin exchanges for the time period of Jan 2012 to December March 2021, with a minute to minute updates of OHLC (Open, High, Low, Close), Volume in BTC and indicated currency, and weighted bitcoin price. 
Timestamps are in Unix time. Timestamps without any trades or activity have their data fields filled with NaNs. 

A custom column was created to convert the Timestamp which were in Unix time to DateTime 

= #datetime(1970,1,1,0,0,0) + #duration(0,0,0,[Timestamp])<br/>

<h2>Data Tool(s) Used</h2>

- <b>Power BI</b> 

<h2>Insights</h2>

- <b>Total BTC Traded</b> 
- <b>Total BTC Price</b> 
- <b>Average BTC Price</b> 
- <b>Average Trading Time in Minutes</b> 
- <b>Total BTC Volume Traded by Year</b> 
- <b>Total BTC Volume Traded by Time</b> 
