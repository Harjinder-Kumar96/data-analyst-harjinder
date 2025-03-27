#  AWS Data Analytics Platform - Harjinder Kumar

##  Project Overview  
This project showcases my contributions to building an **AWS-based Data Analytics Platform (DAP)** for the **City of Vancouver**. The platform enhances **data-driven decision-making** in **urban planning** and **resource management**.  

## ** Key Contributions**  
- **Data Ingestion:** Set up AWS S3 for raw data storage.  
- **Data Profiling:** Used AWS Glue DataBrew to detect anomalies.  
- **Data Cleaning:** Standardized formats, removed duplicates.  
- **Data Cataloging:** Created AWS Glue Data Catalog tables.  
- **Data Summarization:** Generated insights using AWS Athena.  
- **Data Security:** Implemented IAM policies and AWS KMS encryption.  
- **Data Governance:** Managed access control via AWS Lake Formation.  
- **Data Monitoring:** Set up AWS CloudWatch, CloudTrail, and Config.    

##  Architecture Diagram 
![image](https://github.com/user-attachments/assets/62f8017b-43ac-46df-a99c-929620e68059)

##  Technologies Used  
- **AWS Services:** S3, EC2, Glue, Athena, QuickSight, IAM  
- **Programming Languages:** Python, SQL  
- **Tools:** AWS Glue DataBrew, AWS Pricing Calculator  

---

##  Data Processing Steps  

###  Step 1: Data Ingestion  
 **Created an S3 Bucket** for storing raw datasets.  
 **Uploaded data** using the AWS S3 web interface.  
 **Set up EC2 Instance** to automate data ingestion.  


###  Step 2: Data Profiling  
 **Analyzed missing values, inconsistencies, and duplicate entries.**  
 **Used AWS Glue DataBrew** for profiling.    

###  Step 3: Data Cleaning  
 **Standardized data formats (dates, text fields).**  
 **Removed duplicate and corrupted records.**  
 **Stored cleaned data in S3**   

###  Step 4: Data Cataloging  
 **Created AWS Glue Data Catalog** for structured metadata.  
 **Validated data using Athena SQL queries.**    

###  Step 5: Data Summarization  
 **Executed Aggregation Queries (ETL) in Glue.**  
 **Visualized data using AWS QuickSight Dashboards.**  
 **Stored summarized reports in S3**  

---

##  AWS Cost Estimation  
| AWS Service  | Monthly Cost | Yearly Cost |
|--------------|-------------|-------------|
| **S3 Storage** | $15.00  | $180.00  |
| **EC2 Instances** | $25.00  | $300.00  |
| **AWS Glue Jobs** | $10.00  | $120.00  |
| **Athena Queries** | $2.19  | $26.28  |
| **QuickSight Dashboards** | $20.00  | $240.00  |
| **Total Estimated Cost** | **$52.19**  | **$626.28**  |
 
#  AWS Data Analytics Platform Part 2
---
##  **Data Processing Steps**  

###  Step 1: Data Analysis  
 -Stored structured and unstructured data in Amazon S3
 -Used AWS Glue for ETL processing 
 -Queried data using Amazon Athena
 -Answered three business questions based on data analysis  

###  Step 2: Data Security  
-Implemented AWS IAM roles and policies for access contro  
-Enabled encryption at rest and in transit using AWS KMS 
-Secured data governance using AWS Lake Formation    

###  Step 3: Data Governance  
 -Configured AWS Lake Formation for metadata management 
 -Implemented fine-grained access policies  
 -Defined auditing capabilities to ensure compliance

###  Step 4: Data Monitoring  
 -Used AWS CloudWatch to monitor system health  
 -Enabled AWS CloudTrail to track user activity  
 -Set up AWS Config to track resource configurations 
 -Configured real-time anomaly alerts in CloudWatch
 
---

---
