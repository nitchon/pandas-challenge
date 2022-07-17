# pandas-challenge
Module 4 Challenge


The challenge primarily deals with Pandas to create and manipulate DataFrames and using Jupyter Notebook for its interactive interface. In the repository, there is a folder named "PyCitySchools," which includes a Resources folder and a Jupyter Notebook. The Resouces folder has CSV files of school and student data that includes budget, school size and standardized test data. The Jupyter Notebook contains the final script. The project leverages Pandas ability to handle data to anyalze school data and create summary tables. After reading in the two CSV files as DataFrames, first I renamed the columns, merged the two DataFrames on the School Name and created the following summary dataframes.

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
    
![District Summary](https://user-images.githubusercontent.com/107419765/179424316-8728792b-8232-48bd-94e4-673266423900.PNG)

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
    
   ![School_Summary](https://user-images.githubusercontent.com/107419765/179424409-8257c244-26ae-48c5-a351-d0284e3e7011.PNG)
    


## Highest-Performing Schools (by % Overall Passing)
    Using the school summary and Pandas sort function, the five best-performing schools 
    by % overall passing are:

![highest](https://user-images.githubusercontent.com/107419765/179424414-4e6f1014-8a6e-4e33-bc06-062a0f5a262c.PNG)

## Lowest-Performing Schools (by % Overall Passing)
    Using the school summary and Pandas sort function, the five worst-performing schools 
    by % overall passing are:

![worst](https://user-images.githubusercontent.com/107419765/179424418-03a6ee9d-c168-4c60-bef9-ce10a9a1da0b.PNG)


## Math and Reading Scores by Grade Level
    These two DataFrames lists the average math and reading scores broken down by grade level at 
    each school in the dataset.

Math by Grade Level

![math_by_grade](https://user-images.githubusercontent.com/107419765/179424445-40d297df-ae32-4224-979b-884df958bbf3.PNG)

Reading by Grade Level

![reading_by_grade](https://user-images.githubusercontent.com/107419765/179424452-d53a980b-7d65-4eb7-afe7-3e7793d03aa3.PNG)

## Scores by School Spending, School Size and School Type
    Using bins and bin labels, these tables break down school perfomance based on spending, size and type 
    listing the following metrics:

    - Average math score
    - Average reading score
    - % passing math (the percentage of students who passed math)
    - % passing reading (the percentage of students who passed reading)
    - % overall passing (the percentage of students who passed math AND reading)
    
Score by School Spending
 
![spending](https://user-images.githubusercontent.com/107419765/179424465-8ac9aa97-e343-4919-ba03-3eaa156e8bce.PNG)
    
Score by School Size

![size](https://user-images.githubusercontent.com/107419765/179424471-52d48880-2f51-4429-b0c4-ebcd3361f256.PNG)

Score by School Type

![type](https://user-images.githubusercontent.com/107419765/179424484-58ed6b0a-cc91-4d50-b875-21af81c59f57.PNG)



## Conclusions
    Based on these tables, we can observe a couple trends. Charter schools perform better than District schools. 
    The five best-performing schools are charter schools, while the five worst-performing schools are district schools. 
    Larger schools (2000-5000 students) have lower averages and less passing students than Small or Medium schools, 
    which makes sense since larger schools have a bigger student to teacher ratio. It also appears that math and reading scores 
    are higher when spending per student is lower. I believe that conincides with school size. Smaller schools have a smaller budget, 
    but teachers have less students, therefore teachers can afford to spend more time with individual students.
