# Upload Data Set

## Description
A researcher with a data set will come to our site to contribute their data set. In order to share the dataset, the researcher must upload a manifest and a data file or line to a data file. If a manifest is not uploaded, a second use case, called "Generate Manifest", will be executed before the data set can be saved.

## Functional Requirements
1. Include all the things specified in the manifest
2. Place to upload scripts (if provided)
3. Place to upload Jupyter Notebooks (if provided)
4. Docker config file (if provided) [could be generated with use case "Generate Config Settings]

## Technical Requirements
1. Back end version control for the scripts
2. Database for storing manifests
3. Disk space for storage of data (possibly large data sets)
4. Jupyter Hub Installation
5. Working, public web server

## Primary Actors
1. Researchers
2. Students
3. Data scientists
4. System admins

## Dependent Use Cases
1. Generate Manifest
2. Generate Config Settings
