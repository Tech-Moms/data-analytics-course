# Choose Your Adventure Week 

This week is "Choose Your Adventure" week where you go deeper on a topic of your choice - either Data Visualization, SQL, BI tooling, Excel or Google Sheets, or even trying your hand at Python or R if you are interested! 
Using our class format  - find a series of video lessons and watch and complete them. Then choose a data set and analyze it in your prefered tool, leveraging the video lesson you watched to complete the assignment. 
# Video Lessons: 

- [x] Curate the videos you watched for your topic of choice and add here under "Video Lessons".


- [x] Ideas for videos could be Alex the Analyst videos on advanced excel topics, intermidiate SQL, or intro to Python from his [Data Analytics Bootcamp](https://www.youtube.com/watch?v=PSNXoAs2FtQ) series.

# Assignment: 

- [X] Choose a data set that interest you to analyze, using the skills you learned in the video lessons.
- [x] ### Do Before Class:  

_Edit the markdown file with an x in the checkbox when complete, then commit changes._

# Tech Moms Student Demographic Dashboard Project

In this hands-on project, you will help Tech Moms analyze their applicant and student data in order to complete their annual non-profit report.

## Project Overview

The Leadership team is preparing to release their 2024 Tech Moms Survey Report. Survey reports are typically data-driven. They are important for non-profits because they provide transparency and demonstrate impact, which are crucial for sustaining donor support. The team needs to know the updated numbers for their student graduate survey. They share a .csv file titled [Tech-Moms Annual Survey Data](https://docs.google.com/spreadsheets/d/1Rf9-nhBHtUWr0t4c0paNZaaJhFpDMU8lAIbeBR_uk0Q/edit?usp=sharing). The team asks that you analyze the data and provide them with insights into the updated student demographic numbers.

Your deliverable will be a “Student Survey” Dashboard built in the spreadsheet software of your choice - Excel or Google Sheets.

## Complete the Following Steps:

### Step One: Get to Know Your Data

- [x] Review the Tech Moms 2023 Annual Report - paying special attention to the Student Demographic sections
- [x] Download the [Tech-Moms Annual Survey Data]
- [x] Open the .csv file in the spreadsheet tool of your choice - Excel or Google Sheets
- [x] Start by evaluating the columns to understand what data you’re working with
- [x] Create a new tab, “Data Dictionary” and copy the columns -> go to new tab -> paste “transposed”. This will paste the columns vertically.
- [x] Add a row at the top of the Data Dictionary tab. In A1, type “Column Column Name” & in B1, type “Column Description”. Write a short description of each column based on your best-educated guess (you can also use ChatGPT to help with this).
- [x] Add a tab “Questions” as you come across questions about the data. You can add them here. These are questions you can ask the data owners (aka leadership team) to help clarify any questions you may have about the data set.

Video: [Get to Know Your Data](https://www.loom.com/share/c726c715650a4371bce3ee3c1cec6a4e) 

### Step Two: Clean the Data

- [x] You know that you only want data as of July 31th, 2024, so you will make a copy of the “raw” data by duplicating the tab & rename it to “Analysis”. Rename the original tab to “raw”.
- [x] In the “Analysis” tab, review the data in the “Create Date” column. Sort it from oldest to newest. Scroll to the bottom of the spreadsheet and delete any rows with the creation date after July 31st, 2024.
- [x] Check for duplicates and erase any duplicate data.

Video: [Clean the Data](https://www.loom.com/share/cab3f42f344a4b00a13d52e8bd892f87)

### Step Three: Start Analyzing (aka Asking Questions of the Data)

The leadership team has asked you to answer the following questions:

- [x] How many total applicants are there?
- [x] How many applicants were assigned a cohort?
- [x] What is the number of total children of all applicants?
- [x] What percentage of applicants are veterans?
- [x] What percentage of applicants identify as LGBTQ+?
- [x] What percentage of applicants do not have laptops?
- [x] What is the most number of children of any applicant?
- [x] What is the average number of children among all applicants?
- [x] What is the average number of children of applicants that were assigned a cohort?

Create a new tab titled “Functions”. Paste the questions above and answer them using the applicable spreadsheet functions - `COUNT`, `COUNTIF`, `SUM`, `SUMIF`, `MAX`, `MAXIF`, `AVERAGE`, `AVERAGEIF`.

**Additional Questions:**
- Question 1:
- Question 2:
- Question 3:
- Question 4:
- Question 5:


Videos: Fun with Functions - [Part 1](https://www.loom.com/share/0f9ae677ba4c49d7b5c70f498903cba7) | [Part 2](https://www.loom.com/share/9f9080b37c3e470cb32c5b54531f8211) | [Part 3](https://www.loom.com/share/93934778b2c84fc2a373d3ae26e9a1fa)

### Step Four: Fun with Pivot Tables

Functions work great for specific calculations while pivot tables are best for summarizing larger data sets.

- [x] Create a new tab “Pivot Tables”
- [x] Start asking additional questions of the data by creating pivot tables.

**For example:**
- What is the employment status of applicants that were assigned a cohort?
- What is the household income of applicants that were assigned a cohort?
- What is the number of students by cohort?
- What is the education of the applicants who have been assigned a cohort?
- What is the race/ethnicity of applicants that were assigned a cohort?

- [x] Create Calculated Fields to quickly see the percentage of the total for the pivot table data.

### Step Five: Create Charts & Build a Dashboard

- [x] For each pivot table, create a chart next to it that visually represents the data. It is up to you to decide what chart will convey the data the best.
- [x] Review the Annual Report again and make a list of what was reported last year that you will need to report on this year.
- [x] Add another tab “Dashboard” and copy & paste the charts you have made in the Dashboard tab.

### Step Six: Make it Aesthetic

- [x] Evaluate the current dashboard and make some decisions on what would make the dashboard more aesthetically pleasing.
- [x] Create some new columns either in the “analysis” tab or in the “pivot tables” tab to consolidate data into the minimal number of categories in order to best visually represent it in the dashboard.
- [x] Upload the Tech-Moms logo to the dashboard.
- [x] Update the Dashboard theme to use Tech-Moms’ brand colors.

### Last Step: Ship it!

- [X] Ideas for data sets include asking ChatGPT for a dataset for a certain topic or choosing a data set from "Tidy Tuesdays" [here](https://github.com/rfordatascience/tidytuesday/blob/master/data/2024/readme.md).
- [x] Email your this edited README with your video lesson links and your completed assignment to data@tech-moms.org
- [x] Celebrate! Learning how to learning is an important part of learning!

# Lesson Plan: Intermediate Data Analytics Using Excel for a Non-Profit Organization

**Course**: Data Analytics

**Module**: Intermediate Excel for Data Analytics in Non-Profit Organizations

**Estimated Time to Complete**: 2 hours

**Objective**:  
Students will:
- Analyze real-world data from a non-profit organization.
- Apply intermediate Excel functions: **SUMIF**, **XLOOKUP**, and **IF statements**.
- Create charts and pivot tables to visualize non-profit data.
- Reflect on how data analysis can drive decision-making in non-profits.

---

## Scenario  
You are working as a data analyst for a non-profit organization focused on education. The non-profit collects data on student enrollment in programs, donor contributions, and program outcomes. Your task is to analyze this data to help the organization understand its impact and inform future decisions.

---

## Instructions for Students

### 1. Review Key Concepts (20 minutes)  
Before working with the dataset, review these Excel functions:
- **SUMIF**: Sums values based on a specific condition.
- **XLOOKUP**: Retrieves data from a table based on a lookup value (similar to VLOOKUP but more flexible).
- **IF Statements**: Allows for logical comparisons and returns different values based on whether a condition is met.
- **Pivot Tables**: Helps to summarize and analyze large datasets.

**Resources**:
- Video: [Intermediate Excel for Data Analytics](https://www.youtube.com/watch?v=kghcAk7l6eA).
- Documentation: [XLOOKUP](https://support.microsoft.com/en-us/office/xlookup-function) and [SUMIF](https://support.microsoft.com/en-us/office/sumif-function-169b8c99-c05c-4483-a712-1697a653039b).

---

### 2. Practice with Non-Profit Data (30 minutes)  
Download the sample dataset from the non-profit [here] (include link). This dataset includes:
- **Student Enrollment**: Number of students per program.
- **Donor Contributions**: Amounts donated by individuals.
- **Program Outcomes**: Success metrics for each program.

**Tasks**:
1. Use **XLOOKUP** to find which donors contributed to specific programs.
2. Apply the **SUMIF** function to calculate total donations from corporate donors.
3. Create an **IF statement** to label programs as "Successful" or "Needs Improvement" based on their outcome scores (e.g., IF score >= 80, then “Successful”).

---

### 3. Create Visualizations (25 minutes)  
Create visual representations of the data:
- **Pivot Table**: Summarize total student enrollment per program and region.
- **Bar Chart**: Compare donation amounts by type (e.g., individual vs. corporate donors).
- **Pie Chart**: Visualize the proportion of "Successful" versus "Needs Improvement" programs.

---

### 4. Data Storytelling Reflection (20 minutes)  
Reflect on your findings by writing a brief analysis (150–250 words), addressing these questions:
- What trends did you discover in the data?
- How do donation patterns correlate with program success?
- How can this data help the non-profit plan for the future?

Submit your Excel file (with formulas and charts) along with your reflection through the course platform by [Due Date].

---

## Submission Guidelines  
Submit:
- **Excel File**: Include your dataset with XLOOKUP, SUMIF, and IF statements applied, as well as the visualizations.
- **Written Reflection**: Upload a document (Word or PDF) containing your data analysis.

---

## Assessment Criteria

| **Criteria**          |               | 
|-----------------------|-----------------------------------------|
| **Formulas Applied**   | Correct use of SUMIF, XLOOKUP, and IF statements | 
| **Data Visualization** | Clear, accurate, and insightful charts and pivot tables |          
| **Reflection**         | Thoughtful analysis with insights about the non-profit’s data |

---

## Additional Resources  
For further support, refer to:
- **Microsoft Excel Documentation**: [Excel Help Page](https://support.microsoft.com/en-us/excel)
- **Video Tutorials**: [Excel Intermediate Data Analysis](https://www.youtube.com/watch?v=UeJWCqJysKI).

---

## Support & Contact  
If you encounter difficulties, contact the instructor during office hours or via email at [Instructor’s Contact Information].

