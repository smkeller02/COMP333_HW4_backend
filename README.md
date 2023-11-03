# COMP333_HW4
Frontend Mobile (React-Native)

Sydney Keller (<smkeller@wesleyan.edu>)
Minji Woo (<mwoo@wesleyan.edu>)


# Purpose:


# Setting up the developement environment:
- Screenshot of local XAMPP developement environment 
</br><img align ="center"
height="32%"
width="32%"
src="./Images/Sydney_XAMPP.png"
alt="Screenshot of local XAMPP developement environment"
/>

- Screenshot of user table structure
</br><img align ="center"
height="32%"
width="32%"
src="./Images/Sydney_user_table_structure.png"
alt="Screenshot of user_table structure"
/>

- Screenshot of an example of user table data
</br><img align ="center"
height="32%"
width="32%"
src="./Images/Sydney_user_table.png"
alt="Screenshot of user_table"
/>

- Screenshot of ratings table structure
</br><img align ="center"
height="32%"
width="32%"
src="./Images/Sydney_ratings_table_structure.png"
alt="Screenshot of ratings_table structure"
/>

- Screenshot of an example of ratings table data
</br><img align ="center"
height="32%"
width="32%"
src="./Images/Sydney_ratings_table.png"
alt="Screenshot of ratings_table"
/>

# How to run the code:


# Folders and Files:
## Rest API/Model, View, Controller Architecture:
index.php: the entry-point of our application, front-controller of application. index.php connects to UserController.php for all interactions with database</br>
inc:
 - config.php: holds the configuration information of application, holds the database credentials. 
 - bootstrap.php: used to bootstrap  application by including the necessary files
 <!-- end of the list -->
Model:
- Database.php: the database access layer which will be used to interact with the underlying MySQL database.
- UserModel.php: the User model file which implements the necessary methods to interact with the users table in the MySQL database.
<!-- end of the list -->
Controller/Api:
- BaseController.php: a base controller file which holds common utility methods.
- UserController.php: the User controller file which holds the necessary application code to entertain REST API calls. Creates a user, logs a user in, gets data from ratings table for user, deletes, adds, and updates ratings for user.
<!-- end of the list -->
Checkout this tutorial for how more details on how we set up our REST API:
https://code.tutsplus.com/how-to-build-a-simple-rest-api-in-php--cms-37000t

## Frontend React Native App:


## Other files:
Images:
- Sydney_XAMPP - Screenshot of local XAMPP developement environment
- Sydney_user_table_structure.png - Screenshot of user_table structure from phpMyAdmin
- Sydney_user_table.png - Screenshot of user_table from phpMyAdmin
- Sydney_ratings_table_structure.png - Screenshot of ratings_table structure from phpMyAdmin
- Sydney_ratings_table.png - Screenshot of ratings_table from phpMyAdmin


# Sources Cites: