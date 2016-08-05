# Generate or Upload Manifest

## Description
After a user has uploaded the dataset and any SNC (Scripts, Notes & Configuration) files, they will have one of two options. If a complete OCDX Manifest is already avaliable to the user, the file can be uploaded directly. Otherwise, the user will manually fill our a manifest form with the necessary specifications. In both cases, the manifest must be complete before the dataset and SNC files are saved.

## Fucntional Requirements
1. Buttons to "Generate Manifest" and "Upload Manifest"
1. Include input fields for all menifest specifications for "Generate Manifest"
2. Dataset and any SNC files has been contributed.

## Technical Requirements
1. Database for storing manifests

## Primary Actors
1. Researchers
2. Students
3. Data scientists
4. System admins

## Pre Conditions
1. A primary actor has shared data and any SNC files.

## Main Success Scenario
Manifest, data, and any SNC files are uploaded to server and are saved and searchable.

## Failed End Condition
User does not have a complete menifest.

## Trigger
User clicks "Create Manifest" or "Upload Manifest" button on site after submitting dataset.

## Dependent Use Cases
1. Upload Data Set
