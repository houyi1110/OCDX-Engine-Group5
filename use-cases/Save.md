# Save 

## Description
When a user has manipulated or created SNC files in Jupyter, they are given the option of saving
 their work before exiting the program. If they choose to save it, the user will be directed to
"Contribute to Existing Dataset". If they do not want to save, exit nomrally. 

## Fucntional Requirements 
1. Button to "Save"
2. Popup to "Save" if user tries to exit without saving.

## Technical Requirements
1. Route to "Contribute to Existing Dataset" to save

## Primary Actors
1. Researchers
2. Students
3. Data scientists
4. System admins

## Pre Conditions
1. User has opened data or SNC files in Jupyter
2. User has made any changes to original SNC files or has created new SNC files

## Main Success Scenario
User is able to save their additions and is directed to create a new project linked to an exisit
ng dataset. 

## Failed End Condition
The user is not able to save their additions or is not directed to "Contribute to Existing Datas
et" when wanting to save.

## Trigger
User clicks "Save" or tries to exit without saving.

## Dependent Use Cases
1. Search Manifest
2. Browse Manifest
3. Spawn JH Instance
