# Store Item Catalog

This application is an item catalog that provides a variety of built in categories
as well as a user registration and authentication system. Registered users,
through Google, will be able to create, update, and delete their own personal information.

## Prerequisites

* Vagrant will need to be installed. Here is a link: [Vagrant](https://www.vagrantup.com/)

## Installation Instructions

1. Download and open catalog.zip file to local computer
2. Place projectC inside your vagrant folder
3. Log into your terminal and cd to the vagrant directory
4. Type `vagrant up` in terminal to launch virtual machine
5. Type `vagrant ssh` in terminal to sign into virtual machine
6. Type `cd /vagrant` in terminal to access vagrant directory
7. Type `cd projectC` in terminal to access project file
8. Type `python database_setup.py` to setup the database
9. Next, type `python lotsofcategories.py` to populate the database
10. Type `python catalog.py` to launch server and application
11. Open an Internet Browser and type in `localhost:8000`

## Built With

* [Flask](http://flask.pocoo.org/) - Microframework for Python
* [SQL Alchemy](http://www.sqlalchemy.org/) - Python SQL Toolkit
* [Vagrant](https://www.vagrantup.com/intro/index.html) - Introduction to Vagrant

## API Reference

* Flask 

## Author

* **Nicolas Bolduc** _-Initial Work-_ [Lazarus](https://github.com/lazarus432)
