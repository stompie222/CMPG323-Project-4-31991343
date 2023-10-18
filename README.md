# CMPG323-Project-4-31991343

## UI Automation and testing
The goal of this project was to create an automatic process to test the Web API developed in the previous projects. This was done by utilizing the UI automation functionality UI Path provides to test a variety of use cases and edge cases.

The following operations was automated by this bot :

## Website login
The bot automatically logs in to the Website with credentials that is stored securely in Ui Path Orchestrator

## Login Credentials 
Can be fount in the reference document included in the project submission.

## Gathering test data
Once logged in, the bot gathers data to be tested from a specified excel file.

## Using the dataset to test CRUD operations
The bot then loops through each record in the excel file and test all CRUD operations on the website one by one.


## Documenting results
For each operation the bot documents whether the current task was completed successfully or not by indicating in the Test Results sheet the results for each operation. The user then can view the results of the test by simply looking at the Test Results.


## Deployment
Finnaly the project can be deployed to UI Path Orchastrator to be used in production.
