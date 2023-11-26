# Project_Planner

The project is a project planner which helps an indiviual 
create a plan of action to complete any project. 

## Description

The program takes a list of tasks (i.e. from a csv file), sorts then organizes the 
tasks and presents a visual chart (Gantt Chart) to the user.

## Usage

STEP ONE:

Open the planner.py file and have a csv file in the following format:

CSV FILE FORMAT ~

"**task number, title of task, duration to complete, prerequisites**" 
(note: if there is blank space prerequisites the value is taken as 0)

IE 
1, Design game functionality, 2,  
2, Draw basic images, 1, 1
3, Break functionality into steps, 2, 1 

STEP TWO:

ON LINE 105 change the parameter of the **read_task** function to the relative path of the csv file you wish to process 
(this is how the porgram will know which csv file to process to geenrate the gantt chart)

IE
tasks = read_task("ProjectPlanner\project.csv") ~ 

STEP THREE:

Run the program and you will be presented with a simple gantt chart which outlines how to 
complete a large project with a series of smaller task.

## Acknowledgments

The following book was used to complete this project: 
Beginner's Step-by-Step Coding Course by DK


---
# Python_Projects_2023
