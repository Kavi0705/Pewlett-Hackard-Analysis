# Pewlett-Hackard-Analysis

## Project Overview
The purpose of this project is to help prepare for the upcoming 'silver tsunami' at Pewlett-Hackard. The aim is to determine the number of employees that are retiring per job title, so as to prepare for replacements for theses positions in the near future and to also, identify those employees of retirement age, that are eligibile for a mentoring program, where they would remain with the company in a part-time role in order to mentor new hires.

## Results
- A Retirement Titles table was generated for employees born between January 1, 1952 and Deceberm 31, 1955 to determine employees that will be part of the 'silver tusnami'.

- Using information in this table, a new table called, Unique Titles, was generated, utilizing the DISTINCT ON statement to remove any duplicate entries of employees.

- After uniques entries were established, any employees who had already left the company were excluded from the analysis.

<img width="537" alt="Screen Shot 2022-02-14 at 2 31 16 PM" src="https://user-images.githubusercontent.com/93743169/153949917-39c78781-f3fd-43b6-b5b5-9e4c86cc9a4b.png">

- Finaly, the Mentorship Eligibility table was created for current employees born between January 1, 1965 and December 31, 1965, to determine those who are eligible for the mentorship program.

<img width="522" alt="Screen Shot 2022-02-14 at 2 45 32 PM" src="https://user-images.githubusercontent.com/93743169/153952438-8e81b575-6035-4140-87cd-e9ce8973b62e.png">


## Summary
- 72,458 employees were identified as being eligible for retirement based on birthdates between January 1, 1952 and December 31, 1955. 

<img width="160" alt="Screen Shot 2022-02-14 at 3 57 58 PM" src="https://user-images.githubusercontent.com/93743169/153960871-79360270-bf8e-44ca-91be-c9b8e1bac760.png">

- 1,550 employees were identified as being eligible for the mentorship program. This number will not be sufficient to mentor the next generation of Pewlett Hackard employees. 

- The top 3 deparments impacted by upcoming retirees are the Development, Production, and Sales departments.

<img width="217" alt="Retiring_Departments" src="https://user-images.githubusercontent.com/93743169/153966763-61ffa115-1753-400c-8d93-b659b493442c.png">

- Below is the breakdown of the total salary impacted based on Titles. 

<img width="237" alt="Salary Total" src="https://user-images.githubusercontent.com/93743169/153971051-a70ec57a-487d-4074-8e0a-7cd2ed64646c.png">

- Finally, the income bracket of $40,000 will be the most impacted by the 'silver tsunami'.

<img width="321" alt="Screen Shot 2022-02-14 at 5 42 45 PM" src="https://user-images.githubusercontent.com/93743169/153971266-899c17b1-264f-4ee8-93e0-e681b4652aab.png">

- One other possible analysis that may help in managing the number of employees that are going to be retiring would be to determine how many will be retiring each month. This will allow for better understanding of the 'waves' of retirements over the 12 month period, and magnitude of these waves so that recruitement efforts can match the outgoing number of employees.




