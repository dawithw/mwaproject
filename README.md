# Investment Management
Repo for MWA group project

## About

This application that allows members to purchase time based units of stocks in a particular business.
Investors can browse for and select their desired packages, for which they can pay online. The application will keep track of their investments and email any updates.

Admins will be able to add new packages and monitor investments purchased.

## Dependencies

The application is built using MEAN using npm for dependency management. You'll need to have npm installed and configured before you start. 

## Build and Run

Clone repository to your local machine
    
    git clone https://github.com/dawithw/mwaproject
  
Replace *path/to* with the location of the directory where you cloned the repo

### Frontend

    cd path/to/mwaproject/clientside
    npm install
    ng serve -o
    
### Backend

    cd path/to/mwaproject/serverside
    npm install
    node app.js
    
### Notes

- To configure your own mongodb database, modify the property *mongoDbUrl* in **mwaproject/serverside/config/config.js**

- To change the email address to which mail is sent, edit the **mwaproject/serverside/modules/services/mailSender.js**. 

In the real world, this is a terrible way to store credentials. Since this is just a demo application, we decided to keep it simple.


## Screenshots



