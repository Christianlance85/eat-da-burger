# Burger-App
This is a repository for the Vanderbilt Coding Bootcamp Homework 13
By | Christian Lance


## Purpose
This is a GitHub repository for an burger application. 


## User Story
AS A user, I need to be able to order burgers.
I WANT to be able to add new burger to my order.
SO THAT I can devour them.


## Screenshot of Completed Application

![Burger Demo](/public/assets/img/demo.JPG)



## Installation

With GitHub account, clone or download repository using link. 


## Business Context
For users that need to keep track of a lot of Employees, you are able to do multiple things with this
command line application. You can add/update/delete departments, roles, and employees.

## Schema:
CREATE DATABASE burgers_db;
USE burgers_db;

CREATE TABLE burgers
(
	id int NOT NULL AUTO_INCREMENT,
	burger_name varchar(255) NOT NULL,
	devoured BOOLEAN DEFAULT false,
	PRIMARY KEY (id)
);
