# 0x00. AirBnB clone - The console

# HBNB - The Console
- This repository contains the initial stage of a student project to build a clone of the AirBnB website. This stage implements a backend interface, or console, to manage program data. Console commands allow the user to create, update, and destroy objects, as well as manage file storage. Using a system of JSON serialization/deserialization, storage is persistent between sessions.

# Repository Contents by Project Tasks

# General Use
- First clone this repository.
- Once the repository is cloned locate the "console.py" file and run it as follows:
/AirBnB_clone$ ./console.py
- When this command is run the following prompt should appear:
(hbnb)
- This prompt designates you are in the "HBnB" console. There are a variety of commands available within the console program.
Commands
* create - Creates an instance based on given class



* destroy - Destroys an object based on class and UUID



* show - Shows an object based on class and UUID



* all - Shows all objects the program has access to, or all objects of a given class



* update - Updates existing attributes an object based on class name and UUID



* quit - Exits the program (EOF will as well)

# Examples

## Primary Command Syntax

Example 0: Create an object
Usage: create <class_name>
(hbnb) create BaseModel

(hbnb) create BaseModel

3aa5babc-efb6-4041-bfe9-3cc9727588f8

(hbnb)                   
Example 1: Show an object

Usage: show <class_name> <_id>

(hbnb) show BaseModel 3aa5babc-efb6-4041-bfe9-3cc9727588f8

[BaseModel] (3aa5babc-efb6-4041-bfe9-3cc9727588f8) {'id': '3aa5babc-efb6-4041-bfe9-3cc9727588f8', 'created_at': datetime.datetime(2020, 2, 18, 14, 21, 12, 96959), 

'updated_at': datetime.datetime(2020, 2, 18, 14, 21, 12, 96971)}

(hbnb)  



# AUTHORS
- Simanga Mchunu [github](https://github.com/Simacoder)
- Kennedy Okeke [github](https://github.com/Techie-Ken)
