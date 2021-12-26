# acme_project
This is a personal project using Django backend and Angular frontend. The database that I am using is default sqlite3 come with Django framework. 
There are two main features in this app: 
  1. Simulator that simulate device send state data to the backend and perform database manipulation and update.
  2. Monitor that keep real time monitoring device's state (database update). 
User can have two windows open with one of simulator to simulate data flow and update device data, and another one of monitor to keep monitoring database update from simulator. 
As user might switch different roles and both of them are hosted on the same port, please extra refresh the browser of the monitor page to make sure the websocket connection is solid. Websocket is used in this project to achieve real time data update for Monitor dashboard.

Installation: This project contain two submodules. To get the entire project run the below command in you terminal.
```
'git clone --recurse-submodules https://github.com/VincentWang333/acme_project.git'
``` 

All submodules contain a docker, with a docker compose file at the parent folder. 
Make sure you have a working Docker runing on your machine, to fire up the entire stack, simply run
```
docker-compose up
```

Thank you for try it out, and feedback is always welcome and appreciated.



