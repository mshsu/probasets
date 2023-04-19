# STAT400 Datasets

## Data Descriptions

### Poisson Process

 - **Blotter.csv**: Activity logs, summarizing incidents reported to Cal Poly University Police over the past sixty days, appear with the most recent log at the top of the list. An updated log is generally posted by 9:00 AM the following day. This data was scraped on 4/15/2022. *[Source](https://afd.calpoly.edu/police/campus-reports/logs)*
 - **Crashes.csv**: The Transportation Injury Mapping System (TIMS) has been developed over the past ten-plus years by SafeTREC to provide quick, easy and free access to California crash data, the Statewide Integrated Traffic Records System (SWITRS), that has been geo-coded by SafeTREC to make it easy to map crashes. Contains data reported from 2/2/2013 to 2/15/2021. *[Source](https://tims.berkeley.edu/) (signup needed), [Codebook](https://tims.berkeley.edu/help/SWITRS.php#Codebook)*
 - **Earthquakes.csv**: Real-time earthquakes data from the past 30 days, updated every minute. This dataset was downloaded 3/10/2023. *[Source](https://earthquake.usgs.gov/earthquakes/feed/v1.0/csv.php)*

### Bivariate Normal

 - **AirQuality.csv**: EPA Air Quality System (AQS) annual aggregate data by county, for 2022. *[Source](https://aqs.epa.gov/aqsweb/airdata/download_files.html#Annual), [Codebook](https://aqs.epa.gov/aqsweb/airdata/FileFormats.html#_annual_summary_files)*

### LogNormal

 - **Cities.csv**: Basic data on US cities, such as population and median income. *[Source](https://simplemaps.com/data/us-cities)*
 - **COVIDHospitals.csv**: Data on COVID inpatient hospital utilization, as reported on 3/7/2021. *[Source](https://data.cms.gov/covid-19/covid-19-nursing-home-data), [Codebook](https://data.cms.gov/sites/default/files/2022-11/COVID-19%20Nursing%20Home%20Data%20Dictionary%2011.20.2022.pdf)*
 - **Wildfires.csv**: California aggregate wildfire data, with data up until 3/20/23. *[Source](https://www.fire.ca.gov/incidents)*

### Benford's Law

 - **Population.csv**: US 2020 population estimate census data. *[Source](https://www.census.gov/data/tables/time-series/demo/popest/2020s-counties-total.html), [Codebook](https://www2.census.gov/programs-surveys/popest/technical-documentation/file-layouts/2020-2022/CO-EST2022-ALLDATA.pdf)*
 - **Stocks.csv**: Stock market indices S&P500, Nasdaq and Dow Jones as reported and scraped on 4/17/2023. *[Source](https://markets.businessinsider.com/index/components/)*
 - **Bitcoin.csv**: Bitcoin most recent 1000 blockchain transactions on ledger, as of 4/17/2023. From Google's Bitcoin ETL BigQuery set. *[Source](https://cloud.google.com/blog/topics/public-datasets/bitcoin-in-bigquery-blockchain-analytics-on-public-data) (signup needed)*

### Actuarial Data

 - **LengthOfStay.csv**: Synthetic hospital length of stay data. *[Source](https://microsoft.github.io/r-server-hospital-length-of-stay/input_data.html)*
 - **Insurance.csv**: Synthetic medical insurance claims data modeled from 2008-2010 Medicare and Medicaid claims data. *[Source](https://www.cms.gov/Research-Statistics-Data-and-Systems/Downloadable-Public-Use-Files/SynPUFs/DE_Syn_PUF), [Codebook](https://www.cms.gov/Research-Statistics-Data-and-Systems/Downloadable-Public-Use-Files/SynPUFs/Downloads/SynPUF_DUG.pdf)*

## Attribution:

 - AirQuality.csv: From the US Environmental Protection Agency (EPA)
 - Blotter.csv: From California Polytechnic State University, San Luis Obispo
 - Cities.csv: From SimpleMaps
 - COVIDHospitals.csv: From the Center for Medicare and Medicaid Services (CMS)
 - Crashes.csv: From the Berkeley Transportation Injury Mapping System (TIMS)
 - Earthquakes.csv: From the US Geological Survey (USGS)
 - Insurance.csv: From the Center for Medicare and Medicaid Services (CMS)
 - LengthOfStay.csv: From Microsoft Machine Learning Services
 - Population.csv: From the US Census Bureau
 - Stocks.csv: From Business Insider
 - Wildfires: From the California Department of Forestry and Fire Protection (CAL FIRE)
