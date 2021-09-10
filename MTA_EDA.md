# Exploratory Data Analysis for New York City Subway Entries 


## Abstract

The goal of this project is to analyize subway entries daily and hourly based on stations to know peak hours and peak days of each station in order 
to help the NYC city government in their plan to balance the concentration of residents movements around the city as a defense mechanism against future pandamics.

## Design


### Background
The Government of New York City, headquartered at New York City Hall in Lower Manhattan.
Problem. The city government is responsible for public education, correctional
institutions, public safety, recreational facilities, sanitation, water supply, and welfare
services.

### Problem
New York City Government has a plan to balance the existence of the services of city
around the whole city as one of its defense mechanisms towards any health pandemic.
Services of the city include banks, universities, schools, companies, public institutions,
factories, and any place that the New Yorkers may need to go to regularly.

### Value
Identify what areas of the city are more crowded at what
time of the day and the week to prevent having more concentrations of people in specific
areas in specific times.


## Data
The New York subway MTA turnstile data is a series of data files containing
cumulative number of entries and exits by station, turnstile, date and time. Data files are produced weekly, data records are collected typically every 4 hours with
some exceptions.

• Time Interval (9-2019, 10-2019, 11-2019)

• Number of rows: 2676241

• Features:

|  Feature  | Description    |
| :----------:  | :----------: | 
|  C/A | Control Area (A002)  | 
|  UNIT | Remote Unit for a station (R051) | 
|  SCP | Subunit Channel Position represents an specific address for a device (02-00-00) |
|  STATION |   Represents the station name the device is located at    |
|  LINENAME  |  Represents all train lines that can be boarded at this station    |
|  DIVISION     |  Represents the Line originally the station belonged to BMT, IRT, or IND      |
|  DATE     |  Represents the date (MM-DD-YY) |
|  TIME   |   Represents the time (hh:mm:ss) for a scheduled audit event  |
|  DESC  | Represent the "REGULAR" scheduled audit event (Normally occurs every 4 hours) |
|  ENTRIES  |  The comulative entry register value for a device  |
|  EXITS |  The cumulative exit register value for a devic |


• Feature Engineering:
- Calculating entries from cumulative entries
- Dropping outliers
- Formatting Dates and Times
- Grouping data into stations
- Mapping with Day od week 

  

## Tools
Technologies: SQL, SQLite, Python, Jupyter notebook

Libraries: Numpy, Pandas, Matplotlib




