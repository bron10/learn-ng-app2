# Angular QuickStart

Step 1
Here are steps to install an ng2 application
 - Quick start it from https://github.com/angular/quickstart.git
 - npm install
 - npm start
 - Woo! my angular app starts

Step 2
Lets study the structure of an application
 - Angular 2 introduces itself in common js pattern style. One of most common
yet important file is package.json. This json file acts as a registery of an application.
Here .ts are TypeScript files.
Lets head towards development ready enviroment. The structure provided is a development
ready env.
 - There are some files which are not familar. They are as follows
   bs-config.e2e.json browser sync end-to-end config json file
   bs-config.json browser sync end-to-end config json file

   While the developer is working on code, one need to refresh the browser to view
   the modifications. Here browser sync is use to keep watch and monitor the client server

   karma is js test suite. It requires shim file and config file to start the test suite

   non-essential-files contains the list of non essential files

   protractor is ui testing suite. It requires a config file called protractor.config

   and finally tslint.json. Its a TypeScript linting file.

   src filder and e2e folder.

Runn the project and observe the terminal logs by making some changes.
