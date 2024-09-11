java c
Faculty of Information Technology
Semester 2, 2024
FIT5145: Foundations of Data Science
Assignment 2: Description
Due Date: Friday, Week 8 (September 13, 2024), 11:55 PM
The aim of this assignment is to investigate and visualise data using R. It will test your ability to:
1.   Read data files and extract related data from those files;
2.   Clean and process data into the required formats;
3.   Perform. exploratory data analysis and visualisation;
4.   Use basic tools for managing and processing data; and
5.   Communicate your findings in your report.
Assessment Details:
●   Assessment Type: Individual Assignment
●   Total marks: 15%
●   Due Date: Friday, Week  8 (September  13, 2024),  11:55 PM. Please notice that we do not accept submissions after September 20, 2024 (i.e., 7 days after the due date).
Submission Details:
You will need to submit two separate files (PDF report and RMD file).1.   A  report in PDF containing your (a) code, (b) answer, and (c) explanation used to answer each question.
(a) code: Please directly convert the RMD file including your codes into the PDF file (Note: Please Knit RMD to HTML and print the HTML as pdf). If you want to use Word or other word processing software to format your submission, please copy your codes from the RMD file and paste into Word (Please do NOT take the screenshots ofyour code).
(b)  answer:  Please  make  sure  to  include  screenshots/images  of  the  code  outputs  and written answers for each question.
(c) explanation: Please explain how you answered each question (i.e.: explaining your codes or summarising your work for each question).Marks will be assigned to reports based on their correctness and clarity. For example, higher marks will be awarded to reports that include graphs with appropriately labelled axes and sufficient comments for the code.
2.    The RMarkdown  file: Please submit the RMarkdown file that contains your R codes. Your file should contain all the codes, and proper comments. If your work uses new libraries that  have not been introduced in classes, please include instructions on how to get these libraries installed.
Notes:
1.   Whenever a question asks for a certain value, your code should produce the value.  For example, when a question asks for the number of rows contained in a table, your code should print out the number of the rows. Extraction of the answer manually by eye-examination will not earn any marks.
2.   Please  make  sure that you can select and highlight texts in your PDF, as shown below then the turnitin score can be generated properly for your PDF file (we just need the Turnitin score for the PDF file, not the RMD file).
Assignment Task:With the ever-increasing amount of data collected in various Learning Management Systems (e.g., Moodle and Blackboard) about students ’ learning behaviour and performance in a course, researchers and educators have started to analyse the collected data to gain a better understanding of students ’ learning experience and further explore whether there is any improvement they can make.
The dataset for this assignment is the anonymised Open University Learning Analytics  Dataset (OULAD). OULAD contains data about courses, students, and their interactions with seven selected  courses  (also called modules) in a Virtual Learning Environment (VLE). Specifically, this dataset consists of:
●   courses.csv, which contains the list of all available modules and their presentations;
●   assessments.csv, which contains information about assessments in module-presentations;
●   vle.csv, which contains information about the available materials in the VLE;
●   studentInfo.csv, which contains demographic information abou代 写FIT5145: Foundations of Data Science Assignment 2: Description Semester 2, 2024R
代做程序编程语言t the students together with their results;
●   studentRegistration.csv, which contains information about the time when the student registered for the module presentation;
●   studentAssessment.csv, which contains the results of students ’ assessments;
●   studentVle.csv, which contains information about each student’s interactions with the materials in the VLE.A more detailed description of the dataset is available here. As a pilot step, your task in this assignment is to better understand students ’ demographic background and how well they performed in assessments. Therefore, you only need to focus on the following files for this assignment:
●   studentInfo.csv
●   assessments.csv
●   studentAssessment.csv
These three files have been modified for the task. Please download them from the Assessments page on Moodle.
Firstly, let’s focus on the file studentInfo.csv.
1.   How many unique “region” values are there in the data file?
2.   How  many  student  feedback  comments  mention  interacting  or  engaging  and  provide  an overall score of 1 or 2?
3.   What are the dates of the earliest and latest feedback comments?
4.   For  each  code_module  value,  write  code  to calculate the fractions of students of different gender values (M and F), and then visualise the  fraction numbers specific to the code_module value.
5.   Compute the total number  of students  for each region and highest education, and store the result into a dataset named ‘temp ’. Then, use a single R function/command to display the statistical information (i.e., Min, Max, and Mean) of the total number of students for each highest education in the ‘temp ’ data (Note: You may use multiple functions/commands to prepare  the  pre-processed  data  table,  but  when  you  compute  and  display  the  statistical information, you need to use a single R function/command).
6.   Please investigate the relationship between the student feedback scores and scores  in studentAssessment.csv. Additionally, examine the relationship between the student feedback scores and other variables (Note: You may use variables from both   studentAssessment.csv and assessments.csv to explore these relationships.) Marks will be awarded based on the depth  of your investigation (including the analyses and discussions conducted) and the strength of your reasoning (how insights and conclusions are drawn).
Next, let's focus on the file studentAssessment.csv.
7.   Write    code    to   merge    the   “code_module”    and    “code_presentation”   columns    from assessments.csv  into  studentAssessment.csv.  Then,  generate  the  ‘date_submitted’  column (e.g.:  2014-01-23)    from  the  ‘dates_since_submitted’  column  and  draw  a  chart  to  show student average scores against the date submitted. Note: The start of the module presentation is 2014-01-01.
8.   Write code to only keep assessment data relevant to students from the code_module ofAAA  and code_presentation of 2013J, then write code to add a new column named “score_range” and fill it with one of the following values based on the corresponding “score” value:
。  [0, 60)     。  [60, 70)   。  [70, 80)   。  [80, 100]
For  each  id_assessment  value,  draw  a  chart  to  plot  the  number  of students  of different score_range values. What do you observe?
9.   Now using the original datasets, please draw any charts or create any summary tables which haven't been investigated in the previous questions and discuss them. Marks will be awarded based on the depth of your investigation (including the analyses and discussions conducted) and the strength ofyour reasoning (how insights and conclusions are drawn).







         
加QQ：99515681  WX：codinghelp
