# Team 12 MIST 4610 Group Project 2
# Team Name:
150061 Team 12
# Team Members:
1. Pierce Helou [@heloup](https://github.com/heloup)
2. Thomas Rogers [@thomas3rogers](https://github.com/thomas3rogers)
3.  Morgan Emmons [@morganemmons](https://github.com/morganemmons)
# Dataset Description:
Our dataset details the NYPD Shooting Incident Data. We obtained our dataset through the website provided(https://catalog.data.gov/dataset/nypd-shooting-incident-data-historic). Our dataset comprises various dimensions that represent a range of data types. It includes information such as the borough where the incident occurred, a description of the location of occurrence, and a general location description, all of which fall under the string data type. Other string-type data embedded in this data set include the race, sex, and age group of both the perp and the victim. Additional dimensions provide details about the date, specifically the month and year, and are categorized as the number (whole) data type. The final set of dimensions encompasses the date and time of the offense, classified as the "date & time" data type, and the latitude and longitude, both represented as the "number" data type with decimal precision. Collectively, these dimensions within the dataset allow viewers to gain an in-depth understanding and perspective of the data.

# Question 1:
When comparing NYPD shooting incidents across different racial groups, our primary question is: Among three specific racial groups, which one is associated with the highest number of incidents? Further, within each racial group, we aim to identify the age group most commonly involved in these incidents and if these incidents are most common amongst males or females.

Importance:
This question was interesting to us as a group as It allowed us to analyze the data of victims in multiple ways. The first way you could analyze the data is which race/ethnic group is most likely to be a victim of a shooting in New York City. This question allows us to see if their is an underlying prejudice found in shootings or if the shooting are more so at random. The Second way it allowed us to analyze data is by age group. Organizing by age group allows the graphs to show which age group is most at risk per each people group this could be useful in answering questions. The third way it allowed us to analyze is it showed us if Male or Female shootings are more common for each people group. This could be very useful in studying Questions such as " Are young adult males( late teens and early 20s) more likely to be at risk for being shot because of gang activity or are shooting deaths uniform throughout gender and age group?"


![Black Demographic not skewed](https://github.com/heloup/Group-Project-2/assets/148258161/d92ba8c2-58f3-4f7f-9661-d9dd4fbd4426)
**From the graph depicted above we can conclude that Black males aged 25-44 and 18-24 are most likely to be in a shooting related incident.**


![White Dem not skewed](https://github.com/heloup/Group-Project-2/assets/148258161/15e0468e-8bcb-4db2-9a2e-8afe52b52077)
**From the graph above we can conclude that White Males age 25-44 are most likely to be in an **incident.****

![Hispanic Dem not skewed](https://github.com/heloup/Group-Project-2/assets/148258161/61502dc8-2c7e-4dfb-9389-f5d673141dac)
**From the graph above we can conclude that Hispanic males from the age groups of 25-44 and 18-24 are in the most incidents.**


**Conclusion:** 
When diving into this problem we decided to depict 3 bar graphs that contains one race, gender, and age groups. We decided to use separate groups so that all of our data would not look to cramed together on one graph since there would be to many colums and not give the best representation of our data. The data from these graphs provides insights into who is involved, when incidents happen, and where they occur in NYPD shooting cases. We observe a higher involvement of men, and it raises questions about the factors behind this gender difference. The incidents are notably concentrated in age groups 25-44 and 18-24, emphasizing the need for focused efforts and community outreach for these age demographics. Additionally, there is a significant concentration of incidents within the African American demographic, prompting consideration of factors that may contribute to disparities in policing outcomes. Furthermore, the data highlights a concerning trend involving minors, with approximately 2000 incidents over the years, emphasizing the importance of prioritizing the safety and well-being of the city's youth. 





# Question 2:
Our next inquiry focuses on determining which borough has witnessed the highest number of NYPD shooting incidents over the past 17 years.

Importance:
We aim to investigate the trend of NYPD shooting incidents over the past 17 years to discern whether there is a notable increase. In light of the prevalent discussions on gun-related offenses, our analysis seeks to uncover patterns in the frequency of shooting incidents over time. Additionally, we intend to identify the borough that has experienced the highest level of activity in these incidents. With this analysis we hope to better understand the dynamics surrounding shooting incidents in New York City.

<img width="1228" alt="Screenshot 2023-12-04 at 1 34 53 PM" src="https://github.com/heloup/Group-Project-2/assets/148908686/2525b1cb-0b26-4498-b28b-649c290c5593">
**From the graph above we can conclude that a majority of the incidents occur in Multiperson public housing and apartment buildings.
**
# Manupulations applied to the data set for analysis:
We standardized the dataset by changing raw data into a more suitable format for our use. The data is quantifiable and does not include any duplications, irrelevant entries, redundancies, or inaccuracies. We spent time refining the data to ensure there was no use of incomplete, irrelevant, or inaccurate records. 

# Tableau Packaged Workbook:
The packaged workbook containing the visualizations shown above is attached to this repository [here.](https://prod-useast-b.online.tableau.com/#/site/httpswwwmist4610group12com/workbooks/1085949/views)

