# Module 2: Excel and Google Sheets 

### Do Before Class:  

_Edit the markdown file with an x in the checkbox when complete, then commit changes._

- [x] Watch this 1-minute [video](https://app.screencastify.com/v3/watch/XJp2UYdVvVnFIFr2CjeA) about the next step
- [x] Make a copy of the [Pre-Course Checklist Google Doc](https://docs.google.com/document/u/1/d/1DvkYSFrZkkCpClqdR6HO3zsEFOUPDAoqZliurV4QkzA/copy?usp=sharing) and complete
- [x] Overview, Outcomes, and Video Lessons below

## Overview:

This section serves as a comprehensive introduction to Excel and Google Sheets, two of the most widely used tools in data analytics. Designed for beginners, this module will guide students through the basics of these powerful spreadsheet applications, providing a solid foundation for data manipulation, analysis, and visualization.

The module will cover essential functions and formulas that automate calculations and streamline data workflows. Additionally, students will learn how to create pivot tables for summarizing data and various charts for visualizing insights. The module will culminate with a hands-on project on building an aesthetic spreadsheet dashboard, combining all the skills learned into a practical, real-world application.

By the end of this section, students will be proficient in using Excel and Google Sheets as foundational tools for data analysis, equipping them with the skills needed to handle and interpret data effectively in any professional setting.

----

What is Excel/Google Sheets?


* Excel is a spreadsheet program developed by Microsoft.
* Google Sheets is a similar web-based application by Google.
* Both tools are used for organizing, analyzing, and storing data.

Video examples in the section are in Excel and Assignment #1 will be shown in Google Docs, however, you can choose either Excel or Google Sheets to complete the analysis based on what is available to you, your personal preference or which tool you use at your current role.

## Learning Outcomes:  

1)  Data cleaning 
2) Basic functions and formulas
3) Creating pivot tables
4)  Creating charts
5) Creating a spreadsheet dashboard 

## Video Lessons - complete by Wednesday, September 4th

_Watch the videos below, edit the markdown file with an x in the checkbox when complete, then commit changes._

>_Tip: Make timestamped comments as you watch—it’s like the video version of writing notes in the margins of a book._

_Estimated total time to complete: 4 hours_

<a href="https://youtu.be/PSNXoAs2FtQ?si=VzYJ0MCf5Uj7P-2G&t=22498" target="_blank" rel="noopener noreferrer">
    <img src="https://github.com/user-attachments/assets/34d1accf-fb2d-4390-a4de-86654217d10f" alt="Cleaning Data" width="500">
</a>

_Est. Time to Complete: (40 mins)_

In this section, you will learn the importance of data cleaning as a foundational step in the data analysis process. We will cover techniques to identify and correct errors, handle missing values, standardize data formats, and remove duplicates. By mastering these skills, students will ensure their data is accurate and ready for analysis, setting the stage for meaningful insights.

