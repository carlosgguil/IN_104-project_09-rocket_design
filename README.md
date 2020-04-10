# IN104 Project 9: Rocket design with python. 

Repository for project 9 of the course IN104, year 2020.

The objective of this project is to develop a python tool for the preliminary design of rockets and simulation of trajectories.

# Project description

In this project, you are going to code a python tool that can be used for the preliminary design of rockets and simulation of trajectories.

This project has two main lines of work: 

 * Definition of a space mission and simulation of trajectories. Examples of missions can be to put a satellite in Low Earth Orbit (LEO) of Geostationary Orbit (GEO), reach the moon, etc.
 * Bulding a Graphic User Interface (GUI) for the design of rockets.

Both tasks are independent but must be linked somehow. The idea is that the GUI can be used to make preliminary designs of rockets that can be stored in a database. Rockets will be considered as python classes. The database will be created, accessed and modified with the package pandas. 

This database will be accessed by a script that you will develop for simulating the mission. The idea is that this script can analyze the performance of rockets: trajectories will be plotted and animated if possible. For this, you can use python tools such as matplotlib or pygame. 

All the information regarding this project is contained in this repository. The file 'rocket_database.csv' is an example of database containing six rockets; you can use it as starting point for adding more rockets that you might find and for adding your own ones. The file 'rocket_science_notes.pdf' is a document with all the scientific background for carrying the project (as the objective of this project is to develop your computing skills, not becoming experts in rocket science).

Besides, you will need to create your own github repository. You will use git commands for updating this repository. You must also add me as a collaborator (git user carlosgguil) so that I can see your commits and track your work for continuous evaluation.

# Tasks 

* Handle the rocket database. You will develop a script that is able to access and modify the database by adding or eliminating rockets. Each rocket will be stored as a

* 


# Available tools

In this repository, you will be able to find the following tools and documents:

- A **rocket database** containing the geometrical characteristics and performance of real rockets. The database is the file 'rocket_database.csv' located inside the folder 'database'. This folder contains also a handbook with an explanation of the database, named 'handbook.pdf'.

- The file **rocket_science_notes**, which serves as an introduction to the concepts behind rockets that you need to use in this project. It is not intended to be a course on rocket science, but a practical handbook containing the tools for implementing the code. You are encouraged to contact me if you find any errors in the document or if there is something you do not understand so that I can make things easier for you.

# Resources

## Python 

You will need a python editor which is compatible with GUI development. 

If you are using windows OS I recommend you to use the editor **spyder**. You can download it from the following link:

  https://www.anaconda.com/distribution/ 
  
The database will be handled with the package **pandas**. You can get an introduction to how pandas works in the following guide:

  https://pandas.pydata.org/docs/getting_started/index.html

## Git

For git, you can either create your own repository in https://github.com or download the tool **GitHub Desktop**  to create a local repository. You can download it from the follozing link:

  https://desktop.github.com/


# Evaluation 

* 40 % **source code**. The objective is to have a tool that works according to its requirements. You will not be based on how much your tool can do in terms of science (as the objective of the project is not this science in itself), but on how well it can do what it is supposed to do.
* 25 % **continuous evaluation**. Performing tasks and meeting deadlines without leaving everything for the last minute. Monitoring will be done through git commits in your own repository.
* 25 % **presentation**. Final presentation (between 5 and 10 min) plus questions. You can organise the presentation as you wish, as long at it shows the results of the code you have developed. 
* 10 % **report**. Short pdf document (2-5 pages) indicating work performed, difficulties encountered and how they have been overcome. 


# Contact

Mail 1: carlosgguil@outlook.es

Mail 2: carlos.garcia-guillamon@safrangroup.com

Telegram chat for project group discussions: https://t.me/joinchat/QAceNRqql8rS7aE1KTpliA

Skype and zoom meetings are possible under request.
