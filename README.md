# Datasets

## Data Descriptions

### Poisson Process

 - **Blotter.csv**: Activity logs, summarizing incidents reported to Cal Poly University Police over the past 60 days. An updated log is generally posted by 9:00 AM the following day. This data was scraped on 4/15/2023. *[Source](https://afd.calpoly.edu/police/campus-reports/logs)*
 - **Crashes.csv**: SLO County vehicle accidents data. Contains data reported from 2/2/2013 to 2/15/2021. *[Source](https://tims.berkeley.edu/) (signup needed), [Codebook](https://tims.berkeley.edu/help/SWITRS.php#Codebook)*
 - **Earthquakes.csv**: Real-time earthquakes data from the past 30 days, updated every minute. This dataset was downloaded 3/10/2023. *[Source](https://earthquake.usgs.gov/earthquakes/feed/v1.0/csv.php)*
 - **Fireball.csv**: Real-time fireballs (meteors, etc.) data since 1980. This dataset was downloaded 4/26/2023. *[Source](https://cneos.jpl.nasa.gov/fireballs/), [Codebook](https://ssd-api.jpl.nasa.gov/doc/fireball.html)*

### Bivariate Normal

 - **BodyMeasures.csv**: Laboratory body measurements taken from 2017-2018. *[Source](https://wwwn.cdc.gov/nchs/nhanes/search/datapage.aspx?Component=Examination&CycleBeginYear=2017), [Codebook](https://wwwn.cdc.gov/Nchs/Nhanes/2017-2018/BMX_J.htm)*
 - **Fish.csv**: Growth data from the Redfish Lake Idaho Sockeye Salmon captive broodstock study from 2000-2010. *[Source](https://www.webapps.nwfsc.noaa.gov/apex/parrdata/inventory/tables/table/redfish_lake_growth_data), [Codebook](https://www.fisheries.noaa.gov/inport/item/56820)*
 - **OlympicFloor.csv**: Olympic artistic gymnastics floor exercise data for both genders. Years 2020, 2016 and 2012. *[Source](http://www.olympedia.org/event_names)*

### Lognormal

 - **Cities.csv**: Basic data on US cities, such as population and median income. Data updated as of 1/31/23. *[Source](https://simplemaps.com/data/us-cities)*
 - **Crimes.csv**: California reported criminal incidents by agency, 2020. *[Source](https://cde.ucr.cjis.gov/LATEST/webapp/#/pages/docApi)*
 - **COVIDHospitals.csv**: Data on COVID long-term care utilization from New York, as reported the week of 3/7/2021. *[Source](https://data.cms.gov/covid-19/covid-19-nursing-home-data), [Codebook](https://data.cms.gov/sites/default/files/2022-11/COVID-19%20Nursing%20Home%20Data%20Dictionary%2011.20.2022.pdf)*
 - **Reddit.csv**: Comments scraped from top 50 posts of all time in r/CalPoly subreddit. *[Source]([https://www.reddit.com/r/CalPoly/](https://www.reddit.com/r/CalPoly/top/?t=all)), [Codebook](https://praw.readthedocs.io/en/stable/index.html)*
 - **StackOverflow.csv**: 1000 comments from StackOverflow in 2010. *[Source](https://cloud.google.com/blog/topics/public-datasets/google-bigquery-public-datasets-now-include-stack-overflow-q-a)*
 - **Wildfires.csv**: California aggregate wildfire data, with data up until 3/20/23. *[Source](https://www.fire.ca.gov/incidents)*

### Benford's Law

 - **Bitcoin.csv**: Bitcoin most recent 1000 blockchain transactions on ledger, as of 4/17/2023. From Google's Bitcoin ETL BigQuery set. *[Source](https://cloud.google.com/blog/topics/public-datasets/bitcoin-in-bigquery-blockchain-analytics-on-public-data) (signup needed)*
 - **Population.csv**: US 2020 population estimate census data, by county. *[Source](https://www.census.gov/data/tables/time-series/demo/popest/2020s-counties-total.html), [Codebook](https://www2.census.gov/programs-surveys/popest/technical-documentation/file-layouts/2020-2022/CO-EST2022-ALLDATA.pdf)*
 - **SandyLoans.csv**: Data for loans given out to New England businesses in response to damage from Superstorm Sandy. *[Source](https://data.sba.gov/dataset/superstorm-sandy)*
 - **Stocks.csv**: Stock market indices S&P500, Nasdaq and Dow Jones as reported and scraped on 4/17/2023. *[Source](https://markets.businessinsider.com/index/components/)*

### Regression

 - **AirQuality.csv**: EPA Air Quality System (AQS) annual aggregate data by county, for 2022. *[Source](https://aqs.epa.gov/aqsweb/airdata/download_files.html#Annual), [Codebook](https://aqs.epa.gov/aqsweb/airdata/FileFormats.html#_annual_summary_files)*

### Actuarial Data

 - **LengthOfStay.csv**: Synthetic hospital length of stay data. *[Source](https://microsoft.github.io/r-server-hospital-length-of-stay/input_data.html)*
 - **Insurance.csv**: Synthetic medical insurance claims data modeled from 2008-2010 Medicare and Medicaid claims data. *[Source](https://www.cms.gov/Research-Statistics-Data-and-Systems/Downloadable-Public-Use-Files/SynPUFs/DE_Syn_PUF), [Codebook](https://www.cms.gov/Research-Statistics-Data-and-Systems/Downloadable-Public-Use-Files/SynPUFs/Downloads/SynPUF_DUG.pdf)*

## Attribution:

 - **AirQuality.csv**: From the US Environmental Protection Agency (EPA)
 - **Bitcoin.csv**: From Google BigQuery
 - **Blotter.csv**: From California Polytechnic State University, San Luis Obispo
 - **BodyMeasures.csv**: From the National Health and Nutrition Examination Survey (NHANES) 
 - **Cities.csv**: From SimpleMaps.com
 - **Crimes.csv**: From the FBI Summary Reporting System (SRS), through the FBI Crime Data API
 - **COVIDHospitals.csv**: From the Center for Medicare and Medicaid Services (CMS)
 - **Crashes.csv**: From the Berkeley Transportation Injury Mapping System (TIMS)
 - **Earthquakes.csv**: From the US Geological Survey (USGS)
 - **Fireballs.csv**: From NASA Center for Near Earth Object Studies (CNEOS)
 - **Fish.csv**: From the Northwest Fisheries Science Center (NWFSC), through NOAA
 - **Insurance.csv**: From the Center for Medicare and Medicaid Services (CMS)
 - **LengthOfStay.csv**: From Microsoft Machine Learning Services
 - **OlympicFloor.csv**: From Olympedia.org
 - **Population.csv**: From the US Census Bureau
 - **Reddit.csv**: From Reddit, scraped with Python Reddit API Wrapper (PRAW)
 - **SandyLoans**: From the US Small Business Administration (SBA)
 - **Stocks.csv**: From Business Insider
 - **StackOverflow.csv**: From Google BigQuery
 - **Wildfires.csv**: From the California Department of Forestry and Fire Protection (CAL FIRE)
