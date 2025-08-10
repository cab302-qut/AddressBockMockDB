<h1 align="center">WEEK 4 Address Book Application</h1>

<h1 align="center">JavaFX Application - CRUD Operations</h1>

![Image of digital block with shapes](/images/apiImg.jpeg)

> [!NOTE]
AIM: Create an Address Book Application with a Mock Database for CRUD Operations
> This application could form the basic foundation for your CAB302 Project. 

![Screen for entering the contact details.](/images/Update_Contact_Fixed.gif)

**You are free to extend, change, redesign this simple application and modify it to your requirements.**


## Classes

1. Contact Class - Simple class for creating Contacts (people to store in address book)
2. HelloApplication - Entry point for this JavaFX Application - Boilerplate code to load initial view
3. HelloController - Logic for initial screen events
4. IContactDAO - Interface for Contact Data Access Object - Handles CRUD (Create, Read, Update, Delete operations)
5. MainController - Logic for controlling the data displayed on the view - Connects model (data) and views
6. MockContactDAO - Creates a Mock Database using the same interface as the class that will control database operations - This class could be useful for unit testing (**Only it implements same interface as class responsible for database logic**)


## Activity 1

+ Setup Project Views
+ Terms & Conditions Screen
+ Address Book Screeen

## Activity 2 - CRUD Operations

+ Create Contact model & DAO
+ View Contacts
+ Create/Update/Delete Contacts
+ Add final touches

## MockContactDAO
Implements the IContactDAO Interface - this interface will be used in future weeks to implement the Database connection to a SQLite DB
