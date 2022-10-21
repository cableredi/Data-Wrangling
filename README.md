# Data Wrangling

## Summary
National Parks in the United States are a favorite vacation destination for many outdoor enthusiasts. I would like to find out which of the National Parks is best to visit and hike.

Each of the three data sources has its own unique information but also some overlap. The National Parks API has all information about each of the national parks in its system. The National Parks Trails CSV is derived from the AllTrails website and has information on the trails located in the National Parks. The National Parks elevation table from Wikipedia is a table of the highest and lowest elevations in 63 National Parks. Initially. looking at the data for each source, the National Parks API looks to be the parent as it has the most accurate information coming directly from the National Parks Service. I will be using the park’s endpoint to get data about all the National Parks in its database. The CSV file contains the name of the National Park which I will use to connect it to the API data. The website also has the National Park name which will connect to the API data.


## Built With
Python, pandas, matplotlib, seaborn, scipy, numpy, wordcloud BeautifulSoup, requests, re, json, configparser, sqlite3