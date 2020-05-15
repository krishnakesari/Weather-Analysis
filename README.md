# Weather-Analysis


Building a python (tkinter) application to understand the changes in the barometric pressure over a period of time gives insights into any abrupt changes in the environmental conditions.

Data Source: Environment data captured from Lake Pend Orieille in North Idaho

Key Data variables: date, time, air temperature, barometric pressure, dew point

Analysis Steps:

1. Wrote a class funtion that will loop over the data convert them into arrays
2. Using Matplot lib to graph data
3. Building a tkinter GUI application
4. Configuring a message prompt if selected dates are out of the data range
5. Measuring coefficient of slope of barometric pressure and building dynamic color slope line 

Data Interpretion:
A rising slope indicates an increasing barometric pressure, which typically means fair and sunny weather ahead. A falling slope indicates a decreasing barometric pressure, which typically means stormy weather.