# Project Description
This project is for CSCA 5622 at CU Boulder. 

## Deliverable 1 
A Jupyter notebook showing a supervised learning problem description, EDA procedure, analysis (model building and training), result, and discussion/conclusion. 

**Please see Final_Notebook.ipynb**

## Deliverable 2
A video presentation or demo of your work. The presentation should be a condensed version as if you're doing a short pitch to advertise your work, so please focus on the highlights:

What problem do you solve?

What ML approach do you use, or what methods does your app use?

Show the result or run an app demo.

The minimum video length is 5 min, the maximum length is 15 min. The recommended length is about 10 min. Submit the video in .mp4 format.

**Please see presentation.mp4**

## Deliverable 3 
A public project GitHub repository with your work (please also include the GitHub repo URL in your notebook/report and slides).

**Please see this comment you're reading right now. Hello!**

## Details
In this project I collected a few datasets on countries - GDP per Capita, Population, Net Immigration Levels, Global Peace Index (GPI), AECLED Conflict Scores, and Social Progress Indexes. The goal was to use some of these metrics to analyze net inflow or outflow of immigrants to a country. 

### Motivations
What factors play into such an incredibly important decision to leave one's home country for an another? 
There is a lot of interesting discussion around what makes one country a good place to live. Some would say GDP or other economic factors are the most important. Others would say some concept of social progressiveness, access to opportunity, advanced infrastructure, or human rights. Still more would say people just want to go where they may be safe. Some of these factors are not easy to quantify and are highly subjective and often politically charged or biased. As a source of truth, I figured migration rates to and from countries would be the most objective and useful metric to start - again, migrating is not a decision that is taken lightly and is often a result of a lot of factors. If people are migrating from some country or to some country, there is likely a lot of interesting analysis to be done.
My hypothesis was that the reasons many people would be leaving a country are very simple. Disaster or conflict would be the most obvious reason. We also know that in general, moving is extremely expensive and difficult, so social factors or economonic factors being poor would probably not cause as much migration. On the other hand, the factors causing people to migrate into a country are likely far more complex and do depend highly on positive factors in the target country. Once you are forced out of somewhere by conflict, you are likely going to be looking for the best possible place to settle down.

### About the Data
GPI data is from https://worldpopulationreview.com/country-rankings/most-dangerous-countries
"The GPI report evaluates 163 countries that account for more than 99.7% of the world’s total population. The factors analyzed in the report are grouped into three different areas: Safety and Security, Ongoing Conflict, and Militarization. The factors used to compile this report include: the number of internal and external violent conflicts, level of distrust, political instability, potential for terrorist acts, number of homicides, and military expenditures as a percentage of GDP. A score is calculated for each of the 163 nations featured in the report based on these factors. The higher the score, the more dangerous the country is and the lower it ranks in terms of safety."

Conflict Index is from https://acleddata.com/conflict-index/
"The ACLED Conflict Index assesses every country and territory in the world according to four indicators – deadliness, danger to civilians, geographic diffusion, and armed group fragmentation – based on analysis of political violence event data collected for the past year. The top 50 ranked countries and territories are experiencing extreme, high, or turbulent levels of conflict."