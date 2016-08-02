# Browse Manifest

## Description
When the user searches by keyword, relavent manifests and corresponding SNC files are displayed with breif descriptions on what the data and files hold.

## Functional Requirements
1. "Date Uploaded" will be differentiating factors for multiple sets of SNC files for the same data set. 

## Technical Requirements
1. Buttons for "Open in Jupyter" and "Download" for each dataset and SNC files.
2. Possible have sorting options (by date, by relavence).

## Primary Actors
1. Researchers
2. Students
3. Data scientists
4. System admins

## Pre Conditions
1. User has searched for manifests. 

## Main Success Scenario
All datasets whose manifests contained searched keywords and corresponing SNC files are displayed with options to view and test files.

## Failed End Condition
No manifests were found and thus none are displayed. 

## Trigger
User submits search request by entering or clicking "Search".

## Dependent Use Cases
1. Search Manifest
