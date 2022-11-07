# Postman-tests

This repo contains "petsore" and "store" postman collections

## Setup

### Install software and check out the project

- Download and install Node.JS
- Install Visual Studio Code
- Clone and checkout the github project
- Go to the terminal and execute "npm install" command
- Run the "npm run tern-on-api" command

### How to run the tests on windows
Go to the terminal and install newman execute "npm install -g newman" command
The newman run command allows you to specify a collection to be run. You can easily export your Postman Collection as a json file from the Postman App and run it using Newman. 
 <ol>
   <li>Run the "newman run petsore.collection.json" command for run test on petsore colllection</li>  
   <li>Run the "newman run store.collection.json" command for run test on store collection</li>  
  </ol>
Newman also supports reporters. For instance, to use the Newman HTMLExtra Reporter go to the terminal execute "npm install -g newman-reporter-htmlextra" and run "newman run petstore.collection.json -r htmlextra"

#### To see reports without installation
Go to this link to see [newman report](https://leraroy.github.io/postman-tests/) for store collection 



