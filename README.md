# pandas-challenge
Module 4 Challenge


This challenge primarily deals with Pandas to create and manipulate DataFrames and using Jupyter Notebook for its interactive interface. In the repository, there is also a folder named "PyCitySchools," which includes a Resources folder and a Jupyter Notebook. The Resouces folder has CSV files of school and student data that includes budget, school size and standardized test data. The Jupyter Notebook contains the final script. After reading in the two CSV files as DataFrames, first I renamed the columns, merged the two DataFrames on the School Name and created the following summary dataframes.

## District Summary
    The District Summary includes the following metrics:

    - Total schools
    - Total students
    - Total budget
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)

## School Summary
    The School Summary includes the following metrics:

    - School name
    - School type
    - Total students
    - Total school budget
    - Per student budget
    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)

## Highest-Performing Schools (by % Overall Passing)
    Using the school summary and Pandas sort function, the five best-performing schools 
    by % overall passing are:

    - Cabrera High School
    - Thomas High School
    - Griffin High School
    - Wilson High School
    - Pena High School

## Lowest-Performing Schools (by % Overall Passing)
    Using the school summary and Pandas sort function, the five worst-performing schools 
    by % overall passing are:

    - Rodriguez High School
    - Figueroa High School
    - Huang High School
    - Hernandez High School
    - Johnson High School 	

## Math and Reading Scores by Grade
    These two DataFrames lists the average math and reading scores broken down by grade level at 
    each school in the dataset.


## Scores by School Spending, School Size and School Type
    Using bins and bin labels, these tables break down school perfomance based on spending, size and type 
    listing the following metrics:

    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)

    Based on these tables, we can observe a couple trends. Charter schools perform better than District schools. 
    The five best-performing schools are charter schools, while the five worst-performing schools are district schools. 
    Larger schools (2000-5000 students) have lower averages and less passing students than Small or Medium schools, 
    which makes sense since larger schools have a bigger student to teacher ratio. It also appears that math and reading scores are higher 
    when spending per student is lower. I believe that conincides with school size. Smaller schools have a smaller budget, but teachers have 
    less students, therefore teachers can afford to spend more time with individual students.
