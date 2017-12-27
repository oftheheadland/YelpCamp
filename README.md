# YelpCamp

![https://oftheheadlandcamp.herokuapp.com/](https://i.imgur.com/emWipIE.jpg)

YelpCamp is a project that was completed as a part of [Colt Steele's bootcamp](https://www.udemy.com/the-web-developer-bootcamp/).

This project has been expanded beyond what was done in the course.

## Local Setup

Run the following commands in the terminal.  Be sure to update information as necessary.

```
export DATABASEURL=mongodb://localhost/yelp_camp
export SESSION_SECRET=Whatever phrase you choose

```

## Heroku + MongoLab setup

Update the variables as follows:

**DATABASEURL**=mongodb://\<dbuser>:\<dbpassword>@1234.mlab.<span></span>com:19990/yelp-camp

**SESSION_SECRET**=Whatever phrase you choose


This can be accomplished on the Heroku site by accessing the Config Vars on the Settings page.  
Alternatively this can be done on the command line with the following commands:

```
heroku config:set DATABASEURL='mongodb://\<dbuser>:\<dbpassword>@1234.mlab.<span></span>com:19990/yelp-camp'
heroku config:set SESSION_SECRET='Whatever phrase you choose'
```

# Deployed

The app is deployed [here](https://oftheheadlandcamp.herokuapp.com/) at Heroku (also using [MongoLab](http://mlab.com)).
