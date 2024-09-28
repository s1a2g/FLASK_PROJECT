# FLASK_PROJECT

PROGRAM STRUCTURE
   
   /flask_app
      
      app.py
      
      models.py
      
      forms.py
     
     /templates
        
        home.html
        
        login.html
        
        display.html
       
        register.html
     
     /static

#Part 1: CSV Processing Script
  
  A Python script will read a CSV file containing student records and perform the following functions:
  Calculate Average Grade: A function that calculates the average grade of all students.
  Identify Highest Grade: A function that prints the student with the highest grade.

#Part 2: Web Development Using Flask or Django
   
  app.py

      Purpose:The main application file that initializes the Flask app and handles routing.
      
      Features:
          Defines routes for the home page, registration, login, and display of student records.
          Manages user authentication, including registration and login with hashed passwords.
          Interacts with the SQLite database to retrieve and display student records.
   
   models.py
        
        Purpose: Contains the database models for the application.
        User: Represents a user with fields for username and password.
        Student: Represents a student with fields for name, age, and grade.
  
   templates/home.html
        
        Purpose: The home page of the application.
        Content: Welcomes users and provides links to the registration and login pages.
  
   templates/login.html
        
        Purpose: The login page for users.
        Content: Contains a form for entering username and password. Submitting the form attempts to authenticate the user.
  
   templates/register.html
        
        Purpose: The registration page for new users.
        Content: Contains a form for creating a new account with username and password fields. Upon submission, user data is saved to the database.
   
   templates/display.html
       
        Purpose: Displays the student records.
        Content: Shows a table of all students, listing their names, ages, and grades.
  
  API Endpoint:
         A simple API endpoint (/api/users) that returns a JSON response with a list of all submitted user data.
  Error Handling:
          Implement basic error handling for form inputs to manage invalid data submissions.

#Part 3: Database Integration
    
    Description:
         
         Integrate SQLite or MySQL for persistent data storage.
    Features:
        
         Store user data in the database instead of a text file.
         Create a page to view, edit, or delete user data.
    User Authentication:
          
          Implement registration and login functionality.
          Ensure only authenticated users can submit the form and view their submitted data.
    Example Features for User Authentication:
          
           Registration page to create new user accounts.
           Login page to authenticate users.
           Middleware to restrict access to authenticated users.

#This Flask application allows users to register, log in, and manage student records using a web interface. It includes user authentication, database integration for storing user and student data, and structured HTML templates for a user-friendly experience.

Software Requirements

Python
  Version: 3.6 or higher
  Download: Python Official Website

Flask
  
  Framework for building the web application.

Install using pip:
  
  pip install Flask

Flask-SQLAlchemy
   
   Extension for integrating SQLAlchemy with Flask for database management.

Install using pip:
    
    pip install Flask-SQLAlchemy

Installation Steps
    
    Install Python: Ensure Python is installed and available in your system's PATH.


     Set up a virtual environment:
           
           python -m venv venv
          pip install Flask Flask-SQLAlchemy

Run the application:
    
    python app.py


     

    