- [x] Watch [video](https://youtu.be/PSNXoAs2FtQ?si=VzYJ0MCf5Uj7P-2G&t=22498) and mark when complete
- [ ] Excel users: download [.xls file](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Data%20Cleaning%20Excel%20Tutorial.xlsx)
- [x] Google Sheets users: make a copy of the [google sheet](https://docs.google.com/spreadsheets/d/1EkdWcu_bYk6DgJ53HQcPxBlTPsKxtwgxM9EpK6Rp8lI/edit?usp=sharing)
- [x] Complete the hands-on activity

#### NOTES
0:41 [Alex Freeberg](https://www.linkedin.com/in/alex-freeberg), mentions that we can make our free website portfolio <br>
1:00 [Analyst builder](https://www.analystbuilder.com/) <br>
2:50 Learn SQL, learn Tableau or PowerBI <br>
3:55 Learn excel <br>
4:20 Learn Python <br>
5:19 Learn a Cloud Platform <br>
6:30 Youtube channel, Udemy, Coursera, Datacamp, Dataquest (reading and doing) <br>
7:15 Build a project - a visualization in Tableau <br>
7:50 Build a portfolio website <br>
8:35 Build a data analyst resume <br>
[US Presidents Dataset](https://www.kaggle.com/datasets/harshitagpt/us-presidents) <br>
6:15:03 Clean data in Excel <br>
6:17:00 US_Presidents data to clean <br>
6:18:00 What to clean? Names in Caps, Party and extra characters or spaces, spelling, dates, duplicated data, currency <br>
6:19:02 Remove duplicates in sheets - Data Tools select all columns <br>
6:20:03 President column - Change Name to president_fixed column by applying =UPPER(), =PROPER(), LOWER() functions <br>
6:22:05 prior column seems to be useless <br>
6:23:14 Party column - fix spelling 'republicans', extra characters for 'whig' <br>
6:25:00 Vice column - create a new olumn and use =TRIM() to column, it gets rid of extra spaces in the middle, at the beginning and at the end <br>
6:27:23 Salary column - fix the currency, we don't need the symbol for current. Change it to be a NUMBER <br>
6:29:00 Date update and created columns - use SHORT DATE <br>
6:31:00 Save columns as VALUES <br>
6:31:20 Delete columns unnecessary <br>
6:33:00 Updated data

---
<img width="500" alt="Screenshot 2024-08-28 at 3 34 17 PM" src="https://github.com/user-attachments/assets/ecd71d2a-d435-44d8-be97-c8baad80300a">

_Est. Time to Complete: (60 mins)_

This section introduces essential functions and formulas in Excel and Google Sheets that are crucial for data manipulation and analysis. Students will learn how to use functions such as SUM, AVERAGE, COUNT, AND IF statements. By the end of this section, students will be comfortable using these tools to perform calculations and automate repetitive tasks.

- [x] Watch [video](https://youtu.be/PSNXoAs2FtQ?si=0orU_bNAOQuc64fi&t=17175) and mark when complete
- [ ] Excel users: download [.xls file](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Formula%20Excel%20Template.xlsx) 
- [x] Google Sheets users: make a copy of the [google sheet](https://docs.google.com/spreadsheets/d/1_m7bzlByhPAjYNglv_Vp6eK4sQxLVAaXDRAfp1yn7iw/edit?usp=sharing)
- [x] Complete the hands-on activity

#### NOTES
4:46:00 Formulas in Excel <br>
4:49:01 MAX(number1, [number2]...), MIN(number1, [number2],...) <br>
4:50:58 IF(logial_test, [value_if_true], [value_if_false]), IFS(logical_test1, value_if_true1,[logical_test2, value_if_true2],... ) <br>
4:55:55 LEN(text) - Can be use to see difference between 100s and thousands. Can find bad SSNs. <br>
4:57:00 LEFT(text,[number_of_chars]), RIGHT(text,[number_of_chars]) <br>
4:59:50 DateToText  -> TEXT(value,format_text) or TEXT(H2,"dd/mm/yyyy") - Date format in Excel when converted to General jsut gives numbers, that is why it is needed TEXT() formula <br>
5:03:20 TRIM(text) or TRIM(C2) - It just removes unwanted spaces on both sides <br>
5:04:45 CONCATENATE(text1,[text2],[text3], ...) or CONCATENATE(B2," ",C2) - Joins strings
5:07:05 SUBSTITUTE(text, old_text, new_text,[instance_num]) - replaces text <br>
5:10:57 SUM(), SUMIF(range, criteria,[]), SUMIFS(sum_range,criteria_range1,criteria1,[criteria_range2,criteria2],...) <br>
5:14:20 COUNT(value1,[vaue2],..), COUNTIF(range,criteria), COUNTIFS(criteria_range1,criteria1, ...) <br>
5:16:55 Days-NetworkDays -> DAYS(end_date,start_date), NETWORKDAYS(start_date,end_date,[holidays])

---

<img width="500" alt="Formulas" src="https://github.com/user-attachments/assets/c6895615-c093-4779-bde7-4d52bd74226a">

_Est. Time to Complete: (30 mins)_

Pivot tables are powerful tools for summarizing, analyzing, and exploring data. In this section, students will learn how to create pivot tables to quickly extract key insights from large datasets. We will cover how to group, filter, and sort data, as well as how to customize the layout to answer specific business questions.

- [x] Watch [video](https://youtu.be/PSNXoAs2FtQ?si=DsyZu_e9TrHPrr7o&t=16121) and mark when complete
- [ ] Download dataset from [Kaggle](https://www.kaggle.com/datasets/sadiqshah/bike-sales-in-europe?resource=download) and open in Excel or Google Sheets
- [ ] Complete the hands-on activity

---

<img width="500" alt="Charts" src="https://github.com/user-attachments/assets/b755d9fa-1b6e-443c-bce1-ab57d2a85d88">

_Est. Time to Complete: (15 mins)_

Visualizing data is a critical skill in data analytics. This section will guide students through the process of creating various types of charts, such as bar, line, and pie charts, to represent data clearly and effectively. Students will learn best practices for selecting the right chart type and formatting it to communicate their findings visually.

- [x] Watch [video](https://youtu.be/PSNXoAs2FtQ?si=HXkI655b-v2RuNvo&t=21589) and mark when complete
- [ ] Excel users: download [.xls file](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Charts%20Tutorial%20File.xlsx)
- [ ] Google Sheets users: make a copy of the [google sheet](https://docs.google.com/spreadsheets/d/1JVPEzRH7ePeK0GaJZJK1SpfnlrDjWOLeQb_8z8vD10I/edit?usp=sharing)
- [ ] Complete the hands-on activity

---

_Est. Time to Complete: (1.5 hrs)_

In the final section, students will learn how to bring together all the skills they've acquired to create an interactive and aesthetic spreadsheet dashboard. This dashboard will serve as a dynamic tool for presenting data insights, including charts, pivot tables, and key metrics. Students will focus on layout, design principles, and interactivity to ensure their dashboards are both functional and visually appealing.

- [ ] Watch [video](https://youtu.be/PSNXoAs2FtQ?si=Hu0HebxQCSzSWeR4&t=23762) and mark when complete
- [ ] Excel users: download [.xls file](https://github.com/AlexTheAnalyst/Excel-Tutorial/blob/main/Excel%20Project%20Dataset.xlsx)
- [ ] Google Sheets users: make a copy of the [google sheet](https://docs.google.com/spreadsheets/d/1885w07YyzbRQqfIGHvJSftNU42rJVOUHpkWfNROLlbM/edit?usp=sharing)
- [ ] Complete the hands-on activity

----

## Wednesday, September 4th - In Class Agenda: 

1) Review Video Lessons
2) Demo & Tutorial for Assignment #1
3) Q&A 

----

## Assignment #1 - complete by Saturday, September 7th

In this hands-on project, you will help Tech Moms analyze their applicant and student data in order to complete their annual non-profit report. 

_Estimated Time to Complete: 6 hours_

<img width="1552" alt="Screenshot 2024-07-28 at 2 16 17 AM" src="https://github.com/user-attachments/assets/7f6d2d76-29a5-4cff-aec6-cd9ea680d4c3">

- [ ] Complete [Assignment 1](https://github.com/Tech-Moms/data-analytics-course/blob/main/module_2/assignment_1/README.md) and mark when complete 




