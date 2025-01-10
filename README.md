# NewYork-Minute: Evaluating Emergency Response Across Boroughs 

## Project Goal
This project investigates emergency response services across New York City's five boroughs. We aim to identify disparities in emergency response times and incident frequencies to understand how borough-specific factors influence public safety and emergency services outcomes.

## Summary of Approach 
We analyzed two key datasets from NYC Open Data:
- Emergency Response Data: Includes incident types, locations, and response times.
- 911 Calls for Service Data: Details 911 call entries by borough and incident type.

The analysis focused on:
- Identifying boroughs with the highest incident rates.
- Comparing emergency response times across boroughs.
- Exploring correlations between incident volume and response efficiency.

We used R Studio for data cleaning, visualization, and analysis, leveraging clustering and geospatial techniques to uncover patterns in emergency services.

## Challenges:
- Data Volume: The initial dataset had over 40 million rows. We filtered it to focus on 2023 data, reducing it to a manageable size.
- Data Quality: The dataset contained null values and inconsistent formats, requiring rigorous cleaning.
- Geospatial Limitations: Incomplete location data affected the precision of mapping incidents and response times.


## Key Findings
- Manhattan recorded the highest number of incidents in 2023.
- The average emergency response time across all boroughs was approximately 40 minutes.
- Brooklyn and Manhattan exhibited the highest call volumes during summer months.
- Non-critical incidents were most frequently reported.
- Incidents predominantly occurred during daytime hours, especially in Brooklyn.
- There is a partial correlation between incident reports and 911 calls, with Manhattan and Brooklyn showing consistency in both datasets.

![image](https://github.com/user-attachments/assets/9d43bee6-18e4-4a8c-b089-ea01d1f368de) ![image](https://github.com/user-attachments/assets/e0f14471-cc49-46a4-811a-5a8d48afd2cd)










