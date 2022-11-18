# CMPG-323-Project4---28331869-
Testing and RPA

## Overview
Robotic Process Automation (RPA) refers to the use of technology to mimic human tasks in the same way that a person would execute a process. This usually refers to, what we would call,‘front-end’ or UI (User Interface) automation. RPA is often used to automate time-consuming and highly repetitive tasks to allow people the availed capacity to work on more intuitive tasks.


In this project automation was done on the Connected Office Web Application. It automates the different web forms Devices, Zones and Categories on the given web application. It reads items from an excel file for each of these forms, fills them in and then displaying the item details. Items can be edited and delete, onces all these .The excel file in the UiPath project contains a "Test Results" sheet containing the value "FALSE" before you run the project file. This "FALSE" value is changed to "TRUE" to indicate that the item was created successfully.


## How the user would use the report 

Stakeholders has to run the automation on UIPath community studio, the automation solution takes input from the excel, then populates the database table and then the tables are updated and deleted automatically

1. Login , with username and password
2. Select the item you would like to create. 
3. Once the item is created it displayed, it can then be edited or deleted.
4. If all edit , delete, read and create functions are functional and the process is done successfully the data table is updated and the test result is changed from FALSE to True 

# LOGIN web form
The login button to be clicked and allow for login details are automatically populated.

# Zone web form

The Zone webform reads data from the provided excel file from sheet zone, to the Zone form in the web browser. When reading is done the data will be created automatically using the create button. The all data that has been created can then be viewed and can be edited and deleted.


# Device Web form
The Device webform reads data from the provided excel file from sheet device, to the device form in the web browser. When reading done the data will be created automatically using the create button. The all data that has been created can then be viewed and can be edited and deleted.



# Category  Web form

The Category web form reads data from the provided excel file from sheet category, to the category form in the web browser. When reading done the data will be created automatically using the create button. The all data that has been created can then be viewed and can be edited and deleted.


## Process published on Orchestrator

![image](https://user-images.githubusercontent.com/110894098/198298667-f20c33ec-34d5-4657-9ec3-d569e27d0c0b.png)



Althought it shows that the processs has been published , it is not visible on my Orchestrator. Ive tried multiple times, eventually it just gives me the erro :"Publish of Process failied. Package already exists".





## References 

1.Get multiple excel sheets to one DataTable
https://forum.uipath.com/t/get-multiple-excel-sheets-to-one-datatable/261601/1


2.Learn How to Use Excel File Activity
https://www.youtube.com/watch?v=bYhrmWzShxo

3.UiPath | How to Read Excel Data and Search Online and Write the Results back to Excel
https://www.youtube.com/watch?v=DwOOc8Hb1ho

4.UiPath Apps Tutorial - Part 04 | Update or Delete Data Service Records | Tutorial
https://www.youtube.com/watch?v=hyZtHwq17yA&t=168s

5.Combine multiple Excel sheets into one using UiPath
https://www.youtube.com/watch?v=Gmu2IGZ50WY&t=82s

6.Excel Automation with Studio
https://www.youtube.com/watch?v=7SrdrREJtcc&t=405s

7.Merge Multiple Excels to Single Excel using UiPath | Input sheets to separate sheets in output Excel
https://www.youtube.com/watch?v=3-Quuzq_PZc

8.Introduction to UiPath Portal, Orchestrator & Studio
https://www.youtube.com/watch?v=BAYmmUuB2Zo

9.How to Publish to UiPath Orchestrator Tutorial
https://www.youtube.com/watch?v=yWpJ6xZ9BKw&t=69s. date accessed, 24/10/2022.

10.UiPath Do While Activity | Leap Year in UiPath UiPath RPA Tutorial in Hindi. 
https://www.youtube.com/watch?v=Eg13_A5yfnI.

11.How to Automate a Website Login with UiPath Studio.
https://www.youtube.com/watch?v=030dEAB8oyg 


12.UiPath | How to Read Excel Data, do an Online Search and write the result in the next Column | Guide.
https://www.youtube.com/watch?v=9HxtyuAiPTk.

13.https://github.com/JacquiM/CMPG-323-IOT-Device-Management/blob/main/Connected%20Office%20Test%20Data.xlsx

14. Extracting Data from Excel in Uipath | RPA Tutorial. 
https://www.youtube.com/watch?v=QzuxAVa9FN4 . Date accessed, 18/10/2022.

15. Assign Activity in UiPath.
https://www.youtube.com/watch?v=Db9oPPJ9RJA.

16. How to compare two Excel sheets and update cells with UiPath - Full Tutorial.
https://www.youtube.com/watch?v=LAWn9Sz8fac.

17. UiPath Tutorial 14 - Web Automation UiPath Example | Excel to Web Automation in UiPath
https://www.youtube.com/watch?v=Ch5bk8AABZQ&t=1036s

18.UiPath Academy: Introduction to RPA Course | Automation Basics | UiPath
Academy https://academy.uipath.com/courses/introduction-to-rpa-and-automation

19.  UiPath Academy: RPA Developer Foundation (uipath.com)

20. UiPath. 2021b. Manage DataTables. UiPath Activities
https://docs.uipath.com/activities/docs/manage-data-tables

21. UiPath Tutorial || Day 56 : Generate Data Table Activity || Data Table Activities - YouTube
https://www.youtube.com/watch?v=DKZiiSw4Bps

22.UI Automation and Data Inputs
https://www.uipath.com/learning/video-tutorials/ui-automation-and-data-inputs

23.UIPath read excel and enter the data into web forms
https://www.youtube.com/watch?v=lw6bxrMNzfM&t=581s

24. What is Commit in Git | What is Push in Git | What is Commit and Push in Git
https://www.youtube.com/watch?v=GA_aXO1Gn6E

25. UiPath Tutorial 16 - Read data from Config File | Write Config File Data to Dictionary Variable
https://www.youtube.com/watch?v=woBpbt3adBE

26.UiPath Basics #8 - Browser Automation
https://www.youtube.com/watch?v=KSQBJbUoZ-M

27. UiPath Beginners Course [2021] - How to Learn RPA
https://www.youtube.com/watch?v=sp5ZwFKfh-0

28. UiPath Tutorial 08 A - Excel Automation in UiPath | Read Range and Write Range Activity | DataTables
https://www.youtube.com/watch?v=JB5PpuoLo_E
