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

## Project 3 - Standards & Patterns
- Repository created and used:  CMPG-323-Project-3-24095990

## Project 4 - Testing & RPA
- Repository created and used:  CMPG-323-Project-4-24095990

## Project 5 - Reporting & Monitoring
- Repository created and used:  CMPG-323-Project-5-24095990

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
