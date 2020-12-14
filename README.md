# STAT184-FinalProject
Fall-2020 STAT184 Final project 

# Guiding Question: How gun-related violence affect the United States?

  The US is one of the few countries in which the right to bear arms is constitutionally protected. A consequence of this is that the level of gun voilence is very high compared to other countries. For instance, America has six times as many firearm homicides as Canada, and nearly 16 times as many as Germany. 
  
  Based on Wikipedia, Gun violence in the US results in tens of thousands of deaths and injuries annually. In 2013, there were 73,505 nonfatal firearm injuries which included 11,208 homicides, 21,175 suicides, 505 deaths due to accidental or negligent discharge of a firearm, and 281 deaths due to firearms use with "undetermined intent". 
  
  For this project, I have performed a deep exploration on this Dataset of gun violence incidents reported in US by, Gun Violence Archive (GVA), a not for profit corporation formed in 2013 to provide free online public access to information about gun-related violence in the United States.

## Data sources

### Primary data source: gun-violence-data_01-2013_03-2018.csv  (73.1 MB)
  I found this dataset from Kaggle website, it is a csv file called Gun Violence Data which contains data for all recorded gun violence incidents in the US between January 2013 and March 2018.
[link](https://www.kaggle.com/jameslko/gun-violence-data)

### Supporting data: ZipGeography dataset from DataComputing package

  As for this project, I want to perform some relationship between incidents and location, I choose the ZipGeography dataset from DataComputing package which includes the population for 53 states. 

## Conclusion & Summary
  After wrangled the two datasets and construct all these graphs, I have found several idea about the gun-related incidents
  
  * The trend is unfortunately upward. The number of incidents increased year-on-year from 2013 to 2017. The number of incidents in Q1 2018 is lower that this number in Q1 2017, which can be seen as a cautiously positive sign.
  
  * On average, the number of incidents is lower in autumn/winter than in spring/summer. Which means November and December has less incidents than July and August. And the reason might because holidays tend to have more incidents.
  
  * After joining the State_ZipGeography table, Alaska came out as the (to me surprising) state with the relatively highest number of incidents. Besides Alaska, Louisiana and Delaware are also states with high average incident numbers. The safest state regarding the relative number of incidents is Hawaii. However, Alaska has a relatively low ratio of victims (number of people killed + injured) per incident.
  
  *The incident characteristics offer a wealth of information. Altogether 110 categories were used to describe the incidents. On a high level, it for instance explains the low victims/incidents ratio of Alaska. However, categories such as terrorism, gang, and drug involvement were also recorded.
  
  With all these information, we can conclude that gun-related incidents are a very sever thing happen around us, and we cannot just let it keep increasing, instead, we should take gun control more seriously. 

