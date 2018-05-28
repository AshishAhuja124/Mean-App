# Mean App
Initially we have to install node modules using npm install.So that all the dependencies would be installed.
Also start the mongodb database using the following commands

Open cmd and paste it: "C:\Program Files\MongoDB\Server\3.6\bin\mongod.exe" ( as per your mongo settings)
Then open other cmd : "C:\Program Files\MongoDB\Server\3.6\bin\mongo.exe"
create a collection in it and to use data use cmd: use employees
To check the data : db.employees.find().pretty()

It starts over database.

Then start your node server by cmd : node server.js in node js cmd prompt.( localhost:3000)

It completely starts your back end part.

Then go to path of front end and use ng serve and go to browser and open localhost:4200 which completely displays our project
