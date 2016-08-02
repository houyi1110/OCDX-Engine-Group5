#Spawn JH Instance

## Description
When a user has selected a dataset and SNC files he or she is intersted in exploring, the site will spawn into a docker instance on Jupyter where the data/code can be viewed/tested/maniputlated. A dataset may be opened without any SNC files, but SNC files will always be opened with their corresponsing dataset.

## Functional Requirements

## Technical Requirements 
1. Jupyter Hub installation
2. Ability to open docker file and export files into Jupyter

## Primary Actors
1. Researchers
2. Students
3. Data scientists
4. System admins

## Pre Conditions
1. A user has found and selected a dataset possible with SNC files. 

## Main Success Scenario
The user is directed to Jupyter, the necessary environment has been activated, and the files
 are now avaliable for the user. 

## Failed End Condition
The dataset or SNC files selected by the user are not able to be spawned onto Jupyter. 

## Trigger
User clicks "Open with Jupyter"

## Dependent User Cases
1. Search Manifest
2. Browse Manifest
