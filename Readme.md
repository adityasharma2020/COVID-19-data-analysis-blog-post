# udacity Data Science blog


![image](/COVID19png.jpg)


Currently their is a very critical environment all around the world due to corona virus (COVID-19).
diffrent countries are adopting diffrent methods to get prevented from the virus

in this blog post i tried to analysis the covid-19 data with the help of data science so lets get jump into it .

# source of the dataset :
their are lots of data sources regarding COVID-19  on internet .One of the most widely and trusted dataset today is one provided by john hopkins university centre or systems science and engineering [JHU CSSE](https://github.com/CSSEGISandData/COVID-19)

the seperate links to all csv files used in this blog:
1. [time_series_covid19_confirmed_global.csv](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv)

2. [time_series_covid19_deaths_global.csv](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_deaths_global.csv)

3. [time_series_19-covid-recovered_global.csv](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_recovered_global.csv)

4. [cases_country.csv](https://raw.githubusercontent.com/CSSEGISandData/COVID-19/web-data/data/cases_country.csv)

# understanding the dataset

![image](/capture.PNG)

the cases_countries_df is not a time frame series but an aggregate data with an additional  column "active".

so, now i do some analysis on the data and summarize some stats and plot some trends .

![image](/capture2.PNG)
as we can see in the image how this spread has progressed over a period of time , i confirmed the cases using plotly.graph_objects.

the graph is an sharp exponetial curve which shows the devastating rate at which the pandamic is spreading ove the world .

now , to get a more clear picture i tried to plot  recovererd, active, deaths, confirmed cases in  one plot . to do this i make a function for this.

![image](/capture3.PNG)
we call the function four times  to plot the graph in one plot.
![image](/capture4/PNG)
* from the above graph we can conclude that after 6-10-20 the recovered cases increases than the active cases.

![image](/capture5.PNg)
* in this graph we can compare number of cases in diffrent aspects between diffrent countries.
in the graph we can see that currently "US" has the more confirmed cases as well as it has the heighest number of deaths after that their is brazil and then india.

-->now as their  is no official vaccine available right now , the only and the best way to handle the spread and decreaes the number of active cases is by slowing down the transmission rate .
