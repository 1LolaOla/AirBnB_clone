0x00. AirBnB clone - The console

LANGUAGE: Python

DESCRIPTION:
 To create a command line interface (which is sandboxed) through which we can create, modify and delete objects in our file storage. This project is a complete web application which implements the back-end console, integrates database storage and front-end interfacing in cloning an AirBnB.
 
CONCEPTS 
 How to create a Python package
 How to create a command interpreter in Python using the cmd module
 What is Unit testing and how to implement it in a large project
 How to serialize and deserialize a Class
 How to write and read a JSON file
 How to manage datetime
 What is an UUID
 What is *args and how to use it
 What is **kwargs and how to use it
 How to handle named arguments in a function
 
Starting the Commandline Interpreter
The Commandline Interpreter can be started by executing the command ./console.py. The console can create, destroy, and update objects. Type help within the console to get a list of command options and its function.
The console is a command line interpreter that permits management of the backend of AirBnB.

Using the Console
The AirBnB console can be run both interactively and non-interactively. To run the console in non-interactive mode, pipe any command(s) into an execution of the file console.py at the command line.

$ echo "help" | ./console.py
(hbnb) 
Documented commands (type help <topic>):
========================================
EOF  all  count  create  destroy  help  quit  show  update

(hbnb) 
$
  
Also,  to use the AirBnB console in interactive mode, run the file console.py by itself:

$ ./console.py
While running in interactive mode, the console displays a prompt for input:

$ ./console.py
(hbnb) 
To quit the console, enter the command quit, or input an EOF signal (ctrl-D).

$ ./console.py
(hbnb) quit
$
$ ./console.py
(hbnb) EOF
$
  
  
  
  
Authors
  Lola Ola
  
