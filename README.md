# IN104 Project 9: Rocket design with python. 

Repository for project 9 of the course IN104, year 2020.

The objective of this project is to develop a python tool for the preliminary design of rockets and simulation of trajectories.

# Project description

In this project, you are going to code a python tool that can be used for the preliminary design of rockets and simulation of trajectories.

This project has two main lines of work: 

 * Design of rockets with the aid of OOP and GUI.
 * Definition of a space mission and simulation of trajectories. Examples of missions can be to put a satellite in Low Earth Orbit (LEO) of Geostationary Orbit (GEO), reach the moon, etc.

These tasks are independent but linked. Below in this document you have the section **Tasks**, which details the steps to follow in this project. Three tasks are distinguished: tasks 1 and 2 correspond to rocket design, and task 3 corresponds to trajectories.

The idea is that you handle tools such as python classes and data science, which are useful for a wide range of projects. Rockets will be considered as python classes and will be stored in a database. The database will be created, accessed and modified with the package pandas. Graphical tools (for printing rockets and trajectories) are also useful. 

This database will be accessed by a script that you will develop for simulating the mission. The idea is that this script can analyze the performance of rockets: trajectories will be plotted and animated if possible. For this, you can use python tools such as matplotlib or pygame. 

All the information regarding this project is contained in this repository. The file 'rocket_database.csv' is an example of database containing six rockets; you can use it as starting point for adding more rockets that you might find and for adding your own ones. The file 'rocket_science_notes.pdf' is a document with all the scientific background for carrying the project (as the objective of this project is to develop your computing skills, not becoming experts in rocket science).

Besides, you will need to create your own github repository. You will use git commands for updating this repository. You must also add me as a collaborator (git user carlosgguil) so that I can see your commits and track your work for continuous evaluation.

# Tasks 

1. Create a python program to handle the database and build rockets. This program will consists of two files: 
    1. **rocket_module.py**: module file that will contain the definitions of classes with their attributes and methods, plus any other function you can use in main.py (for example, for plotting). This file can be used to create unit tests. You can add as many functions and classes as you wish. The attributes of the rockets should be the ones that are available in the database, but you can add more if desired. You can also apply the inheritance properties as you want.  Feel free to explore options !
    2. **main.py**:  main script what will handle rockets by using the functions and methods defined in rocket_module.py. This file will implement two main functionalities: *read* the rockets in the database (with pandas) and defining them as objects in the script (as you did in TD2), and *build* rockets by defining first the objects and then adding them to the database. Besides this, this script should be able to plot the geometry of the rockets (they can be stored in picture files with .png or .jpg format). The geometry should be schematic (as shown for example in *Chapter 3 - Rockets characteristics* of file rocket_science_notes.pdf), but you can do it as simple or as complex as you want. If you want to go further, you can add the option to plot several rockets together to distinguish their size (as in https://es.m.wikipedia.org/wiki/Archivo:Rocket_size_comparison.png).
   
2. Create a GUI for performing the same functionalities as the file **main.py**. In the same fashion as this script, the GUI should have the options to read the rockets from the database and plot them, and to define the rockets (by means of inputs to the GUI) and store them in the database. The GUI should access the functions and files that you defined in **rocket_module.py**, but should not interact with **main.py**.

3. Simulate the rockets in trajectories. The background for this part is in Chapter 4 of the notes. Tasks:
    1. Choose one two-stages rocket (either one available at the database or one you have created) and plot three flat trajectories.
    2. Choose at least two different rockets (with at least one of your own creation) and plot one trajectory per rocket in the same graph. 
    3. Animate at least one trajectory. Choose any trajectory of the previous ones and create an animated graph as shown in Figure 6 of the rocket science notes.
    4. **Extra**: define a mission and create a rocket for accomplishing it. For it, you will need to define the highest altitude of the trajectory (i.e. the culmination point) and use the relations presented in the notes to calculate the pitch angle and the parameters of the rocket. 

# Available tools

In this repository, you will be able to find the following tools and documents:

- A **rocket database** containing the geometrical characteristics and performance of real rockets. The database is the file 'rocket_database.csv' located inside the folder 'database'. This folder contains also a handbook with an explanation of the database, named 'handbook.pdf'.

- The file **rocket_science_notes.pdf**, which serves as an introduction to the concepts behind rockets that you need to use in this project. It is not intended to be a course on rocket science, but a practical handbook containing the tools for implementing the code. You are encouraged to contact me if you find any errors in the document or if there is something you do not understand so that I can make things easier for you.

# Resources

## Python 

You will need a python editor which is compatible with GUI development. 

If you are using windows OS I recommend you to use the editor **spyder**. You can download it from the following link:

  https://www.anaconda.com/distribution/ 
  
The database will be handled with the package **pandas**. You can get an introduction to how pandas works in the following guide:

  https://pandas.pydata.org/docs/getting_started/index.html
  
The GUI can be created with the took **tkinter**. Here you have a nice video (in french) 

 https://www.youtube.com/watch?v=N4M4W7JPOL4

## GIT

For git, you need to create your own repository and add me as a collaborator. You have all the tools you need for using GIT in TD1. 

If you wish, you can also create repositories directly in https://github.com. If you are using windows, you can download the tool **GitHub Desktop** to clone your repositories in local folders.

  https://desktop.github.com/


# Evaluation 

* 40 % **source code**. The objective is to have a tool that works according to its requirements. You will not be based on how much your tool can do in terms of science (as the objective of the project is not this science in itself), but on how well it can do what it is supposed to do. The use of what you have learnt in the TDs (GIT, OOP and unit test) will be valued.
* 25 % **continuous evaluation**. Performing tasks and meeting deadlines without leaving everything for the last minute. Monitoring will be done through git commits in your own repository.
* 25 % **presentation**. Final presentation (between 5 and 10 min) plus questions. You can organise the presentation as you wish, as long at it shows the results of the code you have developed. 
* 10 % **report**. Short pdf document (2-5 pages) indicating work performed, difficulties encountered and how they have been overcome. 


# Contact

Mail 1: carlosgguil@outlook.es

Mail 2: carlos.garcia-guillamon@safrangroup.com

Telegram chat for project group discussions: 

Zoom meetings are possible under request.
