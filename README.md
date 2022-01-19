# Covid_19 data analysis

As the global pandemic Covid-19 is still interfering with the daily life's of everyone around the globe, it is informative to gain insights from the novel Covid-19 data.
DATA SOURCES: 
Novel Covid-19 data - https://www.worldometers.info/coronavirus/

Worldometer, formerly Worldometers, is a reference website that provides counters and real-time statistics for diverse topics.

Coordinates of the Countries - https://developers.google.com/public-data/docs/canonical/countries_csv

Covid-19 data is obtained from the  Wroldometer using web scraping. We use 
<b>requests and Beautiful Soup</b> libraries for this purpose.
Requests is an HTTP library for the Python programming language. 
Beautiful Soup is a Python library for pulling data out of HTML and XML files.
Pandas library is used to form two data frames from the data obtained.
Then <b>data wrangling and Exploratory Data Analysis(EDA)</b> is performed over the data obtained. 
The Top 15 Countries with the highest Total Corona cases is visualized on a horizontal Bar graph using the <b>matplotlib</b> library. The Total cases per country are visualized on a world map as a scatter plot. <b>Plotly express and Mapbox</b> is used for this purpose.
From the visualization easily we can understand the distribution of the Total cases globally.

