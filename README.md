# Cincinnati 311 (Non-Emergency) Service Requests Dashboard (Power BI)
## Introduction
This project analyzes service requests in Cincinnati to identify trends, response times, and geographical hotspots using Power BI. The database connection is available to the public and is provided by Cincinnati through OData. Power BI was used for the entire data connection, transformation, and visualization process. The project revealed a number of insights. Most requests remain open and exceed estimated resolution times. Certain departments handle far more requests than others: Public Services often handles more requests than the other departments combined, and is followed in request volume by Cincinnati Building Department, Department of Transport and Energy, the City Manager's Office, and the Police Department.

Some anomalies existed in the dataset. Some requests had an "update time" that preceded the filing of the request, in some cases by months. A few select requests related to areas outside of the Cincinnati area. All anomalies were ignored for analysis. There were also issues relating to Power BI failing to recognize certain zip codes; such issues were resolved by pairing the zip code with latitude and longitude data, which exists in the database.


## Dashboard Screenshots
### Overview
![image](https://github.com/user-attachments/assets/ea487036-1c56-4a32-b62d-be03fb2af601)

### Service Performance Analysis
![image](https://github.com/user-attachments/assets/cfd3b91e-5c4e-400e-bace-07de9c2bef31)

### Geographical Insights
![image](https://github.com/user-attachments/assets/62e736df-4883-40ea-9e64-e95c95adca44)

### Agency Performance
![image](https://github.com/user-attachments/assets/680e9d8c-91b9-424e-9e0c-5db29c953cb1)

### Pest Control
![image](https://github.com/user-attachments/assets/9294ad8a-f8f8-4cc1-8e62-65983efc275d)

### Waste Management
![image](https://github.com/user-attachments/assets/00569ef9-c36b-455d-84c2-fb348c94b5d7)

### Public Safety
![image](https://github.com/user-attachments/assets/60d13840-d60a-4b21-b5bc-38e0bafe6a9e)
