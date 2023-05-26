## Student-Mental-Health
A Microsoft Excel Project about the Mental Health of Students

### Step 1: Project Overview

The "Student Mental Health" dataset was compiled through a survey conducted via Google Forms, which can be found through this [link](https://www.kaggle.com/datasets/shariful07/student-mental-health) and under this [license](https://creativecommons.org/publicdomain/zero/1.0/). It was specifically designed to gather information from University Students. The primary purpose of this survey was to investigate the students' present academic circumstances and assess their mental well-being. By utilizing this dataset, this project aims to gain insights into the interplay between academic factors and mental health among university students.

### Step 2: Prepare

Import the Dataset named 'Student Mental health.csv'

Structure of the Dataset:

![image](https://github.com/Sabrialinton/Student-Mental-Health/assets/114893438/919bcec2-d238-44e4-b2a8-1359a3d4867b)

Limitations of the Data:

This dataset is a sample (101 individuals) and does not cover a large population.

### Step 3: Data Cleaning

- Creation of three sheets - a Working Sheet, a Pivot Table Sheet, and a Dashboard Sheet.
- Removal of Timestamp column within the Working Sheet. (The survey was conducted in August of 2020)
- Creation of two new columns "Major - fixed" and "Year of Study - fixed" using the UPPER() and PROPER() functions so the data can be read more easily.
- Removal of duplicates from the entire data set.
- Added explanations for Majors with vague names. For example, changing "BIT" to "BIT (Business Information Technology)". 

### Step 4: Analysis and Visualization Using Pivot Tables

![image](https://github.com/Sabrialinton/Student-Mental-Health/assets/114893438/e95eb3dc-84b8-459b-8008-a10042d5364d)

![image](https://github.com/Sabrialinton/Student-Mental-Health/assets/114893438/164da654-b573-4c60-8503-018abf404146)

![image](https://github.com/Sabrialinton/Student-Mental-Health/assets/114893438/d11e94cb-0285-47a8-9435-bc4741bd6daa)



### Step 5: Dashboard and Findings

<img width="1000" alt="image" src="https://github.com/Sabrialinton/Student-Mental-Health/assets/114893438/6c8da7a4-b9d6-458b-b7b8-61b875d424c8">

<img width="1000" alt="image" src="https://github.com/Sabrialinton/Student-Mental-Health/assets/114893438/dd9c656e-773b-4695-98d4-13b0cb5fd765">

<img width="1000" alt="image" src="https://github.com/Sabrialinton/Student-Mental-Health/assets/114893438/2929d74b-4984-4906-8bf7-6f3aa38ee058">



### Findings:

1. In general, the dataset reveals a higher prevalence of students without depression compared to those who do experience it.
2. The age group of 18-19 exhibited a higher incidence of reported depression compared to older age groups.
3. BCS, Business Information Technology, and Engineering majors demonstrated a higher frequency of reported depression compared to students in other majors.
4. Students with GPAs between 3.00 and 4.00 have reported depression more than those with other GPAs.

