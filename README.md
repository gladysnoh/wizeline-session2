# wizeline-session2
This repository was created in order to deliver my assessment for session 2 regarding test certification provided by wizeline

Project structure:

The **Variables** folder: It has the env variables I exported from my postman application. You need to import it first before executing any request on Postman.
The **Collection** folder: It has all the postman requests I added that use the todist API.
The **CollectionFromFile** folder: This folder has the collection with the request example to create multiple tasks using a csv file (added inside the folder too). I also added some tests for that request, you will be able to see it once you import the json file into postman.

The main project.

Firstly you need to have the newman package installed globally in your machine.r
`npm install -g newman`

Then you need to go to the following directory to access to the newman project:

`cd ./Project/WizelineSession2`
 
 After that you have to execute the npm install command in order to install the html-extra package (since it is a dependency in the project)
 
 The next step is to execute the npm task:
 
 `npm run test`
 
 This should trigger the execution and also generate the report.html file inside the report folder.
 
 And that's pretty much it! :D
 
