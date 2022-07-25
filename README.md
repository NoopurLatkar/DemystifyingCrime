# DemystifyingCrime
Performed exploratory data analytics on crime in New York, USA over last 16 years

Youtube link to presentation : https://www.youtube.com/watch?v=yarRlu-OA6c <br>
Hosted on drive : https://drive.google.com/drive/u/1/folders/1xaZgcmBhzs2EY2FnoVgHzXMoOGM5o0O2

# Motivation

Crime mapping and analyzing peculiar trends and patterns in crime incidents that have happened previously across the city would help police reallocate their resources to specific locations that need attention at particular hours to inhibit crime. It would also highlight racial discrimation if any, and draw attention to being fair and equal with police methods of dealing with criminals hailing from diverse socio-cultural backgrounds. It also serves as a useful tool for civilians to be aware and more vigilant of their surroundings.
<br>
<br>

New York has been divided into 5 boroughs -
- Bronx
- Manhattan
- Brooklyn
- Queens
- Staten Island

Our study ranges across -
- 5 boroughs of New York
- Through years 2006 to 2020

- Astonishing 38.5% increase in overall index crime in NYC this year
- Your chance of being a victim of violent crime in New York is 1 in 172
- Inspiration of analyzing trends and patterns to inhibit crime sparked from a Netflix Series MindHunters that we are a big fan of.

# Agenda : Crime Mapping

- When and where are majority crimes happening? How has that changed over time?
(Time series analysis of crime numbers and evolving crime types)
- Characteristics of criminals and their socio-cultural backgrounds
- Gun violence and its distribution across different geolocations
- Impact of social events and public holidays on shooting incidents
- Seasonal trend of shootings across months on the year, days of the month and hours of the day

# Related Work

The idea sparked while discussing Mind Hunters, a tv show we are interested in. While the series is based on past psychological experiences of people that set them on the wrong path, in this project we will be focusing on the aspects that we found clear evidence of. Factors like unemploybility, income disparity, educational influence could be strong contributors to increasing crime in today's world.

# Data

This research uses an extensive database of criminal records from court summons, the time and location of crime and crime type distribution in the famous city of New York.

- <b> NYPD Court Summons Data (2006 - 2021)
>  Summary </b> : A list of every criminal summons issued in NYC from year 2006 through the end of the previous calendar year. We have focused on the crime location (latitude and longitude features), type of crime, time of crime, demographic information on the criminal (age, gender, race) and crime distribution across years <br>
> https://data.cityofnewyork.us/Public-Safety/NYPD-Criminal-Court-Summons-Historic-/sv2w-rv3k <br>
 Rows : 5.3M <br>
 Columns : 17 <br>


- <b> NYPD Shooting Incident Data (2006 - 2022)
>  Summary </b> : Represents all shooting incidents in NYC from 2006 to 2022 and includes information about the event, the location and time of occurrence. Information on the suspect and victim demographics have also been explored to understand the nature of shooting/criminal activity. <br>
> https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8 
https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Year-To-Date-/5ucz-vwe8 <br>
> Rows : 25.6K <br>
> Columns : 19 <br>

- <b> New York State Crime Type (1990 - 2018) 
>  Summary </b> : Index crime data consists of types of crime including minor crimes like burglary, larceny, motor vehicle theft etc. and major crimes like rape, murder and gun violence, collected from more than 500 New York State police and sheriff’s departments. We have focused on the evolvemnet of different crime types and their yearly trends. <br>
> https://www.kaggle.com/new-york-state/new-york-state-index-crimes <br>
> Rows : 19957 <br>
> Columns : 15 <br>

Loosely based on : Criminals and their background - Why someone did a crime? <br>
https://datasetsearch.research.google.com/search?query=criminal%20behavior&docid=L2cvMTFyampsMmpycw%3D%3D <br>

*Data will be filtered and cleaned based on the scope of the questions we will answer. All of the data will not be used.

# Questions

- What questions would you like to answer using the data set? Enumerate and briefly discuss at least three interesting and non-trivial questions. How do you plan to address these questions? Briefly sketch your workflow of what you plan to do.
> - What are the correlation between unemployment/income/social indicator and crime rates? What are the impacts of these on the latter?
> - How does education influence crime? Do less educated people or college-dropouts have a higher tendency of turning into criminals? Or does higher education contribute to white-collar crimes like frauds and scams?
> - Have the number of crimes increased/decreased over time? And how have crime types evolved over time? Is there a seasonal trend? Does is spike over major social events like New Years Bash or Black Friday?
> - Who makes up of the majority of criminals? What are the characteristics? What is their social or cultural background?
> - When and where are crimes happening? How had that changed over time? 

# Possible Findings and Implications

> - There is expected to be a negative correlation between socio-economic characteristics like income with crime rates.
> - The general market indicators (unemployment and income) have correlation with overall crime trend. 
> - Higher educated people have lower crime rates. However, there may be specific type of crime where there are more higher educated than those lower educated.
> - Locations with high crime rate may continue to have high crime rate, as those that stay in those areas are those that don't have the ability nor resouces to move out.
> - Crime rates increase before holiday seasons as people who need money may commit robbery to get money.
> - Crime rates would increase at night than in broad daylight.
