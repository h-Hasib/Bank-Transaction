
# Bank-Transaction-System

A basic transaction management system. It
serves the purpose of keeping track of financial information such as account number, bank name, amount etc.
This is a MVC Project and performs the basic database CRUD operations.

## Documentation
ASP.NET: It is a web-based framework. It allows us to make business based apps efficiently. The most commmon programming language used by ASP.NET IS C#

SQL: Stands for Structured Query Language. It is used to communicate with the database. SQL statements can be used to update, delete, and more within a database.

API: Stands for Application Programming Interface. API's sre HTTP services that can be accessed from any client. It is an ideal platform for building CRUD applications with the ASP.NET framework

CRUD: Stands for Create, Read, Update, Delete. These are the 4 basic database operations.

MVC: Stands for model-view-controller. MVC is a pattern for developing applications that are testable and easy to maintain. 

Models: These are classes that represent the data of the application and that use validation logic to enforce business rules for that data.

Views: Consist of template files that the application uses in order to dynamically generate HTML responses.

Controllers: This project contains controllers that handle HTTP requests and responses. Each controller is responsible for a specific resource or entity. Controllers use HTTP methods (GET, POST, PUT, DELETE) that map to specific actions for CRUD loperations.


Routing: This maps incoming HTTP requests to the appropriate controller and action method based on the URL. RESTful APIs typically use a resource-based URL pattern.

HTTP Methods: RESTful APIs use standard HTTP methods (GET, POST, PUT, DELETE) to perform CRUD operations on resources. Each HTTP method corresponds to a specific action on the API.

Status Codes: RESTful APIs use standard HTTP status codes to indicate the success or failure of an API request. For example, 200 (OK) for successful GET requests, 201 (Created) for successful POST requests, 204 (No Content) for successful DELETE requests, etc.


## Tech Stack

**Client:** Presentation or View Layer written with HTML, CSS, Razor View Engine

**Server:** ASP.NET Core MVC, MSSQL Server, Entity Framework Core

**IDE/Tools:** Microsoft Visual Studio, Microsoft Visual Studio Code, Microsoft SQL Server Management Studio


**Back-end Task:** I've chosen ASP.NET Core 6 MVC pattern backend framework to build and manage the renowned three modules; Model-View-Controller and execute some functionalities such as Create, Read, Update and Delete by communicating with the database From Controller module based upon the Models.
For Database table creation and data migration, I used Entity Framework Core ORM Tool, And Microsoft SQL Server Management Studio is used for Database Management purpose.

**Front-end Task:** To visualize content on client side (in browser) I've used Razor View Engine as server side markup language but for viewing purpose.  
Specific Components and webpages are created with HTML, CSS and Razor HTML Embedding.

## Getting Started
1. Make sure that you have the required stack installed as stated.
2. Assure that you have ASP.NET Core 6 installed.
3. Clone or Download this repository to your local machine.
4. Open the project/solution in your preferred IDE (Visual Studio, Visual Studio Code).
5. Run the project within your chosen IDE.
6. A "Welcome" text should show in your local host.
7. To add a Transaction, click on the "AddTransaction" tab above.
8. To view your list of transactions, "ViewTransaction" tab above

## Demo (Screenshots)

![Home Page](https://github.com/h-Hasib/Bank-Transaction/blob/main/Screenshots/1.PNG)

![View Transaction](https://github.com/h-Hasib/Bank-Transaction/blob/main/Screenshots/2.PNG)

![Add Transaction](https://github.com/h-Hasib/Bank-Transaction/blob/main/Screenshots/3.PNG)

![Successfully Adding Transaction](https://github.com/h-Hasib/Bank-Transaction/blob/main/Screenshots/4.PNG)

![Delete a Transaction](https://github.com/h-Hasib/Bank-Transaction/blob/main/Screenshots/5.PNG)

![Delete Success](https://github.com/h-Hasib/Bank-Transaction/blob/main/Screenshots/6.PNG)

![Editing an Existing Entry](https://github.com/h-Hasib/Bank-Transaction/blob/main/Screenshots/7.PNG)

![Edit Successful](https://github.com/h-Hasib/Bank-Transaction/blob/main/Screenshots/8.PNG)

## Feedback

This is just a basic web system for my learning perpose.
I'm planning to upgrade this system with some useful features, such as; implement security management, performance level increase, server and client side verification and validation in the upcoming updates. 

if you've any suggestion please feel free to reach out me at hhasan.cse@gmail.com
