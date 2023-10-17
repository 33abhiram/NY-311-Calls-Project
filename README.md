# NY-311-Calls-in-R
** Click on this website to view the final output of my code: 

## Project Goal
This project was assigned to me as a Final Exam for my course Statistics for Informatics during my freshman year at the University of Texas at Austin, and I acknowledge that all code was written by me in RStudio, using class notes and reliable documentation as reference.

In this project, I use several packages in R to clean, filter and create reports on over 1 million rows of data about New York city's 311 calls, which is a dataset that contains 311 line complaint data for years 2011 and 2012. The "311" number is a hotline that people can dial to connect with city representatives to report problems, seek assistance, or obtain information on a wide range of topics. My goal was to extract valuable insights and find trends in the data that could be turned into actionable hypotheses and aid current and future residents of New York city.

## Data Dictionary
The raw dataset can be found on the NYC 311 website here: https://data.cityofnewyork.us/Social-Services/NYC-311-Data/jrb2-thup. The relevant table columns are as follows:

CreatedDate - date the comlpaint was registered

ClosedDate - date the complaint was terminated/resolved

Agency - Agency Code handling the complaint

AgencyName - Agency Full Name handling the complaint

ComplaintType - Type of Complaint

Descriptor - Brief description of complaint

Borough - Borough the complaint was registered in

IncidentZip - Zip code the complaint was registered in

responsetime (user-defined variable) - duration of the complaint

## Results
After thorough analysis, I found that the key factors that affect the response time of a complaint are Borough, type of complaint and agency. All other factors seem to have either weak or no correlation with the response time variable. Based on this, I would advise NYC authorities to optimize resource allocation, streamline services and enhance efficiency in their response system, using only these factors as reference. This would help result in quicker complaint resolution and increased resident satisfaction, leading to a more responsible government. Moreover, these insights could potentially be used to inform future policies and strategies, ultimately improving the quality of life for New York City residents and contributing to the city's overall development and responsiveness.
