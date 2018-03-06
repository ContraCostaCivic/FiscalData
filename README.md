# FiscalData
## 2018 Open Data Day Walnut Creek, CA update
We broke up into four teams Saturday morning, 02 March 2018. Each group had a problem to solve with the target of presenting our results by 4:30pm that day. The problem we wanted to solve with data and visualization was to show the state of the CA pension (CalPERS) funding by city.

We used started with the background data @joffemd shared with our team in this repository. There is also the site published http://marcjoffe.pythonanywhere.com/ , with the repository https://github.com/gitanupam/pd_maps, and the data representing the current CalPERS funding city map with drill down per city. 

We sorted through the data and reviewed which visualization tools we preferred. Data.world, tableau, and html we determined to be our best tools for the time and our experience with them. I considered using https://sarob.pythonanywhere.com as a fork of @joffemd 's work, but I was unable to quickly figure out the hardcoded parts of the site, so it was abandoned. 

To accomplish our objective, we focused on representing the state and by city unfunded CalPERS liablity over time. The first chart is published https://sarob.github.io/california-pensions/ here. The 2016 Accrued Liability (AL) verses Unfunded Accrued Liability (UAL) is presented as a donut chart along with a line chart of the estimated CalPERS total employer contributions over time. 

##Future work
* Create data.world https://data.world/integrations/tableau integration. I believe this requires tableau online, which we do not have a license for. I will review the licensing and requirements to publish tableau charts online.
* Improve the chart quality and add more data to  

##Background
Data About the Financial Status of Contra Costa County Local Governments

This repo contains fiscal data and analysis for local governments in Contra Costa County.

Each city and town in the County produces a Comprehensive Annual Financial Report.  Many have published reports for the Fiscal Year Ended June 30, 2017. For others, the latest is June 30, 2016.  You can see a repository of California CAFRs here:  http://www.govwiki.info/pdfs/General%20Purpose/?state=CA&year=. The repo also contains data extracted from 2017 CAFRs for selected cities in Contra Costa.

You can find budgets and other financial reports on each community's web site.

We have also provided data scraped from CalPERS reports showing current pension obligations and future pension contributions.

A possible resarch question that could be addressed by this data:  Are public employee pension costs crowding out other government spending priorities?  For a national invesigation of this question see:  https://gspp.berkeley.edu/research/working-paper-series/pensions-in-the-trenches-are-rising-city-pension-costs-crowding-out-public

#Some other relevant work
https://github.com/gitanupam/pd_maps

http://marcjoffe.pythonanywhere.com/maps/
