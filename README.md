# Data Wrangling

## National Parks

Data Wrangling is the process of transforming data from an unreadable format to another format to make it more appropriate for analysis.  This project takes three different forms of data and merges it into one all with the National Parks as its theme.

Each of the three data sources has its own unique information but also some overlap. The National Parks API has all information about each of the national parks in its system. The National Parks Trails CSV is derived from the AllTrails website and has information on the trails located in the National Parks. The National Parks elevation table from Wikipedia is a table of the highest and lowest elevations in 63 National Parks. Initially. looking at the data for each source, the National Parks API looks to be the parent as it has the most accurate information coming directly from the National Parks Service. I will be using the park’s endpoint to get data about all the National Parks in its database. The CSV file contains the name of the National Park which I will use to connect it to the API data. The website also has the National Park name which will connect to the API data.

<br />
<br />

![Data Wrangling](./data/readme/data_wrangling.png)

<br />
<br />

## Built With
Python 3, pandas, matplotlib, seaborn, scipy, numpy, wordcloud BeautifulSoup, requests, re, json, configparser, sqlite3