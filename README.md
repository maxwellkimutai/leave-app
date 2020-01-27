# Leave Management Application
#### This is an application that will allow users to easily request for leave and have the leave approved, January 25, 2018
#### By **Maxwell Kimutai**
## Description
This is an application that will allow users to easily request for leave and have the leave approved.
## BDD
The program lets the users request for leave
* Example input: User fills in a leave request form
* Example output: The leave is added the system and the user can view the request

The program lets the admin approve leave request
* Example input: Admin views request and approves it
* Example output: Leave request changes state to approved

## Prerequisites
* Python3.7
* Pip
* flask
* Postgres

## Setup/Installation Requirements

**Application**
* create folder leave_app and open -> mkdir leave_app && cd leave_app
* clone repository -> git clone https://github.com/maxwellkimutai/leave-app.git
* create virtual environment -> python3.7 -m venv env
* install dependencies -> pip install -r requirements.txt

**Database**
* open postgres -> $ postgres psql
* create database -> postgres=# CREATE DATABASE leaveapp;
* create postgres user -> postgres=# CREATE USER leave WITH PASSWORD 'leaveapp';
* quit psql -> postgres=# \q
* initialize database -> python3.7 app.py db init
* migrate changes -> python3.7 app.py db migrate
* persist changes to database -> python3.7 app.py db upgrade

## Running Application
* python3.7 app.py runserver

## Known Bugs
None

## Technologies used
* Python3.7
* flask
* Postgres

## Support and contact details
Contact Maxwell Kimutai on +254713510682
### License
MIT
Copyright (c) 2019 **Maxwell Kimutai**
