# CS121-Final-Project-Proposal-and-UML

# Final Project Proposal
**Car Information Search System** 
**Amanjot Singh** 
CS121 
Purpose
My purpose of this project is to create car information search system using C++. In this project I will demonstrate my understanding what I have learned this semester in CS121, which include object-oriented programming, classes, inheritance, and data structures. 
Overview
For my final project, I will create a C++ program that allows users to search for different cars and view their information. The user will enter a car brand for example Toyota, BMW, HONDA, FORD and so on. The program displays matching cars. The user can also then select a specific car to view the information, for example the model, year ad engine size, fuel type, transmission, milage, condition of the car and the price of the cars. The program will have a menu where users will search for cars, view available brands and exit. 
Intended Users
This program is designed for peoples who are interested in cars and wants to learn more about different vehicles. It also helps someone who wants to compare car information without looking through a large dataset.
Problems This project will Solve.
The main goal of this project is to make it easier for users to find a car information. The dataset contains 2500 car records and searching through all the records manually takes times. This project will allow user to enter a car brand, and it will quickly find matching vehicles It will also show the output of the information for a selected car. 
Classes Design
The program will have four main classes : Vehicle, Car, Car Database and CarSystem. 
1.	Vehicle Class  The vehicle class will store basic information about each vehicle, including brand of the car, model of the car and the year of the car. 
2.	Car Class  the car will inherit from Vehicle class. This class will store additional information about each car, such as its engine size, fuel type, transmission, mileage, condition, and price. 
3.	CarDatabase class  The CarDatabase class will manage the car records. It will read the CSV files and store the information in a vector. It will then allow users to search of cars by brand or car ID. 
4.	CarSystem class  the CarSystem class will control the main program. It will display the menu and allow the user to select different options.

