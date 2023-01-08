# Guide-to-the-Masters-Project
This is a guide to setup the A System for Standardized Collection of Graduate School Transcripts Project
How to run the project

If you are running project for the first time, setting up environment involves step 1 to step 6 . If you have already set up the environment, just execute step 7.

Step 1: First Create the schema

Install MySQL server from https://dev.mysql.com/downloads/workbench/ . 
Download the database_dump.sql from database dump from https://github.com/PriyankaMaru28/Guide-to-the-Masters-Project

Open your desired host and import schema from the dump file

Step 2 : Install node in local computer
Download the .msi or .pkg file from https://nodejs.org/en/download/
Install the file

Step 3 : Check if the node.js and npm are installed In command prompt check 'node -v' to check node version and 'npm -v' to check npm version

Step 4 : Download the project Download the project from Github https://github.com/PriyankaMaru28/A-System-for-Standardized-Collection-of-Graduate-School-Transcripts-main

Step 5 : Install node modules inside the project

Open command prompt and change the directory to the location of the project . Then run the following commands :

npm install

cd frontend

npm install

cd ..

cd backend

npm install

cd ..

Step 6 : Change the database credentials

You need to enter the details of database details that you have set up in step 1

Go to backend folder in the project

Then open database folder and open db.js

Then provide the details of your database hostname, username, password and the database schema name (which was created in step1) .

Step 7 : Run the program

Change the location of directory to location of project and give the command "npm run dev".
