# CMPG-323-Overview-24095990

# Table of Contents
 - [Project 1 - Agile & Scrum](#project-1---agile--scrum)
 - [Project 2 - API Development](#project-2---api-development)
 - [Project 3 - Standards & Patterns](#project-3---standards--patterns)
 - [Project 4 - Testing & RPA](#project-4---testing--rpa)
 - [Project 5 - Reporting & Monitoring](#project-5---reporting--monitoring)
 - [Project and Repository Integration](#project-and-repository-integration)
 - [Branching Strategy](#branching-strategy)
 - [The use of a .gitignore file](#the-use-of-a-gitignore-file)
 - [Storage of creadentials and sensitive information](#storage-of-credentials-and-sensitive-information)


## Project 1 - Agile & Scrum
-  Repository created and used:  CMPG-323-Overview-24095990


## Project 2 - API Development
- Repository created and used:  CMPG-323-Project-2-24095990
- <a href="https://github.com/OJ-B/CMPG-323-Project-2-24095990">Link to project</a>
- Added a readme detailing key points and usage of the API
- Added a gitignore file
- All the required methods related to Devices, Zones and Categories were created
- Implemented authentication on the relevant API endpoints
- Hosted the API on azure (link included in the readme)

## Project 3 - Web Application
- Repository created and used:  CMPG-323-Project-3-24095990
- <a href="https://github.com/OJ-B/CMPG-323-Project-3-24095990">Link to project</a>
- Added a readme detailing key points and usage of the Web Application
- Added a gitignore file
- The generic repository as well as a separate Zone, Device and Category repository were created and implemented
- The implementation of the design pattern were split into different projects
- The Web Application was hosted on Azure (link included in the readme)

## Project 4 - Testing & RPA
- Repository created and used:  CMPG-323-Project-4-24095990
- <a href="https://github.com/OJ-B/CMPG-323-Project-4-24095990">Link to project</a>
- Added a readme containing a screenshot of where the process is added on the UiPath Orchestrator, and details about how to use the test process
- Added a gitignore file
- Added a Form to assist in the login process, prior to starting the tests
- All tests on CRUD operations were added, they can be run in aggregate or separately
- The UiPath process were added to the UiPath orchestrator

## Project 5 - Reporting & Monitoring
- Repository created and used:  CMPG-323-Project-5-24095990
- <a href="https://github.com/OJ-B/CMPG-323-Project-5-24095990">Link to project</a>
- Added a readme giving an overview and providing details of the reports that were created
- Created a new Power BI Report, added a live connection to the sharepoint data
- Corrected the existing data with queries and mapped the relationships between data sources
- Created some key measures and added a calender table
- Added all visuals with regards to Devices, Zones and Categories
- Added filters and slicers on all the pages as well as added an additional filter to add value to the reports

## Project and Repository Integration
- Each Project will have their own repository and will be linked to the same github project for strategy and planning purposes.

This can be seen in the diagram below.

<img src ="https://github.com/OJ-B/CMPG-323-Overview-24095990/blob/main/Resources/Diagram1.png?raw=true" alt="Project and Repository Integration">

## Branching Strategy
Since the projects will not be completed by a large team and minimal to non merging issues are expected the GitHub Flow Branching Strategy will be utilised.
For each change the main branch will be pulled into a local repository, a new branch will then be created which will be merged back to the main branch once changes are completed.

The workflow is illustrated below.

<img src ="https://github.com/OJ-B/CMPG-323-Overview-24095990/blob/main/Resources/Diagram2.png?raw=true" alt="GitHub Flow workflow">
Reference: <a href="https://www.gitkraken.com/learn/git/best-practices/git-branch-strategy#:~:text=GitHub%20Flow%20Branch%20Strategy,contains%20your%20production%2Dready%20code">GitKraken: What is the best Git branch strategy?</a>

## The use of a .gitignore file
Each project will have it's own .gitignore file which will be generated from a standard template and will be altered to include file extensions and folders specific to each project which should not be included in commits.

## Storage of credentials and sensitive information
Depending on the project and information to be stored, it will either be stored in an appsettings.json file or in an external vault such as Azure Key Vault.
