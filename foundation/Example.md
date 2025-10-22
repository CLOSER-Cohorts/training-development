---
title: Dataset example
collaborators: 
date: October, 10 2025
---

Look at the example questionnaire and corresponding dataset below.

<img src="img/Younglifeandtimes2011Qu.png" alt="Alt Text" width="425" height="900"> 

respondentID |	rsex |	yearsni	| placeliv |ethncat | memmec  | thisoct | oct2yrs | typeschl	| relschl
|------------|-------|-------|--------|-----------|-------|-------|-------|-------|------
1211 | 	2	| 16	| 2	|[closed data] |[closed data] | 1	| 1	| 2	| 5
1212 | 1	| 16	| 3	|[closed data] |[closed data] | 1	| 1	| 2	| 1
1213 | 1	| 16	| 2	|[closed data] |[closed data] | 1	| 4	| 2	| 3
1214 |  1	| 16	| 5	|[closed data] |[closed data] | 1	| 1	| 3	| 2
1215 |  2	| 16	| 3	|[closed data] |[closed data] | 4	| 4	| 2	| 2
1216	|  1	| 16	| 1	|[closed data] |[closed data] | 1	| 1	| 3	| 2
1217	|  1	| 16	| 2	|[closed data] |[closed data] | 1	| 1	| 2	| 2
1218	| 2	| 16	| 3	|[closed data] |[closed data] | 1 |	4 |	2	| 1
1219	|  2	| 16	| 2	|[closed data] |[closed data] | 1	| 1	| 2	| 2
1220	|  1	| 16	| 2	|[closed data] |[closed data] | 1	| 1	| 2	| 2


Variable metadata

| Name          |Label         | Description |	Value representation	| Data type | Unit of measurement | Valid range 
|---------------|--------------|--------------|-----------------------|-----------|---------------------|---------
respondentID    | Respondent ID number     | Anonymised ID assigned to respondent            |	Numeric                  	| positive integer          |    -               	| -  
yearsni         |  Years lived in Northern Ireland  |	Number of years respondent has lived in Northern Ireland            |	Numeric        	|  positive integer         | Year                  	|  0-16  
placeliv        | Description of the place respondent lives    |	How the respondent describes their locality    |	Text        	| integer     | -                  	|   -99 - 99
ethncat         | Ethnic group respondent belongs to      | Self-identified ethnic group	       |	 Text                  	|   String        |       -            	|   -
memmec         | Does the respondent consider themselves to be a member of a minority ethnic community       |	            |	 Codelist                    	| integer           | -                  	|   -99 - 2
thisoct         | What has respondent been doing since October 2011       |	            |	 Codelist                    	|     integer      | -                   	|   -99 - 99
oct2yrs         |  What does respondent think they will be doing in October 2013      |	            |	 Codelist               	| integer          | -                  	|   -99 - 99
typeschl        | Type of school respondent attends       |	Self-idenitfy type of school        |	Codelist  |	integer         	|    -99 - 99
relschl         | Religious orientation of school   |	Self-describe religious orientation of school      |	Codelist                	| integer           |  -99 - 99


| Name      | Unit type	| Population   | Universe       |Derived    |	Data provenance  |	Measurement provenance  |	Source reference
|---------------|----------|--------------|----------------|-----------|-------------------|-----------------|---------
| respondentID  | individual   |	resident of Northern Ireland who turned 16 in February and March 2011   |	Young person listed in the Child Benefit Register  | No    |                   	|        |
rsex            |              |	            |	                     	| No    |                	|        |
yearsni         |              |	            |	                     	| No    |                   	|        |
placeliv        |              |	            |	                     	| No    |                   	|        |  
ethncat         |              |	            |	                     	| No    |                   	|        |
memmec          |              |	            |	                     	| No    |                   	|        |
thisoct         |              |	            |	                     	| No    |                   	|        |
oct2yrs         |              |	            |	                     	| No    |                   	|        |
typeschl        |              |	            |	                     	| No    |                   	|        |
relschl         |              |	            |	                     	| No    |                  	|        | 

| name      | Missing value code	| Number of cases | Valid cases |Invalid cases    
|------------|-------|--------------|------------------------|-----------
respondentID    | -            |	10      |	10            	| 0          |           
rsex            |  -99         |	10      |	10            	| 0          |            yearsni         | -            |	10      |	10            	| 0          |                
placeliv        |-99           |	10      |	10            	| 0          |                
ethncat         |  -99         |	10      |	10            	| 0          |     
memmec          |  -99         |	10      |	10            	| 0          |      
thisoct         | -99          |	10      |	10            	| 0          |                    
oct2yrs         | -99          |	10      |	10            	| 0          |               
typeschl        | -99          |	10      |	10            	| 0          |                     	
relschl         | -99          |	10      |	10            	| 0          |                   



