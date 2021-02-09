# Renewable Energy Production

# Project deployed on AWS at http://18.189.31.33:5000

# Stock Predictor
In this project, we used machine learning models to explore the behavior of two different stocks. The stocks we chose were Cisco Systems, Inc. (CSCO) and New Oriential Education (EDU). Cisco Systems (CSCO) supplies hardware and software for networking solutions and other communication needs like mobility and sercuirty. It provides provides software and security for telemedicine platforms, 5G mobile connections, and  platforms for companies to analyze data through AI and machine learning. New Oriental Education & Technology Group (EDU) provides remote educational services to people in China. Both these companies are positioned in industries that are set to grow, but we wanted to see if we could predict their future stock prices using past prices. We used a two different types of machine learning Long Short-Term Model to predict future stock prices based. We used a Multi-variate linear regression to anaylze the impact that certain fundementals had on a stock's price.

## Launched Version
https://stock-predictor1.herokuapp.com/

## Tools and Resources
* HTML / Bootstrap
* Flask
* Plot JavaScript
* Tensorflow / Keras

## Screenshots
Here is an example of the opening page which shows the closing prices of both stocks
![ScreenShot](/Screenshots/Front.png)
https://stock-predictor1.herokuapp.com/static/images/stock2.gif

Here is an example of our prediction for Cisco Systems, Inc.
![ScreenShot](/Screenshots/CSCO.png)


Data Sources: \
https://www.energy.gov/science-innovation \
https://www.eia.gov/electricity/data/browser/#/topic/0?agg=1,0,2&fuel=004&geo=qnifi05c03j78&sec=o3g&linechart=ELEC.GEN.SUN-US-99.M~ELEC.GEN.SUN-NV-99.M~ELEC.GEN.SUN-CA-99.M&columnchart=ELEC.GEN.SUN-US-99.M~ELEC.GEN.SUN-NV-99.M~ELEC.GEN.SUN-CA-99.M&map=ELEC.GEN.SUN-US-99.M&freq=M&start=200101&end=202007&ctype=linechart&ltype=sourcekey&rtype=s&maptype=0&rse=0&pin=\
https://www.sciencedaily.com/news/earth_climate/renewable_energy.
