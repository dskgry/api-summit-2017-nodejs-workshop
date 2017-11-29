Example realtime React + Node Twttr app

# Pre-installation requirements
* Local installation of node >= 8.x    (https://nodejs.org/en/)
    * You can check your installed version with the command "node --version".
* Local installation of rethinkdb (https://www.rethinkdb.com/docs/install/)
    *  if you don't want to litter up your host system, just start a RethinkDB docker container :)
    * `docker run --name some-rethink -p 8080:8080 -p 29015:29015 -p 28015:28015 -d rethinkdb

# Installation

server:

1. start rethink db (from anywhere)
2. go to folder "server"
3. npm install
4. npm start (server will be running on http://localhost:3001)


app:
1. go to folder "server"
2. npm install
3. npm start (server will be running on http://localhost:3000)
4. Login with any user name, password must be 'summit'


# Slides

Slides can be found here:
http://bit.ly/nodejs-slides
 

 
