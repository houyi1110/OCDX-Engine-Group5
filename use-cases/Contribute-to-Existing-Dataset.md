# Contribute to Existing Dataset

## Description
A user wishes to add SNC files for a dataset already uploaded to the server. The user will provide a link to the dataset that will be found on the server using its SHA1 code.

## Functional Requirements
1. Place to upload link to data.
2. Place to upload scripts (if provided).
3. Place to upload Jupyter Notebooks (if provided).
4. Docker config files (if provided) or link to "Generate Config Settings".

## Technical Requirements
1. Back end version control for scripts
2. Jupyter Hub Installation
3. Working, public web server.

## Primary Actors
1. Researchers
2. Students
3. Data scientists
4. System admins

## Pre Conditions
1. User wished to upload SNC files.

## Main Success Scenario
Dataset has been found on server and SNC files have been successfully uploaded to site and connected to the dataset's manifest.

## Failed End Condition
User is unable to upload SNC files or dataset not found on server.

## Trigger
User clicks "Contribute to Existing Database"

## Dependent Use Case
NONE
