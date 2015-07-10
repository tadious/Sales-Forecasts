# Sales-Forecasts

A test service that given a geographical position, a sales forecast and the weather forecast returns the updated sales forecast using a set of given rules. The service reads in an xlsx file for dates and corresponding sales forecasts, gets the weather forecasts for a given geographical position then updates sales forecasts for the dates that have a corresponding weather forecast.

Installation
Download and unpack files into domain root. For example api.quinyx.com/

How to use:

The service has 2 formats, json and html:

JSON: 

Make an http call to /lat/60.555/lon/24/sales-forecast.json

Geographical position is supplied as parameters in the URL. In this case, latitude=60.555 and longitude=24

HTML:

Make an http call to /lat/60.555/lon/24/sales-forecast.html

Geographical position is supplied as parameters in the URL. In this case, latitude=60.555 and longitude=24


DEMO:
