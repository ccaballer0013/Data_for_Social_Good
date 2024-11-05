# Unit 3 - Data for Social Good Project 

## Introduction 

Software engineers develop programs to work with data and provide information to a user. Each user has different needs based on the information they are looking for from data. Your goal is to create a data analysis program for your user that stores and analyzes data to provide the information they need. 

## Requirements 

Use your knowledge of object-oriented programming, one-dimensional (1D) arrays, and algorithms to create your data analysis program: 
- **Write a class** – Write a class to represent your user or business and store and analyze their data with no-argument and parameterized constructors. 
- **Create at least two 1D arrays** – Create at least two 1D arrays to store the data that your user needs information about. 
- **Write a method** – Write a method that finds or manipulates the elements in a 1D array to provide the information your user needs. 
- **Implement a toString() method** – Write a toString() method that returns general information about the data (for example, number of values in the dataset). 
- **Document your code** – Use comments to explain the purpose of the methods and code segments and note any preconditions and postconditions. 

## User Story 

Include your User Story you analyzed for your project here. Your User Story should have the following format: 

> As a CEO of a local nonprofit focused on supporting fine arts students, I want to find groups of graduating high school students interested in the art field so that I can provide them with art-related internships, job offers, scholarships, and other opportunities.


## Dataset 

Dataset: https://data.census.gov/table/ACSST1Y2023.S1502?q=high%20school%20student%20majors
- **Age** (int) - ages of college graduates
- **Major** (String) - majors of college graduates

## UML Diagram 

Put and image of your UML Diagram here. Upload the image of your UML Diagram to your repository, then use the Markdown syntax to insert your image here. Make sure your image file name is one work, otherwise it might not properly get display on this README. 

![UML Diagram for my project](Copyof(Unit3)UMLDiagram.jpg) 

## Description 

In this project, my partner and I created a way for data to be easily accessed and analyzed through using datasets and traversing through them when necessary. In our User Story, we created methods that included nested-loops, increments, and element usage. As these words are all connected to for-loops, the methods used allow users to traverse through the given arrays depending on the specific data they want to receive. For example, when trying to find out how many people graduated with a Business major, a nested-loop, increment, and index would be used. The goal of this program was to help find graduating students with majors in art. This program allows users to access a sample of gradauting college students that accurately portray the ratios of student to major. Users can access different ages and majors of different students to help gauge the number of students who may want to receive help from a nonprofit interested in those who recently graduated with art. In addition, our program incorporates user input. The user will answer a series of questions relating to the goal of their research. These inputs will result in the printing of this specified information. 