The dataset before cleaning https://docs.google.com/spreadsheets/d/1IPS5dBSGtwYVbjsfbaMCYIWnOuRmJcbequohNxCyGVw/edit?resourcekey#gid=1625408792
The data is a Salary Survey from AskAManager.org. 6 variables out of the 17 variables are open-ended question
I removed the unnecessary columns and renamed the columns' headers
In the Age column, the age groups were replaced in categories 
  Teenager - under 18
  Youth - 18-24
  Young Adult - 25-34 
  Adult - 35-44
  Middle Age - 45-54
  Older Adults - 55-64 
  Seniors - 65 or above
I converted the salary to USD in another column
I trimmed the Industry and Job title columns, and made them unique values and removed unnecessary values
the Country column was a mess, so I replaced them with their Continents
The years of Experience column was replaced with categorical values
  Novice - 1 year or below
  Beginner - 2-4years
  Intermediate 5-7years
  Advanced - 8-10years
  Experienced - 11-20years
  Senior - 21-30years
  Veteran - 31-40years
  Master - 41 years or more
Null values were removed
This is the cleaned data [[Ask A Manager Salary Survey 2021 (Responses).xlsx](https://github.com/Oladipupo34/Data-Cleaning-with-PowerQuery/files/14812774/Ask.A.Manager.Salary.Survey.2021.Responses.xlsx) ](https://1drv.ms/x/c/8317544c38acd386/ES0ZRyNXR_5Jih1B4GDiVDABO9_V5N8q_f9xeVz_xlwzlg)

all the string columns were trimmed




