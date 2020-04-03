# COVID-19 Temperature Mortality
 Aggregating temperature and case data

The repo consists of a jupyter notebook file (.ipynb) that aggregates covid-19 case data (confirmed cases, deaths, recoveries).

This notebook associates COVID-19 case information with local weather information. 
Some preliminary visualization, feature engineering, and modeling is performed.
 - Note that at this time, model assumptions are not being met and therefore inference from results is not great.
    * This could be because of ansynchonis limitations in our response featur (Survivorship = recoveries / (deaths + recoveries), failure to incorprate time series components, or missing some clearly important features.

In addition to the library dependencies below, full execution of this script requires an API key from DarkSky. This key is kept in the file 'DarkSkyAPIKey.rtf' in the main directory. This file has been ommitted from the github library to prevent $ charges related to over use but the data has already been downloaded and stored as of 29 March 2020 and should not provide an error when running the notebook. 
