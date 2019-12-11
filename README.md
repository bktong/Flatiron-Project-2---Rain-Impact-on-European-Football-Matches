
# Project:   Mod 2 Final Project - Summary Statistics of the 2011 European Football teams

# Summary:  
The goal of the project is to create a set of 2011 summary statistics for each club team using ETL technologies and methodologies 
taught throughout the our 2nd course module.  

# Technologies and Methodologies used:
SQL queries, API queries, webscraping, MongoDB, and Object Oriented Programming.

# Libraries used:
requests, sqlite3, pandas, json, datetime, time, numpy, matplotlib, pymongo.

# Project Organization and contents
I have contributed a few new files to my project repository used to complete the project. 

stadiums.csv - is used to cross reference the GPS coordinates for each teams stadium.  12 teams were missing in the initial file
so I manually added them to complete the file. Credit goes to github user "Jokecamp" for expediting this process. 
https://github.com/jokecamp/FootballData/blob/master/other/stadiums-with-GPS-coordinates.csv

football_weather.csv - The project is divided into two parts for the purpose of not contaminating the data post API pull.   
this file contains the raw results of the API pull and is used as the source data file for Phase 2 and 3.

dark_sky_api.json - anyone can repeat the code but needs to update their main folder with their API.  Obviously, my unique
key is not included in this repositiory.   A user may request their own key at https://darksky.net/dev

# Roadmap:
as-is.  I do not plan to add anything more for this project.

# Contributions:
Any requests are welcome, feel free to pull whatever.  Update tests as appropriate.

# License:
Anyone can use.
