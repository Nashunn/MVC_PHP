# MVC_PHP
Conception of a website in PHP not using any framework, with an MVC pattern. Made for UPMC as an exercice.

Requirements
============
To install this project you will need a web server with a MySQL database.

Installation
============
Clone the project in your server repository with the following command :
`$ git clone https://github.com/Nashunn/MVC_PHP.git`

You will need to import the MySQL database on your server using the file `database.sql` from the repository.
By default the database name is `upmc` and it has a unique table called `user`.
The table `user` has 2 users in it :
- A default user (login : `user@mail.com` and pwd : `user`)
- An admin user (login : `admin@mail.com` and pwd : `admin`)
