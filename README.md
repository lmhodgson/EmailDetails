# EmailDetails

A web application that allows a user to be added to a database. This repository contains the Web Application and SQL tables and stored procedures.

In my web application, I have chosen not to insert duplicate emails into the database. My reasoning for this is to prevent the database being
populated with lots of duplicate rows if the user decides to click the submit button multiple times. Also, if this is a registration form
the user would require a unique login so if there are multiple rows with the same email and different passwords which password would be the correct
one and if the password needs updating which row should the password be updated in.
