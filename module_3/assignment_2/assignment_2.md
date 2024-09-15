<img width="200" alt="Tech-Moms Logo Vertical" src="https://github.com/user-attachments/assets/02aae052-a29d-493b-bac1-a884f84a6891">

# Tech-Moms Student SQL Analysis 

In this assignment, you will use Deep Note, a data analysis tool, to explore the Tech Moms applicant dataset using SQL. You will upload the applicant dataset into Deep Note and answer key questions to gain insights from the data.

## Step 1: Create a Deep Note Account & Upload Data 

Deepnote.com is a collaborative data science notebook platform designed for data analytics and data science work. It allows users to write and run code in SQL (as well as Python and R) directly within the browser, making it accessible and easy to use without requiring software installation.

- [x]  Go to [Deep Note](https://deepnote.com/) and create a free account if you haven't already.
- [x] Download the `.csv` file of the Tech Moms applicant dataset provided to you.
- [x] In Deep Note, create a new project.
- [x] Upload the `.csv` file into your project.

Video: [Overview, Create a Deep Note Account, & Upload Data](https://www.loom.com/share/5fc400d191dd414088c900cadbc439e5?sid=80486bf3-c3b9-400d-897e-f8f82eabd741)

## Step 2: Get to Know Your Data 

In order to get to know your data, you'll want to see a preview of the table. Use Deep Note's built-in SQL editor to explore the dataset. 

<img width="1524" alt="Screenshot 2024-09-12 at 8 25 50 AM" src="https://github.com/user-attachments/assets/9b5c2ebb-2428-48e3-91d0-19dd871578ec">

To start, write the following query: 

  ```
   SELECT
      *
   FROM [your_table_name]
   LIMIT 10;
  ```

_Note: [your_table_name] will be the exact name of the csv file you uploaded in double quotes. See example below._

<img width="700" alt="Screenshot 2024-09-12 at 8 31 52 AM" src="https://github.com/user-attachments/assets/97feb5d2-8f93-4dcc-9d88-d7b19ebc9187">


This will give you a preview of 10 rows so you can get to know what the data and columns look like generally. 

## Step 3: Clean and Format Your Data 

Once you upload the data, you may notice that the data is not in the format that SQL likes.  

Cleaning and formatting data before running SQL queries is crucial because it ensures consistency, accuracy, and compatibility with SQL syntax. Raw data often contains inconsistencies like mixed date formats, extra spaces, missing values, or improperly named columns that can lead to errors or incorrect query results. 

In your preferred spreadsheet tool, complete the following tasks: 
- [x] Standardize column names to be SQL-friendly (e.g., replacing spaces with underscores). Example: Edit `Contact ID` to be `Contact_ID`. Edit `Application Status` -> `Application_Status`
- [x] Convert data types where necessary, such as ensuring dates are in a proper datetime format. Example: Highlight the `create_date` column in your spreadsheet tool & Format -> Date
- [x] Download the new cleaned & formatted `.csv`
- [x] Re-upload the new cleaned & formatted `.csv` to Deep Note

Now you are ready to run some queries and analyze the data in SQL. 

Note: to skip this step you can use the cleaned tech moms application data [here](https://github.com/Tech-Moms/data-analytics-course/blob/main/module_3/assignment_2/Cleaned_Tech_Moms_Application_Data_9.12.2024.csv). 

## Step 4: Analyze the Data (aka Ask Questions) 

Use Deep Note's built-in SQL editor to explore the dataset and answer the following questions:

1. **How many applications has Tech Moms received?** 
   - [x]  Write a query to count the total number of applications. (as of the end of July)
   - Example SQL:
     
    ```
    SELECT 
      COUNT(distinct contact_id) -- to confirm there aren't duplicate use COUNT(distinct)
    FROM 'Cleaned_Tech_Moms_Application_Data.csv'
    WHERE create_date <= '2024-07-31' 
    ```

2. **How many applications were assigned a cohort?** 
   - [x] Determine how many applicants were successfully assigned to a cohort. (as of the end of July)
   - Example SQL:
   
   ```
     SELECT 
      COUNT(distinct contact_id) as total_count --- to rename the column header in your SQL output use `as [new_column_header]`
     FROM 'Cleaned_Tech_Moms_Application_Data.csv'
     WHERE applicant_status = 'assigned cohort'
     AND create_date <= '2024-07-31' 
   ```

3. **How many children are supported through Tech Moms programs?** 
   - [x] Find out the total number of children supported by the Tech Moms programs using the available data. (as of the end of July)
   - Example SQL:

   ```
   SELECT
     SUM(children) as total_children
   FROM 
   'Cleaned_Tech_Moms_Application_Data.csv'
   WHERE applicant_status = 'assigned cohort'
   AND create_date <= '2024-07-31' 
   ```

Note: Your numbers here should match your Excel/Google Sheets analysis. 
     
4. **Etc** 
     - [x] Answer at least 10 additional questions using SQL

## Step 3: Submission

- [x] Email a [link](https://deepnote.com/workspace/tech-moms-c74a-218b9a89-8e00-4dd9-a40f-fc1925d77d85/project/Tech-Moms-Exploratory-Analysis-fbfb3a5b-034a-4d0c-92d8-005c72020634/notebook/Alyson's%20Tech%20Moms%20Data%20Analysis-acff3488e9ba4193b5fed69fee62b822) to your deep note notebook to data@tech-moms.org

#### How to Share a Deep Note Link:

Step 1: 

<img width="400" alt="Screenshot 2024-09-12 at 8 07 23 AM" src="https://github.com/user-attachments/assets/05c5ab15-fd04-4b0a-9822-72c894ae2734">

Step 2: 

<img width="400" alt="Screenshot 2024-09-12 at 8 08 27 AM" src="https://github.com/user-attachments/assets/705d32ec-831a-4a4b-8fb5-972b04379ea3">

Step 3:

<img width="500" alt="Screenshot 2024-09-12 at 8 09 38 AM" src="https://github.com/user-attachments/assets/1cf191d9-fafc-4a4e-904b-3ac51adaf7ba">

Step 4: 

<img width="500" alt="Screenshot 2024-09-12 at 8 11 12 AM" src="https://github.com/user-attachments/assets/9920c8db-81c4-4b4e-9193-d6cbd3a51b63">

  
