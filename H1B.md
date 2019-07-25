# Predicting and Analyzing the case status of H-1B visa application to hire non-immigrant workers

This dataset was provided by the Office of Foreign Labor Certification (OFLC) where the date of the determination was issues on or after October 1, 2016 and on or before June 30, 2017. 

List Link: https://www.foreignlaborcert.doleta.gov/performancedata.cfm 

**What is H1B?**

The US H-1B visa is a non-immigrant visa that allows US companies to employ graduate level workers in specialty occupations that require theoretical or technical expertise in specialized fields such as in IT, finance, accounting, architecture, engineering, mathematics, science, medicine, etc. 

The procces of getting the visa is really complicated, takes up to 6 months and you can apply only during limited time. 

**Goal of the Project** 

 The goal for this project is to predict the case status of an application submitted by the employer and understand what parameters determines the case status. 

**Dataset and Attributes** 

The H-1B dataset from OFLC contained 40 attributes and 528,147 instances. The attributes are in the table below.

**H1B Disclosure Dataset **

1)CASE_SUBMITTED 

2)DECISION_DATE 

3)VISA_CLASS

4)EMPLOYER_NAME

5)EMPLOYER_STATE 

6)EMPLOYER_COUNTRY 

7)SOC_NAME 

8)NAICS_CODE 

9)TOTAL_WORKERS 

10)FULL_TIME_POSITION 

11)PREVAILING_WAGE 

12)PW_UNIT_OF_PAY

13)PW_SOURCE 

14)PW_SOURCE_YEAR 

15)PW_SOURCE_OTHER 

16)WAGE_RATE_OF_PAY_FROM 

17)WAGE_RATE_OF_PAY_TO 

18)WAGE_UNIT_OF_PAY 

19)H-1B_DEPENDENT 

20)WORKSITE_STATE 

21)WORKSITE_POSTAL_CODE 

22)CASE_STATUS*  - To be predicted

**CASE STATUS**

For the H-1B Dataset our class attribute is ‘CASE_STATUS’. There are 4 categories of Case Status. The values of Case_Status attributes are:

1) Certified 
2) Certified_Withdrawn 
3) Withdrawn 
4) Denied

Certified means the LCA of an employer was approved. Certified Withdrawn means the case was withdrawn after it was certified by OFLC. Withdrawn means the case was withdrawn by the employer. Denied means the case was denied OFLC.			 				 					 					 				 				 					 					 				 				 					 					 				 				 					 					 				 				 					 					 				 				 					 					 				 				 					 					 					 					 				 			 		



