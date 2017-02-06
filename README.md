# MicroDotWeatherClock

You will need to install https://github.com/csparpa/pyowm as the script uses pyowm to query openweathermap.
Create an account at https://openweathermap.org/ in order to get an API key.

The python script takes two parameters. -l is the location you want the weather of the -k is the open weather map key.
The included shell script demonstrates how to call the script and you can add your key to this to save having to enter is multiple times.

The script is currently set to refresh the weather data every 30 minutes but openweathermaps allows something like 60 requests a minute on a free account.
