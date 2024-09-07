<img width="377" alt="Tech-Moms Logo Vertical" src="https://github.com/user-attachments/assets/02aae052-a29d-493b-bac1-a884f84a6891">

# Tech-Moms Student SQL Analysis & Report 

In this assignment, you will use Hex, a data analysis tool, to explore the Tech Moms applicant dataset using SQL. You will upload the applicant dataset into Hex and answer key questions to gain insights from the data.

## Step 1: Create a Hex Account
1. Go to [hex.tech](https://hex.tech) and create a free account if you haven't already.
2. Once your account is set up, log in to access the Hex workspace.

## Step 2: Upload the Dataset
1. Download the `.csv` file of the Tech Moms applicant dataset provided to you.
2. In Hex, create a new project.
3. Upload the `.csv` file into your project by clicking on the data tab, then “Add Data” and select “Upload Data” to choose your file.

## Step 3: Analyze the Data
Use Hex's built-in SQL editor to explore the dataset and answer the following questions:

1. **How many applications has Tech Moms received?**
   - Write a query or script in Hex to count the total number of applications.
   - Example SQL:
    ```
    SELECT
     COUNT(distinct Contact_ID) 
    FROM [your_table_name];
    ```

2. **How many applications were assigned a cohort?**
   - Determine how many applicants were successfully assigned to a cohort.
   - Example SQL: 
   ```
   SELECT 
    Applicant_Status, 
    COUNT(distinct contact_ID) 
   FROM [your_table_name]
   WHERE Applicant_Status = 'Assigned Cohort' 
   GROUP BY Applicant_Status;
   ```

3. **How many children are supported through Tech Moms programs?**
   - Find out the total number of children supported by the Tech Moms programs using the available data.
   - Example SQL:
  ```
  SELECT
    SUM(Children)
  FROM
    [your_table_name]
  WHERE Applicant_Status = 'Assigned Cohort';
  ```
     
4. **Etc** 
     - Leverage your previous Excel/Google Sheets analysis to ask additional questions - but this time in SQL!
     - Answer at least 10 additional questions using SQL 

## Submission
- After completing the analysis, create a [report](https://github.com/Tech-Moms/data-analytics-course/blob/main/module_3/report.md) in google doc summarizing your findings.
- Email your completed google doc to data@tech-moms.org

  