| Name          |Label         |	Description |	Value representation	| Data type | Unit of measurement | Valid range 
|---------------|--------------|--------------|-----------------------|-----------|---------------------|---------
respondentID    |              |	            |	                     	|           |                   	|   
year            |              |	            |	                     	|           |                   	|   
rsex            |              |	            |	                     	|           |                   	|   
ethncat         |              |	            |	                     	|           |                   	|        
memmec          |              |	            |	                     	|           |                   	|        
yearsni         |              |	            |	                     	|           |                   	|   
placeliv        |              |	            |	                     	|           |                   	|   
thisoct         |              |	            |	                     	|           |                   	|   
oct2yrs         |              |	            |	                     	|           |                   	|   
typeschl        |              |	            |	                     	|           |                   	|   
relschl         |              |	            |	                     	|           |                   	|   


| Name      | Unit type	| Population   | Universe       | Derived    |	Data provenance  |	Measurement provenance  |	Source reference
|---------------|----------|--------------|----------------|-----------|-------------------|-----------------|---------
| respondentID  |              |	            |	                     	|           |                   	|        |
year            |              |	            |	                     	|           |                   	|        |
rsex            |              |	            |	                     	|           |                   	|        |
ethncat         |              |	            |	                     	|           |                   	|        |
memmec          |              |	            |	                     	|           |                   	|        |
yearsni         |              |	            |	                     	|           |                   	|        |
placeliv        |              |	            |	                     	|           |                   	|        |  
thisoct         |              |	            |	                     	|           |                   	|        |
oct2yrs         |              |	            |	                     	|           |                   	|        |
typeschl        |              |	            |	                     	|           |                   	|        |
relschl         |              |	            |	                     	|           |                   	|        | 

| name      | Missing value code	| Number of cases | Valid cases |Invalid cases    |
|------------|-------|--------------|------------------------|-----------
respondentID    |              |	            |	                     	|           |  
year            |              |	            |	                     	|           |           
rsex            |              |	            |	                     	|           |                
ethncat         |              |	            |	                     	|           |                   	  
memmec          |              |	            |	                     	|           | 
yearsni         |              |	            |	                     	|           |              
placeliv        |              |	            |	                     	|           |                  
thisoct         |              |	            |	                     	|           |                  
oct2yrs         |              |	            |	                     	|           |              
typeschl        |              |	            |	                     	|           |                   	
relschl         |              |	            |	                     	|           |                 




Question metadata 

| Question label | Question name |Question text          |  Question instruction      | Response Domain        | Select type  | Codelist reference  | Variable reference  |             
|---------------|---------------|-----------------------|----------------------------|---------------------------|----------------------|--------------------|------------
| Q_1 | 1   | Are you male or female?    | -      |  Codelist        | Single select           |       | rsex
| Q_2 | 2   | How many years have you lived in Northern Ireland?    | Please write in          | Numeric         |         |       | yearsni  
| Q_3 | 3   | If you have not always lived in Northern Ireland, What other countries have you lived in?    | -      |  Text        |             |     
| Q_4 | 4   | Would you describe the place where you live as ...       |  -      |  Codelist       | Single select   |       | placeliv
| Q_5 | 5   | To which ethnic group do you consider you belong?      | -         | Text     |  -        |       | ethncat 
| Q_6 | 6   | Do you consider yourself to be a member of a minority ethnic community?      | -       | Codelist      | Single select   |       | memmec   
| Q_7 | 7   | What have you been doing since October 2011?  |  Please tick ONE box only | Codelist       | Single select  |        | thisoct  
| Q_8 | 8   | What do you think you will be doing in two years time, in October 2013?      | Please tick ONE box only  | Codelist          | Single select       |     | oct2yrs 
| Q_9 | 9   |  What type of school do you attend? If you have left school, what type of school did you last attend?  | -  | Codelist  | Single select      |       | typeschl   
| Q_10| 10  |  Would you describe your school as...        | -      | Codelist              | Single select     |    |   relschl 


