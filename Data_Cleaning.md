# Data Cleaning
### Using Google Sheets
For this project I decided to use Google Sheets to clean my data. Google sheets has a built in feature that helps cleaning up your data with a simple button.
Here are the steps I took:
   - I loaded the CSV I obtained from [Kaggle](https://www.kaggle.com/datasets/mohithsairamreddy/salary-data) onto Google Sheets. 
   - Once loaded I used the bulit in functions to identify and remove duplicates. (Data> Data Cleaning> Remove Duplicates) In which it reduced the number of duplicates from 6705 to 1792. :astonished:
   - I did notice missing values on some columns, in which I had to decide if I wanted to remove or keep.
   - I decided to remove columns that I knew would make a significant impact on my analysis. Critical columns such as Age, Salary, Years of experience, and Job Title. They are crucial for our analysis therefore I made the  decision to remove them.
   - I decided to keep columns that had missing values that could provide some insight on some folks with interesting analysis. I decided on columns for Gender and Education levels. 
   - ***Of course in a work enviroment it is always important to investigate duplicates and missing values. Also to double check with stakeholders and team members before making these types of decisions as they can impact the overall analysis.***

