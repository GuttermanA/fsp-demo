# README

##Setting up MongoDB Rails API

###In the terminal:
1. ```brew update```
2. ```brew install mongodb```
3. ```sudo mkdir -p /data/db```
4. Check to see if the DB was installed correctly: ```sudo mongod```

###In Rails
1. ```rails new project-name --skip-active-record```
2. Add to the gemfile: ```gem 'mongoid','~>6.1.1'``` and ```gem 'mongo','~>2.5.1'```
3. Run ```bundle install```
4. Set up controllers and models
5. Make sure MongoDB is running: ```sudo mongod```
6. Enter rails console to see if you can create records
7. Run rails server to go toAPI endpoint to see if server is responding to requests
