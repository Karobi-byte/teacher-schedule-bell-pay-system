# teacher-schedule-bell-pay-system
Python project for automating teacher scheduling, pay management, and creating datasets for school management
# Sweetwater District Teacher Schedule Management Project

## Overview
This project was undertaken in collaboration with a school from the Sweetwater district in Chula Vista. The primary goal was to develop a Python-based solution for managing teacher schedules, prep periods, bell schedules, and payment accounts for both teachers and substitute teachers. 

The project resulted in a consolidated dataset that includes teacher schedules and prep periods for the entire school year, along with a master Excel sheet that helps in managing substitute employee payment accounts more efficiently.

## Project Objectives
1. **Teacher Scheduling**: 
   - Generate teacher schedules for the entire school year based on the bell schedule and their prep periods.
   - Automate the relationship between teacher names, dates, and the bell schedule to create a detailed dataset.

2. **Substitute Employee Payment Management**: 
   - Compile data on substitute employee pay codes, titles, and payment accounts.
   - Create a master Excel sheet to streamline payment processing for substitute teachers.

## Dataset
### Files:
- `Final.csv`: Contains teacher schedules, prep periods, bell schedules, and more.
- `Untitled15.ipynb`: Jupyter notebook containing the code used to process the teacher schedules, create relationships between datasets, and generate new datasets.

## Project Details

### Teacher Schedule Creation
1. **Data Inputs**:
   - Teacher names and schedules.
   - Bell schedule for the school year.
   - Prep periods for teachers.

2. **Data Processing**:
   - The Python script reads the datasets, aligns teacher schedules with the bell schedule, and checks the school calendar for open days.
   - It generates a detailed schedule for each teacher for every active school day in the academic year.

3. **Output**:
   - A CSV file with the schedule for each teacher, showing when they are teaching, when they are on prep, and when school is closed.

### Substitute Employee Payment Management
1. **Data Inputs**:
   - Pay codes, titles, and payment accounts for substitute employees.

2. **Data Processing**:
   - Consolidation of substitute teacher payment data into a master Excel sheet.

3. **Output**:
   - A well-organized Excel sheet that can be used by the school to manage substitute teacher payments efficiently.

## Results and Outputs

### Teacher Scheduling System Output
- The final dataset generated contains the full teacher schedule, including their prep periods for the entire school year.

Example preview of the dataset:

| DATE      | Teacher Name    | Schedule      | Has Prep |
| --------- | --------------- | ------------- | -------- |
| 7/24/24   | John Doe        | P1, P3, P5, P7| Yes      |
| 7/25/24   | Jane Smith      | P2, P4, P6, P7| No       |

### Pay Management System Output
- A master Excel sheet for substitute teachers has been created with detailed pay codes and employee information.

Here’s a sample of the final pay management dataset:

| Employee Name  | Pay Code | Account | Title        |
| -------------- | -------- | ------- | ------------ |
| Alex Johnson   | PC123    | ACC001  | Substitute   |
| Maria Davis    | PC124    | ACC002  | Teacher      |

**Dataset File:** [Final.csv](datasets/Final.csv)

**Notebook File:** [Untitled15.ipynb](notebooks/Untitled15.ipynb)

## How to Use

### Prerequisites
- Install Python 3.x
- Install the required libraries by running:
  ```bash
  pip install pandas openpyxl

