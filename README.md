# Data Visualization &amp; Sentiment Analysis in Python
<img src="https://img.shields.io/badge/python-3.7-blue.svg"> <img src="https://img.shields.io/badge/vaderSentiment-3.2.1-blue.svg"> <img src="https://img.shields.io/badge/rpy2-3.0.5-blue.svg"> <img src="https://img.shields.io/badge/ggplot2-R-orange.svg">

This project utilizes *rpy2*, an interface which allows you to run **R** code imbedded in a **Python** process (Jupyter Notebook). All data manipulation was done in Python using the *pandas* library then the data was passed into R using rpy2. Visualizations were created using the R *ggplot2* library.

## Project Team Members:
- [Ariana Moncada](https://github.com/arianamoncada)
- [Kevin Loftis](https://github.com/loftiskg)

## Project Description
In 2018, The United States House-Intelligence Committee (USHIC) published a report confirming Russian interference in the 2016 US presidential election. Though most Americans accept this fact, the specifics of how the Russian actors meddled in the election is unclear to many. As part of the USHIC report, a set of targeted social media ads created between 2015 and 2017 by a Russian ‘troll farm’, the Internet Research Agency (IRA), was released to the public. Using this [data]( https://github.com/russian-ad-explorer/russian-ad-datasets/tree/master/json) and visualizations we found evidence of the following:
1. The IRA’s ad content targeted both conservative and progressive interest groups.
2. A three-fold increase in social media ad activity in the timeframe leading up to both *primary* and *general* election dates, suggesting a targeted attempt to cause division and chaos between American voters.
3. The average sentiment of the ads before the election to be more negative than following the election.
