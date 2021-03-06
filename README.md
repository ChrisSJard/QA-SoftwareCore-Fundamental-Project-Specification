# QA-SoftwareCore-Fundamental-Project-Specification

## Objective

The overall objective of the project is the following:

  * To create an application with utilisation of supporting tools, methodologies and technologies that encapsulate all fundamental modules covered during training.

Specifically, you are required to create an application using the language from your Programming Fundamentals Module which interacts with a Managed Database.
You must plan the approach you will take to complete this project using the design techniques learnt, and also create a CI Pipeline that can automate the building and deployment of your artifact.

## Domain
You are required to build an application that an end user can interact with via a CLI (Command Line Interface).
The application needs to be an inventory management system that needs to be able to:

* Add a customer to the system
* View all customers in the system
* Update a customer in the system
* Delete a customer in the system.
* Add an item to the system
* View all items in the system
* Update an item in the system
* Delete an item in the system
* Create an order in the system.
* View all orders in the system.
* Delete an order in the system
* Add an item to an order.
* Calculate a cost for an order.
* Delete an item in an order.

When considering the entities in this domain:
* A customer needs to have a name.
* An item needs to have a name and a value.
* An order needs to have a customer and contains items

## Extension
* Add a user to the system
* List all users
* Changes to customers, items and orders need to be tied to a user.
* A user should have a username and password
* You must be able to log in as a user within the system to make any changes.

## Constraints
* Version Control System - Git
* Source Code Management - GitHub
* Kanban Board - Jira
* Database - MySQL Server 5.7+ (local or cloud hosted)
* Back-end Programming Language - Java
* Build Tool - Maven
* Unit Testing - JUnit
