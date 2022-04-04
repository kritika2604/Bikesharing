# Bikesharing Analysis
Visualizing bikesharing data with Tableau <br/>
<img width="560" alt="image" src="https://user-images.githubusercontent.com/94858846/161479750-dd6a5fa2-afe3-471b-8279-978e84462884.png">

 


## Overview
### Purpose
To analyse the bike sharing business and gathering inferences from the successful New York Citibike business model. 

### Resources
**Data source:**  [Citibike trip histories for the month of August 2019](https://ride.citibikenyc.com/system-data)<br/>
**Applications used:** Tableau public, Jupyter Notebook

## Results <br/>
This anaylsis was done on a dataset with a count of 2,344,224 trips in NY city using citibikes during the month of August. <br/> 

<img width="128" alt="image" src="https://user-images.githubusercontent.com/94858846/161475756-a5e76eae-7e04-4ce0-b097-99d601e1cd90.png">

The raw data had a wrong data type in the "datetime" column which was modified using Pandas.

The following conclusions were made:

1. The top starting and end locations for bike share is found in the main downtown area where commute is a probable challenge due to traffic, parking unavailability and several other factors relying on higher population density.<br/>
 <img width="796" alt="image" src="https://user-images.githubusercontent.com/94858846/161476219-a94000bd-adb2-40c5-a169-c799c09b3d36.png"> <br/>
 <img width="796" alt="image" src="https://user-images.githubusercontent.com/94858846/161476613-69822441-3f3c-4f8b-bd59-424bdf876d21.png"> <br/>
 

2. The length of time that bikes are checked out for all riders can be seen to be dropping down heavily by the end of 60 mins. <br/>
<img width="642" alt="image" src="https://user-images.githubusercontent.com/94858846/161477860-42221c81-0736-45ff-af07-dc94898caa27.png">


3. Male riders dominate the riders ratio as seen in the below checkout times by gender viz. <br/>
<img width="803" alt="image" src="https://user-images.githubusercontent.com/94858846/161476832-02801e95-a766-4f2d-aa01-58af9be2693c.png"> <br/>


4. The ridership can be seen on a high during the office hours of the week. (starting from 6am to 9am in the morning and 4 pm to 7pm in the evening hours) <br/>
 Wednesday, though a weekday, lacks ridership by quite a margin. <br/>
 During weekends, the ridership sees an increase on Saturdays from 9 am until noon. <br/>
 The yellow areas in the heat map below indicate possible time windows for scheduled maintenance of the bikes (between 2 am to 4am). 
 <img width="477" alt="image" src="https://user-images.githubusercontent.com/94858846/161477217-89f55b3e-546a-4d0e-8ae0-423a1977285f.png">


5. Below chart shows the ridership based on gender 
<img width="628" alt="image" src="https://user-images.githubusercontent.com/94858846/161478385-816cdb51-f429-480c-b201-b78cdb9aaa82.png">


7. The subscription to ridership allows more customers to opt for bike sharing services for regular commute to the metropolitan city. <br/>
 Guest customers can be seen opting for citibikes during the weekends majorly. <br/>
<img width="874" alt="image" src="https://user-images.githubusercontent.com/94858846/161478465-b3d6d8c2-d121-4f8d-8ee3-b95d5cf6a27a.png">


## Summary:
The bike sharing business should focus on following:
- Availability of bikes during the weekdays in the downtown areas during peak office hours,
- Maintenance window to be 2am to 4am,
- Female riders to be provided with some kind of special offers to encourage ridership,
- Since this data is only for the month of August 2019, in my opinion complete year data analysis will give more accurate insights (perhaps winter months can be avoided or can be generalised)


