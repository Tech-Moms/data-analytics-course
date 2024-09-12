<img width="200" alt="Tech-Moms Logo Vertical" src="https://github.com/user-attachments/assets/02aae052-a29d-493b-bac1-a884f84a6891">

# Tech-Moms Student SQL Analysis & Report 

In this assignment, you will use Deep Note, a data analysis tool, to explore the Tech Moms applicant dataset using SQL. You will upload the applicant dataset into Deep Note and answer key questions to gain insights from the data.

## Step 1: Create a Deep Note Account & Upload Data 

Deepnote.com is a collaborative data science notebook platform designed for data analytics and data science work. It allows users to write and run code in SQL (as well as Python and R) directly within the browser, making it accessible and easy to use without requiring software installation.

- [x]  Go to [Deep Note](https://deepnote.com/) and create a free account if you haven't already.
- [x] Download the `.csv` file of the Tech Moms applicant dataset provided to you.
- [x] In Deep Note, create a new project.
- [x] Upload the `.csv` file into your project.

Video: [Overview, Create a Deep Note Account, & Upload Data](https://www.loom.com/share/5fc400d191dd414088c900cadbc439e5?sid=80486bf3-c3b9-400d-897e-f8f82eabd741)

## Step 2: Analyze the Data
Use Deep Note's built-in SQL editor to explore the dataset and answer the following questions:

1. **How many applications has Tech Moms received?**
   - [ ]  Write a query to count the total number of applications.
   - Example SQL:
    ```
    SELECT
     COUNT(distinct Contact_ID) 
    FROM [your_table_name];
    ```

2. **How many applications were assigned a cohort?**
   - [ ] Determine how many applicants were successfully assigned to a cohort.
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
   - [ ] Find out the total number of children supported by the Tech Moms programs using the available data.
   - Example SQL:
   ```
   SELECT
     SUM(Children)
   FROM
     [your_table_name]
   WHERE Applicant_Status = 'Assigned Cohort';
   ```
     
4. **Etc** 
     - [ ] Answer at least 10 additional questions using SQL

## Step 3: Submission
- [ ] After completing the analysis, create a [report](https://github.com/Tech-Moms/data-analytics-course/blob/main/module_3/report.md) in a google doc summarizing your findings.
- [ ] Email your completed google doc to data@tech-moms.org

  
