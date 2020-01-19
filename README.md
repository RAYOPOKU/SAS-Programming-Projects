# SAS-Programming-Projects
I recently took the Coursera SAS programming course and completed the two case studies. The completes course has 3 modules each of which will take 6 months to complete. I knocked all 3 out in 1 week. The case study in the final module "Practical SAS Programming and Certification Review SAS" was what I found most interesting. There were

1. The TSA Travel Case Study: 

In this case study, I analyzed TSA claims data collected between 2002 and 2017. The case study file was created by from publicly available data from the TSA and the Federal Aviation Administration, or FAA. The TSA data has information about claims and the FAA data has information about USA airport facilities. The case study data was created by concatenating individual TSA airport claims data, removing some extra columns, and then joining the concatenated TSA claims data with the FAA airport facilities data. 

The TSA Claims 2002 to 2017 CSV file has 14 columns and over 220,000 rows. 
The Claim_Number column has a number for each claim. Some claims can have duplicate claim numbers, but different information for each claim. Those claims are considered valid for this case study. Incident_Date and Date_Received columns have the date the incident occurred and the date the claim was filed. 
Claim_Type has a type of the claim. There are 14 valid claim types. 
The Claim_Site column has where the claim occurred. There are 8 valid values for claims site. 
The Disposition column has a final settlement of the claim. 
The Close_Amount column has dollar amount of the settlement. 
The Item_Category column has a type of items in the claim. The values in this column vary by year. Airport_Code and Airport_Name columns have the code and the name where the incident occurred. 
The County, City, State, and Statename columns have the location of the airport. 
The State column has a two letter state code and Statename has the full state name.

2. The World Toursim Case Study: 

Our task is to create 3 tables; 1. The cleaned_tourism table 2. the final_tourism table 3. the nocountryfound table

In it's original form, the tourism table consists of 23 columns and over 2,400 rows. 
The A column contains a numeric ID when a country name appears in the country column. 
The country column contains a variety of information such as country names, tourism type, inbound or outbound, and tourism categories such as the number of arrivals or departures from a country or expenditure in the country or other countries in US dollars. 

The series column contains the data collection method used by the country. 
Columns _1995 through _2014, contains scaled numeric data stored as text. 
The country column contains the information you need to properly convert this data to a numeric value. 
Values are US dollar amounts in millions for rows containing expenditure data and passenger count values for arrivals and departures are in thousands. For example, a scaled value of 21,719 for arrivals in thousands will be calculated by multiplying the number times 1,000 for a value of 21,719,000. 
The country_info table contains two columns and 250 rows. 
The continent column contains IDs for each continent. For example, one is North America, two is South America, and so on. Your document will list each value with the corresponding continent. The country column contains the name of each country.

Attached are the SAS Codes for both case studies.
