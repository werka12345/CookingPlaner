# CookingPlaner
## Table of contents 
* [Genreal info](#general-info)
* [My needs](#my-needs)
* [Technologies](#technologies)
* [Features](#features)
* [Database](#database)
* [Workflow](#workflow)
## General info
This project is used to calculate the amount of products needed to cook a dish for a certain number of people. 
The project can be used by cooks or suppliers as well as any person who intends to make a dish for a certain number of people. 
The project has been structured in an easy and clear way so that every person can benefit from it.
## My needs
We want our system to support us in:
1.Calculating the ingredients needed to prepare a given number of portions of a dish
2. Planning of food supply
3. Not wasting food
4. Ordering the appropriate quantity of products from suppliers
## Technologies
Project is created with:
Python version: 3.8, Jupyter, Excel 
## Features
* Precise data on the number of products needed to make a certain number of dishes
* Fast ingredient converter
## Database
The datbase was created as an Excel file. It contains the ID numbers of the dishes, the names of the dishes and the amounts of each ingredient (in  grams) per serving. To choose a dish, you should imput the ID number of the dish.

![image](https://user-images.githubusercontent.com/94456351/144229752-34b43446-7515-4b1b-a231-67cb3b5ffad8.png)

## Workflow
1.Initiate the project:
At the beginning you have to start a python or jupyter dialog, then you have to paste the code you received.
After entering the code and clicking enter, another line starts under the name "Welcome to our CookingPlaner !". Under the line appears a message "Enter the number of portions", you have to enter the number of people for whom the dish will be prepared. Then you click enter and the command "Enter dish number" appears again. At this point, you must select the ID number of your dish you wish to prepare from the database. Once this has been done, the message "Here's what you need:" appears and the number of ingredients needed in grams is displayed.