| Question label | Question name |Question text          |  Question instruction      | Response Domain                                     | Select type  | Codelist reference  | Variable reference  |             
|---------------|---------------|-----------------------|----------------------------|-----------------------------------------------------|----------------------|--------------------|------------
|            |           |          |       |          |             |             | 
|      |             |     |   |  |        |       | 
|          |            |      | -  |  | -        | -        | -        |




Code and category metadata 


respondentID    |              |	            |	                     	|           |  
year            |              |	            |	                     	|           |           
rsex            |              |	            |	                     	|           |                
ethncat         |              |	            |	                     	|           |                   	  
memmec          |              |	            |	                     	|           | 
yearsni         |              |	            |	                     	|           |              
placeliv        |              |	            |	                     	|           |                  
thisoct         |              |	            |	                     	|           |                  
oct2yrs         |              |	            |	                     	|           |              
typeschl        |              |	            |	                     	|           |                   	
relschl         |   

rsex
| Codelist name     | Codelist label     | Codelist description                      | 
|-------------------|--------------------|-------------------------------------------|
| pers_sex          | Sex of person      | Indciates if reposndent self identificaties as male or female    |                  
  
| Codes | Category         | 
|------|-------------------|
| -99  |  Not answered     |                   
| 1    |  Male             |                   
|   2  |  Female           |     


memmec

| Codelist name     | Codelist label     | Codelist description                      | 
|-------------------|--------------------|-------------------------------------------|
| pers_ethnmi       | Member of an ethnic minority community    | Indicates if respondent self-identifies as a member of ethnic minorty community  |                  
  
| Codes | Category         | 
|------|-------------------|
| -99  |  Not answered     |                   
| 1    |  Yes              |                   
| 2    |  No               |    

placeliv

| Codelist name     | Codelist label     | Codelist description                      | 
|-------------------|--------------------|-------------------------------------------                    
| locality_des     | Description of locality  | Indicates how respondents describe where they live currently                   


| Codes | Category         | 
|------|-------------------|
| -99  |  Not answered                        
| 1    |  a big city                                 
| 2    | the suburbs or outskirts of a big city
| 3    | a small city or town                 
| 4    | a country village   
| 5    | or a farm or home in the country  
| 6    | Don't know 
| 99   | Missing  


thisoct + oct2yrs

| Codelist name     | Codelist label     | Codelist description                      | 
|-------------------|--------------------|-------------------------------------------                    
| Life_activity_now | Current education or employment status | Indicates whether respondent's employment and education status

| Codes | Category         | 
|------|-------------------|
| -99  | Not answered                        
| 1    | At to college or university full time                               
| 2    | Working full time
| 3    | Working part time               
| 4    | At college or university and working part time  
| 5    | On a training scheme
| 6    | Unemployed (Please say why you think you are unemployed)
| 7    | Other (Please write in)
| 99   | Missing  

| Codelist name     | Codelist label     | Codelist description                      | 
|-------------------|--------------------|-------------------------------------------                    
| Life_activity_2yrs | Percieved education or employment status in 2 years | Indicates how respondent's predict their employment and education status in 2 years

| Codes | Category         | 
|------|-------------------|
| -99  | Not answered                        
| 1    | Going to college or university full time                               
| 2    | Working full time
| 3    | Working part time               
| 4    | At college or university and working part time  
| 5    | On a training scheme
| 6    | Unemployed (Please say why you think you will be unemployed)
| 7    | Other (Please write in)
| 99   | Missing  

typeschl

| Codelist name     | Codelist label     | Codelist description                      | 
|-------------------|--------------------|-------------------------------------------                    
| Schl_type | Northern Irish school types | Description of school types in Northern Ireland as of 2011

| Codes | Category         | 
|------|-------------------|
| -99  | Not answered                        
| 1    | Planned integrated                              
| 2    | Grammar
| 3    | Secondary             
| 4    | Irish language
| 5    | Special school
| 6    | Other (Please write in)
| 99   | Missing  

relschl

| Codelist name     | Codelist label     | Codelist description                      | 
|-------------------|--------------------|-------------------------------------------                    
| Schl_rel | Religious make up of school | Describe Protestant and Catholic population of school

| Codes | Category         | 
|------|-------------------|
| -99  | Not answered                        
| 1    | all or nearly all Protestant                            
| 2    | all or nearly all Catholic
| 3    | mostly Protestant            
| 4    | mostly Catholic
| 5    | about half Protestant and half Catholic
| 6    | Other Don't know
| 99   | Missing  
 




